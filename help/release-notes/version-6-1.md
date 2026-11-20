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

* &lbrack;Anwendung&rbrack; Neue Möglichkeit, Warnungen zu minimalen Hardwareanforderungen zu melden
* &lbrack;Captis&rbrack; Fügen Sie eine Option hinzu, um zwischen 4 und 8 Polarisationswinkeln zu wählen
* &lbrack;Captis&rbrack; Neue Captis-Schnellaktion
* &lbrack;Export&rbrack; Fehler beim Export ordnungsgemäß dem Benutzer melden
* &lbrack;Export&rbrack; Exportvorgabe für unreales Engine 4 aktualisieren (umbenannt in Unreal Engine 5)
* &lbrack;Performance&rbrack; Asset-Erstellung aus Datei ist jetzt asynchron
* &lbrack;Performance&rbrack; Arbeitsauslastung vom Hauptthread in Arbeitsthreads verschieben
* &lbrack;Performance&rbrack; Neuer Leistungsmodus
* &lbrack;Projekt&rbrack; Benutzer warnen, wenn Speichern des Projekts fehlgeschlagen ist
* &lbrack;Skripterstellung&rbrack; Neue generate_thumbnail-Methode für Assets und neue Typeigenschaft für Ressourcen
* &lbrack;Skripterstellung&rbrack; Rendern eines 3D-Ansichtsschnappschusses in eine Datei aus dem Python-Modul
* &lbrack;UI&rbrack; Durch Klicken auf eine beliebige Stelle in einem Ablagebereich wird das Dateidialogfeld geöffnet
* &lbrack;UI&rbrack; Linke Tastaturbefehle für die Navigationsleiste zu Werkzeugen (Entzerren, Zuschneiden, Kachelung, transformieren, Reparieren, Farbe, ...)
* &lbrack;UI&rbrack; Aktualisieren Sie qt-spektrum, um die neuesten Symbole zu erhalten

## Fest

* &lbrack;3D-Ansicht&rbrack; Sofortige UV-Versatz- und Drehungskorrektur, Entfernen der normalen Skalierung für OpenPBR
* &lbrack;3D-Ansicht&rbrack; Absturz verhindern, indem sichergestellt wird, dass während des Löschens des Viewports keine Bühnenbearbeitung erfolgt
* &lbrack;3D-Ansicht&rbrack; Richtiges Entfernen von Versatz- (Height-)Informationen beim Ändern des angezeigten Elements
* &lbrack;3D-Ansicht&rbrack; Richtige Aktualisierung des Dokuments beim Löschen von Mesh
* &lbrack;Anwendung&rbrack; Sicherstellen, dass die Oberfläche lebendig bleibt, wenn Debuginformationen für dynamische Filter berechnet werden
* &lbrack;Anwendung&rbrack; Absturz beim Beenden in der Szene beheben
* &lbrack;Anwendung&rbrack; Beheben eines potenziellen Absturzes beim Löschen eines Assets, während der Asset-Datenbankdienst heruntergefahren wird
* &lbrack;Anwendung&rbrack; Sichern Sie den Cache-Debug-Info-Thread, um einen Absturz zu verhindern
* &lbrack;Anwendung&rbrack; Verhindern eines Absturzes durch Testen des Knotens ist nicht NULL, bevor auf ihn zugegriffen wird
* &lbrack;Anwendung&rbrack; Absturz verhindern, der durch den Zugriff auf das erste Element eines leeren Vektors verursacht wird
* &lbrack;Anwendung&rbrack; Absturz in &quot;invalidateVisibleIfs&quot; verhindern
* &lbrack;Anwendung&rbrack; Verhindern eines Absturzes beim Erstellen von Assets, während der Datenbankdienst heruntergefahren wird
* &lbrack;Anwendung&rbrack; Rennbedingung bei Ausfahrt verhindern
* &lbrack;Assets&rbrack; Sicherstellen, dass die Ressourcen hinter der rechten Sperre ordnungsgemäß geschützt sind
* &lbrack;Captis&rbrack; Fehler mit Intensitätswert im manuellen Modus
* &lbrack;Captis&rbrack; Benutzer dürfen keine Zone auswählen, die größer ist als das Backend erlaubt
* &lbrack;Kanaleinstellungen&rbrack; Doppeltes Auftreten von SpecularColor in ASM
* &lbrack;Kanaleinstellungen&rbrack; Die ID einer Verwendung korrigieren, die aus einer Zeichenfolge erstellt wurde
* &lbrack;Inhalt&rbrack; Problem mit der Deckkraft der Atlas Scatter
* &lbrack;Inhalt&rbrack; Stickerei Filter fehlt metallic Funktion
* &lbrack;Inhalt&rbrack; Perforationsfilter korrigieren
* &lbrack;Inhalt&rbrack; Kategorie des Stilisierungsfilters und einige Korrekturen im Ressourcenfenster korrigieren
* &lbrack;Inhalt&rbrack; Füllfilter aktualisieren
* &lbrack;Creative Cloud&rbrack; Pfad zu 3D-Elementen auf dem Creative Cloud fixieren
* &lbrack;Engine&rbrack; Absturz beim Zugriff auf Engine-Daten verhindern, während der Auftrag abgebrochen wurde
* &lbrack;Export&rbrack; Hinzufügen von defensivem Code zur Strukturansicht ist nicht NULL.
* &lbrack;Export&rbrack; Verteidigungscode zur Vermeidung von Abstürzen bei der SBS
* &lbrack;Export&rbrack; Aktivieren Sie die Ausgabe benutzerdefinierter Verwendungen, auch wenn sie dem Engine bekannt sind.
* &lbrack;Export&rbrack; Exportvorgaben korrigieren
* &lbrack;Export&rbrack; Normalen-Map werden in USD als RAW exportiert
* &lbrack;Export&rbrack; Verwenden Sie beim Exportieren mit einer Vorgabe Ausgabebeschriftungen anstelle von Verwendungszwecken
* &lbrack;Freigelegte Parameter&rbrack; Freigelegte Parameter in dynamischen Filtern beheben
* &lbrack;Freigelegte Parameter&rbrack; Aktualisierung des freigelegten Parameters bei Namensänderung beheben
* &lbrack;Filter&rbrack; Stellen Sie sicher, dass dynamische Filter und Tweak-Identifizierungen bei jeder Ausführung auf jeder Plattform identisch sind.
* &lbrack;Filter&rbrack; Ausblenden nicht unterstützter Verwendungsmöglichkeiten bei der automatischen Kachelung der Kartenauswahl
* &lbrack;Layers&rbrack; Durch Ändern der Ebenensichtbarkeit werden Strukturen immer neu erstellt
* &lbrack;Layers&rbrack; Absturz beim Reduzieren eines Klon-Stempels über etwas
* &lbrack;Layers&rbrack; Beim Einfügen eines Generators direkt auf dem Stapel werden jetzt die Tweak-Werte und der Knotenname ordnungsgemäß festgelegt.
* &lbrack;Layers&rbrack; Beim Einfügen eines Generators mit &quot;Füllung&quot; wird die Textur ordnungsgemäß in der Auswahl angezeigt
* &lbrack;Lokalisierung&rbrack; Zeichenkonformität für Chinesisch in GB 18030
* &lbrack;Projekt&rbrack; Absturz beim Speichern nach dem Malen auf einem Klon
* &lbrack;Projekt&rbrack; Sicherstellen, dass Sitzungs- und Projektnamen tatsächlich gespeichert sind
* &lbrack;Projekt&rbrack; Absturz beim Speichern einer Baumstruktur verhindern
* &lbrack;Projekt&rbrack; Das Wiederherstellen eines beschädigten Projekts aus der Datenbank ist wieder möglich.
* &lbrack;Schnellaktionen&rbrack; Anzeigen des Popups &quot;Bildauswahl&quot;, wenn sich kein Bild im Stapel befindet
* &lbrack;Schnellaktionen&rbrack; Behebung von Problemen mit Schnellaktionen; Abbrechen einer Schnellaktion schließt den Schnellstart nicht mehr
* &lbrack;Schnellaktionen&rbrack; Importieren von Texturen fordert, einige Kanäle zu aktivieren, sollte aber nicht
* &lbrack;Schnellaktionen&rbrack; Absturz verhindern, wenn eine Schnellaktion nicht geladen werden kann
* &lbrack;Schnellaktionen&rbrack; Inhalt für Schnellaktionen aktualisieren
* &lbrack;Rendering&rbrack; Beheben von combineNormalAndHeight für ASM-Material
* &lbrack;Rendering&rbrack; Verwendung von anzeigbaren Texturen mit Vulkan beheben
* &lbrack;Rendering&rbrack; Baumstruktur als verschmutzt markieren, wenn die eindeutige Verwendungsausgabe geändert wurde
* &lbrack;Rendering&rbrack; Verwenden Sie die richtige Referenzstruktur, um die zu berechnenden Strukturknoten zu berechnen
* &lbrack;Skripterstellung&rbrack; Nicht blockieren, wenn während eines Exports etwas schief geht
* &lbrack;Skripterstellung&rbrack; Vergewissern Sie sich, dass import_images() die importierte Ebene zurückgibt
* &lbrack;Skripterstellung&rbrack; Das Festlegen einer Bildoptimierung für eine Bildelementreferenz schlägt fehl.
* &lbrack;Skripterstellung&rbrack; get_filters() gibt keine dynamischen Filter zurück
* &Klammer;Miniatur&Klammer; Beheben potenzieller Absturz beim Generieren einer Miniaturansicht
* &Klammer;Miniatur&Klammer; Erstellen Sie den Miniaturbildgenerator neu, wenn sich das Layout ändert
* &lbrack;UI&rbrack; Wenn Sie das Element ändern, kann die Height-Skalierung auf den maximalen Wert des Schiebereglers gesetzt werden
* &lbrack;UI&rbrack; Beim Zeichnen in einer Textur wird die Auswahl der Textur in Echtzeit aktualisiert
* &lbrack;UI&rbrack; Wenn Sie den Vollbildmodus aufrufen, während Sie nicht maximiert sind, wird jetzt das gesamte Fenster ausgefüllt
* &lbrack;UI&rbrack; Fehlerhafte Verknüpfung zum Substance Magazine beheben
* &lbrack;UI&rbrack; Korrigieren von Popup-Rändern beim Export
* &lbrack;UI&rbrack; Größe des Abschnittstitels anpassen
* &lbrack;UI&rbrack; Tippfehler in einer Zeichenfolge korrigieren
* &lbrack;UI&rbrack; Linux-Dateidialog verwendet jetzt das GTK-Plugin
* &lbrack;UI&rbrack; Absturz bei der Anzeige von Emojis verhindern
* &lbrack;UI&rbrack; Umbenennen von .ssa-Dateien in &quot;Adobe Substance 3D Sampler-Archiv&quot; (ohne Version oder Beta)
* &lbrack;UI&rbrack; Wiederherstellen der flackernden Verzögerung bei Verwendung der Maus
* &lbrack;UI&rbrack; Kleine Korrekturen im Dialogfeld &quot;Neues Material erstellen&quot;
