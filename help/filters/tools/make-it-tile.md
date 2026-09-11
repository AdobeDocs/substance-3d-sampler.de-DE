---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/make-it-tile.html"
breadcrumb-title: ''
description: Verwenden Sie das Kachelwerkzeug in Substance 3D Sampler, um aus Nicht-Kachelung-Texturen automatisch nahtlose Kachelungen-Muster zu erstellen.
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

Verwenden Sie den **Kachelfilter erstellen**, um Ihr Material kachelbar zu machen. Mit dem **Filter für Kachelungen** können Sie Ihr Material auch kachelbar machen, aber jeder Filter funktioniert auf andere Weise. Wenn Sie feststellen, dass der **Kachelfilter erstellen** nicht funktioniert, versuchen Sie den **Kachelung-Filter**.

In den folgenden Abbildungen können Sie sehen, wie der **Filter &quot;Anordnen in Kachel erstellen&quot;** ein Material ohne Kachelung in ein kachelbares Material konvertieren kann. Dieses Material passt gut zu einem Motiv, weil es einem Raster-ähnlichen Muster folgt und es keine spezifischen Punkte gibt, die den Fokus lenken.

![](../../assets/3d-2d-filters-cropped-0015-make-it-tile-in.jpg)

Die rote Linie in der Abbildung oben zeigt die Begrenzung des Materials. Es ist ganz klar, dass es eine starke Naht gibt und dass dieses Material nicht kachelt.

![](../../assets/3d-2d-filters-cropped-0014-make-it-tile-out.jpg)

Nach **Kachel erstellen**, kachelt dieses Material gut und ohne die rote Linie, es wäre unmöglich, Nähte an den Rändern des Materials zu sehen.

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
  Den Kontrast der Naht anpassen. Die Verringerung des Kontrasts hat den gleichen Effekt wie die Weichzeichnung der Naht.
* **Entfernen von Bereichen**: Knebel\
  Wenn diese Option aktiviert ist, versucht der Filter, Artefakte in der Nähe der Naht zwischen der oberen und unteren Ebene zu entfernen.
* **Color Equalizer**: 0-50\
  Passen Sie Farbwerte an, um die Sichtbarkeit der Naht zu verringern.
* **Height-Übereinstimmung**:\
  Lege fest, wie die Höhen-Map an die obere und untere Filterebene angeglichen werden. Zeigen Sie den Height-Kanal in der **2D-Ansicht** an, um die Ergebnisse deutlicher zu sehen. Beachten Sie, dass sich der Height-Abgleich nicht auf andere Kanäle als den Height-Kanal auswirkt, sodass die Normalen und AO nicht von Änderungen am Height-Abgleich betroffen sind.

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

* Der grüne Rand zeigt die Kanten des resultierenden Materials aus dem **Filter &quot;Kacheln&quot; erstellen** an.
* Die roten Linien zeigen die Ränder der unteren Ebene an. Die untere Ebene wird um 50 % des UV-Abstands auf der X- und Y-Achse versetzt. Die roten Nähte sind also Kachelungen, die überdeckt werden müssen.
* Das blaue Quadrat und die Halbkreise bedecken die roten Nähte. Mit den Filterparametern können Sie die Ränder der blauen Formen anpassen, um sicherzustellen, dass die rote Naht nicht zu sehen ist, während die blaue Naht so glatt wie möglich bleibt.

![](../../assets/makeittilediagram.png){width="512px"}

Die linken und rechten Halbkreise passen zusammen, um die Material-Kacheln horizontal zu gewährleisten, und die oberen und unteren Halbkreise sorgen für die vertikalen Material-Kacheln. Das blaue Quadrat in der Mitte entfernt alle verbleibenden Nähte und bildet so ein vollständig kachelbares Material ohne Nähte.
