---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/wear-and-finish/paint.html"
breadcrumb-title: ''
description: Verwenden Sie den Malen-Filter in Substance 3D Sampler, um Ihren Materials Malebenen, Beschichtungen und lackierte Oberflächeneffekte hinzuzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Paint
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Farbe
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 0%

---


# Farbe

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-paint-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Malen-Filter** können Sie Ihr Material in einer Malen-Ebene mit unterschiedlicher Thickness abdecken.

*Ein metallisches Material mit abgenutzter Malen wurde hinzugefügt.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0017-paint-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0016-paint-out.jpg){width="200px"}

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
* **Farbe**: Farbauswahl\
  Legen Sie die Malen fest.
* **Rauheit**: 0-1\
  Legen Sie die Rauheit der Bereiche fest, die der Malen abdeckt.
* **Thickness**: 0-1\
  Stellen Sie die Viskosität und Thickness der Malen ein. Dies wirkt sich darauf aus, wie viel des zugrunde liegenden Heights und der normalen Informationen auf der Malen sichtbar sind.
* **Peel**: 0-1\
  Fügen Sie Patches hinzu, bei denen sich die Malen vom darunter liegenden Material gelöst hat.
* **Körnung**: 0-1\
  Ändern Sie die Körnung der Oberfläche der Malen.
* **Körnung**: 1-5\
  Passen Sie die Skalierung der Textur an, die zum Erzeugen der Körner verwendet wird.

**Maske**

* **Hohlraummaske**: Knebel\
  Erstellen Sie eine Maske, die auf den in der Höhen-Map gefundenen Hohlräumen basiert. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Hohlraumgröße**: 0-1\
    Passen Sie den Height-Bereich an, der zum Erstellen der Hohlraummaske verwendet wird.
  * **Hohlraumintensität**: 0-1\
    Passen Sie die Deckkraft der Maske auf der Grundlage der Tiefe der Kavität an.
  * **Kavitäts-Umkehrmaske**: Knebel\
    Kehren Sie die Hohlraummaske um, um zu ändern, ob sie sich auf Höhen- oder Tiefpunkte auswirkt.
* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um eine benutzerdefinierte Maske direkt in die 2D-Ansicht Malen.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Die Maske weichzeichnen.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.

**Erweiterte Parameter**

* **Grundfarbe**: Knebel\
  Legt fest, ob sich der Filterkanal auf die Grundfarbe auswirkt.
* **Metallic**: Knebel\
  Legt fest, ob der metallic Kanal durch den Filter beeinflusst wird.
  * **Metallic Wert**: 0-1\
    Anpassen des metallic Werts der bemalten Bereiche.
* **Rauheit**: Knebel\
  Legt fest, ob sich der Filterkanal auf die Rauheit auswirkt.
* **Normal**: Knebel\
  Legt fest, ob der normale Kanal durch den Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Normal - Intensität**: -1 bis 1\
    Passen Sie die Intensität der Normalen an.
* **Height**: Knebel\
  Legt fest, ob sich der Filterkanal auf das Height auswirkt. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Height - Intensität**: 0-1\
    Passen Sie den Kontrast des Höhen-Map an.
* **Deckkraft**: Knebel\
  Legt fest, ob der Deckkraftkanal vom Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Deckkraft - Wert**: 0-1\
    Ändert die Deckkraft des Materials.
* **Ausstrahlend**: Knebel\
  Legt fest, ob der Emissionskanal durch den Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Ausstrahlend - Farbe**: Farbauswahl\
    Legen Sie die emissive-Kanalfarbe fest.
* **Ambient-Verdeckung**: Knebel\
  Legt fest, ob der ambient occlusion-Kanal durch den Filter beeinflusst wird. Wenn diese Option aktiviert ist, werden die folgenden zusätzlichen Steuerelemente angezeigt:
  * **Ambient occlusion - Intensität**: 0-1\
    Passen Sie die Stärke der generierten AO an.
  * **Ambient occlusion** **- Radius**: 0-1\
    Passen Sie den Radius des AO-Effekts an.
