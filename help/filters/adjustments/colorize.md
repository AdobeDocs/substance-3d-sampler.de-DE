---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/colorize.html"
breadcrumb-title: ''
description: Verwenden Sie den Filter "Färben" in Substance 3D Sampler, um Strukturen und Materialien mit Farbtönen und monochromen Einfärbeeffekten zu versehen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Colorize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Färben
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---


# Färben

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_ColorFill_18_N_D.png)

**In:** Korrekturen

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit der Option &quot;Färben&quot; können Sie einer Auswahl von Kanälen Farbe hinzufügen, ohne Details zu verlieren.

>[!NOTE]
>
> Mit dem Filter &quot;Färben&quot; kannst du den normalen Kanal zwar ändern, aber du solltest dies nicht tun, es sei denn, du verstehst gut, wie der normale Kanal funktioniert und wie sich der Effekt auf dein Material auswirkt. Dies ist eine erweiterte Funktion, die im Allgemeinen nur unter bestimmten Umständen benötigt werden sollte.

In diesen Bildern wurde der **Colorize-Filter** verwendet, um die Grundfarbe anzupassen, um ein viel reichhaltigeres Holzmaterial zu erzeugen.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0045-colorize-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0044-colorize-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Basisparameter**

Die in diesem Abschnitt verfügbaren Parameter ändern sich basierend auf **Kanalauswahl**.

* **Kanalauswahl**:\
  Wählen Sie den Kanal aus, auf den sich der Filter auswirken wird. Es empfiehlt sich, den ausgewählten Kanal in der 2D-Ansicht anzuzeigen, um die Ergebnisse des Filters direkt anzuzeigen.
  * ***Grundfarbe/Emissionsoptionen***
    * ***Kanalname*** **- Farbe**: Farbauswahl\
      Wählen Sie die Farbe aus, die zum Kolorieren des Kanals verwendet wird.
    * ***Kanalname*** **- Luminanz beibehalten**: Knebel\
      Wenn aktiviert, werden die Helligkeits- oder Luminanzwerte der Originalfarben beibehalten
    * ***Kanalname*** **- Intensität**: 0-1\
      Passen Sie die Stärke des Effekts &quot;Färben&quot; an.
  * ***Optionen für normalen Kanal***
    * **Normal - Steigung**: 0-90\
      Verlauf der Normalen ändern
    * **Normal - Richtung**: 0-360\
      Anpassen der Richtung der normalen Flächen
    * **Normal - Luminanz beibehalten**: Knebel\
      Wenn diese Option aktiviert ist, wird die Luminanz der ursprünglichen Normalen beibehalten.
    * **Normal - Intensität**: 0-1\
      Passen Sie die Stärke des Effekts &quot;Färben&quot; an.
* **Benutzerdefinierte Maske**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Weichzeichnen der Maske
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Maske umkehren.
