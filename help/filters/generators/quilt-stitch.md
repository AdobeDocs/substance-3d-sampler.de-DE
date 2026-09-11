---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/quilt-stitch.html"
breadcrumb-title: ''
description: Verwenden Sie den Generator für Sammelflächen-Nähte in Substance 3D Sampler, um Muster aus gesteppten Stoffen und Nähstrukturen für Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Quilt Stitch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Steppstich
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---


# Steppstich

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-quiltstitch-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit diesem Filter kannst du ein Steppmuster in deinen Materialien simulieren.

*Vor und nach dem Anwenden des **Sammelflächennähfilters**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0005-quilt-stitch-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0004-quilt-stitch-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Musterauswahl**:\
  Wählen Sie den Musterstil für die Masche/Sammelfläche aus, der gefolgt werden soll.
* **Betrag**: 1-5\
  Steuern des Ausmaßes der Unterteilung des Musters
* **Drehung**:\
  Muster drehen.
* **topstitch**: Knebel\
  Aktivieren Sie diese Option, um eine topstitch hinzuzufügen und den entsprechenden Parameterabschnitt anzuzeigen.
* **Naht**: Knebel\
  Aktivieren, um eine Naht hinzuzufügen und den entsprechenden Parameterabschnitt anzuzeigen
* **Sammelfläche**: Knebel\
  Aktivieren Sie diese Option, um die Auffüllung hinzuzufügen und den entsprechenden Parameterabschnitt anzuzeigen.
* **Edge-Malen**: Knebel\
  Aktivieren Sie diese Option, um die Kante zwischen gesteppten Abschnitten zu entfernen und den entsprechenden Parameterabschnitt anzuzeigen.
* **Erweitert**: Knebel\
  Aktivieren, um die **erweiterten** Parameter anzuzeigen

**topstitch**

* **topstitch color**: Farbauswahl\
  Festlegen der Farbe des für die topstitch verwendeten Fadens
* **Versatz der Spitzenstiche**: 0-1\
  Steppstich von den Kanten des Steppbereichs verschieben
* **Topstitch-Drehung**: 0-1\
  Ausrichtung der Maschen ändern, aus denen die erste Masche besteht
* **topstitch-Skalierung**: 0-1\
  Passen Sie die Größe der Masche in jeder Dimension an - Breite, Länge und Height.
* **Punktierungsintensität**: 0-1\
  Einzug in die durch die Masche verursachte Steppdecke anpassen.
* **topstitch-Rauheit**: 0-1\
  Anpassen der Rauheit des Threads
* **topstitch Metallic**: 0-1\
  Anpassen des metallic Werts des Threads

**Naht**

* **Naht** **Auswahl**:\
  Wählen Sie den Stil der zu verwendenden Naht aus
* **Intensität der Naht**: 0-1\
  Ändern der Normal- und Height-Intensität der Naht
* **Intensität Gedehnt**: 0-1\
  Passen Sie an, wie stark der dehn des Stoffes die Naht beeinflusst. Dieser Effekt ist ziemlich subtil.

**Sammelfläche**

* **Sammelflächentyp**:\
  Wählen Sie den zu verwendenden Stil für die Steppdecke aus
* **Sammelflächenintensität**:\
  Anpassen der Normal- und Height-Intensität des Steppeffekts

**Kantenfarbe**

* **Kantenauswahl**:\
  Wählen Sie aus, ob der Schmerz die Height- und Normaldetails des zugrunde liegenden Materials überschreibt oder nicht.
* **Kantenfarbe**: Farbauswahl\
  Auswählen der Malen
* **Kantenrauigkeit**: 0-1
* **Edge Metallic**: 0-1

**Erweitert**

* **Basismaterial-Height**: 0-1\
  Passen Sie die Stärke des Höhen-Map vom zugrunde liegenden Material aus an
* **Normalintensität**: 0-1\
  Passen Sie die Stärke der normalen Map-Änderungen aufgrund des **Sammelflächennähts**-Filters an. Dies wirkt sich nicht auf die Normalität des zugrunde liegenden Materials aus.
