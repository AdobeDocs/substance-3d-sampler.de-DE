---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/release-notes/version-5-1-substance-3d-sampler.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 5.1, um mehr über die neuen Funktionen, Verbesserungen und Arbeitsablaufverbesserungen zu erfahren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 5.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '824'
ht-degree: 2%

---


# Version 5.1

![](../assets/welcome_digitization_tool.jpg)

Verbringen Sie weniger Zeit zwischen dem Aufnehmen Ihrer Materials und dem Exportieren ihrer digitalen Zwillinge mit neuen und verbesserten Tools in <b>Substance 3D Sampler 5.1</b>!

Die wichtigsten neuen Funktionen sind:

## Kachelung von automatisch strukturierten Materialien

Sparen Sie Zeit bei der Verarbeitung von strukturierten oder gemusterten Materialien (z. B. Stoffen), indem Sie automatisch nahtlose Kacheln generieren.

Weitere Informationen *[hier](../filters/tools/auto-tiling.md)*.

![](../assets/WhatsNew_Auto-tiling-5_1.jpg)

## Effiziente Ebenen-Workflows

Steigern Sie die Leistung, und verkürzen Sie die Berechnung mit der Ebene &quot;Reduzieren&quot;, indem Sie gestapelte Ebenen transformieren haben. So entsteht eine einzige Kartenmenge innerhalb einer einheitlichen Ebene. Benennen Sie sie um und duplizieren Sie sie, um mehr Effizienz zu erzielen!

Weitere Informationen *[hier](../features-and-workflows/flatten-layers.md)*.

![](../assets/WhatsNew_Flatten-Layers-5_1.png)

## Leistungsstarke Werkzeuge für die Scanverarbeitung

Mit den erweiterten Filtern zum Ausgleichen und zum Stempeln von Klonen sowie der neuen Funktion zum automatischen Entfernen von Falten aus Stoffen können Sie mit nur wenigen Klicks perfekte Scans erzielen, ganz gleich, wie komplex das Material ist.

![](../assets/WhatsNew_Equalize-5_1.jpg)

## Verbesserte Unterstützung für HP Z Captis

Mit der Generierung von Rauheiten-Maps und automatischer Physische Größe-Erkennung im Studiomodus erhalten Sie jetzt einen detaillierteren und präziseren Material-Zwilling als je zuvor.

![](../assets/whatsnew-hp-z-captis-5-1.jpg)

## V5.1 - Versionshinweise

*(Freigegeben: 7. August 2025)*

## Hinzugefügt:

* [2D-Ansicht] Die Pinselgröße passt sich jetzt der aktuellen Auflösung der Textur an
* [3D-Ansicht] Native Anzeigeskalierung für 3D-Rendering in den Voreinstellungen aktivieren/deaktivieren
* [Anwendung] Render-Engine-Update
* [Captis] Hinzufügen der Option &quot;Quadrat erstellen&quot; während der Vorschau
* [Captis] Automatische Erkennung von Physische Größen
* [Captis] Durch das Erfassen eines neuen Materials wird ein neues Asset erstellt.
* [Captis] Ändern Sie die Auflösungsauswahl im Dropdown auf Pixel pro Zoll oder Zentimeter anstelle der Pixelauflösung des maximalen Bereichs
* [Captis] Kontextbezogene Hilfe zur Ausrichtungskalibrierung
* [Captis] Generate Rauheit Map
* [Captis] Warnen Sie den Benutzer, wenn die Standardkalibrierungsdateien fehlen.
* [Filter] Filter für die automatische Kachelung für strukturierte Materialien und Scans
* [Filter] Neuer Fold-Entferner-Filter
* [Klon] Neue Funktionen des Filterstempelfilters
* [Filter] Neue Funktionen des Filters &quot;Tonwertangleichung&quot;
* [Ebenen] Möglichkeit zum Reduzieren von Ebenen
* [Ebenen] Kontextmenü beim Rechtsklick auf eine Ebene zum Umbenennen, Duplizieren, Löschen oder Reduzieren der Ebene
* [Onboarding] Update des Begrüßungsbildschirms und der Bildschirminhalte zu Neuerungen
* [Leistung] Bessere Leistung bei Verwendung des Zuschneidefilters
* [Performance] Verbessern der Speichernutzung für die 3D-Ansicht
* [Leistung] Die 3D-Ansicht wird schneller aktualisiert
* [Physische Größe] Aktivieren Sie &quot;Anzeige mit physischem Verhältnis&quot;, wenn Sie mit Substance-Filtern arbeiten, wenn Physische Größe aktiviert ist.
* [Physische Größe] Wenn Sie Bilder in einen leeren Stapel importieren, schlagen Sie eine Auflösung vor, die dem Bildverhältnis besser entspricht.
* [Schnellaktionen] 3 neue Schnellaktionen für die Scanverarbeitung
* [Scripting] API zum Reduzieren von Ebenen
* [Scripting] Erhalten Sie den Dateinamen für jedes Bild einer Bildimportebene
* [Scripting] Neue Funktion zum Aktivieren/Deaktivieren eines bestimmten Kanals eines Assets
* [UI] Icons und Buttons im Bedienfeld &quot;Ebenen&quot; überarbeiten, um den neuen Funktionen gerecht zu werden
* [UI] Warnung vor dem Verwerfen des Umgebungslicht-Authoring

## Fest:

* [2D-Ansicht] Die Auswahl von &quot;Anzeige mit physischem Verhältnis&quot; funktioniert möglicherweise nicht, wenn Substance-Filter verwendet werden
* [3D-Erfassung] SVG-Dateien werden in der Dateiauswahl aufgeführt, aber nicht unterstützt.
* [3D-Ansicht] Emissionsintensitätsparameter in den Shader-Einstellungen funktioniert nicht
* [3D-Ansicht] Manchmal ist die Position des Meshs falsch, wenn ein neues Asset erstellt wird
* [3D-Ansicht] Wechseln zu Abstürzen beim Rendern von Pfadverfolgung auf nicht unterstützter Hardware
* [Anwendung] Anwendung hängt sich auf, wenn das Popup für manuelle Messungen geschlossen wird, ohne eine Größe festzulegen
* Absturz [Anwendung]
* [Anwendung] Einfrieren unter Windows bei Anzeige des Desktops (Windows-Taste + D-Tastatur-Tastaturbefehl)
* [Anwendung] Mögliche Abstürze beim Wechseln der Sprache
* [Captis] Absturz, wenn die Vorschaudaten ungültig sind
* [Captis] Nach dem Einzoomen ist es nicht möglich, vollständig auszuzoomen
* [Captis] Fehlende Lokalisierung in einigen Schritten des Assistenten
* [Captis] Möglicher Absturz beim Beenden bei Verwendung von Captis
* [Captis] Das Scannen funktioniert nicht, wenn dem Gerät Kalibrierungsdateien fehlen
* [Filter] Die Pinselvorschau bei Verwendung des Klon-Stempelfilters kann je nach Textur und Pinselgröße falsch sein
* [Filter] Fehlerhafte Ausgabegröße nach Verwendung des Filters &quot;Hochskalieren&quot;
* [Filter] Fehlende Symbole für Umgebungsdrehungs- und Stilisierungsfilter
* [Filter] Die Aktualisierung einiger Filter kann zu falschem Rendering führen
* [Ebenen] Falsches erstes Rendering beim Mischen von zwei Materialien
* [Ebenen] Die Schaltfläche zum Aktualisieren von Ebenen zeigt &quot;Alle aktualisieren&quot; an, auch wenn nur ein Update vorhanden ist
* [Ebenen] Unnötige Berechnungen beim Importieren von Bildern im Ebenenstapel
* [Leistung] Verbessern der Normalen-Map-Format-Handhabung zur Reduzierung der Rendering-Zeiten
* [Physische Größe] Popup für manuelle Messung funktioniert nur nach einer automatischen Messung
* [Physische Größe] Falsche Exportauflösung im Popup &quot;Exportieren&quot;, wenn Physische Größe aktiviert ist
* [Schnellaktionen] Fehlende Lokalisierung bei generierten Elementnamen
* [UI] Asset-Vorschau beim Hovern wird möglicherweise nicht angezeigt
* [UI] Durch Klicken auf die Schaltfläche Auf Standardwert zurücksetzen können einige der Steuerelemente beschädigt werden
* [UI] Fehlermeldungen werden beim Wechseln von Projekten nicht gelöscht
* [UI] Stellen Sie sicher, dass der Name des Materials im Bereich Viewport und Eigenschaften leer ist, wenn kein Element vorhanden ist
* [UI] Die Schaltfläche Auf Standardwert zurücksetzen für den Parameter &quot;Point of View&quot; funktioniert nicht
* [UI] Schaltfläche &quot;Auf Standardwert zurücksetzen&quot; überlappt
* [UI] Einige Schaltflächen sind nicht anklickbar, wenn ein Bedienfeld abgedockt ist
* [UI] Textur-Kachel V Parameter teilweise in Anzeigeeinstellungen und 3D-Ansichten ausgeblendet

## Entfernt:

* [3D-Erfassung] Unterstützung für Entfernen von 3D-Erfassungen
* [Anwendung] Unterstützung für macOS x86 entfernen
