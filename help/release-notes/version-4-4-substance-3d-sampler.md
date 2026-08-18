---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-4substance-3d-sampler.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 4.4, um mehr über generative Workflows zu erfahren, einschließlich der Funktionen von Text zu Textur und von Bild zu Textur.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 4.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---


# Version 4.4

<b>Substance 3D Sampler 4.4</b> führt drei neue generative Arbeitsabläufe als Beta-Version ein: Text-zu-Textur, Text-zu-Muster und Bild-zu-Textur.

<b>Generative AI-Funktionen sind nur auf Adobe Version </b> verfügbar, da ein Adobe-Konto erforderlich ist. Daher sind diese Features <b> nicht für Steam </b> verfügbar.

*Freigabedatum: 23. Mai 2024*

## Text-to-texture

![](../assets/textToTexture_whatNewPanel.png)

Mit &quot;Text-zu-Textur&quot; können Sie eine neue Art der Materialerstellung mit einer <b>Textaufforderung</b> erkunden. Du kannst eine Kachelstruktur aus einer detaillierten Textbeschreibung generieren und das Ergebnis über &quot;Bild zu Material&quot; oder einen beliebigen Sampler-Filter weiterbearbeiten, um es einzigartig zu machen.

## Bild-zu-Textur

![Bild-zu-Textur](../assets/imagetoText_whatNewPanel.png "Bild-zu-Textur")

Mit Bild-zu-Textur können Sie gekachelte quadratische Texturen aus <b>Ihrem eigenen Referenzbild</b> erstellen, unabhängig davon, ob es nicht quadratisch und nicht gekachelt ist. So kommen Sie Ihren gewünschten Ergebnissen näher, ohne die perfekte Eingabeaufforderung schreiben zu müssen.\
Mit der Funktion &quot;Bild-zu-Textur&quot; sparst du Zeit, indem du Variationen von bereits erstellten Inhalten erstellst.

## Text-zu-Muster

![Illustrationsbild von Text zu Muster](../assets/patterns_whatNewPanel.png)

Die Funktion &quot;Text-to-pattern&quot; verwendet Ihre <b>-Textaufforderung </b>, um ein quadratisches Kachelmuster zu generieren. Sie können es dann als Grundfarbe mit einem Gewebefilter verwenden, um ein originelles Gewebematerial zu erstellen, es als Eingabe eines Musterfilters verwenden und mehr!

## Versionshinweise

*(Freigegeben: 23. Mai 2024)*

<b>Hinzugefügt</b>:

* [Anwendung] 3D-Erfassungen-Cache ist jetzt in einem separaten Unterordner gespeichert
* [Generative KI] Bild zu Textur (Beta)
* [Generative KI] Text-zu-Muster (Beta)
* [Generative KI] Text zu Textur (Beta)
* [Skripterstellung] Assets verfügen jetzt über die Eigenschaft &#39;resource&#39;.
* [Scripting] Ebenen verfügen jetzt über die Eigenschaft &quot;output\_usages&quot;.

<b>Fest:</b>

* [Anwendung] Absturz beim Öffnen einer beschädigten Projektdatei
* [Anwendung] Absturz, wenn das Projekt beschädigte Elemente enthält
* [Anwendung] Absturz beim Trennen eines Monitors unter Windows
* [Anwendung] Falsches Anwendungssymbol in der Windows-Taskleiste
* [Anwendung] Beschädigung der Hauptkonfigurationsdatei kann zum Löschen von Dateien führen
* [Anwendung] Fenster werden vor Popups angezeigt
* [Inhalt] Texturgeneratoren haben verschwommene Miniaturansichten
* [Export] Der aus einem importierten Bild generierte Deckkraftkanal wird beim Exportieren einer SBS-/.sbsar-Datei unterbrochen
* [Filter] Upscale kann je nach Eingabeebenen abstürzen
* [Generative AI] Mögliche Abstürze beim Empfang unerwarteter Ergebnisse vom Dienst
* [Scripting] Absturz beim automatischen Laden eines Plug-ins aus der Umgebungsvariablen
* [Scripting] Möglicher Absturz beim Zuweisen der Ausgabenauslastung mit der API
