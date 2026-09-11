---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-3.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 3.3, um mehr über die neuen Tools, Inhalte und Funktionen zum Erstellen von Materials zu erfahren.
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

**Substance 3D Sampler 3.3.0** bietet eine Reihe neuer Tools, Inhalte und Funktionen, mit denen Sie Materials und Umgebungslichts einfacher erstellen und bearbeiten können.

*Freigabedatum: 17. Mai 2022*

## Wichtigste Funktionen

## Inhaltsbasierte Füllung

Die inhaltsbasierte Füllung ist eine beliebte Technologie in Adobe Photoshop. Sie wird verwendet, um Bilddetails zu entfernen und gleichzeitig die Integrität der Umgebung zu wahren.

Substance 3D Sampler verwendet nun dieselbe Technologie, mit der Sie PBR-Materialien und -Umgebungslichter bereinigen können. Auf PBR-Materialien wird die inhaltsbasierte Füllung auf alle Kanäle angewendet. Es ist nicht erforderlich, jeden Kanal separat zu verarbeiten.

Die inhaltsbasierte Füllung kann dabei helfen, große Elemente zu entfernen, um Wiederholungen bei der Kachelung eines Materials oder kleine Unvollkommenheiten auf Ihrem gescannten Stoff zu vermeiden.

Bei der Aufnahme von 360 Panoramen hast du möglicherweise nicht die Kontrolle über alle Elemente in der Szene. Daher musst du kleine Objekte auf dem Boden entfernen, Gemälde an einer Wand oder eine Person, die im Hintergrund steht. Die inhaltsbasierte Füllung macht dies jetzt einfacher.

## IBL-Authoring

### Sphärische Projektion

Die Bearbeitung von Umgebungslichts und 360-Grad-Bildern kann schwierig sein, wenn sie als normale Bilder angezeigt werden. Alle Elemente sind verzerrt, sodass eine Bearbeitung fast unmöglich ist. Mit der neuen sphärische Projektion kannst du in 360° navigieren und mit speziellen Tools wie Nadir Patch, inhaltsbasierter Füllung und allen prozeduralen Lichtern ohne Verzerrung bearbeiten. Es ist jetzt z. B. einfacher, gerade Linien zu bearbeiten oder zu bereinigen, das Stativ der Kamera zu entfernen und Linienlichter perfekt zu platzieren.

Neues Tutorial zum Erstellen von [Umgebungslichtern](https://www.youtube.com/watch?v=cfW9IyoTXQ8) mit diesem neuen Modus.

### Belichtungsregler

In der 2D-Ansicht können Sie die Belichtung vorübergehend ändern, damit Sie Details oder Objekte an unterbelichteten oder überbelichteten Teilen der Umgebung, die Sie bearbeiten, besser sehen können.

### Dedizierte Anzeigeeinstellungen

Die Anzeigeeinstellungen gelten dauerhaft für jeden Elementtyp (Material oder Umgebungslicht). Sie können für jeden Elementtyp den Mesh, die Standardeinstellungen oder das Sichtfeld der Kamera festlegen, damit Sie leichter zwischen den Texturen wechseln können und sie im richtigen Kontext funktionieren.

## Verbesserte Widgets

### Klon

Mit diesem Klon-Stempel-Update können Sie mehrere Stempelstriche mit verschiedenen Malen aus verschiedenen Quellen in einer einzigen Ebene erstellen und auf den Stempelverlauf im Ebenenstapel zugreifen. Außerdem können Sie das Stempelergebnis jetzt direkt in der Pinselvorschau vor dem Malen sehen. Dies erleichtert die Reinigung der Material und vermeidet ein Hin und Her zwischen verschiedenen Ansichten.

### Zuschneiden und Transformieren

Mit diesem Update werden neue Tastaturbefehle für die Bearbeitung von Zuschneiden und Transformieren-Widgets eingeführt.

### Pinsel-Symbolleiste

Die neue Benutzeroberfläche, die den neuesten Adobe-Produkten wie Fresco ähnelt, ermöglicht es Ihnen, die Symbolleiste an eine beliebige Stelle in der 2D-Ansicht zu verschieben, wobei sie vertikal oder horizontal angezeigt wird. Wechseln Sie beim Malen mit der Taste &quot;E&quot; zwischen Pinsel und Radiergummi und verwenden Sie die neuen Kachelung-Optionen, um den Malen besser zu steuern.

## Bild-zu-Material (KI-gestützt)

### Kachelung beibehalten

&quot;Bild zu Material&quot; (KI-gestützt) erhält eine neue Option: Es kann jetzt die Kachelung des kachelbaren Bildes beibehalten und die Zeit zum Kacheln des Materials danach reduzieren.

## Interoperabilität

Materialien an Stager senden

Es war bereits möglich, Umgebungslichts an Stager zu senden. Sende deine Materials mit nur einem Klick an 3D Stager, wie du es auch mit Designer und Painter kannst. Dank dieser Funktion müssen Sie Ihre Materialien nicht mehr veröffentlichen und als Einzeldateien in Stager laden (Stager-Version 1.2.0 mit dem neuen Material-Manager erforderlich).

## Versionshinweise

### 3.3.0 Zucchini

*(veröffentlicht am 17. Mai 2022)*

**Hinzugefügt:**

* [Inhalt] Neuer inhaltsbasierter Füllfilter (Windows und Mac)
* [Content] Content Aware Fill bearbeitet Bilder, PBR-Materialien und Umgebungslichter
* [Inhalt] Hinzufügen des Parameters &quot;Kachelung beibehalten&quot; zu &quot;Bild zu Material&quot; (KI-gestützt)
* [Inhalt] Der Filter &quot;Perspektive Transformieren&quot; kann einen Raster zwischen seinen vier Punkten anzeigen.
* [Interoperabilität] Senden von Materialien an Adobe Substance 3D Stager
* [Tools] Zentrieren Sie die Transformation, indem Sie Strg drücken, wenn Sie das Transformieren- oder Freistellungswerkzeug skalieren
* [Tools] Sperren des Verhältnisses zum Quadrat durch Drücken der Umschalttaste beim Ändern der Größe des Transformieren- oder Freistellungswerkzeugs
* [Tools] Klon-Stempel-Cursor bietet eine Vorschau dessen, was gestempelt wird
* [Tools] Vorschau des Originalinhalts im Radiergummi-Cursor bei Verwendung des Klon-Stempels
* [Tools] Strg+Klick erstellt einen neuen Klon in der Stempelebene
* [Tools] Aufeinander folgende Klonstempel sind jetzt in einer einzigen Ebene gruppiert
* [Tools] Benutzeroberfläche der Pinsel-Symbolleiste überarbeiten
* [Tools] Die Position der Pinsel-Symbolleiste bleibt während einer Sitzung erhalten.
* [Tools] Neue Optionen für die Kachelung von Pinseln nach Achse
* [Tools] Überlagerung über der 2D-Ansicht beim Malen ausblenden/anzeigen
* [Tools] Neuer Tastaturbefehl, X-Taste, zum Umschalten zwischen Pinsel und Radiergummi
* [Tools] Neuer Tastaturbefehl, &quot;[&quot; &quot;]&quot; zum Ändern der Pinselgröße
* [Tools] Neuer Tastaturbefehl, Taste &quot;E&quot;, zum Umschalten des Radiergummis
* [2D-Ansicht] Neuer Sphärische Projektion-Modus beim Erstellen von Umgebungslichtern
* [2D-Ansicht] Das Pinselwerkzeug wird vom sphärische Projektion-Modus unterstützt.
* [2D-Ansicht] Das Positionierungswerkzeug wird im sphärische Projektion-Modus unterstützt.
* [2D-Ansicht] Rückgängigmachen/Wiederholen wird mit dem Modus sphärische Projektion unterstützt.
* [2D-Ansicht] Legen Sie in Sphärische Projektion die Standardposition fest, um auf den Mittelpunkt der Umgebung zu schauen.
* [2D-Ansicht] Neue Belichtungssteuerung
* [UI] Im Bedienfeld &quot;Eigenschaften&quot; zeigt die Bildoptimierung die Quelle des Inhalts an (Bild oder aus einer Ebene).
* [UI] Verbesserte Ebenen-/Material-Ausgaben Dropdown-Hintergrund
* [UI] Neue Position der Auflösungsinformationen in den 2D-Ansichten
* [UI] Neue QuickInfo mit Tastaturbefehlen für 3D-Ansichtsnavigation
* [UI] Neue QuickInfo mit Pinselsteuerungen
* [UI] Neue QuickInfo mit Tastaturbefehlen für Projektion-Navigationssteuerungen
* [Verbundfilter] Verbundfilter behandeln Varianten zur Arbeit an Bildern, PBR-Materialien und Umgebungslichtern
* [Zusammengesetzte Filter] Die Tweak-Reihenfolge entspricht der Knoten-Listenreihenfolge im zusammengesetzten Filter
* [Zusammengesetzte Filter] Kleine Knoten mit derselben Gruppe werden im Bedienfeld &quot;Eigenschaften&quot; in einer Gruppe zusammengeführt.
* [Anwendung] Dedizierte Viewer-Einstellungen für jeden Asset-Typ

**Fest:**

* [Anwendung] Anwendung kann Absturz beim Wechseln zu 2D-Ansichten verursachen
* [Anwendung] Beheben einer möglichen Deadlock oder eines Absturzes beim mehrmaligen Exportieren
* [Anwendung] Festlegen von Standardwerten für Kanäle für die Konsistenz mit Substance 3D Designer
* [Anwendung] Das Laden eines Projekts löst keine Neuberechnung des Materials aus
* [Anwendung] URL zur Importdokumentation für Texturen aktualisiert
* [Inhalt] Wenn Sie einen zusammengesetzten Filter verwenden, muss er beim erneuten Laden aktualisiert werden, wenn dies nicht der Fall sein sollte
* [Inhalt] Details auf dem Höhen-Map verschwinden bei Verwendung der Deckkraft-Überblendung
* [UI] Im Farbdialogfeld können Sie mithilfe der Textfelder des Reglers den Bereich verlassen
* [UI] Die Verwendungsliste enthält eine nutzlose vertikale Bildlaufleiste

**Bekannte Probleme:**

* [Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* [Inhalt] Shape Light-Widget funktioniert nicht im sphärische Projektion-Modus
* [Interoperabilität] Material mit an Stager gesendetem Versatz verliert die Versatz-Steuerelemente.
