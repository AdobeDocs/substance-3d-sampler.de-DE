---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie Python-Skripte für Substance 3D Sampler erstellen, um Workflows zu automatisieren und die Anwendungsfunktionalität zu erweitern.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Erstellen eines Skripts mit Python
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Erstellen eines Skripts mit Python

In diesem Handbuch wird beschrieben, wie Sie ein einfaches Plug-in zum automatischen Speichern mit Python erstellen.

## Skriptstruktur

Für den Import von Skripten in Sampler ist eine einzelne PY-Datei erforderlich. Sie können das unten stehende Beispielskript als PY-Datei speichern und in Sampler importieren.

## Beispielskript

Das folgende Skript erstellt automatisch Variationen Ihres Materials, indem ein neuer zufälliger Impfstoff für jede Ebene im Material ausgewählt wird. Dies ist nützlich, um sicherzustellen, dass Ihr Material in einem allgemeinen Fall verwendet werden kann, anstatt sich auf bestimmte zufällige Samen zu verlassen.

### random\_seed\_variation.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


Der obige Code enthält Kommentare, in denen erläutert wird, was in jeder Zeile passiert.

## Skript importieren

Nachdem Sie das obige Skript als PY-Datei auf Ihrem Computer gespeichert haben, können Sie es mit Bearbeiten > Voreinstellungen > Plug-ins und Skripten importieren. Nach dem Import wird in der Menüleiste neben **Datei** und **Bearbeiten** eine Option **Skripte** angezeigt. Hier können Sie das Skript ausführen.

Weitere Informationen zum Verwalten Ihrer Skripts [finden Sie hier:](../manage-installed-plugins-and-scripts.md).
