---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/height-to-normal.html"
breadcrumb-title: ''
description: Mit dem Substance 3D Sampler-Tool "Height in Normal" können Sie Höhen-Map in Normalen-Map umwandeln, um Materials zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to Normal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Height in Normal
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# Height in Normal

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-heighttonormal-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Generieren Sie auf der Grundlage des Height-Kanals normale Kanaldaten.

In den folgenden Abbildungen sehen Sie den Filter **Height zu Normal** in Aktion.

![](../../assets/h2n-in.jpg)

In der Abbildung oben sind keine normalen Daten aus dem Material vorhanden. Nur die Höhen-Map ist verfügbar und wird in der **2D-Ansicht** angezeigt.

![](../../assets/h2n-out.jpg)

Mit dem Filter &quot;**Height zu Normal&quot;** werden Normaldaten von der im oberen Bild angezeigten Höhen-Map generiert. Das Licht reflektiert das Material im zweiten Bild realistischer als auf der erzeugten Normalen-Map.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Welteinheiten verwenden**: Knebel\
  Ändert, ob Parameter mit realen Einheiten gemessen werden. Dadurch wird geändert, welche Parameter verfügbar sind.
  * **Wenn &quot;World Units verwenden&quot; aktiviert ist:**
    * **Oberflächengröße (cm)**: 0-500\
      Legen Sie die Größe des UV-Raums in weltweiten Einheiten fest.
    * **Height Tiefe (cm)**: 0-10\
      Legen Sie den Abstand fest, der durch den Höhen-Map dargestellt wird. Wenn der Höhen-Map eine kleine Entfernung darstellt, kann eine große Differenz bei den Höhen-Map-Werten einen kleinen Einfluss auf den Normalwinkel haben. Wenn der Höhen-Map eine große Entfernung darstellt, kann eine kleine Differenz der Höhen-Map-Werte einen großen Winkel auf dem Normalen-Map darstellen.
  * **Wenn &quot;World Units verwenden&quot; deaktiviert ist:**
    * **Intensität**: 0-3\
      Anpassen der Steilheit der normalen Winkel
* **Unten Normalzustand zusammenführen**: 0-1\
  Fügen Sie den Ergebnissen dieses Filters die vorhandene Normalmap hinzu.

**Maske**

* **Benutzerdefinierte Maske**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um eine benutzerdefinierte Maske direkt in die 2D-Ansicht Malen
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Weichzeichnen der Maske
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Maske umkehren.
