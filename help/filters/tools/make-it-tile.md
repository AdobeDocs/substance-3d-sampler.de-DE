---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/make-it-tile.html"
breadcrumb-title: ''
description: Verwenden Sie das Kachelwerkzeug in Substance 3D Sampler, um aus nicht kachelbaren Texturen automatisch nahtlose Kachelmuster zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Make it Tile
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Anordnen.
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '556'
ht-degree: 0%

---


# Anordnen.

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den Filter **Kachel erstellen**, um Ihr Material kachelbar zu machen. Der **Kachelfilter** macht Ihr Material ebenfalls kachelbar, aber jeder Filter funktioniert auf andere Weise. Wenn Sie feststellen, dass der **Kachelfilter erstellen** nicht funktioniert, versuchen Sie es mit dem **Kachelfilter**.

In den folgenden Bildern können Sie sehen, wie der **Filter &quot;Make it Tile&quot;** ein nicht gekacheltes Material in ein kachelbares Material konvertieren kann. Dieses Material ist gut kachelbar, weil es einem rasterartigen Muster folgt und es keine spezifischen Punkte gibt, die den Fokus ziehen.

![](../../assets/3d-2d-filters-cropped-0015-make-it-tile-in.jpg)

In der Abbildung oben zeigt die rote Linie die Begrenzung des Materials. Es ist ganz klar, dass es eine starke Naht gibt, und dass dieses Material nicht kachelt.

![](../../assets/3d-2d-filters-cropped-0014-make-it-tile-out.jpg)

Nach **Make it Tile**, dieses Material gut kachelt und ohne die rote Linie, wäre es unmöglich, Nähte an den Rändern des Materials zu sehen.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Schwellenwert**: 0-1\
  Passen Sie die Größe und den Abgleich der obersten Ebene an.
* **Smoothness**: 0-1\
  Glätte die Naht der oberen Ebene.
* **Kontrast**: 0-1\
  Passen Sie den Kontrast der Naht an. Die Verringerung des Kontrasts hat den gleichen Effekt wie die Weichzeichnung der Naht.
* **Entfernen von Bereichen**: Knebel\
  Wenn diese Option aktiviert ist, versucht der Filter, Artefakte in der Nähe der Naht zwischen der oberen und unteren Ebene zu entfernen.
* **Color Equalizer**: 0-50\
  Passen Sie die Farbwerte an, um die Sichtbarkeit der Naht zu verringern.
* **Height-Übereinstimmung**:\
  Ändern Sie, wie die Height Maps für die obere und untere Ebene des Filters angeglichen werden. Zeigen Sie den Height-Kanal in der **2D-Ansicht** an, um die Ergebnisse besser zu sehen. Beachten Sie, dass sich der Height-Abgleich nicht auf andere Kanäle als den Height-Kanal auswirkt, sodass die Normalen und AO nicht von Änderungen am Height-Abgleich betroffen sind.

**Erweiterte Parameter**

* **Chrominanzeinfluss**: 0-1\
  Passen Sie an, wie stark die Farbwerte die Naht beeinflussen.
* **Umkehren der Maske**: Knebel\
  Kehre die Masken der oberen und unteren Ebenen um.
* **Smoothness mit passendem Height**: 0-16\
  Passen Sie die Weichzeichnung von Heights an, die zwischen der oberen und unteren Ebene übereinstimmen.
* **Patch-Quelle links/rechts**: -1 bis 1\
  Passen Sie den Quellspeicherort für das linke und das rechte Patch an.
* **Quelle für oberen/unteren Patch**: -1 bis 1\
  Passen Sie den Quellspeicherort für die oberen und unteren Patches an.

## Benutzerhandbuch

Der **Make it Tile** **filter** funktioniert, indem mehrere Kopien des Materials übereinander gelegt werden.

Die folgende Abbildung zeigt das Layout der Ebenen:

* Der grüne Rand zeigt die Kanten des resultierenden Materials aus dem **Filter &quot;Kacheln&quot; erstellen**.
* Die roten Linien zeigen die Ränder der unteren Ebene an. Die untere Schicht ist um 50 % des UV-Raumes auf der X- und Y-Achse versetzt, sodass die roten Linien Kachelnähte sind, die abgedeckt werden müssen.
* Das blaue Quadrat und die Halbkreise bedecken die roten Nähte. Mit den Parametern des Filters können Sie die Ränder der blauen Formen anpassen, um sicherzustellen, dass die rote Naht nicht sichtbar ist, während die blaue Naht so glatt wie möglich bleibt.

![](../../assets/makeittilediagram.png){width="512px"}

Die linken und rechten Halbkreise passen zueinander, um die Materialfliesen horizontal zu sichern, und die oberen und unteren Halbkreise sorgen für die vertikalen Materialfliesen. Das blaue Quadrat in der Mitte entfernt alle verbleibenden Nähte, um ein vollständig kachelbares Material ohne Nähte zu erstellen.
