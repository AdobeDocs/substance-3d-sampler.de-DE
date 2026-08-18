---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/splatter.html"
breadcrumb-title: ''
description: Verwende den Farbspritzer-Generator in Substance 3D Sampler, um Farbspritzer und zufällige Mustereffekte für Materialtexturen zu erstellen.
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

Verteile Instanzen anderer Materialien über dein Material.

>[!NOTE]
>
> Verwenden Sie bei Atlasmaterialien stattdessen den Filter &quot;Atlas Scatter&quot;.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Materialeingabe**:\
  Wählen Sie die Anzahl der Materialien aus, die als Eingaben verwendet werden sollen. Hinweis: eine Splatter-Ebene mit 3 Eingangsschlitzen, aber nur einem mit einem Eingang gefüllten Schlitz, wird anders aussehen als eine Splatter-Ebene mit 1 Eingangsschlitz und dieser Schlitz mit demselben Eingang gefüllt. Aus diesem Grund wird empfohlen, nur so viele Eingaben zu verwenden, wie erforderlich sind.
* **Rastergröße**: 1-64\
  Die Rastergröße bestimmt die Anzahl der Instanzen, die vom Filter &quot;Farbfläche&quot; erstellt werden.
* **AO Height Tiefe**: 0-1\
  Passen Sie die Stärke des AO für die vom Filter erstellten Instanzen an.

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
  Ändert den Einfluss der Normalen des zugrunde liegenden Materials auf die Drehung von Instanzen.

**Grundfarbe**

* **Übereinstimmung der Albedo**: 0-1\
  Die Farbe von Instanzen an die Farbe des darunter liegenden Materials anpassen.
* **HSL-Anpassung**: 0-1\
  Farbton, Sättigung und Helligkeit von Instanzen anpassen.
* **HSL Random**: 0-1\
  Steuern Sie die Zufälligkeit des Farbtons, der Sättigung und der Helligkeit jeder Instanz

**Normal**

* **Normal von** **Hintergrund**: 0-1\
  Passen Sie an, wie sehr sich die Normale des Materials unter jeder Instanz auf die Normale der Instanz auswirkt.
* **Normalwinkel zufällig**: 0-1\
  Neigen Sie die Normalen jeder Instanz zu einem zufälligen Winkel.

**Raueit**

* **Raueitskorrektur**: -1 bis 1\
  Gleichmäßiges Hinzufügen oder Entfernen des Raueitswerts über Instanzen hinweg
* **Unregelmäßigkeit zufällig**: -1 bis 1\
  Addieren oder Subtrahieren des Raueitswerts jeder Instanz nach dem Zufallsprinzip
* **Raueit aus dem Hintergrund**: 0-1\
  Passen Sie an, wie sehr sich der Raueitswert des zugrunde liegenden Materials auf den Raueitswert jeder Instanz auswirkt.

**Height**

* **Height-Offset**: -1 bis 1\
  Versatz des Heights von Instanzen. Dies kann sich darauf auswirken, wie sich Instanzen mit dem zugrunde liegenden Material mischen.
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
  Legen Sie fest, wie sich die Hintergrundstruktur des Heights auf die Instanzen der Height-Map auswirkt. Dadurch können Sie Instanzen um die Hintergrunddetails verkleinern
* **Glätten konformer Hintergrund**: 0-1\
  Passen Sie an, wie viele Details aufgrund von **Mit Hintergrund konform** sichtbar sind.

**Metallisch**

* **Metallische Anpassung**: -1 bis 1\
  Steuern der metallischen Werte von Instanzen
* **Metallisch zufällig**: -1 bis 1\
  Hinzufügen oder Entfernen zufälliger Werte aus der Metallisierung jeder Instanz
* **Metallisch aus Hintergrund**: 0-1\
  Passen Sie den Einfluss der metallischen Hintergrundwerte auf jede Instanz an.

**Maske**

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren Sie diese Option, um eine benutzerdefinierte Maske zu verwenden und auf die Steuerelemente für benutzerdefinierte Masken zuzugreifen:
  * **Benutzerdefinierte Maske**: Bild/Pinsel\
    Bild importieren, um es als benutzerdefinierte Maske zu verwenden, oder direkt in der **2D-Ansicht malen**
  * **Benutzerdefinierte Maskenunschärfe**: 0-1\
    Die Kanten der benutzerdefinierten Maske weichzeichnen.
  * **Benutzerdefinierte Maskenumkehrung**: Knebel
  * **Benutzerdefinierte Maskendeckkraft**: 0-1\
    Stärke der benutzerdefinierten Maske anpassen.

Benutzerhandbuch

Der Filter &quot;Farbspritzer&quot; ist nützlich, um Elemente über Ihr Material hinweg Streuung, z. B. Blätter, Steine oder Müll.

So verwenden Sie den Splatter-Filter:

1. Füge den Filter &quot;Sprenkeln&quot; zu deinem Ebenenstapel hinzu.
1. Unter der Ebene &quot;Splatter&quot; werden Eingabefächer angezeigt.
1. Ändern Sie optional die Anzahl der verfügbaren Eingabeschlitze mit **Basisparametern > Materialeingabe**.
1. Ziehen Sie Materialien in die Splatter-Eingabefächer.

Sie können die Parameter für die Streuung im **Eigenschaften-Bedienfeld** anpassen, indem Sie die Farbspritzer-Ebene auswählen.

Sie können die Parameter der Eingabematerialien im Bedienfeld **Eigenschaften** anpassen, indem Sie das Material im Eingabeschacht auswählen.
