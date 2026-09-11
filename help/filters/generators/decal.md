---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/decal.html"
breadcrumb-title: ''
description: Verwenden Sie den Aufklebergenerator in Substance 3D Sampler, um Aufklebermuster und Overlay-Texturen für Material-Oberflächen zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Decal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Aufkleber
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 1%

---


# Aufkleber

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-decal-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem Filter &quot;Aufkleber&quot; können Sie Instanzen eines anderen Materials an einer bestimmten Position hinzufügen. Das ist nützlich, wenn du Sticker oder bestimmte Details hinzufügen möchtest, die bei der Erstellung nicht so einfach zu generieren sind.

Die folgenden Bilder zeigen den **Aufkleberfilter**, der verwendet wird, um dem Beton Schaden zuzufügen.

![](../../assets/3d-2d-filters-cropped-0045-decal-in.jpg)

Vor dem Aufkleber ist die Betonunterlage sauber und unbeschädigt.

![](../../assets/3d-2d-filters-cropped-0044-decal-out.jpg)

Mit dem **Aufkleberfilter** werden dem Material realistische Risse und Beschädigungen hinzugefügt.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Kachelung-Modus**:\
  Bestimmt, ob die Kachel über die Handles in der **2D-Ansicht** hinausgehen soll.\
  H steht für &quot;Horizontal&quot;, V für &quot;Vertikal&quot;.
* **Farbabgleich für unteres Material**: 0-1\
  Passen Sie die Farben des Materials an, sodass sie dem Farbwert der darunter liegenden Ebenen entsprechen.
* **Normaler Mischmodus**:\
  Anpassen, wie Normale zwischen dem Aufkleber-Material und den darunter liegenden Ebenen gemischt werden
* **Überblendung der normalen Deckkraft**: 0-1\
  Ändern der Deckkraft der Normalen des Decal-Materials
* **Decal Height Position**: 0-1\
  Height des Aufklebers im Verhältnis zum Height der darunterliegenden Ebenen anpassen.
* **Decal Height Scale**: 0-1\
  Ändern des Kontrasts der Höhen-Map für das Aufkleber-Material

**Erweiterte Parameter**

* **Dekaltransformation**:\
  Passen Sie die transformieren Matrixwerte für den Aufkleber an. Im Allgemeinen ist es einfacher, nur die Handles in der **2D-Ansicht** zu verwenden, um den transformieren des Aufklebers anzupassen.
* **Decal** **Offset**: -1 bis 1\
  Passen Sie den Versatz des Aufklebers an.

## Benutzerhandbuch

So verwenden Sie den Decal-Filter:

1. Hinzufügen des Decal-Filters zu Ihrem Ebenenstapel
1. Unter der Decal-Ebene wird ein Eingangssteckplatz angezeigt.
1. Ziehen Sie das Aufkleber-Material in den Eingangssteckplatz der Aufkleber-Ebene.

Sie können die Filterparameter im Bereich **Eigenschaften** anpassen, indem Sie die Decal-Ebene auswählen.

Sie können die Parameter des Decal-Materials im **Eigenschaftenbedienfeld** anpassen, indem Sie das Material im Eingangssteckplatz auswählen.
