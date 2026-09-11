---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/adjustments/blur.html"
breadcrumb-title: ''
description: In Substance 3D Sampler kannst du mit dem Weichzeichnungsfilter Unschärfe-Effekt anwenden und die Bildschärfe bei Texturen und Materialien reduzieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Blur
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Weichzeichnen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 2%

---


# Weichzeichnen

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-blur-18-n-d.png)

**In:** Korrekturen

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Du kannst das gesamte Material weichzeichnen oder bestimmte Kanäle auswählen, die weichgezeichnet werden sollen.

In den folgenden Bildern wurde der **Weichzeichnungsfilter** auf den Grundfarbe-Kanal angewendet.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0055-blur-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0054-blur-out.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Intensität**: 0-1\
  Weichzeichnungsgrad für alle Kanäle anpassen.

**Benutzerdefiniert nach Kanälen**

Passen Sie den Grad der Unschärfe für jeden Kanal unabhängig mithilfe dieser Steuerelemente an. Aktivieren Sie zuerst die kanalspezifische Weichzeichnung. Über einen Schieberegler können Sie den Weichzeichnungsgrad steuern, der auf den Kanal angewendet wird.

>[!NOTE]
>
> Der kanalspezifische Weichzeichner überschreibt **Grundlegende Parameter > Intensität** des Weichzeichners für das gesamte Material. Wenn Sie also die Intensität des Material-Weichzeichners auf 1 setzen, aber einen Kanal aktivieren und seine Intensität auf 0 setzen, wird der Kanal überhaupt nicht weichgezeichnet, während alle anderen Kanäle weichgezeichnet werden.

* ***Kanal*** **- Intensität der benutzerdefinierten Weichzeichnung**: Knebel\
  Aktivieren Sie den kanalspezifischen Weichzeichnungswert.
* ***Kanal*** ***-*** **Weichzeichnungsintensität**: 0-1\
  Passen Sie die Weichzeichnung für den angegebenen Kanal an.
