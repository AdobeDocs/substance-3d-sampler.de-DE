---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/wear-and-finish/rust.html"
breadcrumb-title: ''
description: Verwenden Sie den Rost-Filter in Substance 3D Sampler, um Materialien und Flächen aus Metall realistische Rost- und Korrosionseffekte zu verleihen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Rust
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Rost
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 1%

---


# Rost

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-rust-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Rost-Filter**, um Ihrem Material eine Oxidationsmetallschicht hinzuzufügen.

In den folgenden Abbildungen sehen Sie ein Metallmaterial vor und nach dem Hinzufügen des **Rost-Filters**.

![](../../assets/3d-filters-cropped-0002-rust-out.jpg){width="200px"}

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Rost Spread**: 0-1\
  Steuern Sie den Druckbogen oder die Menge des Rosts.
* **Kanteneinfluss**: 0-1\
  Passen Sie an, wie Rost auf der Grundlage der Krümmungszuordnung mit Kanten interagiert.
* **Spread-Smoothness**: 0-1\
  Erhöhen Sie diesen Wert, um die verrosteten Bereiche blubbiger zu machen, oder verringern Sie ihn, um sie detaillierter zu machen.
* **Nur Metall betreffen**: Knebel\
  Wenn diese Option aktiviert ist, wirkt sich der **Rost-Filter** nur auf Bereiche aus, deren metallic Wert größer als 0 ist.

**Rost**

* **Rost Shape**:\
  Ändern Sie das Muster, auf dem der Rost basiert.
* **Rost-Intensität**: 0-1\
  Ändern Sie die Stärke des Effekts &quot;Rost&quot;. Wenn Sie diesen Wert erhöhen, wird der Rost älter und stärker.

**Peel**

* **Peel-Skalierung**: 0-1\
  Ändern Sie die Skalierung des Peeling-Rosts.
* **Normalintensität schälen**: 0-1\
  Passen Sie die Sichtbarkeit der Schälnormale an.
* **Peel-Height-Intensität**: 0-1\
  Passen Sie die Wirkung der Peels auf dem Höhen-Map an.

**Treiber**

* **Drips-Intensität**: 0-1\
  Ändern Sie die Stärke des Tropfeffekts.
* **Drips-Ausrichtung**: 0-1\
  Die Tropfen so ausrichten, dass sie zur Schwerkraft oder zum Wind passen.
* **Länge der Tropfen**: 0-1\
  Passen Sie an, wie weit die Tropfen von der Quelle entfernt sind.

**Maske**

* **Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Die Maske weichzeichnen.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.
