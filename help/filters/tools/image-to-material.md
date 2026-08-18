---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Verwende das Werkzeug "Bild zu Material" in Substance 3D Sampler, um einzelne Bilder mithilfe KI-gestützter Verarbeitung in PBR-Materialien umzuwandeln.
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

Mit der Vorlage **Bild zu Material** können Sie aus einem einzigen Eingabebild ein hochwertiges PBR-Material generieren.

Diese Vorlage verfügt über zwei Hauptalgorithmen:

* **KI-gestützt**
* **B2M**

Unten finden Sie eine detaillierte Erläuterung der einzelnen Algorithmen.

## Beispiel

Hier ist ein Beispiel für Materialkanäle, die aus einem einzigen Eingabebild erzeugt werden:

![](../../assets/sat-image-to-material.jpg){width="500px"}

## Algorithmen

Um den Algorithmus der Vorlage &quot;**Image to Material**&quot; zu ändern, klicken Sie auf die Dropdown-Liste unter dem Vorlagennamen:

![](../../assets/image-to-material-algo-setting.png)

### KI-gestützt

Der <b>KI-gestützte </b>-Algorithmus nutzt maschinelles Lernen, um Formen und Objekte zu erkennen und präzise Normal-, Height- und Raueitskarten zu generieren sowie die Albedo von Schatten oder Lichtern zu entfernen.

Das neuronale Netzwerk wurde auf eine breite Palette von Materialien wie Textilien, Bio-Materialien, Innen- und Außenoberflächen geschult.

>[!NOTE]
>
> &quot;Bild zu Material&quot; (KI-gestützt) wird bei hochauflösenden Bildern länger berechnet. Wir empfehlen, das System [Ebenenauflösung](../../interface/preferences/layer-resolution.md) zu verwenden, um Ihren Arbeitsablauf während der Arbeit zu optimieren.

### B2M

Der **B2M**-Algorithmus verwendet die Substance-basierte Bitmap-zu-Material-Methode, um mithilfe von Prozedurtechniken mehrere Kanäle wie Grundfarbe, Normal, Metallisch, Raueit und Umgebungsfarbe zu generieren.

Dieser Algorithmus liefert möglicherweise weniger genaue Ergebnisse, funktioniert aber bei einer größeren Bandbreite von Eingabebildern.

## Adobe Capture

Diese Funktion ist auch in der mobilen Adobe Capture-App (Android und iOS) verfügbar. Sie können unterwegs ein Foto aufnehmen und direkt auf Ihrem Smartphone eine Vorschau des Ergebnisses anzeigen.

Senden Sie die Ergebnisse einfach zur weiteren Bearbeitung an Substance 3D Sampler.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> Diese Funktion ist nur mit einem Adobe Substance 3D Collection-Abonnement verfügbar.
