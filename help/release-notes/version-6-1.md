---
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 6.1, um mehr über die neuen Funktionen, Verbesserungen und Arbeitsablaufverbesserungen zu erfahren.
title: Version 6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# Version 6.1

**Kouign amann** (bretonisches Gebäck mit Schichten)

![Alternativtext](../../help/assets/Sampler_splash_large.jpg)

In dieser Version wird der Leistungsmodus eingeführt, sodass jeder die Möglichkeit hat, Einstellungen zu deaktivieren, die seinen Arbeitsablauf verlangsamen können, sowie automatische Stabilitätsverbesserungen, die Benutzer auf leichterer Hardware schützen.

Die wichtigsten neuen Funktionen sind:

## Leistungsmodus

Erleben Sie ein schnelleres, responsiveres Erlebnis mit Sampler. Der neue **Leistungsmodus** vereint alle Einstellungen, die Ihren Arbeitsablauf verlangsamen können: Auflösungsgrenzen, Schatten, Versatz-Qualität und Pfadverfolgung. Deaktivieren Sie Funktionen, die Sie nicht zur Verbesserung der Leistung und Reaktionsfähigkeit benötigen.

Weitere Informationen [*hier*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode)

![](../assets/v6.1/6_1-Performance_Mode.png)

## Verbesserte Unterstützung für Geräte mit minimalen Spezifikationen

Wenn Ihre Hardware die [minimale Spezifikation](../getting-started/system-requirements.md) unterschreitet, passt sich Sampler jetzt automatisch an, um die Stabilität zu gewährleisten. Die Funktionen, die die meisten Dinge verlangsamen oder einen Absturz verursachen, werden automatisch deaktiviert.

Weitere Informationen [*hier*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode)

![](../assets/v6.1/6_1-Checked.png)

## V6.1 - Versionshinweise

*(Freigegeben: 19. November 2026)*

## Hinzugefügt

* &amp;lbrack;Anwendung&amp;rbrack; Neue Möglichkeit, Warnungen zu minimalen Hardwareanforderungen zu melden
* &amp;lbrack;Captis&amp;rbrack; Fügen Sie eine Option hinzu, um zwischen 4 und 8 Polarisationswinkeln zu wählen
* &amp;lbrack;Captis&amp;rbrack; Neue Captis-Schnellaktion
* &amp;lbrack;Export&amp;rbrack; Fehler beim Export ordnungsgemäß dem Benutzer melden
* &amp;lbrack;Export&amp;rbrack; Exportvorgabe für unreales Engine 4 aktualisieren (umbenannt in Unreal Engine 5)
* &amp;lbrack;Performance&amp;rbrack; Asset-Erstellung aus Datei ist jetzt asynchron
* &amp;lbrack;Performance&amp;rbrack; Arbeitsauslastung vom Hauptthread in Arbeitsthreads verschieben
* &amp;lbrack;Performance&amp;rbrack; Neuer Leistungsmodus
* &amp;lbrack;Projekt&amp;rbrack; Benutzer warnen, wenn Speichern des Projekts fehlgeschlagen ist
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue generate_thumbnail-Methode für Assets und neue Typeigenschaft für Ressourcen
* &amp;lbrack;Skripterstellung&amp;rbrack; Rendern eines 3D-Ansichtsschnappschusses in eine Datei aus dem Python-Modul
* &amp;lbrack;UI&amp;rbrack; Durch Klicken auf eine beliebige Stelle in einem Ablagebereich wird das Dateidialogfeld geöffnet
* &amp;lbrack;UI&amp;rbrack; Linke Tastaturbefehle für die Navigationsleiste zu Werkzeugen (Entzerren, Zuschneiden, Kachelung, transformieren, Reparieren, Farbe, ...)
* &amp;lbrack;UI&amp;rbrack; Aktualisieren Sie qt-spektrum, um die neuesten Symbole zu erhalten

## Fest

* &amp;lbrack;3D-Ansicht&amp;rbrack; Sofortige UV-Versatz- und Drehungskorrektur, Entfernen der normalen Skalierung für OpenPBR
* &amp;lbrack;3D-Ansicht&amp;rbrack; Absturz verhindern, indem sichergestellt wird, dass während des Löschens des Viewports keine Bühnenbearbeitung erfolgt
* &amp;lbrack;3D-Ansicht&amp;rbrack; Richtiges Entfernen von Versatz- (Height-)Informationen beim Ändern des angezeigten Elements
* &amp;lbrack;3D-Ansicht&amp;rbrack; Richtige Aktualisierung des Dokuments beim Löschen von Mesh
* &amp;lbrack;Anwendung&amp;rbrack; Sicherstellen, dass die Oberfläche lebendig bleibt, wenn Debuginformationen für dynamische Filter berechnet werden
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden in der Szene beheben
* &amp;lbrack;Anwendung&amp;rbrack; Beheben eines potenziellen Absturzes beim Löschen eines Assets, während der Asset-Datenbankdienst heruntergefahren wird
* &amp;lbrack;Anwendung&amp;rbrack; Sichern Sie den Cache-Debug-Info-Thread, um einen Absturz zu verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Verhindern eines Absturzes durch Testen des Knotens ist nicht NULL, bevor auf ihn zugegriffen wird
* &amp;lbrack;Anwendung&amp;rbrack; Absturz verhindern, der durch den Zugriff auf das erste Element eines leeren Vektors verursacht wird
* &amp;lbrack;Anwendung&amp;rbrack; Absturz in &quot;invalidateVisibleIfs&quot; verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Verhindern eines Absturzes beim Erstellen von Assets, während der Datenbankdienst heruntergefahren wird
* &amp;lbrack;Anwendung&amp;rbrack; Rennbedingung bei Ausfahrt verhindern
* &amp;lbrack;Assets&amp;rbrack; Sicherstellen, dass die Ressourcen hinter der rechten Sperre ordnungsgemäß geschützt sind
* &amp;lbrack;Captis&amp;rbrack; Fehler mit Intensitätswert im manuellen Modus
* &amp;lbrack;Captis&amp;rbrack; Benutzer dürfen keine Zone auswählen, die größer ist als das Backend erlaubt
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Doppeltes Auftreten von SpecularColor in ASM
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Die ID einer Verwendung korrigieren, die aus einer Zeichenfolge erstellt wurde
* &amp;lbrack;Inhalt&amp;rbrack; Problem mit der Deckkraft der Atlas Scatter
* &amp;lbrack;Inhalt&amp;rbrack; Stickerei Filter fehlt metallic Funktion
* &amp;lbrack;Inhalt&amp;rbrack; Perforationsfilter korrigieren
* &amp;lbrack;Inhalt&amp;rbrack; Kategorie des Stilisierungsfilters und einige Korrekturen im Ressourcenfenster korrigieren
* &amp;lbrack;Inhalt&amp;rbrack; Füllfilter aktualisieren
* &amp;lbrack;Creative Cloud&amp;rbrack; Pfad zu 3D-Elementen auf dem Creative Cloud fixieren
* &amp;lbrack;Engine&amp;rbrack; Absturz beim Zugriff auf Engine-Daten verhindern, während der Auftrag abgebrochen wurde
* &amp;lbrack;Export&amp;rbrack; Hinzufügen von defensivem Code zur Strukturansicht ist nicht NULL.
* &amp;lbrack;Export&amp;rbrack; Verteidigungscode zur Vermeidung von Abstürzen bei der SBS
* &amp;lbrack;Export&amp;rbrack; Aktivieren Sie die Ausgabe benutzerdefinierter Verwendungen, auch wenn sie dem Engine bekannt sind.
* &amp;lbrack;Export&amp;rbrack; Exportvorgaben korrigieren
* &amp;lbrack;Export&amp;rbrack; Normalen-Map werden in USD als RAW exportiert
* &amp;lbrack;Export&amp;rbrack; Verwenden Sie beim Exportieren mit einer Vorgabe Ausgabebeschriftungen anstelle von Verwendungszwecken
* &amp;lbrack;Freigelegte Parameter&amp;rbrack; Freigelegte Parameter in dynamischen Filtern beheben
* &amp;lbrack;Freigelegte Parameter&amp;rbrack; Aktualisierung des freigelegten Parameters bei Namensänderung beheben
* &amp;lbrack;Filter&amp;rbrack; Stellen Sie sicher, dass dynamische Filter und Tweak-Identifizierungen bei jeder Ausführung auf jeder Plattform identisch sind.
* &amp;lbrack;Filter&amp;rbrack; Ausblenden nicht unterstützter Verwendungsmöglichkeiten bei der automatischen Kachelung der Kartenauswahl
* &amp;lbrack;Layers&amp;rbrack; Durch Ändern der Ebenensichtbarkeit werden Strukturen immer neu erstellt
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Reduzieren eines Klon-Stempels über etwas
* &amp;lbrack;Layers&amp;rbrack; Beim Einfügen eines Generators direkt auf dem Stapel werden jetzt die Tweak-Werte und der Knotenname ordnungsgemäß festgelegt.
* &amp;lbrack;Layers&amp;rbrack; Beim Einfügen eines Generators mit &quot;Füllung&quot; wird die Textur ordnungsgemäß in der Auswahl angezeigt
* &amp;lbrack;Lokalisierung&amp;rbrack; Zeichenkonformität für Chinesisch in GB 18030
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Speichern nach dem Malen auf einem Klon
* &amp;lbrack;Projekt&amp;rbrack; Sicherstellen, dass Sitzungs- und Projektnamen tatsächlich gespeichert sind
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Speichern einer Baumstruktur verhindern
* &amp;lbrack;Projekt&amp;rbrack; Das Wiederherstellen eines beschädigten Projekts aus der Datenbank ist wieder möglich.
* &amp;lbrack;Schnellaktionen&amp;rbrack; Anzeigen des Popups &quot;Bildauswahl&quot;, wenn sich kein Bild im Stapel befindet
* &amp;lbrack;Schnellaktionen&amp;rbrack; Behebung von Problemen mit Schnellaktionen; Abbrechen einer Schnellaktion schließt den Schnellstart nicht mehr
* &amp;lbrack;Schnellaktionen&amp;rbrack; Importieren von Texturen fordert, einige Kanäle zu aktivieren, sollte aber nicht
* &amp;lbrack;Schnellaktionen&amp;rbrack; Absturz verhindern, wenn eine Schnellaktion nicht geladen werden kann
* &amp;lbrack;Schnellaktionen&amp;rbrack; Inhalt für Schnellaktionen aktualisieren
* &amp;lbrack;Rendering&amp;rbrack; Beheben von combineNormalAndHeight für ASM-Material
* &amp;lbrack;Rendering&amp;rbrack; Verwendung von anzeigbaren Texturen mit Vulkan beheben
* &amp;lbrack;Rendering&amp;rbrack; Baumstruktur als verschmutzt markieren, wenn die eindeutige Verwendungsausgabe geändert wurde
* &amp;lbrack;Rendering&amp;rbrack; Verwenden Sie die richtige Referenzstruktur, um die zu berechnenden Strukturknoten zu berechnen
* &amp;lbrack;Skripterstellung&amp;rbrack; Nicht blockieren, wenn während eines Exports etwas schief geht
* &amp;lbrack;Skripterstellung&amp;rbrack; Vergewissern Sie sich, dass import_images() die importierte Ebene zurückgibt
* &amp;lbrack;Skripterstellung&amp;rbrack; Das Festlegen einer Bildoptimierung für eine Bildelementreferenz schlägt fehl.
* &amp;lbrack;Skripterstellung&amp;rbrack; get_filters() gibt keine dynamischen Filter zurück
* &amp;Klammer;Miniatur&amp;Klammer; Beheben potenzieller Absturz beim Generieren einer Miniaturansicht
* &amp;Klammer;Miniatur&amp;Klammer; Erstellen Sie den Miniaturbildgenerator neu, wenn sich das Layout ändert
* &amp;lbrack;UI&amp;rbrack; Wenn Sie das Element ändern, kann die Height-Skalierung auf den maximalen Wert des Schiebereglers gesetzt werden
* &amp;lbrack;UI&amp;rbrack; Beim Zeichnen in einer Textur wird die Auswahl der Textur in Echtzeit aktualisiert
* &amp;lbrack;UI&amp;rbrack; Wenn Sie den Vollbildmodus aufrufen, während Sie nicht maximiert sind, wird jetzt das gesamte Fenster ausgefüllt
* &amp;lbrack;UI&amp;rbrack; Fehlerhafte Verknüpfung zum Substance Magazine beheben
* &amp;lbrack;UI&amp;rbrack; Korrigieren von Popup-Rändern beim Export
* &amp;lbrack;UI&amp;rbrack; Größe des Abschnittstitels anpassen
* &amp;lbrack;UI&amp;rbrack; Tippfehler in einer Zeichenfolge korrigieren
* &amp;lbrack;UI&amp;rbrack; Linux-Dateidialog verwendet jetzt das GTK-Plugin
* &amp;lbrack;UI&amp;rbrack; Absturz bei der Anzeige von Emojis verhindern
* &amp;lbrack;UI&amp;rbrack; Umbenennen von .ssa-Dateien in &quot;Adobe Substance 3D Sampler-Archiv&quot; (ohne Version oder Beta)
* &amp;lbrack;UI&amp;rbrack; Wiederherstellen der flackernden Verzögerung bei Verwendung der Maus
* &amp;lbrack;UI&amp;rbrack; Kleine Korrekturen im Dialogfeld &quot;Neues Material erstellen&quot;
