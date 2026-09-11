---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Verwende das Material-in-Bild-Werkzeug von Substance 3D Sampler, um einzelne Bilder mithilfe KI-gestützter Verarbeitung in PBR-Materialien umzuwandeln.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Image To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Von Bild zu Material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---


# Von Bild zu Material

![](../../assets/sat-icon-image-to-material.png)

Mit der Vorlage **Image zu Material** können Sie aus einem einzigen Eingabebild ein qualitativ hochwertiges PBR-Material generieren.

Diese Vorlage verfügt über zwei Hauptalgorithmen:

* **KI-gestützt**
* **B2M**

Unten finden Sie eine detaillierte Erläuterung der einzelnen Algorithmen.

## Beispiel

Im Folgenden finden Sie ein Beispiel für Material-Kanäle, die aus einem einzigen Eingabebild generiert wurden:

![](../../assets/sat-image-to-material.jpg){width="500px"}

## Algorithmen

Um den Algorithmus der Vorlage **Image in Material** zu ändern, klicken Sie auf die Dropdown-Liste unter dem Vorlagennamen:

![](../../assets/image-to-material-algo-setting.png)

### KI-gestützt

Der <b>KI-gestützte </b>-Algorithmus nutzt maschinelles Lernen, um Formen und Objekte zu erkennen und präzise Normal-, Height- und Raueitskarten zu generieren sowie die Albedo von Schatten oder Lichtern zu entfernen.

Das neuronale Netzwerk wurde in einer Vielzahl von Materialien wie Textilien, Organik, Innen- und Außenoberflächen geschult.

>[!NOTE]
>
> &quot;Bild zu Material&quot; (KI-gestützt) wird bei hochauflösenden Bildern länger berechnet. Wir empfehlen, das System [Ebenenauflösung](../../interface/preferences/layer-resolution.md) zu verwenden, um Ihren Arbeitsablauf während der Arbeit zu optimieren.

### B2M

Der **B2M**-Algorithmus verwendet die Substance-basierte Bitmap-zu-Material-Methode, um mithilfe prozeduraler Techniken mehrere Kanäle wie Grundfarbe, Normal, metallic, Rauheit und ambient occlusion zu generieren.

Dieser Algorithmus liefert möglicherweise weniger exakte Ergebnisse, funktioniert aber in einer größeren Bandbreite von Eingabebildern.

## Adobe Capture

Diese Funktion ist auch in der mobilen Adobe Capture-App (Android und iOS) verfügbar. Sie können unterwegs ein Foto einrasten haben, um direkt auf Ihrem Smartphone eine Vorschau des Ergebnisses zu erhalten.

Senden Sie die Ergebnisse einfach zur weiteren Bearbeitung an Substance 3D Sampler.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> Diese Funktion ist nur mit einem Adobe Substance 3D Collection-Abonnement verfügbar.
