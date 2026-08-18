---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/height-to-normal.html"
breadcrumb-title: ''
description: Verwenden Sie das Height-Normal-Werkzeug in Substance 3D Sampler, um Height-Maps in Normal-Maps für Materialerstellungs-Workflows zu konvertieren.
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

In der obigen Abbildung sind keine normalen Daten aus dem Material vorhanden. Nur die Height-Map ist verfügbar und wird in der **2D-Ansicht** angezeigt.

![](../../assets/h2n-out.jpg)

Mit dem Filter &quot;**Height zu Normal&quot;** werden Normaldaten aus der Bildzuordnung generiert, die im oberen Height angezeigt wird. Das Licht reflektiert das Material im zweiten Bild realistischer, da eine Normalmap erzeugt wird.

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
      Legen Sie den Abstand fest, der durch die Height-Map dargestellt wird. Wenn die Height-Map eine kleine Entfernung darstellt, kann eine große Differenz bei den Height-Map-Werten einen kleinen Einfluss auf den Normalwinkel haben. Wenn die Height-Map eine große Entfernung darstellt, kann eine kleine Differenz der Height-Map-Werte einen großen Winkel auf der Normalmap darstellen.
  * **Wenn &quot;World Units verwenden&quot; deaktiviert ist:**
    * **Intensität**: 0-3\
      Anpassen der Steilheit der normalen Winkel
* **Unten Normalzustand zusammenführen**: 0-1\
  Fügen Sie den Ergebnissen dieses Filters die vorhandene Normalmap hinzu.

**Maske**

* **Benutzerdefinierte Maske**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Weichzeichnen der Maske
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Maske umkehren.
