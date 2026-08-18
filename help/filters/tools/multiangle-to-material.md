---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/multiangle-to-material.html"
breadcrumb-title: ''
description: Verwende das Mehrwinkel zu Material-Werkzeug in Substance 3D Sampler, um Materialien aus mehreren Winkelaufnahmen einer Oberfläche zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Multiangle To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mehrwinkel zu Material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Mehrwinkel zu Material

![](../../assets/sat-multi-angle.png)

Die **Mehrwinkel zu Material**-Vorlage erstellt ein Material aus 2 bis 8 Eingabebildern, die unter bestimmten Lichtbedingungen aufgenommen wurden. Solche Lichtverhältnisse können mit einem Materialscanner erreicht werden.

>[!NOTE]
>
> Weitere Informationen zum Erstellen eines eigenen Materialscanners [&#x200B; finden Sie in diesem Artikel &#x200B;](https://www.adobe.com/products/substance3d/magazine/your-smartphone-is-a-material-scanner-vol-ii.html).

## Beispiel

Hier ist ein Beispiel für ein Material, das aus 8 Eingabebildern erstellt wurde:

* Die ersten 8 Bilder sind die Scan-Bilder, die unter 8 Lichtwinkeln aufgenommen wurden.
* Die unteren Bilder sind die Ausgaben der Vorlage (Grundfarbe, Normal, Height, Metall und Raueit).

![](../../assets/scan-801x697.jpg){width="400px"}

## Substance 3D Sampler-Konfiguration

Es gibt drei Dinge, die festgelegt und konfiguriert werden müssen, um sicherzustellen, dass die PBR-Kanäle korrekt extrahiert werden:

* Reihenfolge der gescannten Bilder
* Der erste Eingangslichtwinkel
* der nächste Eingangslichtwinkel

![](../../assets/multiangles-1024x1024.jpg){width="450px"}

### Reihenfolge der gescannten Bilder

Vergewissern Sie sich beim Importieren Ihrer Bilder in der Bildimportebene, dass die 8 Bilder aufeinander folgen.

Beispiel: Das erste Bild bei 0° muss **scan1** sein, das Bild bei 45° **scan2** ... und das Bild bei 315° **scan8**.

![](../../assets/multiangle-image-import.png){width="450px"}

### Erster und nächster Lichtwinkel

Auf der Ebene &quot;Mehrwinkel zu Material&quot;:

* Legen Sie den ersten Eingangslichtwinkel fest. Wenn Ihr **Scan1** bei 180° liegt, der erste Eingangslichtwinkel =0,5 oder wenn Ihr **Scan1** bei 0° liegt, ist der erste Eingangslichtwinkel = 0
* Nächsten Eingangslichtwinkel festlegen: Es definiert die Richtung der Drehung Ihres Bildes. Wenn scan1 0° ist, scan2 45°... ist der Wert **gegen den Uhrzeigersinn**

![](../../assets/multiangle-multiangle-to-material.png){width="450px"}
