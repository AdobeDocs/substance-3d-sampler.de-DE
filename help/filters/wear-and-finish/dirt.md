---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/dirt.html"
breadcrumb-title: ''
description: Mit dem Filter "Dirt" in Substance 3D Sampler lassen sich Materials und Texturen durch realistische Akkumulation von Dirt und Grime-Effekte aufwerten.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Dirt
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Verschmutzung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '289'
ht-degree: 1%

---


# Verschmutzung

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-dirt-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Dirt-Filter**, um Dirt über einem Material hinzuzufügen. Der **Dirt-Filter** eignet sich hervorragend, um Materialien älter und ungepflegt erscheinen zu lassen.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-before-tra.png)

Vergleichen Sie die obigen sauberen Kacheln mit dem Dirt-Filter, der unten auf sie angewendet wurde.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-after-tra.png)

</td>
</tr>
</table>

## Parameter

<b>Basisparameter</b>

* <b>Zufallsparameter</b>: \
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.

* <b>Dirt Spread</b>: 0-1 \
  Steuert die Ausdehnung der vom Dirt abgedeckten Oberfläche

* <b>Spread des obersten Dirts</b>: 0-1\
  Steuert die obere Fläche, die von Dirt bedeckt ist, ohne die Falten des Materials zu fokussieren.

* <b>Kontrast des Dirts</b>: 0-1 \
  Passen Sie den Kontrast zwischen den verschiedenen Dirt-Flecken an, um zu steuern, wie sich der Dirt mit dem darunter liegenden Material vermischt.

* <b>Deckkraft des Dirts</b>: 0-1 \
  Steuert den Transparenzgrad des Dirts im Grundfarbe-Kanal. 1 ist vollständig deckend.

* <b>Farbe des Dirts</b>: 0-1 \
  Wählen Sie die Farbe des Dirts aus.

* <b>Dirt-Rauheit</b>: 0-1 \
  Anpassen, wie helle Streuungen auf der Oberfläche des Materials

* <b>Dirt Metallic</b>: 0-1 \
  Definieren Sie, wie reflektierend die Oberfläche des Dirts ist.

* <b>Dirt-Height</b>: 0-1 \
  Steuert die Auswirkungen des Dirts auf den Höhen-Map

* <b>Normalintensität des Dirts</b>: 0-1 \
  Steuert, wie stark sich der Dirt auf den Normalen-Map auswirkt

* <b>Oberflächenfehler verwenden</b>: Knebel \
  Aktivieren oder deaktivieren Sie die Verwendung einer Oberflächenunvollkommenheit. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:

  <b>Oberflächenstörungen</b>: Bild \
  Importieren Sie ein Bild, um es als Oberflächenunvollkommenheit zu verwenden, oder verwenden Sie einen der Bildgeneratoren, die standardmäßig in der Sampler-Elementbibliothek verfügbar sind, z. B. &quot;Textur&quot; oder &quot;Schönheitsfehler&quot;
