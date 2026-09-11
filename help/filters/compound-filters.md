---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Erfahre, wie du in Substance 3D Sampler zusammengesetzte Filter erstellst und verwendest, um mehrere Filter zu einer einzigen wiederverwendbaren Ebene zu kombinieren.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Zusammengesetzte Filter
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# Zusammengesetzte Filter

Mit dieser Funktion können Sie einen neuen Filtertyp erstellen, der in der Benutzeroberfläche als einzelne Ebene dargestellt wird und aus mehreren Filtern besteht.

>[!NOTE]
>
> Unterstützt seit Substance 3D Sampler 3.1.0

## Beschreibung

Ein zusammengesetzter Filter ist eine **.ssafilter**-Datei, die ein komprimierter .7zip-Ordner ist mit:

* eine Beschreibungsdatei mit JSON-Formatierung: **myfilter\_name.json**
* ein **Ressourcenordner** mit:
  * Filterminiatur: icon.png
  * Abhängigkeiten externer Dateien

### Inhalt der Beschreibungsdatei

* Name: Bezeichnung des zusammengesetzten Filters, die in der Benutzeroberfläche angezeigt wird
* ID: Eindeutige Identifizierung des Verbundfilters
* Kategorie: Kategorie des zusammengesetzten Filters, der im Bedienfeld &quot;Elemente&quot; verwendet wird, wenn Sie Elemente nach Kategorie gruppieren
* Version: Inkrementelle Zahl zum Definieren der Version des Verbundfilters.
* Knoten: Liste der zu verwendenden Knoten
* Link: Liste der Verbindungen zwischen den verschiedenen Knoten

### Beispiel

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## Schrittweise Erstellung

1. Neue Datei erstellen: **my\_new\_filter.json**
1. Geben Sie den Namen, die ID, die Kategorie,... ein.
1. Liste der benötigten Knoten definieren
1. Wenn Sie externe Dateien benötigen, erstellen Sie den Ordner **resources** neben **.json**.
1. Fügen Sie Ihre Datei(en) im Ordner **Ressourcen** hinzu.
1. Schreiben Sie die Liste der Verknüpfungen zwischen Ihren Knoten
1. Überprüfen Sie, ob Ihre JSON-Datei gültig ist (kein Tippfehler, kein Koma oder keine Klammer).
1. Wenn Sie eine Miniaturansicht wünschen, fügen Sie ein Bild **icon.png** im Ordner **resources** hinzu.
1. Wählen Sie die Datei &quot;**.json**&quot; und den Ordner &quot;**resources**&quot; aus und zippen Sie sie 7zip.

## Dokumentation

### Version

Mithilfe einer Versionsnummer können Sie Ihre verschiedenen Iterationen verfolgen. Wenn Sie einen Ebenenstapel mit einer Vorversion Ihres Verbundfilters geöffnet haben, wird eine Benachrichtigung angezeigt, die Sie zum Upgrade auf die neueste Version auffordert.

### Knoten

Ein Knoten kann auf einen internen Filter von Substance 3D Sampler verweisen. Definieren einer eindeutigen Identifizierung **Id**, die zum Definieren von Verknüpfungen zwischen Knoten und der Bezeichnung des internen Filters **InternalFilter** verwendet werden soll

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

Ein Knoten kann auf eine Sbsar-Datei verweisen, die nicht in Substance 3D Sampler vorhanden ist. Definieren Sie eine eindeutige Identifizierung **Id**, die zum Definieren von Verknüpfungen zwischen Knoten und dem Dateinamen **File** der Sbsar-Datei verwendet werden soll. Die Sbsar-Dateien müssen sich in einem Ordner **Ressourcen** neben der .alchfilter-Datei befinden.

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> **filterImg** und **filterMat** können nicht als Knoten-ID verwendet werden.

### Link

Eine Verknüpfung ist eine Beschreibung, wie zwei Knoten verknüpft sind und sich aus zwei Elementen zusammensetzen:

* Von: Vom Knoten zu verwendende Verwendung
* Funktion: Nutzungsausgabe des Knotens

Jedes Element hat drei Attribute:

* Knoten: Deklarieren Sie die **ID** des zu verwendenden Knotens.
  * die Eingabe des zusammengesetzten Filters festlegen, lautet die Knoten-ID **FilterInput**.
  * die Ausgabe Ihrer zusammengesetzten Ebene festlegen, lautet die Knoten-ID **FilterOutput**.
* Verwendung: Deklarieren Sie die Verwendung, die Sie verwenden möchten. Es gibt drei Optionen:
  * Einzelne Verwendung gleichzeitig und Deklarieren der Verknüpfung durch Verknüpfung (baseColor, normal, Height, ambientOcclusion, Rauheit, metallic, diffuse, Specular, Glanz, specularLevel, opacity, emissive, scan1, ...)
  * Sie können auch eine Liste [&quot;baseColor&quot;, &quot;normal&quot;] angeben. Das erste Element der Liste von **Von** entspricht dem ersten Element der Liste von **Nach**. usw.
  * Verwenden Sie **\***, damit Substance 3D Sampler den Abgleich zwischen identischen Verwendungen aller Verwendungen des Von-Knotens und des An-Knotens durchführen kann. (Es ist nicht möglich, **\*** mit einem anderen Link zu kombinieren, während einzelne Links und Listenverknüpfungen zwischen denselben Knoten möglich sind.)
* Gruppe: Wenn ein Knoten mehrmals dieselbe Verwendung hat, können Sie das Gruppenattribut verwenden, um eine bestimmte Verwendung auszuwählen. Beispiel: Verwenden Sie für Überblendung-Filter zum Abrufen der baseColor des unteren Materials *Material1* und zum Abrufen der baseColor des oberen Materials *Material2*

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
