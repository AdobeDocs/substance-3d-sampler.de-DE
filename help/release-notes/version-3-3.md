---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-3.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 3.3, um mehr über die neuen Werkzeuge, Inhalte und Funktionen zur Materialerstellung zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.3
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 3.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1108'
ht-degree: 0%

---


# Version 3.3

**Substance 3D Sampler 3.3.0** bietet eine Reihe neuer Tools, Inhalte und Funktionen, mit denen Sie Materialien und Umgebungslichter einfacher erstellen und bearbeiten können.

*Freigabedatum: 17. Mai 2022*

## Wichtigste Funktionen

## Inhaltsbasierte Füllung

Die inhaltsbasierte Füllung ist eine beliebte Technologie in Adobe Photoshop. Sie wird verwendet, um Bilddetails zu entfernen und gleichzeitig die Integrität der Umgebung zu wahren.

Substance 3D Sampler verwendet nun dieselbe Technologie, mit der Sie PBR-Materialien und Umgebungslichter reinigen können. Bei PBR-Materialien wird die inhaltsbasierte Füllung auf alle Kanäle angewendet. Es ist nicht erforderlich, jeden Kanal separat zu verarbeiten.

Die inhaltsbasierte Füllung kann dabei helfen, große Elemente zu entfernen, um Wiederholungen beim Kacheln eines Materials zu vermeiden, oder kleine Unvollkommenheiten auf Ihrem gescannten Stoff zu entfernen.

Bei der Aufnahme von 360 Panoramen hast du möglicherweise nicht die Kontrolle über alle Elemente in der Szene und musst daher kleine Objekte auf dem Boden, Gemälde an einer Wand oder eine Person, die im Hintergrund steht, entfernen. Die inhaltsbasierte Füllung macht dies jetzt einfacher.

## IBL-Authoring

### Sphärische Projektion

Die Bearbeitung von Umgebungslichtern und 360-Grad-Bildern kann schwierig sein, wenn sie als normale Bilder angezeigt werden. Alle Elemente sind verzerrt, sodass eine Bearbeitung fast unmöglich ist. Mit der neuen sphärische Projektion können Sie in 360° navigieren und mit speziellen Tools wie Nadir Patch, inhaltsbasierter Füllung und allen Prozedurlichtern ohne Verzerrung bearbeiten. So ist es jetzt z. B. einfacher, gerade Linien zu bearbeiten oder zu bereinigen, das Stativ der Kamera zu entfernen und die Linienbeleuchtung perfekt zu platzieren.

Sehen Sie sich dieses neue Tutorial an, um [Umgebungslichter &#x200B;](https://www.youtube.com/watch?v=cfW9IyoTXQ8) mit diesem neuen Modus zu erstellen.

### Belichtungsregler

In der 2D-Ansicht können Sie die Belichtung vorübergehend ändern, um Details oder Objekte an unterbelichteten oder überbelichteten Teilen der Umgebung, die Sie bearbeiten, besser sehen zu können.

### Dedizierte Anzeigeeinstellungen

Die Anzeigeeinstellungen gelten dauerhaft für jeden Asset-Typ (Material- oder Umgebungslicht). Sie können das Gitter, Standardtexturen oder das Kamerafeld für jeden Elementtyp festlegen, um leichter zwischen ihnen zu wechseln und im richtigen Kontext zu arbeiten.

## Verbesserte Widgets

### Kopierstempel

Mit diesem Update für den Kopierstempel können Sie mehrere Stempelstriche mit verschiedenen Quellen in einer einzelnen Ebene malen und auf den Stempelverlauf im Ebenenstapel zugreifen. Außerdem können Sie das Stempelergebnis jetzt direkt in der Pinselvorschau vor dem Malen sehen. Dies erleichtert die Materialreinigung und vermeidet viel Hin und Her zwischen Ansichten.

### Zuschneiden und transformieren

Dieses Update enthält neue Tastaturbefehle für die Bearbeitung von Widgets für Zuschneiden und Transformieren.

### Pinsel-Symbolleiste

Die neue Benutzeroberfläche, die den neuesten Adobe-Produkten wie Fresco ähnelt, ermöglicht es Ihnen, die Symbolleiste an eine beliebige Stelle in der 2D-Ansicht zu verschieben, wobei sie vertikal oder horizontal angezeigt wird. Wechseln Sie beim Malen mit der Taste &quot;E&quot; zwischen Pinsel und Radiergummi und verwenden Sie die neuen Kacheloptionen, um die gezeichneten Objekte besser zu steuern.

## Von Bild zu Material (KI-gestützt)

### Kacheln beibehalten

&quot;Bild zu Material&quot; (KI-gestützt) erhält eine neue Option: Es kann jetzt die Kachelung Ihres kachelbaren Bildes beibehalten und die Zeit zum Kacheln des Materials danach reduzieren.

## Interoperabilität

Materialien an Stager senden.

Es war bereits möglich, Umgebungslichter an Stager zu senden. Sende Materialien mit nur einem Klick an 3D Stager, wie du es auch mit Designer und Painter kannst. Dank dieser Funktion müssen Sie Ihre Materialien nicht mehr veröffentlichen und als einzelne Dateien in Stager laden (Stager-Version 1.2.0 mit dem neuen Material-Manager erforderlich).

## Versionshinweise

### 3.3.0 Zucchini

*(veröffentlicht am 17. Mai 2022)*

**Hinzugefügt:**

* [Inhalt] Neuer inhaltsbasierter Füllfilter (Windows und Mac)
* [Content] Content Aware Fill bearbeitet Bilder, PBR-Materialien und Umgebungslichter
* [Inhalt] Hinzufügen des Parameters &quot;Kachelung beibehalten&quot; zu &quot;Bild zu Material&quot; (KI-gestützt)
* [Inhalt] Der Filter &quot;Perspektivische Transformation&quot; kann ein Raster zwischen seinen vier Punkten anzeigen
* [Interoperabilität] Materialien an Adobe Substance 3D Stager senden
* [Werkzeuge] Zentrieren Sie die Transformation, indem Sie beim Skalieren des Transformieren- oder Freistellungswerkzeugs die Strg-Taste drücken
* [Tools] Sperren des Verhältnisses zum Quadrat durch Drücken der Umschalttaste beim Ändern der Größe des Transformieren- oder Zuschneide-Werkzeugs
* [Tools] Kopierstempel-Cursor bietet eine Vorschau dessen, was gestempelt wird
* [Tools] Vorschau des Originalinhalts im Radiergummi, wenn Kopierstempel verwendet werden
* [Tools] Strg+Klick erstellt einen neuen Stempel in der Kopierstempel-Ebene
* [Tools] Aufeinander folgende Klonstempel sind jetzt in einer einzigen Ebene gruppiert
* [Tools] Benutzeroberfläche der Pinsel-Symbolleiste überarbeiten
* [Tools] Die Position der Pinsel-Symbolleiste bleibt während einer Sitzung erhalten.
* [Tools] Neue Optionen für die Pinselneigung nach Achse
* [Tools] Blenden Sie die Überlagerung über der 2D-Ansicht beim Malen aus/zeigen Sie sie an.
* [Tools] Neuer Tastaturbefehl &quot;X&quot; zum Umschalten zwischen Pinsel und Radiergummi
* [Tools] Neuer Tastaturbefehl, &quot;[&quot; &quot;]&quot; zum Ändern der Pinselgröße
* [Tools] Neuer Tastaturbefehl &quot;E&quot; zum Umschalten des Radiergummis
* [2D-Ansicht] Neuer Sphärische Projektion-Modus beim Erstellen der Umgebungsbeleuchtung
* [2D-Ansicht] Das Pinselwerkzeug wird im sphärische Projektion-Modus unterstützt.
* [2D View] Positionierungswerkzeug wird mit der sphärische Projektion unterstützt
* [2D-sphärische Projektion] Rückgängig/Wiederholen wird im Anzeigemodus unterstützt.
* [2D-Ansicht] Legen Sie in Sphärische Projektion die Standardposition fest, sodass der Blick auf den Mittelpunkt der Umgebung gerichtet ist.
* [2D-Ansicht] Neue Belichtungssteuerung
* [UI] Im Bedienfeld &quot;Eigenschaften&quot; zeigt die Bildoptimierung die Quelle des Inhalts an (Bild oder aus einer Ebene).
* [UI] Verbesserte Ebenen-/Material-Ausgaben-Dropdown-Hintergrund
* [UI] Neue Position der Auflösungsinformationen in der 2D-Ansicht
* [UI] Neue QuickInfo mit Tastaturbefehlen für 3D-Ansichtsnavigation
* [UI] Neue QuickInfo mit Pinselsteuerungen
* [UI] Neue QuickInfo mit Tastaturbefehlen für Projektionsnavigation
* [Verbundfilter] Verbundfilter behandeln Variationen zur Arbeit an Bildern, PBR-Materialien und Umgebungsbeleuchtungen
* [Zusammengesetzte Filter] Die Tweak-Reihenfolge entspricht der Knoten-Listenreihenfolge im zusammengesetzten Filter
* [Zusammengesetzte Filter] Kleine Knoten mit derselben Gruppe werden im Bedienfeld &quot;Eigenschaften&quot; in einer Gruppe zusammengeführt.
* [Anwendung] Dedizierte Viewer-Einstellungen für jeden Asset-Typ

**Fest:**

* [Anwendung] Anwendung kann abstürzen, wenn zur 2D-Ansicht gewechselt wird
* [Anwendung] Beheben einer möglichen Deadlock oder eines Absturzes beim mehrmaligen Export
* [Anwendung] Festlegen von Standardwerten für Kanäle für die Konsistenz mit Substance 3D Designer
* [Anwendung] Das Laden eines Projekts löst keine Neuberechnung des Materials aus
* [Anwendung] Die URL zur Dokumentation zum Texturimport wurde aktualisiert.
* [Inhalt] Wenn Sie einen zusammengesetzten Filter verwenden, muss er beim erneuten Laden aktualisiert werden, wenn dies nicht der Fall sein sollte
* [Inhalt] Details in der Height-Map verschwinden bei Verwendung der Deckkraftüberblendung
* [UI] Im Farbdialogfeld können Sie mithilfe der Textfelder des Reglers den Bereich verlassen
* [UI] Die Verwendungsliste enthält eine nutzlose vertikale Bildlaufleiste

**Bekannte Probleme:**

* [Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* [Inhalt] Shape Light-Widget funktioniert nicht im sphärische Projektion-Modus
* [Interoperabilität] Material mit Versatz, der an Stager gesendet wird, verliert die Versatz-Steuerelemente.
