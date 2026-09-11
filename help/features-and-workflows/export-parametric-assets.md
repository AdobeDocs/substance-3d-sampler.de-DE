---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/features-and-workflows/export-parametric-assets.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie parametrische Assets aus Substance 3D Sampler exportieren, um die Parameteränderung in anderen Anwendungen zu aktivieren, ohne zu Sampler zurückzukehren.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Export parametric assets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Exportieren von parametrischen Elementen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 1%

---


# Exportieren von parametrischen Elementen

Freigelegte Parameter können in anderen Anwendungen geändert werden, ohne dass Sie zu Sampler zurückkehren müssen. Dies verkürzt die Zeit bis zur Iteration, sodass Sie sich auf das Finden des besten Looks konzentrieren können, ohne zwischen den Anwendungen hin- und herwechseln zu müssen.

## Leg- und Unbelichtungsparameter

Öffnen Sie zum leg von Parametern das **Eigenschaftenfenster**. Zeigen Sie mit der Maus oder klicken Sie mit der rechten Maustaste auf den gewünschten Parameter, klicken Sie dann auf das Symbol der Nadel oder auf &quot;leg this parameter&quot;.

![](../assets/ezgif-com-gif-maker-2.gif)

Es gibt zwei Möglichkeiten, die Anzeige eines Parameters aufzuheben:

* Klicken Sie auf der **Bedienfeld „Veröffentlichte Parameter“** mit der rechten Maustaste auf den Parameter, und wählen Sie &quot;unexpose&quot; aus.

  ![](../assets/ezgif-com-gif-maker-3.gif)
* Klicken Sie im **Eigenschaftenbedienfeld** auf das Symbol mit dem gekreuzten Pin, oder klicken Sie mit der rechten Maustaste auf den Parameter, und wählen Sie &quot;diesen Parameter entlarven&quot;.

  ![](../assets/ezgif-com-gif-maker-4.gif)

Die Parameter der folgenden Filter können nicht gelegt werden:

* Bild zu Material (KI-gestützt)
* Inhaltsbasierte Füllung
* Normal zu Height
* Hochskalieren

Wenn Sie einen der Filter über den Ebenen hinzufügen, die freigelegte Parameter enthalten, werden diese beim Exportieren nicht gelegt.\
Um dies zu vermeiden, entfernen Sie den Filter oder platzieren Sie ihn dort, wo er keine Auswirkungen auf Ebenen mit freigelegten Parametern hat.

Wenn freigelegte Parameter aus einer Angleichung vorhanden sind, gehen sie verloren, wenn Sie die Ebene am unteren Rand des Stapels verschieben.

![](../assets/ezgif-com-gif-maker-10.gif)

## Parameter bearbeiten.

Bearbeiten Sie die Beschriftung des Parameters, indem Sie mit der rechten Maustaste auf der **Bedienfeld „Veröffentlichte Parameter“** darauf klicken, geben Sie den neuen Namen ein und klicken Sie auf &quot;Anwenden&quot;.

![](../assets/ezgif-com-gif-maker-5.gif)

![](../assets/ezgif-com-gif-maker-6.gif)

Sie können den Parameter auf der **Bedienfeld „Veröffentlichte Parameter“** wie im **Eigenschaftenfenster** verwenden.

## Material exportieren.

So exportieren Sie das Material mit den exponierten Parametern

1. Öffnen Sie das <b>Exportbedienfeld.</b>
1. Klicken Sie auf Exportieren.
1. Wählen Sie SBSAR oder SBS.
1. Klicke auf Exportieren .

Sie können Ihr Material jetzt mit Ihren freigelegten Parametern in jeder Software verwenden, die Sbsar-Dateien unterstützt.
