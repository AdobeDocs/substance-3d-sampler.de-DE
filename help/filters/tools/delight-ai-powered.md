---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/delight-ai-powered.html"
breadcrumb-title: ''
description: Mit dem KI-gestützten Filter "Delight" in Substance 3D Sampler entfernst du Beleuchtungsinformationen aus Bildern und erzeugst neutrale Basismaterialien.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Delight (AI Powered)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Delight (KI-gestützt)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# Delight (KI-gestützt)

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-lightgeneric-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem Delighter können Sie Beleuchtungsinformationen aus dem Grundfarbe-Kanal entfernen. Dies ist wichtig, wenn Sie Bilder in Materialien konvertieren, da Materialien im Allgemeinen keine Beleuchtungsinformationen enthalten sollten. Ein Material ist eine Sammlung von Informationen, die erklären, wie das Material auf eine Fläche reagieren soll. Wenn also bereits Lichtinformationen in einen Kanal Baking geführt werden, der keine Lichtinformationen enthalten sollte, kann dies die Fähigkeit des Lichts beeinträchtigen, die Fläche realistisch darzustellen.

*A **n Beispiel für ein Bild vor und nach der Verarbeitung durch den Filter**Delight (AI Powered)**. Beachten Sie, dass die Tiefen und Lichter entfernt wurden, nur die Grundfarbe bleibt erhalten.*

![](../../assets/120-0-comparison.png)

Die folgenden Bilder zeigen ein Material vor und nach der Verarbeitung durch einen **Delight-Filter (AI-gestützt)**.

![](../../assets/3d-2d-filters-cropped-0043-delighter-in.jpg)

In der obigen Abbildung enthält das Material noch eine beträchtliche Menge an Beleuchtungsinformationen in der Grundfarbe. Die dunklen Schatten zwischen den Ziegeln sollten nicht in der Grundfarbe vorhanden sein.

![](../../assets/3d-2d-filters-cropped-0042-delight-out.jpg)

Nach dem Freuddurchgang wurden die Schatten entfernt, um eine physikalisch akkuratere Grundfarbe zu erzeugen. Auch wenn die Ergebnisse in diesem Beispiel kaum zu bemerken scheinen, ist die Freude an Bildern ein wichtiger Schritt beim Konvertieren von Bildern in Materials.

Bei Quellbildern stammt das Licht von statischen Quellen, aber Materialien müssen in der Lage sein, Licht aus jedem Winkel zu verarbeiten. Beispiel: Wenn ein Quellbild, bei dem das Licht von oben nach unten scheint, in ein Material konvertiert wird, ohne dass ein Freudenschritt ausgeführt wird, kann es in einem 3D-Raum dargestellt werden, in dem das Licht von unten nach oben scheint. Das Material wird schnell unpassend aussehen, weil es gleichzeitig Schatten von mehreren Lichtern zu werfen scheint, wenn es nur eine einzige Lichtquelle gibt.

</td>
</tr>
</table>

## Parameter

Der Delighter hat keine Parameter - er arbeitet automatisch.

## Benutzerhandbuch

Wie benutzt man es?

Fügen Sie den Filter **Delighter** oben im Ebenenstapel hinzu.

### Wann wird sie verwendet?

Wenn Sie **Image to Material (B2M)** verwenden, entfernen Sie nach dem Extrahieren aller Kanäle aus Ihren Bildern und dem Kacheln des Materials die Beleuchtungsinformationen aus der Grundfarbe. **Bild zu Material (KI-gestützt)** beinhaltet einen Freudingpass, sodass Sie den **Delighter (KI-gestützt)-Filter** nicht mitverwenden müssen.
