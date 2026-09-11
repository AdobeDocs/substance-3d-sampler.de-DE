---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/gravel.html"
breadcrumb-title: ''
description: Verwenden Sie den Kies-Generator in Substance 3D Sampler, um realistische Texturen aus Kies und Gestein für Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Gravel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Schotter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '457'
ht-degree: 0%

---


# Schotter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-gravel-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem Filter &quot;Kies&quot; kannst du auf natürliche Weise Kies über dein Material legen und Gletscherspalten füllen.

Diese Bilder zeigen den **Kiesfilter**, der zum Füllen der Spalten eines Schlammes mit Kies verwendet wird.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0029-gravel-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0028-gravel-out.jpg)

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
* **Menge**: 0-1\
  Ändern Sie die Stärke des Kieses, der sich über das Material verteilt.
* **Primärfarbe**: Farbauswahl\
  Wählen Sie die Grundfarbe der Schottersteine aus
* **Sekundäre Farbe**: Farbauswahl\
  Sekundärfarbe der Kiessteine auswählen
* **Farbabgleich für unteres Material**: 0-1\
  Legt fest, wie stark die Schotterfarbe von der Hintergrundfarbe des Materials beeinflusst wird.
* **Hohlraummaske aktivieren**: Knebel\
  Wenn diese Option aktiviert ist, füllt der Kies Hohlräume und wird nicht auf höhere Teile des Materials verteilt. Dies kann zu einer realistischeren Kiesstreuung führen.
* **Schwellenwert für Streuvolumen**: 0-50\
  Anpassen der Streuungslautstärke auf Basis der Werte in den Heights
* **Zufällige Maskierung**: 0-1\
  Den Kiesanteil so einstellen, dass er zufällig maskiert wird
* **Steingröße**: 1-10\
  Die Größe der Steine kontrollieren.
* **Steingrößenvariation**: 0-1\
  Zufälligkeit der Steingröße steuern
* **Steinrundung**: 0-1\
  Steine runderer oder mehr angular machen
* **Stone-Rauheit**: 0-1\
  Ändern Sie die Rauheit der Steine.
* **Stone-Height**: 0-1\
  Ändern Sie das Height der Steine. Dies beeinflusst, wie sich die Steine mit dem darunter liegenden Material vermischen.
* **Steinerhebung**: 0-1Ändern Sie die Grundhöhe der Steine. Die Höhe legt den Fußboden der Steine fest, während das Height das Height der Steine vom Fußboden absetzt.
* **Steinzunahme zufällig**: 0-1\
  Fügen Sie der Höhe jedes Steins einen zufälligen Wert hinzu.
* **Surface-Smoothness**: 0-1\
  Glätten der Steinspitzen
* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske zum Malen von Steinpositionen. Die folgenden Parameter sind nur sichtbar, wenn **Benutzerdefinierte Maske verwenden** aktiviert ist.
  * **Maske weichzeichnen**: 0-1\
    Weichzeichnen der Kanten der gemalten Maske
  * **Benutzerdefinierte Maske**: Bild/Pinsel\
    Klicken Sie auf den Pinsel, um eine benutzerdefinierte Maske Malen, in der Steine angezeigt werden. Klicken Sie auf das Quadrat, um ein Bild zu importieren, das als Maske verwendet werden soll.

**Erweiterte Parameter**

* **Oberflächengröße (cm)**: 0-1000\
  Passen Sie die Größe der Fläche an, die durch Ihr Material repräsentiert wird. Durch die Vergrößerung der Oberfläche ist die Physische Größe der Schottersteine größer, und sie werden entsprechend angepasst.
* **Height Tiefe** **(cm)**: 0-100\
  Ändern Sie die physische Tiefe, die durch den Höhen-Map Ihres Materials dargestellt wird. Eine erhöhte Tiefe der Heights bedeutet, dass die Physische Größe der Steine höher ist, als sie es sonst wäre, sodass die Normalintensität der Steine erhöht wird.
