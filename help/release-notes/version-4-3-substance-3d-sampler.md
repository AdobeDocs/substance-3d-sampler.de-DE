---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-3substance-3d-sampler.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 4.3, um mehr über die neuen Generatoren für Texturen, den Stickereifilter und das Werkzeug zum Zuschneiden von Perspektiven zu erfahren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 4.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '808'
ht-degree: 0%

---


# Version 4.3

<b>Substance 3D Sampler 4.3</b> führt neue Starterinhalte ein, darunter <b>Stickerzeuger</b>, eine neue Textur des <b>Stickereifilters</b> und ein <b>Perpective Crop</b>-Tool.

*Freigabedatum: 25. Januar 2024*

## Ein neuer Inhalt für Starter-Assets

![](../assets/NewStarterContent.png)

Die in Sampler enthaltenen Materialien wurden aktualisiert, um die Anforderungen von <b>Arbeitsabläufen für Industriedesign</b>, <b>Arbeitsabläufen für Mode </b> besser zu erfüllen, und technische Künstler, die in den Bereichen Medien und Unterhaltung arbeiten, haben jetzt mehr Kontrolle über die technischen Aspekte der Erstellung von Texturen.

## Texturgenerator

![](../assets/sa_whats-new-screen_v4-3-0_generators.png)

Neue Textur-Generatoren bieten eine verbesserte Kontrolle über die Mustererstellung mithilfe von <b>parametrischen Rauschen, Materialien </b> und <b> Schmutz</b>-Optionen.  Das erzeugte Bildmaterial kann in Masken oder Kanalkarten verwendet werden, was die Zusammenarbeit zwischen technischen und kreativen Teams beim Material-Design einfacher macht als je zuvor.

![](../assets/sampler4.3-texturegenerators-ezgif.com-video.gif)

Verwenden Sie das neue Filterung-Symbol, um nur Textur-Generatoren zu analysieren.

![](../assets/parse-texgen.gif)

## Stickerei

![](../assets/Embroideryv3.png)

Der aktualisierte Stickereifilter hat eine verbesserte Stickergenauigkeit und unterstützt bis zu 8 Farben. Die Eingaben des Materials befinden sich wieder im Ebenenstapel, was die Einfügung anderer Metarialien in den Patch ermöglicht.

## Perspektivisches Freistellen

![](../assets/PerspectiveCropTool.png)

Mit dem neuen Perspektive-Freistellungswerkzeug können Sie verzerrte Materialien und Scans mit vier Kontrollpunkten zuschneiden, um Artefakte in der Perspektive zu entfernen und ein kachelbares Element zu erhalten.

![](../assets/sampler4.3-perspectivecrop-ezgif.com-video-gif.gif)

## Stilisierung

![](../assets/03-8.png)

Mit dem Stilisierungsfilter können Sie jedes Material formatieren, um einen handgemalten Look zu erzielen.

## Füllmethode im Füllfilter

![](../assets/Fill-Blend-mode.gif)

Das Upgrade des Füllfilters führt Überblendung-Modi ein, mit denen Sie den Wert, die Eingabe-Map oder die Textur-Generatoren der Füllung mit den Kanalergebnissen der folgenden Ebenen multiplizieren können.

## Verbesserungen beim Bildimport von Ebenen

![](../assets/Import-Layer-improvements.gif)

Sie können einer Bildebene mehrere Alphas hinzufügen und eine Deckkraftzuordnung aus dem Bildkanal eines Bilds generieren.

## Versionshinweise

*(Freigegeben: 25. Januar 2024)*

<b>Hinzugefügt</b>:

* [Anlagen] Neuer Anlagentyp: Textur Generators
* [Elemente] Neue Material in den Starter-Elementen
* [Assets] Neue Asset-Auswahl für Bildparameter im Eigenschaftenfenster
* [Elemente] Ziehen Sie Generatoren per Drag &amp; Drop aus dem Bedienfeld &quot;Elemente&quot; in die Bildauswahl im Bedienfeld &quot;Eigenschaften&quot;.
* [Assets] Ziehen Sie Generatoren per Drag &amp; Drop aus dem Explorer mit den Betriebssystemdateien in die Textur.
* [Assets] Filter können Anpassungsgeneratoren über ein Benutzer-Tag an der Bildeingabe vorschlagen
* [Assets] Textur Generators können definieren, welcher Filter sie über ein Benutzer-Tag vorschlagen soll
* [Inhalt] Neuer perspektivischer Zuschneidefilter
* [Inhalt] Neuer Stilisierungsfilter
* [Inhalt] Füllmethode beim Füllfilter
* [Inhalt] Aktualisierter Stickereifilter
* [Inhalt] Aktualisierter Farbumflussfilter
* [Inhalt] Alle Filter wurden aktualisiert, um Textur Generators zu unterstützen
* [Ebenen] Möglichkeit, einen Texturgenerator-Ausgabekanal auszuwählen, wenn er dem Ebenenstapel hinzugefügt wird
* [Ebenen] Möglichkeit, Vorgaben auf Textur-Generatoren einfach aufzulisten und anzuwenden
* [Ebenen] Anzeigen einer Vorschau des Textur-Generators in den Bildwählern
* [Ebenen] Texturgenerator-Parameter können angezeigt und exportiert werden
* [Ebenen] Weisen Sie die Verwendung der Grundfarbe zu, wenn Sie ein einzelnes Bild mit der Textur &quot;Import Creation Template&quot; importieren.
* [Ebenen] Feedback beim Versuch, inkompatible Dateien per Drag &amp; Drop in die Bildauswahl im Eigenschaftenfenster zu ziehen
* [Ebenen] Generieren eines Deckkraftkanals aus dem Alphakanal eines importierten Bildes
* [Ebenen] &quot;Bild zu Material&quot; (AI) ist schneller zu berechnen, wenn die Kategorie geändert wird
* [Ebenen] Wählen Sie die relevanteste Ebene aus, nachdem eine Erstellungsvorlage verwendet wurde.
* [Ebenen] Die Positions-Widgets können jetzt mit einem Schieberegler in der Gruppe &quot;Erweiterte Parameter&quot; angepasst werden.
* [Exportieren] Zeigt einen Prozentsatz in der Warteschlange anstelle von Raw-Zahlen an
* [Interoperabilität] Der Deckkraftkanal wird jetzt beim Senden an Painter als Alphakanal erkannt.
* [Anwendung] Neues Dialogfeld zum Anzeigen und Speichern von Hardwareinformationen
* [Anwendung] Neue Voreinstellung zum Ändern der Standardprojektskalierung für jedes Height
* [Anwendung] Verbesserung der Darstellung veralteter Assets
* [Scripting] Neue Funktionen asset.documentResolution() und asset.setDocumentResolution()
* [Skripterstellung] Neue select\_asset()-Funktion
* [Scripting] Python-API für Textur-Generatoren
* [Scripting] get\_project\_assets() gibt jetzt 3D-Objekte zurück.
* [UI] Die Größe der Miniaturansichten von Elementen kann im Bedienfeld &quot;Elemente&quot; geändert werden
* [UI] Aktualisierte Viewport-Anzeigesymbole

<b>Fest:</b>

* [2D-Ansicht] Zoom mit Mausrad ist bei 244 % blockiert
* [Anwendung] Absturz beim Start bei der Initialisierung der Grafik-API
* Absturz [Anwendung], wenn der Projektname das Zeichen # enthält
* [Anwendung] Möglicher Absturz beim Öffnen eines alten Projekts
* [Anwendung] Das erneute Öffnen des aktuellen Projekts kann zu einem Absturz führen
* [Anwendung] Einige Projektänderungen sind nicht registriert und gehen beim Schließen des Projekts ohne Warnung verloren, wenn sie nicht gespeichert wurden.
* [Export] .sbs/.sbsar-Exportprobleme bei der Verwendung mehrerer Dateien mit demselben Namen
* [Exportieren] Falscher Farbraum für exportierte Graustufenbilder .sbs/.sbsar-Datei
* [Filter] Probleme mit dem Verhalten &quot;Deckkraftüberblendung&quot;
* [Ebenen] SVG-Dateien werden manchmal nicht mit der richtigen Auflösung gerendert
* [Leistung] Einige Projektspeicherungen auf der Festplatte sind nicht erforderlich.
* [Projekt] Beim Importieren eines alten Projekts werden die zugehörigen Vorgaben nicht geladen.
* [Scripting] Parameter der ersten eingefügten Ebene können nicht abgerufen werden.
* [UI] Das Popup-Fenster für die Vorschau, wenn Sie mit dem Mauszeiger auf ein Element zeigen, kann an der falschen Stelle oder auf dem falschen Bildschirm angezeigt werden
* [UI] Nicht angedockte Bedienfelder sind sichtbar und können oben im Begrüßungsbildschirm angezeigt werden
