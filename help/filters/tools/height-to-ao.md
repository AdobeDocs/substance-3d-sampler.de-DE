---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/height-to-ao.html"
breadcrumb-title: ''
description: Verwenden Sie das Height-zu-AO-Tool in Substance 3D Sampler, um Höhen-Map in ambient occlusion-Maps für die Erstellung von Materials zu konvertieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to AO
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Height in AO
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 1%

---


# Height in AO

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hbao-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Generieren Sie eine Ambient occlusion-Map aus Height- und Normaldaten.

Sehen Sie sich die Ergebnisse des **Height-zu-AO-Filters** in den folgenden Abbildungen an.

![](../../assets/3d-2d-filters-cropped-0025-height-to-ao-in.jpg)

In der Abbildung oben zeigt **2D-Ansicht** die Höhen-Map an. Das Material enthält keine Ambient occlusion-Informationen in diesem Bild.

![](../../assets/3d-2d-filters-cropped-0024-height-to-ao-out.jpg)

In diesem Image wurde die Ambient occlusion-Map vom **Height zum AO-Filter** erstellt und ist in der **2D-Ansicht** sichtbar. Ambient occlusion ist im Allgemeinen ein subtiler Effekt, daher ist er in diesem Material nicht leicht zu erkennen. Verwenden Sie den **Height-zu-AO-Filter** auf Ihren Materialien, um die AO-Intensität zu erhöhen und ein Gefühl für die Arbeit mit Ambient occlusion zu erhalten.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Modus**:\
  Legen Sie fest, ob Daten aus dem Height-Kanal, dem Normalkanal oder beiden Kanälen gemeinsam generiert werden sollen.
* **Ambient occlusion - Intensität**: 0-1\
  Stärke der generierten AO-Daten anpassen
* **Ambient occlusion - Druckbogen**: 0-1\
  Radius der generierten AO-Daten anpassen
