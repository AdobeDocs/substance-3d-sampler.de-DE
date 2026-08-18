---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: Verwenden Sie das Belichtungsvorschau-Werkzeug in Substance 3D Sampler, um eine Vorschau der Belichtungskorrekturen in HDR-Bildern anzuzeigen, bevor Sie Änderungen anwenden.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Belichtungsvorschau
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# Belichtungsvorschau

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit der **Belichtungsvorschau** **filter** können Sie schnell eine Vorschau eines Spektrums von Belichtungswerten anzeigen.

Im Folgenden sehen Sie, was der Filter **Belichtungsvorschau** bewirkt.

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

Im Bild oben wurde eine Umgebungsbeleuchtung erstellt, und die HDR-Bilddaten sind in der **2D-Ansicht** sichtbar.

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

Mit der **Belichtungsvorschau** **filter**, die dem Ebenenstapel hinzugefügt wurde, wird ein neuer Kanal - Umgebungsdiagnose - verfügbar, der das Umgebungslicht mit verschiedenen Belichtungen anzeigt.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Min. Belichtung (EV)**: -8 bis 8\
  Stellen Sie die Belichtung des am wenigsten belichteten Bildes ein.
* **Maximale Belichtung (EV)**: -8 bis 8\
  Legen Sie die Belichtung des am meisten belichteten Bildes fest.

## Benutzerhandbuch

Der **Belichtungsvorschaufilter** funktioniert etwas anders als andere Sampler-Filter. Es ist ein Tool, mit dem Sie die richtige Belichtung für Ihr Umgebungslicht finden können, das sich aber überhaupt nicht auf den Umgebungskanal auswirkt. Wenn Sie stattdessen den Filter **Belichtungsvorschau** zum Ebenenstapel hinzufügen, wird ein zusätzlicher Kanal zur Anzeige in der **2D-Ansicht** - dem Umgebungsdiagnosekanal - verfügbar.

Wenn Sie den Umgebungsdiagnose-Kanal anzeigen, sollten Sie einige Instanzen des 2D-Umgebungsbilds mit unterschiedlichen Belichtungswerten sehen können. Passen Sie die Parameter des **Belichtungsvorschaufilters** an, um den im Umgebungsdiagnosekanal sichtbaren Belichtungsbereich zu ändern.
