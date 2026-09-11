---
helpx_url: 'https://helpx.adobe.com/de/substance-3d-sampler/filters/custom-filters.html'
breadcrumb-title: ''
description: Erfahren Sie, wie Sie in Substance 3D Sampler benutzerdefinierte Filter verwenden, um die Funktionalität mit Substance Designer-Filtern und benutzerdefinierten Effekten zu erweitern.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Custom Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Benutzerdefinierte Filter
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 1%

---


# Benutzerdefinierte Filter

## Substance von benutzerdefinierten Filtern

Sie können mit Adobe Substance 3D Designer erstellte Ebenenstapel über die Schaltfläche *Importieren* in den Filteraktionen importieren.

### Erstellen eines Substance-Filters

Filter müssen in Designer auf bestimmte Weise erstellt werden, damit sie nach dem Import in Sampler ordnungsgemäß funktionieren.

Für die Eingabe- und Ausgabeknoten des Filters muss eine Identifizierung oder Verwendung definiert sein.

>[!NOTE]
>
> Es ist möglich, entweder die **Verwendung** oder die **Identifizierung** zu verwenden (die Verwendung hat die Priorität).

#### Format

Exportieren Sie den Filter als Substance-Archivdatei (.SBSAR)

>[!NOTE]
>
> Es können Filterparameter gelegt werden, um den Filter direkt in Sampler zu steuern. Weitere Informationen zu [hier](https://experienceleague.adobe.com/de/docs/substance-3d-designer/using/substance-graphs/manage-parameters/exposing-a-parameter)

#### Erstellen von Filtern zum Ändern von Bildern

![](../assets/image-template.png)

| Bildname | Nutzung |
| --- | --- |
| *Scan1* | **scan1** |
| *Scan2* | **scan2** |
| *...* | **...** |

#### Erstellen von Filtern zum Ändern von Kanälen

![](../assets/material-template.png)

| Kanalname | Nutzung |
| --- | --- |
| *Grundfarbe* | **Grundfarbe** |
| *Diffuse* | **diffuse** |
| *Specular* | **Specular** |
| *Specular level* | **Glanzstufe** |
| *Metallisch* | **metallisch** |
| *Raueit* | **Rauheit** |
| *Glossarität* | **Glanz** |
| *Normal* | **normal** |
| *Height* | **Height** |
| *Umgebungs-Verdeckung* | **ambientOcclusion** |
| *Deckkraft* | **Deckkraft** |

>[!IMPORTANT]
>
> Wenn Sie einen benutzerdefinierten Filter für Sampler erstellen, müssen Sie die folgenden Benutzerdaten in Ihr Substance-Diagramm einfügen:
>
> alchemist::type=filter;

>[!IMPORTANT]
>
> Wenn in Ihrem Paket ein Graf zum Verarbeiten von Bildern (scan1 bis scanX) und ein Graf zum Verarbeiten von Materialien (PBR-Kanäle) vorhanden ist, kann Sampler den richtigen Graf auswählen, je nachdem, wo der Filter in den Ebenenstapel eingefügt wird.
>
> Fügen Sie in Ihrem &quot;Bild&quot;-Diagramm die folgenden Benutzerdaten hinzu:
>
> * alchemist::type=filter;alchemist::variation::type=multi
>
> Fügen Sie auf dem Graf &quot;Material&quot; die folgenden Benutzerdaten hinzu:
>
> * alchemist::type=filter;alchemist::variation::type=Material

### Spezifische Parameter

Bestimmte Parameter werden von der Anwendung global verwaltet. Auf diese Weise können Sie globale Parameter der Anwendung, des Projekts und des Ebenenstapels in Ihren benutzerdefinierten Filtern verwenden.

#### Normalformat

Kontrolle des normalen Formats über die Anwendung. In Sampler auf DirectX setzen

**Parameter-Identifizierung**: Normalformat, normal_format, $normalformat, $normal_format

#### Eingabezählung

Wenn Sie Bilder ändern möchten (scan1 zu scanX), können Sie die Anzahl der Bilder im Ebenenstapel verwenden, indem Sie den Parameter **Bildanzahl** verwenden.

* **Parameter-Identifizierung**: input_count
* **Parametertyp**: Ganzzahl 1

#### Material-Eingabe

Wenn Sie einen Material-Slot im Ebenenstapel wie die Atlas Scatter oder die Spritzer anzeigen möchten:

* Fügen Sie eine neue Gruppe von Eingabeknoten hinzu (Grundfarbe, Normal, ... ).
* Alle Eingabeknoten des Hintergrunds (unteres Material im Ebenenstapel) sollten sich in der Gruppe **Material1** befinden.
* Alle Eingabeknoten des ersten Materials, das Sie oben hinzufügen möchten, sollten sich in der Gruppe **Material2** befinden und so weiter, wenn Sie mehrere Material-Slots benötigen.
* Material-Eingabeparameter hinzufügen:
  * **Parameter-Identifizierung**: Material_input
  * **Parametertyp**: Ganzzahl 1

#### Workflow-Typ

Wenn Sie bestimmte Parameter für den Workflow Ihres Projekts ein- bzw. ausblenden möchten (PBR Metal/Raueit oder PBR Specular/Glossiness), können Sie den Parameter &quot;Workflow-Typ&quot; verwenden.

**Parameter-Identifizierung**: workflow_type

**Parametertyp**: Ganzzahl1, Dropdown-Liste

Optionen:

* 0: PBR Metallic/Rauheit
* 1: PBR Specular/Glanz

![](../assets/workflow-type.jpg){width="300px"}
