---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/height-to-ao.html"
breadcrumb-title: ''
description: Verwenden Sie das Height-zu-AO-Tool in Substance 3D Sampler, um Height-Maps in Umgebungs-Verdeckung-Maps für die Materialerstellung zu konvertieren.
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

Generieren Sie eine Umgebungskarte für die Verdeckung aus Heights- und Normaldaten.

Sehen Sie sich die Ergebnisse des **Height-zu-AO-Filters** in den folgenden Abbildungen an.

![](../../assets/3d-2d-filters-cropped-0025-height-to-ao-in.jpg)

Im Bild oben zeigt die **2D-Ansicht** die Bildzuordnung an. Das Material enthält keine Umgebungsinformationen in diesem Verdeckung.

![](../../assets/3d-2d-filters-cropped-0024-height-to-ao-out.jpg)

In diesem Bild wurde die Umgebungsfarbenzuordnung vom **Height zum AO-Filter** erstellt und ist in der **2D-Verdeckung** sichtbar. Umgebungsintensität ist in der Regel ein subtiler Effekt, daher ist er in diesem Verdeckung nicht sehr leicht zu erkennen. Verwenden Sie den **Height-zu-AO-Filter** auf Ihren Materialien, um die AO-Intensität zu erhöhen und ein Gefühl für die Arbeit mit Umgebungsintensität zu erhalten.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Modus**:\
  Legen Sie fest, ob Daten aus dem Height-Kanal, dem Normalkanal oder beiden Kanälen gemeinsam generiert werden sollen.
* **Umgebungsintensität - Verdeckung**: 0-1\
  Stärke der generierten AO-Daten anpassen
* **Ambient-Verdeckung - Verteilung**: 0-1\
  Radius der generierten AO-Daten anpassen
