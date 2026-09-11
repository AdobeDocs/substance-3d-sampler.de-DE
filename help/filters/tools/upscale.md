---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/upscale.html"
breadcrumb-title: ''
description: Verwende das Hochskalieren-Tool in Substance 3D Sampler, um die Auflösung der Textur mit KI-gestützter Hochskalierungstechnologie zu erhöhen.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Hochskalieren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 2%

---


# Hochskalieren

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![Filtersymbol](../../assets/SAPR_SuperResolution_18_N_D.png)

**In:** Tools

</td>
<td style="border: 0;" valign="top">

## Beschreibung

Der <b>Hochskalieren </b>-Filter verwendet KI, um die PBR-Kanäle (BaseColor, Rauheit, Normal, Metallic, Height) von den darunter liegenden Ebenen hochzuladen.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">



</td>
<td style="border: 0;" valign="top">

![](../../assets/F5W_vAHaYAQLsz7.jpg)

</td>
</tr>
</table>

In diesem Beispiel beginnen wir mit einem Bild mit einer Auflösung von 1024 x 1024 px, aber das Ausgabeergebnis ist 4098 x 4098 px. Die Ergebnisse, die den Filter <b>Hochskalieren</b> verwenden, sind genauer definiert.

</td>
<td style="border: 0;" valign="top">

>[!NOTE]
>
> **Erweiterter Filter**
> 
> <b>Hochskalieren</b> ist ein erweiterter Filter.\
> Um es mit seiner maximalen Kapazität zu verwenden und unscharfe Ergebnisse zu vermeiden, empfehlen wir, die Ebenen unter <b>Hochskalieren</b> in &quot;Ebeneneingabe - Max.&quot; oder &quot;Ebeneneingabe - Min.&quot; festzulegen.
> 
> Die Anzahl der <b>Upscale </b>-Filter ist nicht begrenzt, aber ein Upsampling über eine Auflösung von 8k kann die Leistung erheblich beeinträchtigen.

</td>
</tr>
</table>

## Parameter

<b>Basisparameter</b>

* <b>Beispiel nach oben</b>: Schaltflächengruppe ein/aus\
  Hochskalierungsfaktor für Multiplikation auswählen

## Anleitung

![](../../assets/SAPR_Upscale_screen_001.png)

Im Bild oben wird ein Bild mit niedriger Auflösung vom [Bild zu Material (KI-gestützt) verarbeitet](image-to-material.md).

![](../../assets/SAPR_Upscale_Screen_003.png)

Der Filter <b>Hochskalieren</b> wird hinzugefügt, um die Ergebnisse als Beispiel aufzunehmen. Es halluziniert Details, um eine höhere Auflösung zu erreichen, die die Qualität des Materials beibehält. Sie können in den Eigenschaften auswählen, ob die Neuauflösung um 2 oder um 4 erfolgen soll.
