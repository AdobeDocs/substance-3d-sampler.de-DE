---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie Plug-ins mit Python und QML für Substance 3D Sampler erstellen, um benutzerdefinierte Benutzeroberflächen zu erstellen und Funktionen zu erweitern.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Plug-in mit Python und QML erstellen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Plug-in mit Python und QML erstellen

In diesem Handbuch wird beschrieben, wie Sie ein einfaches Plug-in zum automatischen Speichern mit Python und QML erstellen.

## Plugin-Struktur

Sampler-Plug-ins erfordern mindestens eine Python- und QML-Datei, damit sie importiert werden können. Es können jedoch auch andere Dateien einbezogen werden, z. B. Bilder, die für Symbole im Bedienfeld &quot;Plug-ins&quot; verwendet werden. Im folgenden Beispiel gibt es drei Dateien:

* **autosave.py** enthält die Logik des Plug-ins und bestimmt, wie es funktioniert.
* **autosave.qml** definiert das Erscheinungsbild des Plug-ins in Sampler.
* **autosave.svg** ist eine Vektorgrafik, die als Symbol für das Plug-in verwendet wird.

Sobald Sie die für Ihr Plug-in benötigten Dateien in einem einzigen Ordner gespeichert haben, können Sie das Plug-in über Bearbeiten > Voreinstellungen > Plug-ins und Skripten zu Sampler hinzufügen. Weitere Informationen zum Verwalten von Plug-ins finden Sie [hier](manage-installed-plugins-and-scripts.md).

## Python

Der folgende Code ist die vollständige Python-Datei für das automatische Speichern des Plug-ins. Im Folgenden finden Sie eine kurze Beschreibung der Funktionsweise des Codes, der Code enthält jedoch auch Kommentare mit weiteren Informationen:

1. Importieren Sie relevante Module.
   1. Qt ist ein Multiplattform-GUI-Toolkit. QtcCore, QtQml und QtQuick sind Module, die wir verwenden, um zwischen autosave.py und autosave.qml zu kommunizieren.
1. Definieren Sie eine **save()**-Methode, die das Projekt alle X Minuten speichert.
1. Erstellen Sie eine Klasse für automatisches Speichern. Diese Klasse gibt an, wie die **save()**-Methode mit der Plug-In-Benutzeroberfläche verbunden wird, sodass Parameter das Verhalten des Plug-Ins ändern können.
1. Definieren Sie eine Methode **register\_qml\_type()**, die das Setup für das Plug-in durchführt.
1. Rufen Sie das Plug-in in Sampler auf.

### autosave.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

Die QML-Datei definiert die Benutzeroberfläche des Plug-ins. QML steht für Qt Markup Language und verhält sich ähnlich wie andere Markup-Sprachen wie HTML und XML. [Weitere Informationen zu QML finden Sie hier](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings).

Die allgemeine Struktur von autosave.qml lautet wie folgt:

1. Module importieren.
   1. Die importierten Qt-Module sind für die in der Datei verwendeten UI-Elemente erforderlich.
   1. Die in **autosave.py** erstellte API-Klasse für automatisches Speichern wird ebenfalls importiert. Die QML-Datei verweist auf diese Klasse in Zeile 20.
1. Erstellen Sie Variablen, die verfolgt werden müssen.
   1. **autoSaveFolder** ist der Ordner, in dem die Sampler-Datei automatisch gespeichert wird.
   1. **Das Timing** ist die Zeit in Sekunden zwischen den automatischen Speichervorgängen.
   1. **textColor** wird verwendet, damit die Textfarbe in der Plug-in-Benutzeroberfläche an einer einzigen Stelle aktualisiert werden kann.
1. Instanziieren der Python-API
1. Definieren Sie die Benutzeroberfläche.
   1. Dies umfasst Hooks auf die Python-API, die in **autosave.py** erstellt wurde. Beispiel:
      1. Zeile 47 aktualisiert den Variablenwert **timing** in der QML-Datei, wenn das Element &quot;Automatisch speichern alle (min):&quot; geändert wird.
      1. Zeile 64 ruft die Funktion **start\_auto\_save** von der API auf und übergibt die Variablen **timing** und **autoSaveFolder** als Parameter.
1. Erstellen Sie eine Methode, um den Standarddateipfad zu bereinigen.

### autosave.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

Möglicherweise haben Sie bemerkt, dass **autosave.svg** nicht explizit aufgerufen oder in **autosave.py** oder **autosave.qml** erwähnt wird. Das liegt daran, dass Sampler nach einer SVG-Datei mit demselben Namen wie die PY-Datei sucht und diese automatisch als Plug-in-Symbol verwendet.

>[!NOTE]
>
> Wenn Ihr Plug-in-Ordner eine SVG mit einem Dateinamen enthält, der nicht mit der PY-Datei des Plug-ins übereinstimmt, enthält Ihr Plug-in kein Symbol. Dadurch kann der Eindruck entstehen, dass Ihr Plug-in nicht in der Sampler-Benutzeroberfläche angezeigt wurde. Wenn dies der Fall ist, bewegen Sie den Cursor über die rechte Leiste von Sampler, um Ihr Plug-in zu markieren.
> 
> Ihr Browser unterstützt das HTML5-Videoelement nicht

Wenn dein Plug-in-Ordner keine SVG-Datei enthält, wird stattdessen ein Standard-Plug-in-Symbol verwendet.

Unten sehen Sie ein Beispiel für eine SVG, die Sie für das oben erstellte Plug-in zum automatischen Speichern verwenden können.

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## Einschränkungen des Plug-ins zum automatischen Speichern

Das oben erstellte Plug-in zum automatischen Speichern ist funktionsfähig, aber nicht perfekt. Wenn Sie beispielsweise das Intervall für das automatische Speichern anpassen, nachdem das automatische Speichern aktiviert wurde, wird die Zeit zwischen dem automatischen Speichern nicht geändert. Sie müssen das automatische Speichern deaktivieren und erneut aktivieren, damit der Wert in der Benutzeroberfläche an die API gesendet wird.

Wenn Sie zum ersten Mal mit Python und QML zusammen arbeiten, ist das Beheben dieses Fehlers eine nützliche Möglichkeit, um ein Verständnis dafür aufzubauen, wie die verschiedenen Teile des Plug-ins miteinander kommunizieren.
