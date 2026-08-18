---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/paint.html"
breadcrumb-title: ''
description: Verwenden Sie den Malfilter in Substance 3D Sampler, um Ihren Materialien Farbschichten, Beschichtungen und bemalte Oberflächeneffekte hinzuzufügen.
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

Mit dem **Farbfilter** können Sie Ihr Material in einer Farbschicht mit unterschiedlicher Thickness abdecken.

*Ein Metallmaterial mit abgenutzter Farbe darüber.*

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
  Legen Sie die Farbe fest.
* **Raueit**: 0-1\
  Stellen Sie die Raueit der von der Farbe bedeckten Bereiche ein.
* **Thickness**: 0-1\
  Stellen Sie die Viskosität und Thickness des Lackes ein. Dies beeinflusst, wie viel des zugrunde liegenden Heights und der normalen Informationen durch den Anstrich zu sehen sind.
* **Peel**: 0-1\
  Füge Flecken hinzu, an denen sich die Farbe vom Untergrund gelöst hat.
* **Körnung**: 0-1\
  Ändern Sie die Körnung der Oberfläche der Farbe.
* **Körnung**: 1-5\
  Passen Sie die Skalierung der Struktur an, die zum Erstellen der Körner verwendet wird.

**Maske**

* **Hohlraummaske**: Knebel\
  Erstellen Sie eine Maske, die auf den in der Height-Map gefundenen Hohlräumen basiert. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Hohlraumgröße**: 0-1\
    Passen Sie den Height-Bereich an, der zum Erstellen der Hohlraummaske verwendet wird.
  * **Hohlraumintensität**: 0-1\
    Passen Sie die Deckkraft der Maske auf der Grundlage der Tiefe der Kavität an.
  * **Kavitäts-Umkehrmaske**: Knebel\
    Kehren Sie die Hohlraummaske um, um zu ändern, ob sie sich auf Höhen- oder Tiefpunkte auswirkt.
* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Die Maske weichzeichnen.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.

**Erweiterte Parameter**

* **Grundfarbe**: Knebel\
  Legt fest, ob der Grundfarbkanal vom Filter beeinflusst wird.
* **Metallisch**: Knebel\
  Legt fest, ob der metallische Kanal durch den Filter beeinflusst wird.
  * **Metallischer Wert**: 0-1\
    Passen Sie den metallischen Wert der bemalten Bereiche an.
* **Raueit**: Knebel\
  Legt fest, ob der Raueitskanal vom Filter beeinflusst wird.
* **Normal**: Knebel\
  Legt fest, ob der normale Kanal durch den Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Normal - Intensität**: -1 bis 1\
    Passen Sie die Intensität der Normalen an.
* **Height**: Knebel\
  Legt fest, ob sich der Filterkanal auf das Height auswirkt. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Height - Intensität**: 0-1\
    Passen Sie den Kontrast der Height-Map an.
* **Deckkraft**: Knebel\
  Legt fest, ob der Deckkraftkanal vom Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Deckkraft - Wert**: 0-1\
    Ändert die Deckkraft des Materials.
* **Ausstrahlend**: Knebel\
  Legt fest, ob der Emissionskanal durch den Filter beeinflusst wird. Wenn aktiviert, wird ein zusätzliches Steuerelement angezeigt:
  * **Ausstrahlend - Farbe**: Farbauswahl\
    Legen Sie die Farbe des Emissionskanals fest.
* **Ambient-Verdeckung**: Knebel\
  Legt fest, ob der Kanal für die umgebende Verdeckung durch den Filter beeinflusst wird. Wenn diese Option aktiviert ist, werden die folgenden zusätzlichen Steuerelemente angezeigt:
  * **Umgebungsintensität - Verdeckung**: 0-1\
    Passen Sie die Stärke der generierten AO an.
  * **Umgebungsradius** **- Verdeckung**: 0-1\
    Passen Sie den Radius des AO-Effekts an.
