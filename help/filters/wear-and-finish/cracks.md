---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/cracks.html"
breadcrumb-title: ''
description: Verwenden Sie den Risse-Filter in Substance 3D Sampler, um Ihren Materials realistische Rissmuster und Oberflächenbeschädigungseffekte hinzuzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Cracks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Risse
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 1%

---


# Risse

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-cracks-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Risse-Filter**, um Ihr Material zu altern und zu beschädigen, indem Sie ihm ein Netzwerk mit Rissen und Spalten hinzufügen.

Der **Risse-Filter** wurde auf ein sauberes Marmorfilter-Material angewendet.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0043-cracks-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0042-cracks-out.jpg){width="200px"}

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
* **Risse Spread**: 0-1\
  Passen Sie an, wie weit die Risse sich ausbreiten - dadurch werden sowohl die Rissbreite als auch die Risslänge geändert.
* **Anzahl der Risse**: 0-1\
  Ändern Sie, wie viele Risse angezeigt werden.

**Maske**

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.

**Risse**

* **Farbe für Risse**: Farbauswahl\
  Ändern Sie die Farbe der Innenfläche, die von den Rissen aufgedeckt wird.
* **Risse Rauheit**: 0-1\
  Passen Sie die Rauheit der Risse an.
* **Risse Rauheit Deckkraft**: 0-1\
  Passen Sie an, wie sich der Wert **Risse Rauheit** auf die Rauheiten-Map auswirkt.
* **Metallic Risse**: 0-1\
  Ändern Sie den metallic Wert der Risse.
* **Metallic Deckkraft der Risse**: 0-1\
  Anpassen, wie sich der Wert **Risse Metallic** auf die metallic Map auswirkt
* **Risse Height-Intensität**: 0-1\
  Passen Sie die Tiefe der Risse an. Dies wirkt sich sowohl auf das Höhen-Map- als auch auf das Normalen-Map-Ergebnis des Filters aus.

**Erweiterte Parameter**

* **Normalintensität**: 0-1\
  Passen Sie die Stärke der Rissnormalitäten an.
* **Height-Bereich**: 0-1\
  Ändern Sie den Bereich des Heights des gesamten Materials. Verwenden Sie zum Anpassen des Heights der Risse **Risse > Risse Height Intensität**.
* **Height-Position**: 0-1\
  Versatz der Höhen-Map des gesamten Materials.
