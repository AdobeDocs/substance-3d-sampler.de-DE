---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-4substance-3d-sampler.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 4.4, um mehr über generative Arbeitsabläufe einschließlich der Funktionen von Text zu Textur und von Bild zu Textur zu erfahren.
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

<b>Substance 3D Sampler 4.4</b> führt drei neue generative Arbeitsabläufe als Beta-Version ein: Text zu Textur, Text zu Muster und Bild zu Textur.

<b>Generative AI-Funktionen sind nur auf Adobe Version </b> verfügbar, da ein Adobe-Konto erforderlich ist. Daher sind diese Features <b> nicht für Steam </b> verfügbar.

*Freigabedatum: 23. Mai 2024*

## Text-to-Textur

![](../assets/textToTexture_whatNewPanel.png)

Mit &quot;Text-zu-Textur&quot; können Sie eine neue Art der Erstellung von Materialien mit einer <b>Textaufforderung</b> erkunden. Du kannst eine gekachelte Textur aus einer detaillierten Textbeschreibung generieren und anhand des Ergebnisses über &quot;Bild zu Material&quot; oder einen beliebigen Sampler-Filter weiterarbeiten, um es einzigartig zu machen.

## Bild-zu-Textur

![Bild-zu-Textur](../assets/imagetoText_whatNewPanel.png "Bild-zu-Textur")

Mit Image-to-Textur können Sie gekachelte quadratische Texturen aus <b>Ihrem eigenen Referenzbild</b> erstellen, unabhängig davon, ob es sich um ein nicht quadratisches Bild und eine nicht-quadratische Kachelung handelt. So kommen Sie Ihren gewünschten Ergebnissen näher, ohne die perfekte Eingabeaufforderung schreiben zu müssen.\
Mit der Funktion &quot;Von Bild zu Textur&quot; sparst du Zeit, indem du Variationen von bereits erstellten Inhalten erstellst.

## Text-zu-Muster

![Illustrationsbild von Text zu Muster](../assets/patterns_whatNewPanel.png)

Die Funktion &quot;Text-to-pattern&quot; verwendet Ihre <b>-Textaufforderung </b>, um ein Muster für quadratische Kachelungen zu generieren. Sie können es dann als Grundfarbe mit einem Gewebefilter verwenden, um ein originelles Material zu erstellen, es als Eingabe eines Musterfilters verwenden und vieles mehr!

## Versionshinweise

*(Freigegeben: 23. Mai 2024)*

<b>Hinzugefügt</b>:

* [Anwendung] 3D-Erfassungen-Cache ist jetzt in einem separaten Unterordner gespeichert
* [Generative KI] Image-to-Textur (Beta)
* [Generative KI] Text-zu-Muster (Beta)
* [Generative KI] Text-zu-Textur (Beta)
* [Skripterstellung] Assets verfügen jetzt über die Eigenschaft &#39;resource&#39;.
* [Scripting] Ebenen verfügen jetzt über die Eigenschaft &quot;output\_usages&quot;.

<b>Fest:</b>

* [Anwendung] Absturz beim Öffnen einer beschädigten Projektdatei
* [Anwendung] Absturz, wenn das Projekt beschädigte Elemente enthält
* [Anwendung] Absturz beim Trennen eines Monitors unter Windows
* [Anwendung] Falsches Anwendungssymbol in der Windows-Taskleiste
* [Anwendung] Beschädigung der Hauptkonfigurationsdatei kann zum Löschen von Dateien führen
* [Anwendung] Fenster werden vor Popups angezeigt
* [Inhalt] Texturen-Generatoren haben verschwommene Miniaturansichten
* [Export] Der aus einem importierten Bild generierte Deckkraftkanal wird beim Exportieren einer SBS-/.sbsar-Datei unterbrochen
* [Filter] Upscale kann je nach Eingabeebene einen Absturz verursachen
* [Generative AI] Mögliche Abstürze beim Empfang unerwarteter Ergebnisse vom Dienst
* [Scripting] Absturz beim automatischen Laden eines Plug-ins aus der Umgebungsvariablen
* [Scripting] Möglicher Absturz beim Zuweisen der Ausgabenauslastung mit der API
