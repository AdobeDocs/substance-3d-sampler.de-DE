---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/features-and-workflows/texture-generators.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie in Substance 3D Sampler mithilfe von Texturgeneratoren prozedurale Texturen und Muster für die Materialerstellung erstellen.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Texturgeneratoren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---


# Texturgeneratoren

![](../assets/sa_whats-new-screen_v4-3-0_generators.png)

Texturgeneratoren bieten eine verbesserte Kontrolle über die Materialerstellung mithilfe von <b> parametrischen Geräuschen, Mustern </b> und <b> Grunges</b>-Optionen. Die erzeugten Bilder können in Masken oder Kanalkarten verwendet werden.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/Capture-decran-2024-01-31-105700.png)

</td>
<td style="border: 0;" valign="top">

Texturgeneratoren sind eine Art von Elementen in Substance 3D Sampler. Sie können im Bedienfeld &quot;Elemente&quot; mit dem Symbol &quot;Texturgeneratoren&quot; gefiltert werden.

</td>
</tr>
</table>

## Texturgeneratoren verwenden

### Kanalzuordnungen

Ziehen Sie einen Texturgenerator per Drag &amp; Drop in die 3D-, 2D-Ansicht oder den Ebenenstapel und wählen Sie einen Kanal aus, um ihn zu verwenden.

![](../assets/DndTexgen.gif)

Im Stapel wird ein Füllfilter erstellt, wobei der Texturgenerator am rechten Eingang anliegt. Sie können auf die Texturgenerator-Eigenschaften im Eigenschaftenbereich zugreifen.

#### Filter

Einige Filter wie <b>Parquet</b> verwenden standardmäßig Texturgeneratoren für Mustermasken. Andere verwenden ein Bild oder einen Texturgenerator wie den Filter <b>Muster</b>.\
In Filtern können Sie Texturgeneratoren in jeder Bildeigenschaft verwenden, z. B. <b>benutzerdefinierte Masken</b>.

Filter können Generatoren vorschlagen, mit denen sie arbeiten sollen. Sie werden in der neuen Elementauswahl angezeigt, wenn Sie auf eine Bildeigenschaft klicken.

![](../assets/suggested-filter.png)

#### Tutorial

Alle Tutorials zu Substance 3D Sampler finden Sie auf unserer [Lernseite](https://creativecloud.adobe.com/cc/learn/app/substance-3d-sampler).

[Textil-Design mit den Textur-Generatoren von Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/fabric-texture-generator?locale=en)

[Kohlenstofffasermaterial in Minuten mit Substance 3D Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/create-carbon-fiber-material?locale=en)

[Plaid Fabric Material in Minuten mit Substance 3D Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/create-plaid-fabric-material?locale=en)

## Benutzerdefinierte Texturgeneratoren erstellen

Sie können mit Adobe Substance 3D Designer erstellte Texturgeneratoren über die Schaltfläche *Importieren* in den Ebenenstapelaktionen importieren. Sie müssen in Designer auf bestimmte Weise erstellt werden, damit sie beim Importieren in Sampler korrekt funktionieren.

### Art

Wählen Sie &quot;Texturgenerator&quot; als Diagramm <b> Typ </b>.

![](../assets/typetexgen.png)

#### Ausgaben

Der Ausgabeknoten des Filters muss den <b>Bezeichner</b> oder <b>Verwendung </b> aufweisen.

* Die Hauptausgabe des Texturgenerators sollte keine Verwendung haben. Anschließend kann es von 3D Sampler als Hauptausgabe erkannt werden.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/patternMask.png)

</td>
<td style="border: 0;" valign="top">

![](../assets/PatternMaskusage.png)

</td>
</tr>
</table>

* Für die <b>sekundäre Ausgabe</b>(en) des Texturgenerators muss <b>Verwendung</b> verwendet werden.\
  Ihr Gruppenname wäre die Hauptausgabe <b>Identifier</b>.

>[!NOTE]
>
> Wenn Sie Ihre eigenen Filter und Texturgeneratoren erstellen, um zusammenzuarbeiten, empfehlen wir, <b>benutzerdefinierte Verwendungen</b> gemäß den <b>Ausgabekennungen</b> zu verwenden.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/patterndata2.png)

</td>
<td style="border: 0;" valign="top">

![](../assets/patterndata2usage2.png)

</td>
</tr>
</table>

>[!IMPORTANT]
>
> Wenn Sie möchten, dass Ihr benutzerdefinierter Texturgenerator in einer Filterliste Vorgeschlagene Elemente angezeigt wird, müssen Sie die folgenden Benutzerdaten in Ihr Substance-Diagramm einfügen:
> 
> alchemist::suggestions=[FilterName,FilterName2];

>[!NOTE]
>
> Die Benutzerdaten können mit [benutzerdefinierten Filtern](../filters/custom-filters.md) verwendet werden.

#### Format

Exportieren Sie den Filter als Substance-Archivdatei (.sbsar)

>[!NOTE]
>
> Sie können Filterparameter verfügbar machen, um den Filter direkt in Sampler zu steuern. Weitere Informationen zu [hier](https://experienceleague.adobe.com/en/docs/substance-3d-designer/using/substance-graphs/manage-parameters/exposing-a-parameter)
