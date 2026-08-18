---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/features-and-workflows/flatten-layers.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie Ebenen in Substance 3D Sampler reduzieren können, um die Leistung zu verbessern und Ihren Ebenenstapel zu vereinfachen, während Sie gleichzeitig die Auswirkungen verstehen.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ebenen reduzieren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 1%

---


# Ebenen reduzieren

Das Reduzieren von Ebenen ist eine hilfreiche Möglichkeit, die Leistung zu verbessern und den Ebenenstapel zu vereinfachen. Es ist jedoch wichtig, sich der Auswirkungen bewusst zu sein, die das Reduzieren von Ebenen auf Ihr Projekt haben kann.

## Was macht die Schaltfläche &quot;Ebenen reduzieren&quot;?

Mit &quot;Ebenen reduzieren&quot; werden alle Ebenen unter der aktuell ausgewählten Ebene in einer einzigen Ebene zusammengeführt. Die resultierende abgeflachte Ebene hat das gleiche Erscheinungsbild wie die Originalebenen, aber Sie können keine Anpassungen mehr an den einzelnen Originalebenen vornehmen.

### Warum Ebenen reduzieren?

Wenn Sie eine Ebene im Ebenenstapel ändern, muss Sampler die Ausgabe dieser Ebene und aller darüber liegenden Ebenen neu berechnen. Jede zusätzliche zu berechnende Schicht bedeutet zusätzliche Verarbeitungszeit und Speicherauslastung. Das Reduzieren mehrerer Ebenen verringert den Zeit- und Arbeitsspeicher, der zur Verarbeitung dieser Ebenen erforderlich ist. Anstatt beispielsweise 10 Ebenen neu zu berechnen, muss Sampler nur eine einzelne Ebene verarbeiten.

Darüber hinaus führt das Reduzieren von Ebenen zu einem einfacheren Ebenenstapel, der einfacher zu navigieren und zu verstehen ist.

### Wann sollte ich Ebenen nicht reduzieren?

Auf alle Ebenen, die abgeflacht werden, kann im Ebenenstapel nicht einzeln zugegriffen werden, sodass Sie keine Änderungen an Parametern im abgeflachten Ergebnis vornehmen können. Daher sollten Sie Ebenen nur reduzieren, wenn Sie keine Änderungen an den Ergebnissen dieser Ebenen mehr vornehmen müssen.

## Parameter für abgeflachte Ebenen

Während die Parameter der Originalebenen verloren gehen, verfügen die reduzierten Ebenen über eigene Parameter, die Sie anpassen können, um zu steuern, wie die resultierenden Kanäle verwendet werden.

Für jeden Kanal können Sie:

* <b>Ausgabenutzung</b>: Ändern Sie, für welchen Kanal die Ausgabe verwendet wird. Wenn Sie Ebenen reduzieren, wird für jeden Kanal eine TIFF erstellt und benannt, die automatisch diesem Kanal zugewiesen wird.
* <b>Deckkraft aus Alphakanal</b>: Stellt ein, ob die Deckkraft auf dem Ergebnis des Alpha-Kanals basiert.
* <b>Entfernen</b>: den Kanal aus dieser Ebene entfernen. Dies kann für Kanäle nützlich sein, die keine nützlichen Informationen enthalten. Es empfiehlt sich beispielsweise, einen Kanal mit vollständig weißer Deckkraft zu entfernen, da so Speicher frei wird, ohne dass sich dies auf die visuellen Ergebnisse auswirkt.
