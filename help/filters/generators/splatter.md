---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/splatter.html"
breadcrumb-title: ''
description: Verwenden Sie den Farbspritzer-Generator in Substance 3D Sampler, um Malen-Farbspritzer und zufällige Mustereffekte für Material-Texturen zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Splatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Spritzer
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '736'
ht-degree: 0%

---


# Spritzer

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-splatter-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verteile Instanzen anderer Material über dein Material.

>[!NOTE]
>
> Verwenden Sie bei Atlas-Materialien stattdessen den Filter &quot;Atlas Scatter&quot;.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Material-Eingabe**:\
  Wählen Sie die Anzahl der Materials aus, die als Eingaben verwendet werden sollen. Hinweis: eine Splatter-Ebene mit 3 Eingangsschlitzen, aber nur einem mit einem Eingang gefüllten Schlitz, wird anders aussehen als eine Splatter-Ebene mit 1 Eingangsschlitz und dieser Schlitz mit demselben Eingang gefüllt. Aus diesem Grund wird empfohlen, nur so viele Eingaben zu verwenden, wie erforderlich sind.
* **Größe des Rasters**: 1-64\
  Die Größe des Rasters bestimmt die Anzahl der Instanzen, die vom Filter &quot;Farbspritzer&quot; erstellt werden.
* **AO Height Tiefe**: 0-1\
  Passen Sie die Stärke des AO für Instanzen an, die vom Filter erstellt wurden.

**Form**

* **Skalierung**: 0-5\
  Basisgröße aller Instanzen anpassen
* **Zufällige Skalierung**: 0-1\
  Zufälligkeit des Skalierungswerts für jede Instanz anpassen
* **Keine Überlappung skalieren**: 0-1\
  Ändern der Größe von Instanzen, um Überlappungen zu vermeiden
* **Position zufällig**: 0-2\
  Zufälligkeit der Streuung von Instanzen steuern
* **Drehung zufällig**: 0-1\
  Zufälligkeit der Drehung von Instanzen steuern
* **Drehung aus der Hintergrund-Steigung**: 0-1\
  Ändern Sie, wie sehr sich die Normalen des zugrunde liegenden Materials auf die Drehung von Instanzen auswirken.

**Grundfarbe**

* **Übereinstimmung der Albedo**: 0-1\
  Die Farbe der Instanzen an die Farbe des darunter liegenden Materials anpassen.
* **HSL**: 0-1\
  Farbton, Sättigung und Helligkeit von Instanzen anpassen.
* **HSL Random**: 0-1\
  Steuern Sie die Zufälligkeit des Farbtons, der Sättigung und der Helligkeit jeder Instanz

**Normal**

* **Normal von** **Hintergrund**: 0-1\
  Passen Sie an, wie sehr sich die Normalität des Materials unter jeder Instanz auf die Normalität der Instanz auswirkt.
* **Normalwinkel zufällig**: 0-1\
  Neigen Sie die Normalen jeder Instanz zu einem zufälligen Winkel.

**Raueit**

* **Anpassung der Rauheit**: -1 bis 1\
  Gleichmäßiges Hinzufügen oder Entfernen von Rauheiten in verschiedenen Instanzen
* **Unregelmäßigkeit zufällig**: -1 bis 1\
  Addieren oder Subtrahieren des Werts der Rauheit jeder Instanz nach dem Zufallsprinzip
* **Rauheit aus Hintergrund**: 0-1\
  Passen Sie an, wie sehr sich der Raueitswert des zugrunde liegenden Materials auf den Raueitswert jeder Instanz auswirkt.

**Height**

* **Height-Offset**: -1 bis 1\
  Versatz des Heights von Instanzen. Dies kann sich darauf auswirken, wie Instanzen mit dem zugrunde liegenden Material überblendet werden.
* **Height-Offset zufällig**: 0-1\
  Zufallswert zum Height-Offset jeder Instanz hinzufügen
* **Height-Skalierung**: 0-2\
  Passen Sie das Height aller Instanzen an.
* **Zufällige Skalierung des Heights**: 0-1\
  Fügen Sie dem Height jeder Instanz einen zufälligen Wert hinzu
* **Neigung von Bg-Steigung**: 0-1\
  Fügen Sie jeder Instanz eine Steigung hinzu, die der Steigung des zugrunde liegenden Materials entspricht.
* **Smoothness der Hintergrund-Steigung**: 0-2\
  Passen Sie die Steigung des Hintergrunds für den Parameter &quot;**Skew from Bg Steigung**&quot; an.
* **Mit Hintergrund konform**: 0-1\
  Steuern Sie, wie stark sich der Hintergrund-Höhen-Map auf den Instanzen-Höhen-Map auswirkt. Dadurch können Sie Instanzen um die Hintergrunddetails verkleinern
* **Glätten konformer Hintergrund**: 0-1\
  Passen Sie an, wie viele Details aufgrund von **Mit Hintergrund konform** sichtbar sind.

**Metallisch**

* **Metallische Anpassung**: -1 bis 1\
  Steuern der metallic Werte von Instanzen
* **Metallic zufällig**: -1 bis 1\
  Zufallswerte vom metallic jeder Instanz hinzufügen oder entfernen
* **Metallic aus dem Hintergrund**: 0-1\
  Passen Sie den Einfluss der metallischen Hintergrundwerte auf jede Instanz an.

**Maske**

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren Sie diese Option, um eine benutzerdefinierte Maske zu verwenden und auf die Steuerelemente für benutzerdefinierte Masken zuzugreifen:
  * **Benutzerdefinierte Maske**: Bild/Pinsel\
    Importieren Sie ein Bild, das als benutzerdefinierte Maske oder Malen direkt in die **2D-Ansicht** verwendet werden soll.
  * **Benutzerdefinierte Maskenunschärfe**: 0-1\
    Die Kanten der benutzerdefinierten Maske weichzeichnen.
  * **Benutzerdefinierte Maskenumkehrung**: Knebel
  * **Benutzerdefinierte Maskendeckkraft**: 0-1\
    Stärke der benutzerdefinierten Maske anpassen

Benutzerhandbuch

Der Filter &quot;Farbspritzer&quot; ist nützlich, um Elemente wie Blätter, Steine oder Müll über Ihr Material hinweg Streuung.

So verwenden Sie den Splatter-Filter:

1. Den Filter &quot;Sprenkeln&quot; zum Ebenenstapel hinzufügen.
1. Unter der Ebene &quot;Splatter&quot; werden Eingabefächer angezeigt.
1. Optional können Sie die Anzahl der verfügbaren Eingabesteckplätze mit **Basisparametern > Material-Eingabe** ändern.
1. Ziehen Sie Materialien in die Splatter-Eingabefächer

Sie können die Parameter für die Streuung im **Eigenschaften-Bedienfeld** anpassen, indem Sie die Farbspritzer-Ebene auswählen.

Sie können die Parameter für die Eingabeparameter im **Eigenschaften-Material** anpassen, indem Sie das Material im Eingabebereich auswählen.
