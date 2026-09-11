---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/atlas-creator.html"
breadcrumb-title: ''
description: Verwenden Sie das Atlas-Erstellungstool in Substance 3D Sampler, um Texturen-Atlanten aus mehreren Bildern zu erstellen und Materials effizient zu organisieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Creator
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Creator
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---


# Atlas Creator

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlasgenerator-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Atlas Creator** **filter** können Sie Materialien und Bilder in einen Atlas konvertieren. Sie können dann andere Filter wie **Atlas Scatter** und **Atlas Splitter** verwenden, um Atlaselemente in Materialien zu verwenden.

Die folgenden Bilder zeigen einen Atlas mit Dschungelblättern vor und nach der Verarbeitung durch den **Atlas Creator**.

![](../../assets/3d-2d-filters-cropped-0041-atlas-creator-in.jpg)

Im Bild oben wurde ein Atlasbild importiert und in ein Material konvertiert, aber es ist immer noch kein Atlasbild, da in der Deckkraftmap keine individuellen Material berücksichtigt werden.

![](../../assets/3d-2d-filters-cropped-0040-atlas-creator-out.jpg)

Nach dem Ausführen des **Atlas Creator** wird eine Deckkraftzuordnung generiert und der Bereich zwischen den Atlaselementen wird in den Grundfarbe-Kanal eingefüllt.

</td>
</tr>
</table>

Parameter

**Basisparameter**

* **Kleine Formen entfernen**: 0-1

  So passen Sie die Mindestgröße von Objekten im Atlas an. Dies ist nützlich, um Artefakte zu entfernen.
* **Deckkraft - Chrominanzeinfluss**: 0-2

  Passen Sie die Kanten von Atlaselementen basierend auf Farbwerten an.
* **Deckkraft hinzufügen**: Bild/Pinsel

  Importieren Sie eine Datei, die als Maske verwendet werden soll, oder malen Sie mit dem Pinsel direkt in der **2D-Ansicht** Bereiche, die deckend sein sollen.

Benutzerhandbuch

## Vorbereiten eines Atlasbilds

Bevor Sie den **Atlas Creator-Filter** verwenden, sollten Sie sicherstellen, dass Ihr Atlasbild korrekt vorbereitet wird.

Der **Atlas Creator** funktioniert auf der Grundlage der Bildfarbe und berücksichtigt keine Transparenz. Das bedeutet, dass Sie Ihr Atlasbild am besten vorbereiten, indem Sie sicherstellen, dass der Abstand zwischen den Elementen ein einheitliches Schwarz oder Weiß ist. Dies erleichtert dem **Atlas Creator** das Generieren der Deckkraftmaske.

## Generieren eines Atlas-Materials aus einem Bild

Der **Atlas Creator** ist für die Konvertierung eines Atlasbilds in einen Atlasatlas für Materialien konzipiert.

1. Importieren Sie Ihr Quellbild in den Ebenenstapel.
1. Wenn Sie aufgefordert werden, eine Vorlage zum Erstellen von Materialien auszuwählen, wählen Sie &quot;Bild zu Material&quot;. Andernfalls fügen Sie mit dem Bild im Ebenenstapel über dem Material einen Filter **Image to Image (AI-powered)** hinzu.
1. Warten Sie, bis der Filter **Image zu Material** Ihr Quellbild in ein Material konvertiert hat. Passen Sie die Parameter an, bis Sie mit dem Ergebnis zufrieden sind.
1. Fügen Sie den **Atlas Creator-Filter** oben im Ebenenstapel hinzu.
1. Passen Sie die Parameter von **Atlas Creator** an, bis Sie mit den Ergebnissen zufrieden sind.

1. Fügen Sie das Bild dem Ebenenstapel hinzu. Wenn Sie aufgefordert werden, eine Vorlage zum Erstellen von Materialien auszuwählen, wählen Sie **Als Bitmap verwenden**.
1. Ändern Sie bei ausgewählter Bildebene im Bereich **Eigenschaften** die **Ausgabenutzung** in **Grundfarbe**.
1. Fügen Sie den **Atlas Creator** oben im Ebenenstapel hinzu.
1. Passen Sie die Parameter des **Atlas-Erstellers** an, bis Sie mit den Ergebnissen zufrieden sind. Zeigen Sie den Deckkraftkanal in der **2D-Ansicht** an, um die Filterergebnisse deutlicher zu sehen.
1. Verwenden Sie das **Exportbedienfeld**, um die generierten Kanäle zu exportieren.
