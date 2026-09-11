---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/nadir-patch.html"
breadcrumb-title: ''
description: Verwende das Nadir Patch-Tool in Substance 3D Sampler, um den Tiefpunkt von HDR-Bildern für nahtlose Umgebungs-Map zu korrigieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Nadir Patch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Nadir Patch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Nadir Patch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-nadirpatch-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Patch für den Nadir deines Umgebungslichts, um Artefakte oder Nähte auszublenden.

In den folgenden Abbildungen können Sie sehen, wie **Nadir Patch** verwendet wird, um die Kamera in diesem Panoramabild zu entfernen.

![](../../assets/3d-2d-filters-cropped-0011-nadir-patch-in.jpg)![](../../assets/3d-2d-filters-cropped-0010-nadir-patch-out.jpg)

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Aktivieren**: Knebel\
  Aktivieren oder deaktivieren Sie den Patch - dies kann nützlich sein, um schnell die Auswirkungen des Patches zu sehen, ohne die Sichtbarkeit der Ebene ändern zu müssen.
* **Helfer der Rahmen anzeigen**: Knebel\
  Schalten Sie die Rahmen ein oder aus.
* **Rahmen-Thickness**: 0-1\
  Passen Sie die Thickness des Rahmens an. Dies kann hilfreich sein, wenn die Quelle des Patches weit vom Nadir entfernt ist.
* **Patch-Skalierung**: 0-1\
  Passen Sie die Begrenzung des zu patchenden Bereichs an.
* **Patch-Größe**:\
  Passe die Größe des Ausschnitts an.
* **Patch-Drehung**: 0-1\
  Drehen Sie die Ausbesserungsbegrenzungen. Dadurch werden sowohl die Quelle als auch die Ausbesserungsstelle gedreht, sodass der Ausbesserungsbereich immer noch dieselbe Ausrichtung hat. Um den Patch an Ort und Stelle zu drehen, verwenden Sie **Offset für Quelldrehung**.
* **Patch-Alpha**:\
  Wählen Sie die Form aus, die zum Maskieren der Ausbesserung verwendet wird. Wenn **Maskeneingabe** ausgewählt ist, wird ein zusätzlicher Parameter angezeigt:
  * **Maskeneingabe**: Bild/Pinsel\
    Importieren Sie ein Bild, das als Maske verwendet werden soll, oder Malen einer Maske direkt in die **2D-Ansicht**.
* **Patch-Härte**: 0-1\
  Passen Sie die Weichzeichnung an den Kanten der Korrekturmaske an.
* **Offset für Quelldrehung**: 0-1\
  Versetzen Sie die Drehung der Quelle - dies hat den Effekt, dass der Patch gedreht wird.

## Benutzerhandbuch

Ein häufiges Problem, das beim Erstellen eines Umgebungslichts aus Fotos auftreten kann, sind Artefakte am oberen und unteren Rand der Textur. Der **Nadir Patch** **filter** hilft dabei, diese Probleme zu minimieren.

1. Fügen Sie den **Nadir Patch-Filter** oben im Ebenenstapel hinzu.
1. Verwenden Sie das Handle in der **2D-Ansicht**, um den Quellspeicherort für den Patch zu ändern.
   1. Der gepatchte Nadir ändert sich je nach Speicherort der Quelle. Befindet sich die Quelldatei in der unteren Hälfte der Textur, wird ein Patch für den unteren Nadir-Bereich erstellt. Wenn sich die Quelle in der oberen Hälfte befindet, wird der oberste Nadir gepatcht.
1. Passen Sie die Parameter an, um den transformieren des Patches zu optimieren und Nähte und Artefakte optimal auszublenden.
