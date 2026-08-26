---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Prüfe alle Änderungen und Updates in den verschiedenen Substance 3D Sampler-Versionen, um den Funktionsverlauf und Verbesserungen im Laufe der Zeit nachzuverfolgen.
helpx_description: Sampler > Release Notes > All Changes
title: Alle Änderungen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0484ed7ae81bd16687abe23ac0ce8f5ad84d1888
workflow-type: tm+mt
source-wordcount: '24940'
ht-degree: 0%

---


# Alle Änderungen

Auf dieser Seite werden alle Änderungen, die an Substance 3D Sampler vorgenommen wurden, zusammengefasst, von neuen Funktionen bis hin zu Fehlerbehebungen.

## Version 6

### **6.0.3**

*(Freigegeben: 24. August 2026)*

**Fest:**

[Rendern] Stellen Sie einen temporären Workaround für fehlerhafte NVIDIA-Treiber wieder her.

### **6.0.2**

*(Freigegeben: 25. Juni 2026)*

**Hinzugefügt:**

* &lbrack;Assets&rbrack; Überprüfen Sie die sbsar-Version und warnen Sie Benutzer ist die Engine zu alt, um sie zu lesen
* &lbrack;Captis&rbrack; Option &quot;Zurück&quot; hinzufügen, um die Kapitelphotometrie in den Voreinstellungen zu speichern

**Fest:**

* &lbrack;2D Ansicht&rbrack; Nicht mit physischem Verhältnis anzeigen, wenn Physische Größe deaktiviert ist
* &lbrack;Analyse&rbrack; Fehlende Analyseereignisse
* &lbrack;Analyse&rbrack; Verhindern Sie Abstürze, um einen Absturz auf vk-Geräten zu meldenListe
* &lbrack;Anwendung&rbrack; Zerstören Sie keine vkdevices beim Beenden, um einen Absturz des nvidia-Treibers zu vermeiden
* &lbrack;Anwendung&rbrack; Verknüpfte Sammlungs-Watcher-Ausgang + Kanal-Manager reparieren
* &lbrack;Anwendung&rbrack; Absturz beim Beenden verhindern
* &lbrack;Inhalt&rbrack; Filter &quot;Metal-Finish&quot; wirkt sich nicht auf die Metallisierung aus
* &lbrack;Inhalt&rbrack; Physische Größe zu dynamischen Filtern hinzufügen, wenn sie fehlt
* &lbrack;Filter&rbrack; Entfernen des inhaltsbasierten Füllens aus der Liste &quot;Ausgeblendete Elemente&quot;
* &lbrack;Layers&rbrack; Durch Klicken auf &quot;Alle Einstellungen zurücksetzen&quot; wird die Dropdown-Liste &quot;Betrifft&quot; nicht zurückgesetzt
* &lbrack;Layers&rbrack; Minimale und maximale Anpassung für Positions-Widget
* &lbrack;Layers&rbrack; Filter richtig aktualisieren
* &lbrack;Physische Größe&rbrack; Sorgen Sie mit dynamischen Filtern dafür, dass die physische Skalierung überall funktioniert, und machen Sie die physische Größe ok.
* &lbrack;Projekt&rbrack; Sicherstellen, dass die Standardauflösung für Assets (2K x 2K) beim Erstellen eines neuen Assets festgelegt ist
* &lbrack;Projekt&rbrack; Aktuelles Projekt, mit dem die vorherige Version geöffnet wurde, erneut öffnen
* &lbrack;Projekt&rbrack; Sampler bietet nicht mehr an, eine Sicherung beschädigter Projekte wiederherzustellen.
* &lbrack;Rendering&rbrack; Miniaturansicht des Materials mit einer maximalen Auflösung von 2k rendern
* &lbrack;UI&rbrack; Defensiver Code zur Vermeidung von Abstürzen, wenn der Benutzer schneller als die Benutzeroberfläche ist

### **6.0.1**

*(Freigegeben: 21. Mai 2026)*

**Hinzugefügt:**

* &lbrack;Anwendung&rbrack; Benutzer beim Öffnen eines Projekts mit 3D-Objekten oder Umgebungslichtern warnen
* &lbrack;Captis&rbrack; Anpassen der Benutzeroberfläche an kleine Bildschirme
* &lbrack;Captis&rbrack; Captis-Benutzeroberfläche aktualisieren
* &lbrack;Kanaleinstellungen&rbrack; Automatisches Aktivieren von SSS bei Verwendung des SSS-Kanals in ASM
* &lbrack;Motor&rbrack; Substance Engine auf Version 9.4.3 aktualisieren
* &lbrack;Vorgabe&rbrack; Option &quot;Vorgabewerte für Miniaturansichten anwenden&quot; standardmäßig aktiviert
* &lbrack;Resources&rbrack; Standardmäßig &quot;alle Bibliotheken&quot; anstelle von &quot;Starter-Assets&quot; im Ressourcenbedienfeld anzeigen
* &lbrack;Skripterstellung&rbrack; Hinzufügen von Python-Funktionen zum Verwalten von &quot;Angewendet auf&quot; einer Ebene
* &lbrack;UI&rbrack; Die Elementliste reagiert jetzt: Größe des Assets passt sich an den Container an
* &lbrack;UI&rbrack; 3D-/2D-Ansicht standardmäßig anzeigen
* &lbrack;UI&rbrack; Popup-Fenster zur Materialoptimierung beim Ablegen eines Materials aus dem Explorer anzeigen
* &lbrack;UI&rbrack; Kippen von Gerätestangenschaltflächen aktivieren - QuickInfo

**Fest:**

* &lbrack;Anwendung&rbrack; Beheben von Farbraumproblemen
* &lbrack;Anwendung&rbrack; Anpassen der Einstellungen
* &lbrack;Anwendung&rbrack; Scankanäle aktivieren, wenn sie auf &quot;Automatisch&quot; eingestellt sind
* &lbrack;Anwendung&rbrack; Die Schaltfläche &quot;Neues Projekt&quot; auf dem Startbildschirm löscht nicht mehr das vorherige Projekt mit demselben Namen
* &lbrack;Anwendung&rbrack; Absturz beim Beenden von macOS verhindern
* &lbrack;Anwendung&rbrack; Zugriff auf Assets mit ungültigen Asset-Referenzen verhindern
* &lbrack;Anwendung&rbrack; Absturz beim Zugriff auf die Oberfläche aus VersionedImage in einer Optimierung verhindern
* &lbrack;Anwendung&rbrack; Absturz beim Löschen einer Bühne verhindern, wenn keine vorhanden ist
* &lbrack;Captis&rbrack; Stellen Sie sicher, dass Captis getrennt ist, bevor Sie Sampler schließen.
* &lbrack;Captis&rbrack; Doppelte Anzeige der USB-2-Warnung verhindern
* &lbrack;Kanaleinstellungen&rbrack; OpenPBR-Kanalnamen korrigieren
* &lbrack;Kanaleinstellungen&rbrack; Aktualisieren langer Beschriftungen für OpenPBR-Kanäle
* &lbrack;Inhalt&rbrack; Alle Gittereinheiten von Meter auf Zentimeter für SSS-Werte aktualisieren
* &lbrack;Export&rbrack; Sicherstellen, dass Standardwerte an dynamische Filter angeschlossen sind
* &lbrack;Export&rbrack; Bilder werden jetzt in einem Arbeitsthread gespeichert, um die Leistung zu verbessern
* &lbrack;Filter&rbrack; Inhaltsbasierte Füllung stürzt ab, wenn die Skalierung aktiviert wird
* &lbrack;Filter&rbrack; Der Speicherort eines dynamischen Filters konnte nicht aus dem Bedienfeld &quot;Elemente&quot; geöffnet werden.
* &lbrack;Filter&rbrack; Fixieren Sie alle im AutoTiling-Anpassungsschritt zurücksetzen
* &lbrack;Filter&rbrack; Wiederherstellen Deaktivieren der Verarbeitung der Verwendung bei der Erstellung von Baumstrukturen
* &lbrack;Filter&rbrack; Festlegen des richtigen Standardwerts für den Parameter &quot;upscale&quot;
* &lbrack;Filter&rbrack; Generatoren aktualisieren, auch wenn sie sich in einer Füllebene befinden
* &lbrack;Layers&rbrack; Umbenennen der Kopfzeile einer Eingabeebene oder der Platzhalterebenen ist untersagt
* &lbrack;Layers&rbrack; Absturz beim Einfügen von Ebenen durch baumelnde Zeiger verhindern
* &lbrack;Layers&rbrack; Falsche Anzahl von Bildern im flachen Ebenennamen
* &lbrack;Lokalisierung&rbrack; Stellen Sie sicher, dass Vorgabennamen beim Wechseln der Sprachen aktualisiert werden.
* &lbrack;Lokalisierung&rbrack; Mehrere Übersetzungsprobleme im Ressourcenbereich
* &lbrack;Lokalisierung&rbrack; Schnellaktionen - Kategorien Lokalisierungsprobleme
* &lbrack;Performance&rbrack; Laden von Änderungen nur im geöffneten Abschnitt
* &lbrack;Voreinstellungen&rbrack; Das Löschen des Voreinstellungs-Cache-Pfads wird auf den vorherigen Wert zurückgesetzt
* &lbrack;Rendering&rbrack; Speicherverlust bei Verwendung des Pfadverfolgung
* &lbrack;Rendering&rbrack; Löschen von Texturen verhindern, solange Vulkan noch auf sie zugreifen kann
* &lbrack;Rendering&rbrack; Die Texturdrehung wurde nicht von 0-1 auf 0-360 konvertiert.
* &lbrack;Skripterstellung&rbrack; Entfernen nicht vorhandener Klassen aus der Python-Dokumentation
* &lbrack;Skripterstellung&rbrack; selectedAsset gibt Keine zurück, wenn kein ausgewähltes Asset vorhanden ist
* &lbrack;Extras&rbrack; Durch das Zurücksetzen eines Texturwerts wird das Malen beendet und die Patch-Ansicht gelöscht.
* &lbrack;UI&rbrack; Schließen Sie die Abschnitte im Eigenschaftenfenster nicht, wenn etwas geändert wird
* &lbrack;UI&rbrack; Sichtbares Farb-Tweak-Label beim Bewegen des Mauszeigers nicht sichtbar
* &lbrack;UI&rbrack; Verhalten &quot;Responsive&quot; für Elementliste korrigieren
* &lbrack;UI&rbrack; Bindungsschleife in der QuickInfo für AssetItem reparieren
* &lbrack;UI&rbrack; Doppelklick auf ausgewählte Vorgabengruppe korrigieren
* &lbrack;UI&rbrack; Ablagebereich im Bildmoderator korrigieren
* &lbrack;UI&rbrack; Beschriftung mit Schaltfläche für alle Sprachen korrigieren
* &lbrack;UI&rbrack; Height &quot;Line&quot; für Japanisch im Kanallisten-Popup korrigieren
* &lbrack;UI&rbrack; Behebung eines akzeptierten Signals im Längenfeld
* &lbrack;UI&rbrack; Popupbreite mit langem linken Steuerelement korrigieren
* &lbrack;UI&rbrack; Popup-Vorschau in Elementelementen korrigieren
* &lbrack;UI&rbrack; Reparieren des groben/reflektierenden Pflückers
* &lbrack;UI&rbrack; Stringellipse fixieren
* &lbrack;UI&rbrack; Problem beim Abschneiden von Zeichenfolgen beheben
* &lbrack;UI&rbrack; Reset-Taste für Schalteroptimierung beheben
* &lbrack;UI&rbrack; Ausblenden der Dropdown-Liste &quot;Materialmodell&quot;, wenn eine benutzerdefinierte Exportvorgabe ausgewählt ist
* &lbrack;UI&rbrack; Auflösung in der Kanalliste des Export-Popup entfernen
* &lbrack;UI&rbrack; Auf Standardlayout zurücksetzen behält die Projektionsanzeige bei
* &lbrack;UI&rbrack; Menüelemente &quot;In Photoshop bearbeiten&quot; und &quot;In Illustrator bearbeiten&quot; wiederherstellen

**Entfernt:**

* &lbrack;UI&rbrack; Entfernen des Abschnitts &quot;Angewendet auf&quot; für Bildimportebenen
* &lbrack;UI&rbrack; QuickInfo zum automatischen Öffnen beim ersten Start entfernen

## Version 5

### **5.1.3 ÎLE FLOTTANTE**

*(Freigegeben: 6. Januar 2026)*

**Hinzugefügt:**

* &lbrack;Captis&rbrack; Warnmeldung anzeigen, wenn das FTP-Protokoll von der Firewall deaktiviert wurde

**Fest:**

* &lbrack;Captis&rbrack; Abbrechen während einer Aufnahme kann zu Fehlern führen
* &lbrack;Captis&rbrack; Das Herunterladen der Ergebnisse am Ende einer Aufnahme beansprucht zu viel RAM
* &lbrack;Captis&rbrack; Das Ausführen eines Autofokus direkt nach einer Autointensität kann zu Fehlern führen
* &lbrack;Captis&rbrack; Die Anzeige von HDR-Ergebnissen im Bedienfeld &quot;Zusammenfassung&quot;
* &lbrack;UI&rbrack; In einigen Fällen wählt das Ordnerdialogfeld auf MacOS nicht den richtigen Ordner aus

### **5.1.2 ÎLE FLOTTANTE**

*(Freigegeben: 20. November 2025)*

**Hinzugefügt:**

* &lbrack;Anwendung&rbrack; Grafikgeräteverlust erkennen, Benutzer warnen und ordnungsgemäß beenden
* &lbrack;Layers&rbrack; Verbesserte Messaging-Funktion beim Reduzieren von Ebenen
* &lbrack;Layers&rbrack; Verbesserte Miniaturen für Bildimport- und abgeflachte Ebenen
* &lbrack;Onboarding&rbrack; Aktualisierte Lerninhalte auf dem Startbildschirm
* &lbrack;Projekt&rbrack; Wiederherstellen des zuletzt gespeicherten Sitzungszustands vor dem Absturz
* &lbrack;UI&rbrack; Aktualisierung des Applikationssymbols

**Fest:**

* &lbrack;Anwendung&rbrack; Das Einfügen eines Materials in den Ebenenstapel kann in macOS zu einem Absturz führen
* &lbrack;Anwendung&rbrack; Möglicher Absturz bei hoher Belastung auf macOS
* &lbrack;Anwendung&rbrack; Mögliche Abstürze beim Hinzufügen von Ebenen, wenn der Videospeicher voll ist
* &lbrack;Anwendung&rbrack; Möglicher Absturz beim Öffnen eines Projekts
* &lbrack;Captis&rbrack; Fehler, wenn der Autofokus kurz nach der automatischen Intensitätskalibrierung ausgeführt wird
* &lbrack;Captis&rbrack; Zuverlässigkeits- und Leistungsprobleme nach der ersten Aufnahme
* &lbrack;Captis&rbrack; Verzögerungen und Fehler beim Kopieren von Dateien am Ende einer Aufnahme
* &lbrack;Captis&rbrack; Kleines Speicherleck bei der Abfrage von Captis-Geräteinformationen
* &lbrack;Export&rbrack; Durch mehrere Regler exponierte Parameter werden beschädigte .sbsar-Dateien erzeugt
* &lbrack;Layers&rbrack; Das Muster für die automatische Unterteilung wird beim Wechseln von Elementen auf die Standardwerte zurückgesetzt
* &lbrack;Layers&rbrack; Standardmäßige benutzerdefinierte Grundfarbe wird rot angezeigt
* &lbrack;Layers&rbrack; Die teilweise Reduzierung der untergeordneten Ebenen des Kopierstempels ist möglich und verursacht Renderprobleme
* &lbrack;Layers&rbrack; Möglicher Absturz beim Anpassen eines Ebenenstapels während des Renderns
* &lbrack;Layers&rbrack; Unerwarteter Fehler beim Schritt zum automatischen Anordnen von Fokusbereichen beim Ändern der Quellkanäle
* &lbrack;Projekt&rbrack; Manchmal falsche Miniaturansicht beim Erstellen eines neuen Materials
* &lbrack;Schnellaktionen&rbrack; Einige Schnellaktionen haben eine falsche Eingabeanzahl.
* &lbrack;UI&rbrack; Aktionsgruppen-Schaltfläche hat unterschiedliche Breiten
* &lbrack;UI&rbrack; Schaltfläche &quot;Löschen&quot; in Textfeldern löst manchmal Fokusverlust aus
* &lbrack;UI&rbrack; Kombinationsfelder und Textfelder sind zu groß
* &lbrack;UI&rbrack; Symbole und Beschriftungen sind falsch ausgerichtet
* &lbrack;UI&rbrack; Namensfeldbeschriftung ist falsch platziert
* &lbrack;UI&rbrack; Schaltflächenbeschriftungen für Schnellaktionen sind falsch ausgerichtet
* &lbrack;UI&rbrack; Schieberegler zeigen zu lange nachgestellte 0s an

**Entfernt:**

* &lbrack;Generative KI&rbrack; Generative AI-Funktionen werden entfernt. *Diese Funktion wurde aus der Anwendung entfernt und der Dienst funktioniert in früheren Versionen von Sampler am 5. März nicht mehr.*

### **5.1.1 ÎLE FLOTTANTE**

*(Freigegeben: 18. September 2025)*

**Hinzugefügt:**

* &lbrack;2D Ansicht&rbrack; Vergrößern der 2D-Ansicht für hochauflösende Texturen
* &lbrack;Captis&rbrack; Benutzer über Probleme beim Kopieren von Dateien warnen
* &lbrack;Layers&rbrack; Verwenden Sie beim Duplizieren einer Ebene eine inkrementelle Nummer im Namen der neuen Ebene

**Fest:**

* &lbrack;2D Ansicht&rbrack; Beim Malen von Strichen nach dem Zurücksetzen aller Eigenschaften des Kopierstempels werden zuvor erstellte Striche wieder angezeigt
* &lbrack;Anwendung&rbrack; Aktuelles Projekt speichern? popup verwendet falschen Projektnamen
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Potenzieller Absturz
* &lbrack;Anwendung&rbrack; Manchmal wird eine Miniaturansicht mit einem falschen Material generiert
* &lbrack;Captis&rbrack; Auf einigen Geräten wird beim Scannen in hoher Auflösung das Height schwarz angezeigt
* &lbrack;Captis&rbrack; Die Schaltfläche &quot;Aufnahme starten&quot; ist nicht mehr deaktiviert, wenn kein Aufnahmename festgelegt ist und wenn eine Kalibrierung ausgeführt wird
* &lbrack;Export&rbrack; Beim Exportieren einer .sbsar-Datei kann der Export fehlschlagen, ohne dass der Benutzer benachrichtigt wird
* &lbrack;Filter&rbrack; Bildschirm &quot;Erweiterte Parameter&quot; für den Filter &quot;Automatische Kachelung&quot; flackert manchmal, wenn Parameter angepasst werden
* &lbrack;Filter&rbrack; Standardparameter für den Musterfilter erzeugen graue Artefakte in der Ausgabe
* &lbrack;Filter&rbrack; Bei Eingaben mit hoher Auflösung zeigen die erweiterten Einstellungen des Filters &quot;Automatische Kachelung&quot; manchmal nicht die einzelnen Musterpunkte an
* &lbrack;Filter&rbrack; Die Mustergröße für den Parameter &quot;Automatische Kachelung&quot; der benutzerdefinierten Größe hat einen falschen Standardwert.
* &lbrack;Layers&rbrack; Gelegentliche Farbprobleme mit dem automatischen Kachelfilter, die meistens auf roten Materialien sichtbar sind
* &lbrack;Layers&rbrack; Manchmal werden durch das Hinzufügen von Ebenen einige Änderungen auf ihren Standardwert zurückgesetzt
* &lbrack;Physische Größe&rbrack; Miniaturansicht von Elementen mit einer Physische Größe haben eine falsche Height-Skala
* &lbrack;UI&rbrack; Belichtete Parameter können nicht umbenannt werden
* &lbrack;UI&rbrack; Kanalaktivierungstaste ist nicht quadratisch
* &lbrack;UI&rbrack; Wenn eine Reglerbeschriftung zu lang ist, ist die Schaltfläche &quot;Zurücksetzen&quot; nicht verfügbar.
* &lbrack;UI&rbrack; Durch Drücken der Eingabetaste oder Klicken auf den Out-Point wird der Fokus nicht aus den Textfeldern entfernt.
* &lbrack;UI&rbrack; Manchmal wird eine unerwünschte QuickInfo im Bedienfeld &quot;Physische Größe&quot; angezeigt
* &lbrack;UI&rbrack; In der 3D-Ansicht wird beim Erstellen eines leeren Projekts ein falsches Gitter angezeigt
* &lbrack;UI&rbrack; Wenn eine Farbwählereingabe angezeigt wird, verschwindet ihre Beschriftung beim Bewegen der Maus
* &lbrack;UI&rbrack; Beim Belichten von Parametern wird der Farbpunkt manchmal falsch positioniert

### **5.1.0 ÎLE FLOTTANTE**

*(Freigegeben: 7. August 2025)*

**Hinzugefügt:**

* &lbrack;2D Ansicht&rbrack; Die Pinselgröße passt sich jetzt der aktuellen Texturauflösung an
* &lbrack;3D-Ansicht&rbrack; Native Anzeigeskalierung für 3D-Rendering in den Voreinstellungen aktivieren/deaktivieren
* &lbrack;Anwendung&rbrack; Aktualisierung der Rendering-Engine
* &lbrack;Captis&rbrack; Hinzufügen der Option &quot;Quadrat erstellen&quot; während der Vorschau
* &lbrack;Captis&rbrack; Automatische Erkennung von Physische Größen
* &lbrack;Captis&rbrack; Durch das Erfassen eines neuen Materials wird ein neues Asset erstellt.
* &lbrack;Captis&rbrack; Ändern Sie die Auflösungsauswahl im Dropdown in Pixel pro Zoll oder Zentimeter anstelle der Pixelauflösung des maximalen Bereichs
* &lbrack;Captis&rbrack; Kontextbezogene Hilfe für die Ausrichtungskalibrierung
* &lbrack;Captis&rbrack; Raueitskarte generieren
* &lbrack;Captis&rbrack; Benutzer warnen, wenn die Standardkalibrierungsdateien fehlen
* &lbrack;Filter&rbrack; Auto-Kachelfilter für strukturierte Materialien und Scans
* &lbrack;Filter&rbrack; Neuer Falten-Entferner-Filter
* &lbrack;Filter&rbrack; Neue Funktionen im Filter &quot;Kopierstempel&quot;
* &lbrack;Filter&rbrack; Neue Funktionen im Filter &quot;Tonwertangleichung&quot;
* &lbrack;Layers&rbrack; Möglichkeit zum Reduzieren von Ebenen
* &lbrack;Layers&rbrack; Kontextmenü beim Klicken mit der rechten Maustaste auf eine Ebene zum Umbenennen, Duplizieren, Löschen oder Reduzieren der Ebene
* &lbrack;Onboarding&rbrack; Aktualisieren des Begrüßungsbildschirms und des Inhalts der neuen Bildschirme
* &lbrack;Performance&rbrack; Bessere Leistung bei Verwendung des Zuschneidefilters
* &lbrack;Performance&rbrack; Verbessern der Speichernutzung für die 3D-Ansicht
* &lbrack;Performance&rbrack; Die 3D-Ansicht wird schneller aktualisiert
* &lbrack;Physische Größe&rbrack; Aktivieren Sie &quot;Anzeige mit physischem Verhältnis&quot;, wenn Sie an Substance-Filtern arbeiten, wenn Physische Größe aktiviert ist.
* &lbrack;Physische Größe&rbrack; Wenn Sie Bilder in einen leeren Stapel importieren, schlagen Sie eine Auflösung vor, die dem Bildverhältnis besser entspricht.
* &lbrack;Schnellaktionen&rbrack; 3 neue Schnellaktionen für die Scanverarbeitung
* &lbrack;Skripterstellung&rbrack; API zum Reduzieren von Ebenen
* &lbrack;Skripterstellung&rbrack; Abrufen des Dateinamens für jedes Bild einer Bildimportebene
* &lbrack;Skripterstellung&rbrack; Neue Funktion zum Aktivieren/Deaktivieren eines bestimmten Kanals eines Elements
* &lbrack;UI&rbrack; Symbole und Schaltflächen im Ebenenbedienfeld überarbeiten, um Platz für die neuen Funktionen zu schaffen
* &lbrack;UI&rbrack; Warnung vor dem Verfall der Erstellung von Umgebungslicht

**Fest:**

* &lbrack;2D Ansicht&rbrack; Die Auswahl von &quot;Anzeige mit physischem Verhältnis&quot; funktioniert möglicherweise nicht, wenn Substance-Filter verwendet werden
* &lbrack;3D-Erfassung&rbrack; SVG-Dateien werden in der Dateiauswahl aufgeführt, aber nicht unterstützt.
* &lbrack;3D-Ansicht&rbrack; Der Parameter für die Emissionsintensität in den Shader-Einstellungen funktioniert nicht
* &lbrack;3D-Ansicht&rbrack; Manchmal ist die Gitterposition beim Erstellen eines neuen Elements falsch
* &lbrack;3D-Ansicht&rbrack; Das Wechseln zum Rendering der Pfadverfolgung stürzt auf nicht unterstützter Hardware ab
* &lbrack;Anwendung&rbrack; Anwendung bleibt hängen, wenn das Popup für manuelle Messungen geschlossen wird, ohne eine Größe festzulegen
* &lbrack;Anwendung&rbrack; Absturz
* &lbrack;Anwendung&rbrack; Einfrieren unter Windows bei Anzeige des Desktops (Windows-Taste + D-Tastaturbefehl)
* &lbrack;Anwendung&rbrack; Mögliche Abstürze beim Wechseln der Sprache
* &lbrack;Captis&rbrack; Absturz, wenn die Vorschaudaten nicht gültig sind
* &lbrack;Captis&rbrack; Nach dem Einzoomen ist das Auszoomen nicht möglich
* &lbrack;Captis&rbrack; Fehlende Lokalisierung in einigen Schritten des Assistenten
* &lbrack;Captis&rbrack; Möglicher Absturz beim Beenden bei Verwendung von Captis
* &lbrack;Captis&rbrack; Das Scannen funktioniert nicht, wenn auf dem Gerät Kalibrierungsdateien fehlen
* &lbrack;Filter&rbrack; Die Pinselvorschau bei Verwendung des Kopierstempelfilters kann je nach Struktur und Pinselgröße falsch sein
* &lbrack;Filter&rbrack; Fehlerhafte Ausgabegröße nach Verwendung des Filters &quot;Hochskalieren&quot;
* &lbrack;Filter&rbrack; Fehlende Symbole für Umgebungsdrehung und Stilisierungsfilter
* &lbrack;Filter&rbrack; Die Aktualisierung einiger Filter kann zu falschem Rendering führen
* &lbrack;Layers&rbrack; Falsches erstes Rendering beim Mischen von zwei Materialien
* &lbrack;Layers&rbrack; Die Schaltfläche zum Aktualisieren von Ebenen zeigt &quot;Alle aktualisieren&quot; an, auch wenn nur ein Update vorhanden ist
* &lbrack;Layers&rbrack; Unnötige Berechnungen beim Importieren von Bildern im Ebenenstapel
* &lbrack;Performance&rbrack; Verbessern der Normalen-Map-Format-Handhabung zur Reduzierung der Rendering-Zeiten
* &lbrack;Physische Größe&rbrack; Das Popup für manuelle Messungen funktioniert nur nach einer automatischen Messung
* &lbrack;Physische Größe&rbrack; Falsche Exportauflösung im Popup &quot;Exportieren&quot;, wenn Physische Größe aktiviert ist
* &lbrack;Schnellaktionen&rbrack; Fehlende Lokalisierung generierter Elementnamen
* &lbrack;UI&rbrack; Asset-Vorschau beim Hovern wird möglicherweise nicht angezeigt
* &lbrack;UI&rbrack; Durch Klicken auf die Schaltfläche Auf Standardwert zurücksetzen können einige der Steuerelemente beschädigt werden
* &lbrack;UI&rbrack; Fehlermeldungen werden beim Wechseln von Projekten nicht gelöscht
* &lbrack;UI&rbrack; Stellen Sie sicher, dass der Materialname im Bedienfeld &quot;Viewport &amp; Eigenschaften&quot; leer ist, wenn kein Element vorhanden ist.
* &lbrack;UI&rbrack; Die Schaltfläche &quot;Auf Standardwert zurücksetzen&quot; für den Parameter &quot;Point of View&quot; funktioniert nicht
* &lbrack;UI&rbrack; Schaltflächenüberlappung auf Standardwert zurücksetzen
* &lbrack;UI&rbrack; Einige Schaltflächen sind nicht anklickbar, wenn ein Bedienfeld abgedockt ist
* &lbrack;UI&rbrack; Texturbearbeitung - V-Parameter teilweise ausgeblendet in den Anzeigeeinstellungen und der 3D-Ansicht

**Entfernt:**

* &lbrack;3D-Erfassung&rbrack; Unterstützung zum Entfernen von 3D-Erfassungen
* &lbrack;Anwendung&rbrack; Unterstützung für macOS x86 entfernen

### **5.0.3 HAZELNUT**

*(Freigegeben: 3. Juni 2025)*

**Hinzugefügt:**

* &lbrack;Captis&rbrack; Einem Material denselben Namen wie einem bereits vorhandenen Material zuweisen
* &lbrack;Captis&rbrack; Fehlermeldungen in Popups statt in Toasts verschieben
* &lbrack;Filter&rbrack; Stickerei aktualisieren
* &lbrack;Voreinstellungen&rbrack; Hinzufügen von &quot;Zurücksetzen&quot; in den Anzeigeeinstellungen und in den Shader-Einstellungen
* &lbrack;UI&rbrack; Zeigen Sie in Projektelementen nicht die Menüoption &quot;Speicherort anzeigen&quot; an.

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Der Netznachbearbeitungsfilter gibt keine erwarteten Zuordnungen aus
* &lbrack;3D-Ansicht&rbrack; 3D-Ansicht funktioniert aufgrund einer Beschädigung des Shader-Caches nicht
* &lbrack;3D-Ansicht&rbrack; Grundebene und Raster sind vertikal, wenn die Szene Z-förmig ist
* &lbrack;3D-Ansicht&rbrack; Das Gitter verschwindet manchmal
* &lbrack;Anwendung&rbrack; Wenn Sie das Anmeldefenster beim Start schließen, ohne sich anzumelden, stürzt die App manchmal ab
* &lbrack;Anwendung&rbrack; Absturz, wenn der Zugriff auf die Plug-in-Konfigurationsdatei verweigert wird
* &lbrack;Anwendung&rbrack; Die Auswahl des aktuellen Materials wird aufgehoben, wenn das Projekt gespeichert wird
* &lbrack;Anwendung&rbrack; Durch Zurücksetzen auf das Standardlayout wird die Auflösung auf 64x64 eingestellt.
* &lbrack;Anwendung&rbrack; Sampler stürzt manchmal beim Rendern eines Ebenenstapels ab
* &lbrack;Export&rbrack; Die Exportauflösung wird manchmal auf 64x64 zurückgesetzt
* &lbrack;Export&rbrack; Manchmal ist es nicht möglich, .sbs/.sbsar-Dateien zu exportieren
* &lbrack;Layers&rbrack; Die Schaltfläche &quot;Basismaterial hinzufügen&quot; hat keine Wirkung, wenn das Material leer ist
* &lbrack;Layers&rbrack; Beim Duplizieren eines Materials wird die Kachelung geändert.
* &lbrack;Physische Größe&rbrack; Das automatische Messen funktioniert nicht, wenn das Bedienfeld &quot;Physische Größe&quot; vor dem Importieren des Bildes angedockt wurde
* &lbrack;Skripterstellung&rbrack; Modul zum automatischen Speichern ist defekt
* &lbrack;UI&rbrack; Falscher Abstand im Dialogfeld &quot;Exportieren&quot;
* &lbrack;UI&rbrack; Schieberegler-Animationen von Änderungen funktionieren nicht mehr
* &lbrack;UI&rbrack; Schieberegler rasten bei Bedarf nicht an Ganzzahlwerten ein
* &lbrack;UI&rbrack; Einige Dropdown-Menüs sind beschnitten

### **5.0.2 HAZELNUT**

*(Freigegeben: 22. April 2025)*

**Fest:**

* &lbrack;Anwendung&rbrack; Schaltfläche &quot;Zurück&quot; auf der Startseite ist defekt
* &lbrack;Anwendung&rbrack; Sampler wird manchmal nicht gestartet, wenn beschädigte Daten aus früheren Versionen auf der Festplatte vorhanden sind
* &lbrack;Anwendung&rbrack; Das importierte Bild wird nicht im Darstellungsfenster oder im Ebenenstapel angezeigt
* &lbrack;Captis&rbrack; Das Feld &quot;Captivate IP-Adresse&quot; bleibt auch nach dem Neustart von Sampler leer.
* &lbrack;Captis&rbrack; Die Live-Kameravorschau funktioniert nur, wenn die Anwendungssprache auf Englisch festgelegt ist
* &lbrack;Export&rbrack; Absturz beim Export &blbrack;Layers&rbrack; Das Malen funktioniert manchmal nicht in zuvor gespeicherten Projekten
* &lbrack;Layers&rbrack; Sampler aktualisiert manchmal alle Texturen, wenn nur ein Kanal aktualisiert wird
* &lbrack;Layers&rbrack; Nach dem Upgrade auf 5.0.x können keine Materialüberblendungen im Ebenenstapel verwendet werden
* &lbrack;Layers&rbrack; Durch die Aktualisierung eines Projekts mit einer vorherigen Version von &quot;Bild zu Material&quot; (AI) wird das Material vollständig schwarz.
* &lbrack;Layers&rbrack; Wenn Sie versuchen, ein nicht unterstütztes Bild zu importieren, erstellt Sampler eine fehlerhafte Ebene
* &lbrack;Skripterstellung&rbrack; Ein Teil der Python-API funktioniert nicht mit einem leeren Projekt
* &lbrack;UI&rbrack; Menüelemente überlaufen manchmal das Menü &quot;Datei&quot;.

### **5.0.1 HAZELNUT**

*(Freigegeben: 20. März 2025)*

**Hinzugefügt**

* &lbrack;Anwendung&rbrack; Aktualisierte Grafiktreiber-Kompatibilitätsliste
* &lbrack;Captis&rbrack; Popup anzeigen, wenn die Verwendung von HP Z Captis durch Betriebssystemrichtlinien blockiert wird
* &lbrack;Schnellaktionen&rbrack; Erklären, warum eine Schnellaktion in einer QuickInfo deaktiviert ist
* &lbrack;UI&rbrack; UI-Styling für Absturzberichtsfenster
* &lbrack;UI&rbrack; Wenn du in die Zwischenablage kopierst, gib einen Hinweis an, dass der Vorgang abgeschlossen wurde

**Fest:**

* &lbrack;2D Ansicht&rbrack; Der Belichtungsregler hat keine Wirkung, wenn die sphärische Projektion deaktiviert ist
* &lbrack;2D Ansicht&rbrack; Durch Malen außerhalb der Textur wird ein eingestellter Strich erstellt
* &lbrack;2D Ansicht&rbrack; Die Belichtungstaste hat keine QuickInfo.
* &lbrack;2D Ansicht&rbrack; Das Zoomen auf der Seite eines nicht quadratischen Bildes folgt nicht der Maus
* &lbrack;3D-Erfassung&rbrack; 3D-Erfassung funktioniert nicht unter Windows 11 24H2
* &lbrack;3D-Erfassung&rbrack; Absturz, wenn Sampler während des Netzrekonstruktionsschritts beendet wird
* &lbrack;3D-Ansicht&rbrack; Die Rechenzeit wird manchmal als 0ms angezeigt
* &lbrack;3D-Ansicht&rbrack; Wenn Sie die Projektion von orthografisch in perspektivisch ändern, wird das Viewport grau.
* &lbrack;Anwendung&rbrack; Absturz beim Start beim Überprüfen der GPU-Funktionen
* &lbrack;Anwendung&rbrack; Absturz während der Installation
* &lbrack;Anwendung&rbrack; Absturz beim Beenden nach dem Rechtsklick auf ein Metadatenfeld
* &lbrack;Anwendung&rbrack; Umgebungslicht fehlt beim Öffnen eines SBSAR im Dateiexplorer des Betriebssystems
* &lbrack;Anwendung&rbrack; Wenn Sie eine .sbsar-Datei öffnen, während Sampler ausgeführt wird, ändert sich die Einstellung für die Strukturaufteilung.
* &lbrack;Captis&rbrack; Einige Metadaten werden möglicherweise nicht zwischen den Erfassungsschritten übertragen
* &lbrack;Captis&rbrack; Der Name des erstellten Assets ist nicht der, der im Metadatenfeld eingegeben wurde
* &lbrack;Inhalt&rbrack; Beispielprojekt fordert zur Aktualisierung eines Filters auf, ist aber bereits auf dem neuesten Stand
* &lbrack;Filter&rbrack; Der Korrekturfilter für Normal/Height hat kein Symbol
* &lbrack;Layers&rbrack; Bilder in einer Bildimportebene können nicht geändert werden
* &lbrack;Layers&rbrack; Absturz bei Verwendung des Filters &quot;Hochskalieren&quot;
* &lbrack;Layers&rbrack; Durch Aktualisieren eines Projekts mit einem alten Bild auf Material wird das Material schwarz.
* &lbrack;Rendering&rbrack; Wenn Sie einen Ebenenstapel direkt nach dem Erstellen eines Elements anpassen, wird das Rendering unterbrochen
* &lbrack;Skripterstellung&rbrack; Das Plug-In zum automatischen Speichern stürzt ab, wenn kein Asset im Projekt vorhanden ist
* &lbrack;Extras&rbrack; In der Pinselsymbolleiste fehlt ein Wert für die Pinselgröße
* &lbrack;UI&rbrack; Wenn Sie die Anwendungssprache ändern, werden einige der Beschriftungen auf dem Startbildschirm nicht aktualisiert
* &lbrack;UI&rbrack; Durch Drücken der Esc-Taste oder der Eingabetaste in den Schieberegler-Textfeldern wird der Fokus nicht verloren
* &lbrack;UI&rbrack; Im Bedienfeld &quot;Eigenschaften&quot; überlappen sich die Schaltfläche &quot;Alle zurücksetzen&quot; und die Bezeichnung des Elementnamens.
* &lbrack;UI&rbrack; Probleme beim Andocken und Abdocken von Bedienfeldern
* &lbrack;UI&rbrack; Wenn Sie in einem Überlagerungsfenster scrollen, wird auch das darunter liegende Fenster durchlaufen
* &lbrack;UI&rbrack; Das Wechseln zur Listenansicht im Abschnitt &quot;Zuletzt verwendete Projekte&quot; auf dem Startbildschirm funktioniert nicht
* &lbrack;UI&rbrack; Symbol für Viewport-Anzeigemodus zeigt immer 2D/3D an

### **5.0.0 HAZELNUT**

*(Freigegeben: 20. Februar 2025)*

**Hinzugefügt**

* &lbrack;Onboarding&rbrack; Neue Startseite mit schnellem Zugriff auf Lerninhalte, Beispielprojekt, Schnellaktionen und aktuelle Projekte.
* &lbrack;Onboarding&rbrack; Schnell loslegen mit den neuen Schnellaktionen, die über die Startseite und das spezielle Bedienfeld zugänglich sind
* &lbrack;Onboarding&rbrack; &lbrack;Inhalt&rbrack; Schnellaktionen sind vordefinierte Arbeitsabläufe, die den Ebenenstapel mit den am häufigsten verwendeten Ebenen füllen.
* &lbrack;Onboarding&rbrack; Möglichkeit, ein neues Projekt über ein neues Schnellstartmenü, über Schnellaktionen oder über ein benutzerdefiniertes Projekt zu erstellen
* &lbrack;Onboarding&rbrack; Möglichkeit, leeres Projekt direkt von der Startseite über eine spezielle Schaltfläche zu erstellen
* &lbrack;3D-Ansicht&rbrack; Neuer erweiterter Raster- und Pathtracer, der neue Rendering-Funktionen (Eigenschaften wie Beschichtung, Glanz, Transparenz, Volumenstreuung) und visuelle Konsistenz im Substance-Ökosystem bietet
* &lbrack;3D-Ansicht&rbrack; Viewer-Einstellungen sind jetzt direkt in der 3D-Ansicht verfügbar
* &lbrack;3D-Ansicht&rbrack; Möglichkeit zum Speichern eines Renderschnappschusses in der Zwischenablage oder in Dateien
* &lbrack;3D-Ansicht&rbrack; Anzeigen eines Rasters zur Visualisierung des Szenenursprungs
* &lbrack;3D-Ansicht&rbrack; Schatten und Spiegelungen mit der Grundebene erfassen.
* &lbrack;3D-Ansicht&rbrack; Steuern Sie, wie reflektierend und undurchsichtig Ihre Grundebene ist
* &lbrack;3D-Erfassung&rbrack; Positionieren von Maschen auf dem Boden
* &lbrack;Anwendung&rbrack; Überprüfen der Hardwarekompatibilität beim Starten der Anwendung
* &lbrack;Anwendung&rbrack; Das Fenster für Absturzberichte wird jetzt direkt nach einem Absturz geöffnet
* &lbrack;Inhalt&rbrack; Beispielprojekt öffnen, um den Einstieg zu erleichtern
* &lbrack;Export&rbrack; Exportieren von Adobe Standard Material Shader in USD-Dateien
* &lbrack;Generative KI&rbrack; Aktivieren Sie das Tag &quot;Nicht ableiten&quot;, wenn Sie ein Bild als Eingabe in den Arbeitsabläufen &quot;Bild zu Textur&quot; verwenden.
* &lbrack;Projekt&rbrack; Miniaturen werden in der Projektdatei gespeichert, um das Öffnen von Projekten zu beschleunigen
* &lbrack;Projekt&rbrack; Festlegen in den Voreinstellungen zum Speichern von Cache-Daten innerhalb der Projektdatei mit verschiedenen Modi (kein Cache, heller Cache, voller Cache)
* &lbrack;Skripterstellung&rbrack; &Klammer;Änderung&Klammer; Qt-Migration zu Qt6.15 - Auswirkungen auf die Kompatibilität vorhandener Plug-ins
* &lbrack;Skripterstellung&rbrack; Standard-Plug-ins und -Skriptordner befinden sich jetzt im Ordner &quot;Dokumente&quot;
* &lbrack;Skripterstellung&rbrack; Neue Benutzeroberfläche für Plug-ins, um die optische Konsistenz mit den Hauptbedienfeldern von Sampler zu gewährleisten
* &lbrack;Skripterstellung&rbrack; Beispiele für 2 Plug-ins, um die Funktionen von Sampler Plug-ins kennenzulernen
* &lbrack;Skripterstellung&rbrack; Neue open_3d_capture()-Funktion
* &lbrack;Skripterstellung&rbrack; Beim Einfügen einer Ebene können Sie steuern, ob diese über oder unter der Zielposition eingefügt wird

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Absturz, wenn die Objekterfassung auf macOS nicht gestartet werden kann
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Hängenbleiben beim Hinzufügen von Elementen zum Projektfenster
* &lbrack;Anwendung&rbrack; Das Umbenennen eines Projektelements funktioniert nur, wenn Sie die Eingabetaste drücken
* &lbrack;Anwendung&rbrack; Menüeinträge zum Rückgängigmachen und Wiederholen sind nicht deaktiviert, wenn sie
* &lbrack;Assets&rbrack; Elemente können nicht aus dem Abschnitt &quot;Alle Bibliotheken&quot; des Bedienfelds &quot;Elemente&quot; gelöscht werden
* &lbrack;Inhalt&rbrack; Atlasersteller - Vorhandene Deckkraftmap verwenden, sofern vorhanden
* &lbrack;Inhalt&rbrack; Farb-ID-Überblendung - Korrigieren Sie die Farbauswahl in der Grundfarbe
* &lbrack;Layers&rbrack; Vermeiden Sie nutzlose Berechnungen bei der Verwendung von Generatoren
* &lbrack;Layers&rbrack; Das Tweaking eines Generators kann dazu führen, dass zu viele Computer ausgelöst werden.
* &lbrack;Performance&rbrack; Verbessern der GPU-Speicherverwaltung
* &lbrack;Performance&rbrack; Der Render-Cache darf beim Neustart der Anwendung nicht verwendet werden
* &lbrack;Resources&rbrack; Schreibgeschützte Dateien werden im Bedienfeld &quot;Elemente&quot; nicht angezeigt
* &lbrack;Skripterstellung&rbrack; Wiederverwenden einer Ebene nach dem Hinzufügen einer anderen Ebene zulassen
* &lbrack;Skripterstellung&rbrack; Das mehrmalige Ändern der Ebenenstapelstruktur in einem Skript kann fehlschlagen

**Entfernt:**

* &lbrack;Anwendung&rbrack; Entfernen der Unterstützung für .dng- und .nef-Bilddateien

## Version 4

### **4.5.2 GRUYERE**

*(Freigegeben: 07. November 2024)*

**Fest:**

* &lbrack;Inhalt&rbrack; Filter zum Zuschneiden, Sticken und Mischen von Heights

### **4.5.1 GRUYERE**

*(Freigegeben: 30. Juli 2024)*

**Fest:**

* &lbrack;Layers&rbrack; Das Malen von Graustufenmasken funktioniert nicht, was sich auf Werkzeuge wie Kopierstempel, Formverkrümmung und inhaltsbasierte Füllung auswirkt

### **4.5.0 GRUYERE**

*(Freigegeben: 18. Juli 2024)*

**Hinzugefügt**

* &lbrack;Interoperabilität&rbrack; Materialien an UE5, Blender, Maya, 3DsMax Unity senden
* &lbrack;Inhalt&rbrack; Neue Texturgenerator-Kategorie - Verläufe
* &lbrack;Inhalt&rbrack; HDRI-Werkzeug - Neuer Umgebungsdrehungsfilter

**Fest:**

* &lbrack;Verfügbare Parameter&rbrack; Das Freigeben von .sbsar-Eingabewerten funktioniert nicht
* &lbrack;Layers&rbrack; Grundfarbe wird bei Graustufenbildern rot
* &lbrack;Rendering&rbrack; In Farbkanälen verwendete Graustufenbilder weisen einen falschen Farbraum auf
* &lbrack;Skripterstellung&rbrack; Bei Verwendung einer Exportvorgabe werden die erwarteten Kanäle möglicherweise nicht exportiert.
* &lbrack;Inhalt&rbrack; Dirt - Durch Anwenden eines Dirt-Filters über dem Bild auf Material wird eine schwarze Normalität erzeugt.
* &lbrack;Inhalt&rbrack; Relief - Die Skalierung eines Musters im Relief-Filter ist nicht linear zwischen 0 und 1
* &lbrack;Inhalt&rbrack; Kachel erstellen - Verbesserte Konsistenz von Normal- und Heights

### **4.4.1 FONDUE**

*(Freigegeben: 6. Juni 2024)*

**Fest:**

* &lbrack;Inhalt&rbrack; Dirt-Filter fehlt
* &lbrack;Generative KI&rbrack; Bei der Verwendung von Bild zu Textur kann ein Netzwerkfehler auftreten

### **4.4.0 FONDUE**

*(Freigegeben: 23. Mai 2024)*

**Hinzugefügt:**

* &lbrack;Anwendung&rbrack; 3D-Erfassungen-Cache ist jetzt in einem separaten Unterordner abgelegt
* &lbrack;Generative KI&rbrack; Bild zu Struktur (Beta)
* &lbrack;Generative KI&rbrack; Text zu Muster (Beta)
* &lbrack;Generative KI&rbrack; Text zu Textur (Beta)
* &lbrack;Skripterstellung&rbrack; Assets verfügen jetzt über eine Ressourceneigenschaft.
* &lbrack;Skripterstellung&rbrack; Ebenen verfügen jetzt über die Eigenschaft &quot;output_usages&quot;

**Fest:**

* &lbrack;Anwendung&rbrack; Absturz beim Öffnen einer beschädigten Projektdatei
* &lbrack;Anwendung&rbrack; Absturz, wenn das Projekt beschädigte Elemente enthält
* &lbrack;Anwendung&rbrack; Absturz beim Trennen eines Monitors unter Windows
* &lbrack;Anwendung&rbrack; Falsches Anwendungssymbol auf der Windows-Taskleiste
* &lbrack;Anwendung&rbrack; Beschädigung der Hauptkonfigurationsdatei kann zum Löschen von Dateien führen
* &lbrack;Anwendung&rbrack; Bedienfelder erscheinen vor Popups
* &lbrack;Inhalt&rbrack; Texturgeneratoren haben unscharfe Miniaturen
* &lbrack;Export&rbrack; Aus einem importierten Bild generierter Deckkraftkanal bricht beim Exportieren von .sbs/.sbsar ab
* &lbrack;Filter&rbrack; Upscale kann je nach Eingabeebenen abstürzen
* &lbrack;Generative KI&rbrack; Mögliche Abstürze beim Empfangen unerwarteter Ergebnisse vom Dienst
* &lbrack;Skripterstellung&rbrack; Absturz beim automatischen Laden eines Plug-ins aus der Umgebungsvariablen
* &lbrack;Skripterstellung&rbrack; Möglicher Absturz beim Zuweisen der Ausgabenutzung mit der API

### **4.3.3 EMPANADA**

*(Freigegeben: 26. März 2024)*

**Hinzugefügt:**

* &lbrack;3D-Erfassung&rbrack; Neue erweiterte Auto-UV-Parameter während des Nachbearbeitungsprozesses
* &lbrack;Filter&rbrack; Perforationsfilter: Möglichkeit zum Umkehren und Ändern der Größe des benutzerdefinierten Musters

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Die Grundfarbe kann in macOS falsch sein
* &lbrack;3D-Erfassung&rbrack; Absturz beim Verarbeiten einer neuen Version
* &lbrack;3D-Erfassung&rbrack; Der Nachbearbeitungsschritt kann auf macOS abstürzen
* &lbrack;3D-Erfassung&rbrack; Die Ebene &quot;Gittertransformation&quot; kann zu falschem Rendering führen
* &lbrack;Anwendung&rbrack; Absturz beim Starten von Sampler, während eine vorherige Instanz noch exportiert wird
* &lbrack;Anwendung&rbrack; Sampler reagiert keinen Moment, wenn es zum ersten Mal gestartet wird
* &lbrack;Export&rbrack; Anisotropie Winkelzuordnung wird nicht exportiert
* &lbrack;Filter&rbrack; Das Hinzufügen von Stoffgewebe zum Ebenenstapel kann zu einem Absturz führen
* &lbrack;Filter&rbrack; Das Hinzufügen von Relief zum Ebenenstapel kann zu einem Absturz führen
* &lbrack;Filter&rbrack; Inhaltsbasierte Füllung stürzt ab, wenn 32-Bit-Bilder verwendet werden
* &lbrack;Filter&rbrack; Relief: Die Deckkraft der folgenden Ebenen wird nicht vollständig überschrieben
* &lbrack;Filter&rbrack; Füllung: Der Mischmodus funktioniert nicht in Designer und Painter
* &lbrack;Filter&rbrack; Stickerei: automatische Farbauswahl funktioniert nicht
* &lbrack;Voreinstellungen&rbrack; Festlegen eines nicht unterstützten Pfads für den 3D-Erfassung-Cache verhindern
* &lbrack;Voreinstellungen&rbrack; Die Voreinstellung &quot;Normales Format&quot; funktioniert nicht
* &lbrack;Skripterstellung&rbrack; Bei den Kanalparametern von Asset.export_material wird Groß- und Kleinschreibung unterschieden

### **4.3.2 EMPANADA**

*(Freigegeben: 22. Februar 2024)*

**Fest:**

* &lbrack;Anwendung&rbrack; Das Speichern eines Projekts in einer Netzwerkfreigabe unter Windows beschädigt die Projektdatei.

### **4.3.1 EMPANADA**

*(Freigegeben: 15. Februar 2024)*

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Absturz, wenn Bilddateien beim Generieren von Masken im Stapel nicht mehr zugänglich sind
* &lbrack;Export&rbrack; Beim Exportieren eines Materials mit &quot;Zuschneiden&quot; oder relativ zur Eingaberichtlinienebene werden ungültige Ergebnisse angezeigt
* &lbrack;Layers&rbrack; Seltener Absturz beim Rendern eines Ebenenstapels
* &lbrack;Filter&rbrack; Stickerei - Problem bei der Verwendung von Materialeingaben auf MacOS beheben
* &lbrack;Filter&rbrack; Stilisierung - Unterstützung von Texturgeneratoren
* &lbrack;Filter&rbrack; Muster - Festlegen der Parameternamen
* &lbrack;Lokalisierung&rbrack; Speichern unter... im Fenster mit Hardware-Informationen im Hilfemenü wird nicht lokalisiert angezeigt

### **4.3.0 EMPANADA**

*(Freigegeben: 25. Januar 2024)*

**Hinzugefügt**

* &lbrack;Assets&rbrack; Neuer Elementtyp: Texturgeneratoren
* &lbrack;Assets&rbrack; Neue Materialien in den Starter-Elementen
* &lbrack;Assets&rbrack; Neue Bildauswahl für Bildparameter im Eigenschaftenbedienfeld
* &lbrack;Assets&rbrack; Ziehen Sie Texturgeneratoren per Drag-and-Drop aus dem Bedienfeld Elemente auf die Bildwähler im Bedienfeld Eigenschaften .
* &lbrack;Assets&rbrack; Ziehen Sie Texturgeneratoren per Drag &amp; Drop aus dem Dateiexplorer des Betriebssystems.
* &lbrack;Assets&rbrack; Filter können Anpassungsgeneratoren über ein Benutzer-Tag an der Bildeingabe vorschlagen
* &lbrack;Assets&rbrack; Texturgeneratoren können festlegen, welcher Filter sie über ein Benutzer-Tag vorschlagen soll
* &lbrack;Inhalt&rbrack; Neuer perspektivischer Freistellungsfilter
* &lbrack;Inhalt&rbrack; Neuer Stilisierungsfilter
* &lbrack;Inhalt&rbrack; Füllmethode beim Füllfilter
* &lbrack;Inhalt&rbrack; Aktualisierter Stickereifilter
* &lbrack;Inhalt&rbrack; Aktualisierter Farbumflussfilter
* &lbrack;Inhalt&rbrack; Alle Filter wurden aktualisiert, um Texturgeneratoren zu unterstützen
* &lbrack;Layers&rbrack; Möglichkeit, einen Texturgenerator-Ausgabekanal auszuwählen, wenn er dem Ebenenstapel hinzugefügt wird
* &lbrack;Layers&rbrack; Möglichkeit, Vorgaben auf Texturgeneratoren einfach aufzulisten und anzuwenden
* &lbrack;Layers&rbrack; Anzeigen einer Vorschau des Texturgenerators in den Bildwählern
* &lbrack;Layers&rbrack; Texturgenerator-Parameter können angezeigt und exportiert werden
* &lbrack;Layers&rbrack; Weisen Sie beim Importieren eines einzelnen Bildes mit der Texturimport-Erstellungsvorlage die Grundfarbverwendung zu.
* &lbrack;Layers&rbrack; Feedback beim Versuch, inkompatible Dateien per Drag &amp; Drop in die Bildauswahl im Eigenschaftenfenster zu ziehen
* &lbrack;Layers&rbrack; Generieren eines Deckkraftkanals aus dem Alphakanal eines importierten Bildes
* &lbrack;Layers&rbrack; &quot;Bild zu Material&quot; (AI) ist beim Ändern der Kategorie schneller zu berechnen
* &lbrack;Layers&rbrack; Wählen Sie die relevanteste Ebene nach Verwendung einer Erstellungsvorlage aus.
* &lbrack;Layers&rbrack; Die Positions-Widgets können jetzt mit einem Schieberegler in der Gruppe &quot;Erweiterte Parameter&quot; angepasst werden.
* &lbrack;Export&rbrack; Zeigt einen Prozentsatz in der Warteschlange anstelle von Raw-Zahlen an.
* &lbrack;Interoperabilität&rbrack; Beim Senden an Painter wird jetzt der Deckkraftkanal als Alphakanal erkannt
* &lbrack;Anwendung&rbrack; Neues Dialogfeld zum Anzeigen und Speichern von Hardwareinformationen
* &lbrack;Anwendung&rbrack; Neue Voreinstellung zum Ändern der Standardprojektskalierung für jedes Height
* &lbrack;Anwendung&rbrack; Verbesserung der Darstellung veralteter Assets
* &lbrack;Skripterstellung&rbrack; Neue Funktionen asset.documentResolution() und asset.setDocumentResolution()
* &lbrack;Skripterstellung&rbrack; Neue Funktion select_asset()
* &lbrack;Skripterstellung&rbrack; Python-API für Texturgeneratoren
* &lbrack;Skripterstellung&rbrack; get_project_assets() gibt jetzt 3D-Objekte zurück
* &lbrack;UI&rbrack; Die Größe der Miniaturansichten von Elementen kann im Bedienfeld &quot;Elemente&quot; geändert werden
* &lbrack;UI&rbrack; Aktualisierte Viewport-Anzeigesymbole

**Fest:**

* &lbrack;2D Ansicht&rbrack; Zoom mit Mausrad ist bei 244 % blockiert
* &lbrack;Anwendung&rbrack; Absturz beim Start beim Initialisieren der Grafik-API
* &lbrack;Anwendung&rbrack; Absturz, wenn der Projektname das Zeichen # enthält
* &lbrack;Anwendung&rbrack; Mögliche Abstürze beim Öffnen eines alten Projekts
* &lbrack;Anwendung&rbrack; Das erneute Öffnen des aktuellen Projekts kann zu einem Absturz führen
* &lbrack;Anwendung&rbrack; Einige Projektänderungen sind nicht registriert und gehen beim Schließen des Projekts ohne Warnung verloren, wenn sie nicht gespeichert wurden.
* &lbrack;Export&rbrack; .sbs/.sbsar-Exportprobleme bei der Verwendung mehrerer Dateien mit demselben Namen
* &lbrack;Export&rbrack; Falscher Farbraum für exportierte Graustufenbilder .sbs/.sbsar-Datei
* &lbrack;Filter&rbrack; Probleme mit dem Verhalten &quot;Deckkraftüberblendung&quot;
* &lbrack;Layers&rbrack; SVG-Dateien werden manchmal nicht mit der richtigen Auflösung gerendert
* &lbrack;Performance&rbrack; Einige Projektspeicherungen auf der Festplatte sind nicht erforderlich.
* &lbrack;Projekt&rbrack; Beim Importieren eines alten Projekts werden die zugehörigen Vorgaben nicht geladen.
* &lbrack;Skripterstellung&rbrack; Parameter der ersten eingefügten Ebene können nicht abgerufen werden
* &lbrack;UI&rbrack; Das Popup-Fenster für die Vorschau kann sich beim Zeigen auf ein Element an der falschen Stelle oder auf dem falschen Bildschirm befinden
* &lbrack;UI&rbrack; Nicht angedockte Bedienfelder sind sichtbar und können oben im Begrüßungsbildschirm angezeigt werden.

### **4.2.2 DORAYAKI**

*(Freigegeben: 5. Dezember 2023)*

**Hinzugefügt:**

* &lbrack;3D-Erfassung&rbrack; 3D-Erfassungen sind jetzt unter Windows 5 % bis 10 % schneller
* &lbrack;3D-Erfassung&rbrack; Verbessern der Netzbereinigung vor der Dezimierung
* &lbrack;Motor&rbrack; Substance Engine auf Version 9.0.3 aktualisieren
* &lbrack;Layers&rbrack; Inhaltsbasierte Füllung: Upstream-Update, verschiedene Fehlerbehebungen für Anwendungsfälle und Linux-Unterstützung

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Durch Klicken auf &quot;Zurück&quot; nach der Ausrichtung und dann auf &quot;Weiter&quot; wird die Punktwolke nicht aktualisiert
* &lbrack;3D-Erfassung&rbrack; Gitter mit Löchern nach dem Hinzufügen zum Projekt
* &lbrack;Anwendung&rbrack; Absturz beim Beenden des Vollbildmodus nach einer 3D-Erfassung
* &lbrack;Anwendung&rbrack; Absturz mit erstellten Bilddateien
* &lbrack;Anwendung&rbrack; Wenn beim Beenden von Sampler das Bedienfeld &quot;Elemente&quot; in &quot;Alle Bibliotheken&quot; leer ist, wird es beim Neustart neu gestartet
* &lbrack;Anwendung&rbrack; Speicherverlust beim Exportieren von Material
* &lbrack;Anwendung&rbrack; Das Öffnen eines mit einer früheren Sampler-Version gespeicherten Projekts kann zu einem Absturz führen
* &lbrack;Anwendung&rbrack; Potenzielle Abstürze bei fehlender Konvertierung von 3D-Netzen
* &lbrack;Anwendung&rbrack; Automatischer Absturz beim Öffnen einer .sbsar-Datei, während Sampler ausgeführt wird
* &lbrack;Export&rbrack; Absturz beim Exportieren einer .sbs/.sbsar-Datei mit einer benutzerdefinierten Verwendung
* &lbrack;Export&rbrack; Exportierte Normalmaps sind immer DirectX, unabhängig von der Benutzereinstellung
* &lbrack;Export&rbrack; Das Exportieren eines 3D-Objekts in eine FBX-Datei unter macOS funktioniert nicht
* &lbrack;Export&rbrack; Inkonsistenzen beim Exportieren eines Ebenenstapels mit einem Stickfilter als SBS-/.sbsar-Datei
* &lbrack;Export&rbrack; Manchmal funktioniert das Exportieren von .sbs/.sbsar-Dateien nicht
* &lbrack;Export&rbrack; Manchmal beim Exportieren einer .sbs/.sbsar-Datei haben Bilder nicht die richtige Bittiefe
* &lbrack;Layers&rbrack;  Wenn Sie eine Spritzer-Ebene ausblenden, wird stattdessen das erste untergeordnete Element gerendert
* &lbrack;Layers&rbrack; Absturz beim Laden der Maske in der Helligkeits-/Kontrastebene
* &lbrack;Layers&rbrack; Nach dem Löschen der Ebene werden irreführende Fehlermeldungen angezeigt
* &lbrack;Layers&rbrack; Möglicher Absturz beim Herunterstufen eines Assets
* &lbrack;Layers&rbrack; Einige Ausgänge sind nur dann mit Eingängen verbunden, wenn die Verwendung im Bedienfeld &quot;Kanaleinstellungen&quot; erzwungen wird
* &lbrack;Physische Größe&rbrack; Das Dropdown der Referenzebene kann versehentlich zurückgesetzt werden
* &lbrack;UI&rbrack; Symbol &quot;Vorlageninfo importieren&quot; muss aktualisiert werden
* &lbrack;UI&rbrack; Ein Tipp für einen Viewport-Tastaturbefehl wird immer angezeigt, wenn sich das Viewport-Layout ändert

### **4.2.1 DORAYAKI**

*(Freigegeben: 21. September 2023)*

**Hinzugefügt:**

* &lbrack;Inhalt&rbrack; Bild zu Material - Verbessern der Generierung von Mikrodetails in normalen Karten
* &lbrack;Inhalt&rbrack; Bild zu Material - Neuer Parameter für die Begeisterungsintensität
* &lbrack;Layers&rbrack; Bilder können in den Bildimportebenen hinzugefügt werden.
* &lbrack;Layers&rbrack; Bilder können in den Bildimportebenen entfernt werden.
* &lbrack;Layers&rbrack; Ungültige Ebenen können jetzt gelöscht werden.
* &lbrack;2D Ansicht&rbrack; Umschalt+C-Verknüpfung zum Zurückblättern der Kanäle
* &lbrack;3D-Erfassung&rbrack; Warntoast anzeigen, wenn Benutzer weniger als 20 Bilder importieren
* &lbrack;Anwendung&rbrack; Neue Voreinstellungen zum Festlegen des Standardwerts für die Kachelung der Materialtextur
* &lbrack;Onboarding&rbrack; Aktualisierte Tutorial-Benutzeroberfläche für Bild-zu-Material (AI) und Hochskalieren
* &lbrack;Skripterstellung&rbrack; 3D-Erfassung-API: DatasetInfo verfügt über mehr Daten, wenn Capture3dState auf align festgelegt ist.
* &lbrack;Skripterstellung&rbrack; Neues select_asset-Argument für create_asset(). Neue Funktionen: wait_for_computation() und clear_render_cache()

**Fest:**

* &lbrack;Layers&rbrack; Absturz, wenn der Zuschneidebereich sehr klein ist
* &lbrack;Layers&rbrack; Absturz beim Hinzufügen oder Anpassen des Zuschneidefilters
* &lbrack;Layers&rbrack; Die Quadratur des Zuschneidebereichs führt zu einer falschen Auflösung der Materialausgabe
* &lbrack;Layers&rbrack; Die Ausgaben verschwinden manchmal, wenn mehrere Ebenen deaktiviert sind
* &lbrack;Layers&rbrack; Der Render-Cache wird mit den Filtern &quot;Bild zu Material&quot; (AI) und &quot;Hochskalieren&quot; möglicherweise nicht ordnungsgemäß ungültig
* &lbrack;Layers&rbrack; Hochskalierungsfilter kann nicht hinzugefügt werden, wenn Sie im Warnpopup &quot;Diese Meldung nicht mehr anzeigen&quot; auswählen
* &lbrack;Layers&rbrack; Das Bild kann nach der Änderung nicht im Stickereifilter wiederhergestellt werden
* &lbrack;Export&rbrack; Die exportierte normale Kartenauflösung ändert sich, wenn das normale Format geändert wird
* &lbrack;Export&rbrack; Entfernen Sie das Dateinamensuffix &quot;\_environment&quot; beim Exportieren einer Umgebung
* &lbrack;Export&rbrack; Eine .sbsar-Datei kann nicht exportiert werden, wenn sich eine Verkrümmungstransformationsebene im Ebenenstapel befindet
* &lbrack;2D Ansicht&rbrack; &quot;An Bildschirm anpassen&quot; funktioniert nicht, wenn sich die Auflösung ändert
* &lbrack;Anwendung&rbrack; Nachdem das Anwendungsfenster während der Berechnung geschlossen wurde, kann der Anwendungsprozess noch ausgeführt werden
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Render-Cache beim Umschalten GPU-beschleunigter neuronaler Netzwerke ungültig
* &lbrack;Skripterstellung&rbrack; Das Benennen eines Plug-ins als vorhandener Bedienfeldname führt zu unerwarteten Verhalten
* &lbrack;UI&rbrack; Wenn Sie auf ein Element mit einer QuickInfo klicken, wird die QuickInfo bis zum Neustart ausgeblendet
* &lbrack;UI&rbrack; Der Skalierungswert des Heights kann sich beim Wechseln von Elementen ändern
* &lbrack;UI&rbrack; Falscher Rand in Kombinationsfeldern

### **4.2 DORAYAKI**

*(Freigegeben: 05. September 2023)*

**Hinzugefügt:**

* &lbrack;Inhalt&rbrack; Wesentlich verbesserte Bild-zu-Material (AI)- und Delighter-Filter
* &lbrack;Inhalt&rbrack; Neuer Hochskalierungsfilter
* &lbrack;Inhalt&rbrack; Der Freistellungsfilter hat jetzt eine dynamische Ausgabeauflösung.
* &lbrack;Materialerstellungsvorlage&rbrack; Einstellung &quot;Dokumentgröße hinzufügen&quot;.
* &lbrack;Materialerstellungsvorlage&rbrack; Neue Umschalttaste &quot;Zuschnitt hinzufügen&quot;.
* &lbrack;Materialerstellungsvorlage&rbrack; Neuer Schalter &quot;Material hochskalieren&quot;
* &lbrack;Materialerstellungsvorlage&rbrack; Anzeigen der importierten Bildgröße
* &lbrack;Materialerstellungsvorlage&rbrack; Feedback geben, wenn einige importierte Bilder nicht verwendet werden können
* &lbrack;Materialerstellungsvorlage&rbrack; Warnung bei inkonsistenten Bildgrößen
* &lbrack;Materialerstellungsvorlage&rbrack; Neue Warnungen und QuickInfos
* &lbrack;Layers&rbrack; Anzeigen der Auflösung der Ebenen im Ebenenstapel
* &lbrack;Layers&rbrack; Die Ebenenberechnungsauflösung kann jetzt entweder auf Dokumentgröße oder Eingabegröße eingestellt werden.
* &lbrack;Layers&rbrack; Ebenenauflösung im Ebenenstapel anzeigen
* &lbrack;Layers&rbrack; Ändern Sie ggf. eine Richtlinie zur Ebenenauflösung in Dokument- oder Ebeneneingabe .
* &lbrack;Layers&rbrack; Benutzer warnen, wenn manuell ein Hochskalieren-Filter hinzugefügt wird, und Dokumentation bereitstellen
* &lbrack;Layers&rbrack; Warnen Sie den Benutzer, wenn eine lineare Hochskalierung durchgeführt wird, und bieten Sie an, stattdessen den Filter Hochskalieren zu verwenden.
* &lbrack;Layers&rbrack; Die Berechnung einer Bild-zu-Material-Ebene (AI) kann jetzt schneller abgebrochen werden, um die Renderzeiten beim Anpassen des Ebenenstapels zu verbessern
* &lbrack;Layers&rbrack; Die Berechnung einer Hochskalierungsebene kann jetzt schneller abgebrochen werden, um die Renderzeiten beim Anpassen des Ebenenstapels zu verbessern
* &lbrack;Export&rbrack; Überschreiben der Auflösung exportierter Texturen zulassen
* &lbrack;Export&rbrack; Kanäle für die Exportliste sind jetzt sortiert
* &lbrack;Export&rbrack; Kanalauflösung in der Liste der zu exportierenden Kanäle anzeigen
* &lbrack;Anwendung&rbrack; Neue Voreinstellung zum Aktivieren oder Deaktivieren von GPU-beschleunigten neuronalen Netzwerken
* &lbrack;UI&rbrack; Dropdown-Listen mit verbesserter Auflösung
* &lbrack;UI&rbrack; Neue Symbole für die Filter &quot;Gittertransformation&quot;, &quot;Gitternachbearbeitung&quot; und &quot;Weben&quot;
* &lbrack;UI&rbrack; Bedienfeld &quot;Freigeben&quot; in &quot;Exportieren&quot; umbenennen
* &lbrack;Skripterstellung&rbrack; Unterstützung der Ausgabeauflösung für Ebenen zur Export-API hinzufügen
* &lbrack;Skripterstellung&rbrack; Der Bild-Import-API wurden die Optionen &quot;Zuschneiden&quot;, &quot;Hochskalieren&quot; und &quot;Dokumentgröße&quot; hinzugefügt
* &lbrack;Onboarding&rbrack; Neue Tutorials
* &lbrack;Onboarding&rbrack; Aktualisieren des Begrüßungsbildschirms und des Inhalts der neuen Bildschirme
* &lbrack;Motor&rbrack; Substance Engine auf Version 9.0.1 aktualisieren

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Verbessern der Benennung von Genauigkeits-Optionen in den Parametern der Ausrichtungseinstellungen
* &lbrack;Anwendung&rbrack; Das Importieren von Bildern mit nicht mehreren 16 Dimensionen kann zu einem Absturz führen
* &lbrack;Anwendung&rbrack; Absturz beim Duplizieren eines Assets im Projektfenster
* &lbrack;Anwendung&rbrack; Absturz beim Wechseln von Elementen im Projektfenster
* &lbrack;Inhalt&rbrack; Das Malen einer benutzerdefinierten Maske für den Snow-Filter funktioniert nicht richtig
* &lbrack;Verfügbare Parameter&rbrack; Änderungen der exponierten Parameter können beim Materialwechsel verloren gehen
* &lbrack;Interoperabilität&rbrack; Das Senden eines Materials über das Exportierenbedienfeld kann zu einem Absturz führen
* &lbrack;Layers&rbrack; Inhaltsbasierte Füllung wird nicht mehr berechnet, wenn von einer einzelnen Bildeingabe zu einer Materialeingabe gewechselt wird
* &lbrack;Layers&rbrack; Absturz nach dem Duplizieren eines Umgebungslichts, das ein Material enthält
* &lbrack;Layers&rbrack; Bildimportebene zeigt falschen Bildnamen im Eigenschaftenfenster an, wenn die Bilddatei umbenannt wurde
* &lbrack;Layers&rbrack; Manchmal wird ein Drehfeld auf einer inaktiven Ebene angezeigt
* &lbrack;Layers&rbrack; Manchmal funktioniert das Ändern der Ausgabenutzung eines Bildes in einer Bildimportebene nicht
* &lbrack;Layers&rbrack; Tippfehler im Fenster &quot;Erstellungsvorlage&quot;
* &lbrack;UI&rbrack; 3D-Ansichtsport-Onboarding-QuickInfo hat Fokusprobleme
* &lbrack;UI&rbrack; Der Bildname kann überlaufen, wenn der Dateiname zu lang ist
* &lbrack;UI&rbrack; Geringfügige Probleme mit dem Layout der Pinselsymbolleiste bei Verwendung des Radiergummis
* &lbrack;UI&rbrack; Zeichenfolgen werden in einigen Sprachen im Bedienfeld &quot;Anzeigeeinstellungen&quot; abgeschnitten
* &lbrack;UI&rbrack; Wenn die QuickInfo für das Ansichtsfenster angezeigt wird, wird durch Drücken der Leertaste ein neues Projekt erstellt.

### **4.1.2 CANNOLI**

*(Freigegeben: 20. Juni 2023)*

**Fest:**

* &lbrack;Layers&rbrack; Speicherlecks beim Anpassen von Substance-Materialien und Filtern, die zu Abstürzen führen

### **4.1.1 CANNOLI**

*(Freigegeben: 6. Juni 2023)*

**Hinzugefügt**

* &lbrack;Motor&rbrack; Substance Engine auf Version 9.0 aktualisieren
* &lbrack;Interoperabilität&rbrack; 3D-Objekte an Stager und Painter senden

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Anwendungen stürzt ab, wenn der 3D-Erfassung-Renderer fehlschlägt
* &lbrack;3D-Erfassung&rbrack; Absturz, wenn ein Bild nicht geladen werden kann
* &lbrack;3D-Erfassung&rbrack; Absturz beim Erreichen des Schritts &quot;Gitterrekonstruktion&quot;
* &lbrack;3D-Erfassung&rbrack; Absturz beim Ändern der Größe des Begrenzungsrahmens
* &lbrack;3D-Erfassung&rbrack; Beim Importieren von Masken, die der Konvention folgen, wird die Maske nicht ordnungsgemäß zugewiesen.
* &lbrack;3D-Erfassung&rbrack; Renderfehler beim Anpassen des Begrenzungsrahmens
* &lbrack;3D-Erfassung&rbrack; Der Wechsel zwischen Versions- und Umschalt-Rendering-Optionen während des 3D-Erfassung-Nachbearbeitungsprozesses ist langsam
* &lbrack;3D-Erfassung&rbrack; Das Wechseln zwischen Versionen während des 3D-Erfassung-Nachbearbeitungsschritts ist manchmal unterbrochen
* &lbrack;Anwendung&rbrack; Absturz beim Start
* &lbrack;Anwendung&rbrack; Absturz beim Duplizieren eines umbenannten Materials
* &lbrack;Anwendung&rbrack; Absturz beim Öffnen eines älteren .alch-Projekts ohne seinen Abhängigkeitsordner
* &lbrack;Anwendung&rbrack; Absturz beim Anschließen/Abziehen eines Bildschirms, Computer geht in den Ruhemodus oder wird remote aufgerufen
* &lbrack;Anwendung&rbrack; Abstürze und Speicherlecks im Zusammenhang mit der Verwaltung nicht dauerhafter Elemente
* &lbrack;Export&rbrack; Die Auswahl des Materialformats für 3D-Objektdateitypen, in die Texturen eingebettet oder referenziert werden, sollte deaktiviert sein.
* &lbrack;Export&rbrack; Absturz, wenn beim Exportieren von 3D-Objekten etwas schief geht
* &lbrack;Export&rbrack; Absturz beim Exportieren einer .sbs/.sbsar-Datei
* &lbrack;Export&rbrack; Absturz beim Importieren einer benutzerdefinierten Vorgabe, die dieselbe Bezeichnung, aber nicht denselben Dateinamen aufweist
* &lbrack;Export&rbrack; Das Exportieren einer Umgebungsbeleuchtung in eine .sbs/.sbsar-Datei funktioniert manchmal nicht
* &lbrack;Export&rbrack; Der Gltf/Glb-Export codiert Texturen in base64
* &lbrack;Export&rbrack; Das Namenstextfeld funktioniert beim erneuten Fokussieren nicht
* &lbrack;Export&rbrack; Kachelung beibehalten funktioniert beim Exportieren einer Bild-zu-Material-Ebene (AI-gestützt) in eine SBS-/.sbsar-Datei nicht
* &lbrack;Export&rbrack; Beim Exportieren von gltf und Ersetzen von Dateien ist die Liste der zu ersetzenden Dateien nicht korrekt
* &lbrack;Verfügbare Parameter&rbrack; Zufällige Seed-Dateien funktionieren nicht in exportierten .sbs/.sbsar-Dateien
* &lbrack;Layers&rbrack; Die inhaltsbasierte Füllung stürzt manchmal ab, wenn sie zum zweiten Mal hinzugefügt wird
* &lbrack;Layers&rbrack; Absturz beim Berechnen eines Ebenenstapels
* &lbrack;Layers&rbrack; Disk-Cache für Image-to-Material (AI) funktioniert nicht
* &lbrack;Layers&rbrack; Möglicher Absturz beim Anpassen einer Ebene
* &lbrack;Performance&rbrack; Speicherlecks
* &lbrack;Projekt&rbrack; Absturz beim Speichern eines Projekts
* &lbrack;Projekt&rbrack; Wenn Sie dasselbe Projekt zweimal hintereinander importieren, werden die Elemente dupliziert
* &lbrack;UI&rbrack; Abgerundete Schaltflächen mit nur einem Symbol werden nicht korrekt gerendert

### 4.1.0 Cannoli

*(Freigegeben: 28. März 2023)*

**Hinzugefügt:**

* &lbrack;Inhalt&rbrack; Neuer Stickereifilter
* &lbrack;Inhalt&rbrack; Neuer Farbverkrümmungsfilter
* &lbrack;UI&rbrack; Exportoption &quot;Datei&quot; hinzufügen
* &lbrack;3D-Erfassung&rbrack; Schaltfläche &quot;Zurück&quot; ist jetzt für den Ausrichtungsschritt verfügbar
* &lbrack;3D-Erfassung&rbrack; Bilder behandeln JPEG EXIF-Ausrichtung
* &lbrack;3D-Erfassung&rbrack; Scripting - Neue dataset_info.camera-Eigenschaft
* &lbrack;3D-Erfassung&rbrack; Unterstützung für Linux hinzufügen (siehe Dokumentation)
* &lbrack;3D-Erfassung&rbrack; Lesezugriff der importierten Bilder überprüfen
* &lbrack;Onboarding&rbrack; Lernen - 2 neue Tutorials (Sticken und Malen verformen)
* &lbrack;Onboarding&rbrack; Aktualisierter Inhalt zu neuen Funktionen

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Kameraposition beim Ändern der Version beibehalten
* &lbrack;3D-Erfassung&rbrack; Alle Gruppen eines Objekts in einem Objekt zusammenführen
* &lbrack;3D-Erfassung&rbrack; Generierte Gitter in Original umbenannt
* &lbrack;Anwendung&rbrack; Absturz beim Generieren der Miniaturansicht eines nicht vorhandenen Bildes
* &lbrack;Assets&rbrack; Das Papierkorbsymbol im Bedienfeld &quot;Elemente&quot; hat keine Wirkung
* &lbrack;Inhalt&rbrack; Das Aktualisieren von Filtern mit Materialsteckplätzen funktioniert nicht wie erwartet
* &lbrack;Export&rbrack; Mögliche Abstürze beim Exportieren eines Assets mit bestimmten Filtern
* &lbrack;Export&rbrack; SBS/SBSAR-Export - Bildimportebenen hatten Priorität vor Bildparametern
* &lbrack;Export&rbrack; Die UE4-Exportvorgabe funktioniert nicht mit PNG
* &lbrack;Layers&rbrack; Absturz beim gleichzeitigen Ablegen eines Materials und eines Filters aus dem Betriebssystem-Explorer
* &lbrack;Layers&rbrack; Absturz beim Ziehen einer SBSAR-Datei mit einer Bilddatei
* &lbrack;Layers&rbrack; Der Kanal für die Deckkraft der Stickerei kann vollständig weiß sein.
* &lbrack;Lokalisierung&rbrack; Die chinesische Sprache wird unter Linux möglicherweise standardmäßig angezeigt
* &lbrack;Performance&rbrack; Es wurde ein Speicherproblem beim Entfernen einer Ebene aus einem Asset behoben.
* &lbrack;Projekt&rbrack; Möglicher Absturz beim Speichern
* &lbrack;UI&rbrack; Fehlenden Abstand auf der Menüschaltfläche &quot;Version&quot; hinzufügen
* &lbrack;UI&rbrack; Schaltfläche &quot;Abbrechen&quot; wird nicht richtig angezeigt
* &lbrack;UI&rbrack; Deaktivieren der Schieberegleranimation für die 3D-Erfassung von Nachbearbeitungsparametern
* &lbrack;UI&rbrack; Das Fenster Materialerstellungsvorlage wird nicht geschlossen, wenn Sie außerhalb des Fensters klicken.
* &lbrack;UI&rbrack; Der Schnellzugriff auf den Filter schließt sich, wenn Sie außerhalb klicken

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.2 Bananen

*(Freigegeben: 09. März 2023)*

**Hinzugefügt:**

* &lbrack;3D-Erfassung&rbrack; Datenträgernutzung zeigt die verwendete Menge an
* &lbrack;3D-Erfassung&rbrack; Der Import von Fotos erfolgt asynchron und schneller
* &lbrack;Skripterstellung&rbrack; Neue Klassen und Funktionen zum Skripten der 3D-Erfassung-Funktion
* &lbrack;Skripterstellung&rbrack; Neue ExportController-Klasse zum Ausführen von Aktionen, wenn der Export abgeschlossen, fehlgeschlagen oder abgebrochen wird
* &lbrack;Skripterstellung&rbrack; Übergabe-Argumente Python-Skripte, die mit —run-script ausgeführt werden
* &lbrack;UI&rbrack; UI-Feedback beim Ziehen eines Elements über das Ebenenbedienfeld
* &lbrack;Inhalt&rbrack; Farbtemperaturfilter arbeitet jetzt an Materialien
* &lbrack;Inhalt&rbrack; &quot;Normal zu Height&quot;-Filter bieten eine neue Option zum Beibehalten der Unterteilung

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Korrigierte Bildgröße im Schritt zur Datensatzausrichtung
* &lbrack;3D-Erfassung&rbrack; Entfernen duplizierter Scheitelpunkte nach dem Ausgliedern von UVs
* &lbrack;3D-Erfassung&rbrack; MacOS - Bessere Erkennung, wenn 3D-Erfassungen verfügbar sind
* &lbrack;3D-Erfassung&rbrack; Absturz beim Schließen des Datenfensters beim Importieren von 3D-Erfassungen
* &lbrack;3D-Erfassung&rbrack; Absturz beim Generieren einer neuen Version
* &lbrack;3D-Erfassung&rbrack; Absturz beim Versuch, das 3D-Objekt im Viewer zu laden
* &lbrack;3D-Erfassung&rbrack; Absturz bei Verwendung eines Pfads mit Nicht-UTF8-Zeichen
* &lbrack;3D-Erfassung&rbrack; Tipps &amp; Klicks Tippfehler
* &lbrack;3D-Erfassung&rbrack; Gitter werden nicht mehr so skaliert, dass sie in den Einheitswürfel passen
* &lbrack;3D-Erfassung&rbrack; Absturz beim Schließen der 3D-Erfassung beim Rendern verhindern
* &lbrack;3D-Erfassung&rbrack; Durch Entfernen einer Maske verschwindet das Bild
* &lbrack;Anwendung&rbrack; Absturz beim gleichzeitigen Importieren von zwei Elementen
* &lbrack;Anwendung&rbrack; Sichern früherer Versionen von Elementen beim Öffnen eines Projekts, wenn diese nie gesichert wurden
* &lbrack;Anwendung&rbrack; Durch Baking erzeugte Map richtig zwischenspeichern, wenn nicht alle Maps bereits vorhanden sind
* &lbrack;Anwendung&rbrack; Vollbild stürzt ab, wenn ein 3D-Objekt angezeigt wird.
* &lbrack;Anwendung&rbrack; Letztes Material wird beim Speichern des Projekts dupliziert
* &lbrack;Anwendung&rbrack; Absturz verhindern, wenn der Mesh-Nachbearbeitungscomputer während des Backvorgangs abgebrochen wird
* &lbrack;Anwendung&rbrack; Beim erneuten Öffnen des aktuellen Projekts werden die Änderungen nicht verworfen
* &lbrack;Anwendung&rbrack; Generieren von Miniaturen für 3D-Objekte anhalten
* &lbrack;2D Ansicht&rbrack; Absturz bei Verwendung des Pinselwerkzeugs
* &lbrack;Inhalt&rbrack; Inhaltsbasierte Füllung - Berechnung bleibt möglicherweise hängen
* &lbrack;Inhalt&rbrack; Der Atlas-Erstellungsfilter verkleinert den Deckkraftkanal
* &lbrack;Export&rbrack; Korrektur der Exportwarteschlange für fehlgeschlagene Exporte
* &lbrack;Export&rbrack; OBJ-Export erstellt Objekt 100-mal kleiner als erwartet
* &lbrack;Layers&rbrack; Farbbilder, die als Graustufen-Kanäle importiert wurden, werden jetzt als Graustufen betrachtet
* &lbrack;Export&rbrack; FBX-Dateien können nicht in Anwendungen von Drittanbietern importiert werden
* &lbrack;Export&rbrack; Shader-Ausgabenamen in USD-Dateien sind nicht korrekt
* &lbrack;Layers&rbrack; Der Bildname wird nicht aktualisiert, wenn sein Name im Betriebssystem-Explorer geändert wird
* &lbrack;Skripterstellung&rbrack; Fehlermeldung beim erneuten Laden eines ungültigen Skripts anzeigen
* &lbrack;UI&rbrack; Basismaterial-Schaltfläche deaktiviert, wenn nicht verfügbar
* &lbrack;UI&rbrack; Absturz beim Zugriff auf das Dateidialogfeld im Fenster &quot;Materialerstellungsvorlage&quot;
* &lbrack;UI&rbrack; Der Schnellzugriff ist auch bei geschlossenem Ebenenbedienfeld möglich
* &lbrack;UI&rbrack; Symbole für &quot;Senden an&quot; sind falsch ausgerichtet
* &lbrack;UI&rbrack; Das Ebenensymbol ändert sich, wenn Sie auf das Symbol &quot;Angleichen&quot; klicken

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.1 Bananen

*(Freigegeben: 07. Februar 2023)*

**Fest:**

* &lbrack;3D-Erfassung&rbrack; Bei Masken kann die Texturprojektion unterbrochen werden
* &lbrack;3D-Erfassung&rbrack; Auf dem Objekt können Artefakte erscheinen.
* &lbrack;3D-Erfassung&rbrack; Das exportierte Gitter kann sehr klein sein

**Bekannte Probleme:**

* &lbrack;3D-Erfassung&rbrack; FBX- und OBJ-Exporte skalieren das Ergebnis herunter
* &lbrack;3D-Erfassung&rbrack; 3D-Erfassungen sind auf MacOS verfügbar, auch wenn Ihre Hardware nicht kompatibel ist. Lesen Sie die Dokumentation.
* &lbrack;3D-Erfassung&rbrack; Absturz, wenn die Gitterrekonstruktion abgeschlossen ist.
* &lbrack;Layers&rbrack; Die inhaltsbasierte Füllung kann hängen bleiben, wenn Sie die Ebenen unten anpassen
* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.0 Bananen

*(Freigegeben: 31. Januar 2023)*

**Hinzugefügt:**

* &lbrack;3D-Erfassung&rbrack; Erstellen von 3D-Objekten aus Bildern
* &lbrack;3D-Erfassung&rbrack; Assistent für dedizierte 3D-Erfassungen
* &lbrack;3D-Erfassung&rbrack; Importieren oder Generieren von Schwarzweißmasken in Ihrem Datensatz
* &lbrack;3D-Erfassung&rbrack; Ausrichtungsergebnis - Alle übereinstimmenden Funktionen als Punktwolke anzeigen
* &lbrack;3D-Erfassung&rbrack; Ausrichtungsergebnis - Kameras anzeigen und mit ihnen interagieren, die jedem ausgerichteten Foto zugeordnet sind
* &lbrack;3D-Erfassung&rbrack; Definieren des Wiederaufbaubereichs mithilfe eines Begrenzungsrahmen-Widgets
* &lbrack;3D-Erfassung&rbrack; Skalieren, Verschieben und Drehen auf allen Achsen des Begrenzungsrahmen-Widgets
* &lbrack;3D-Erfassung&rbrack; Festlegen der Geometriepräzision für das rekonstruierte Gitter
* &lbrack;3D-Erfassung&rbrack; Gitter und Strukturen mit einer neuen Version optimieren.
* &lbrack;3D-Erfassung&rbrack; Jede der Versionen wird automatisch auf den Zielflächennummernsatz dezimiert.
* &lbrack;3D-Erfassung&rbrack; Bei der Nachbearbeitung werden Texturen automatisch ausgepackt, neu projiziert und die Height- und AO-Informationen aus dem High-Poly-Gitter entfernt.
* &lbrack;3D-Erfassung&rbrack; Originalergebnis oder Originalversion zum Sampler-Projekt hinzufügen
* &lbrack;3D-Erfassung&rbrack; Neue Mesh-Nachbearbeitungsebene zum automatischen Dezimieren, Ausgliedern, Neuprojektieren von Texturen und Backen von Details der zugrunde liegenden Mesh-Ebene
* &lbrack;3D-Erfassung&rbrack; Neue Ebene &quot;Gittertransformation&quot; zum Skalieren, Drehen oder Verschieben der zugrunde liegenden Gitterebene
* &lbrack;Export&rbrack; Neues Exportfenster
* &lbrack;Export&rbrack; Spezielle Einstellungen und Benutzeroberfläche je nach Elementtyp (Material, Umgebungslicht, Gitter)
* &lbrack;Export&rbrack; Exportieren Sie das Gitter als USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &lbrack;Export&rbrack; Materialart beim Exportieren von Substance-Dateien definieren (SBSAR, SBS)
* &lbrack;UI&rbrack; Cache-Einstellungen auf eine neue Registerkarte im Popup &quot;Voreinstellungen&quot; verschieben
* &lbrack;Anwendung&rbrack; Die Größe von 2D- und 3D-Viewports kann jetzt geändert, ausgetauscht und vertikal gestapelt werden
* &lbrack;Anwendung&rbrack; Neue Umgebungsvariable SAMPLER_RESOURCES_PATH zum Hinzufügen zusätzlicher Starter-Assets
* &lbrack;Skripterstellung&rbrack; Die Umgebungsvariablen SAMPLER_PLUGIN_PATH und SAMPLER_SCRIPT_PATH wurden hinzugefügt, um Plug-ins und Skripte beim Start zu importieren.
* &lbrack;Skripterstellung&rbrack; Exportfunktionen für Materialien, Umgebungslichter und 3D-Objekte hinzugefügt
* &lbrack;Skripterstellung&rbrack; Bezeichner, Standardwert, Minimal- und Maximalwerte, Beschriftungen und Enumerationswerte zu Parametern hinzugefügt
* &lbrack;Skripterstellung&rbrack; Funktion import_textures hinzugefügt, um beim Importieren von Bildern eine benutzerdefinierte Verwendung einzugeben

**Fest:**

* &lbrack;Anwendung&rbrack; Absturz beim Öffnen eines zuletzt verwendeten Projekts und Speichern im Bestätigungsdialogfeld
* &lbrack;Anwendung&rbrack; Dateidialog verhindert das Öffnen von .ssa-Dateien
* &lbrack;Anwendung&rbrack; Dateidialoge können in einem Hintergrundfenster in macOS angezeigt werden
* &lbrack;Anwendung&rbrack; Potenzieller Absturz beim Öffnen von 3.2-Projekten
* &lbrack;Anwendung&rbrack; Beim Auswählen einer Datei wird das Dialogfeld &quot;Datei&quot; geschlossen, bevor Warnungen angezeigt werden.
* &lbrack;Verfügbare Parameter&rbrack; Das Exportieren von parametrischen Umgebungslichtern funktioniert nicht
* &lbrack;Layers&rbrack; Der Link &quot;Zum Durchsuchen hier klicken&quot; im Ebenenstapel funktioniert nicht mehr
* &lbrack;Layers&rbrack; Das Malen mehrerer Bilder innerhalb einer Ebene funktioniert manchmal nicht
* &lbrack;Layers&rbrack; Wenn Sie ein Bild in den Ebeneneigenschaften festlegen, wird die Miniaturansicht der Bildauswahl nicht aktualisiert
* &lbrack;Layers&rbrack; Das Tweenen eines Sampler-Elements, das als Ebene hinzugefügt wurde, funktioniert nicht
* &lbrack;Projekt&rbrack; Unerwünschte Aktualisierung von Elementen beim Öffnen eines Projekts
* &lbrack;Skripterstellung&rbrack; Das Durchsuchen des Plug-in-Ordners schlägt unter Windows manchmal fehl
* &lbrack;Skripterstellung&rbrack; Absturz bei Verwendung von &quot;open_project()&quot; in einem Python-Skript
* &lbrack;Skripterstellung&rbrack; JPEG-Export fehlt in der API
* &lbrack;Skripterstellung&rbrack; Der Protokollbereich ist nicht schreibgeschützt
* &lbrack;Skripterstellung&rbrack; Der Parameterwert image_picker funktioniert nicht
* &lbrack;UI&rbrack; Symbol &quot;Fehlendes Element&quot; für Umgebungslichter im Projektfenster
* &lbrack;UI&rbrack; Dropdown-Liste &quot;An Designer-Format senden&quot; im Popup &quot;Voreinstellungen&quot; kann leer sein
* &lbrack;UI&rbrack; Einige Schaltflächen haben einen falschen Stil
* &lbrack;UI&rbrack; Die Beschriftung überlappt die Schaltflächen in Schaltflächengruppen-Widgets.
* &lbrack;UI&rbrack; Die QuickInfo-Position für &quot;Tools&quot; im Menü &quot;Physische Größe festlegen&quot; ist falsch
* &lbrack;UI&rbrack; Beim Ändern der Sprache ist das Menü &quot;Datei&quot; falsch ausgerichtet

**Bekannte Probleme:**

* &lbrack;3D-Erfassung&rbrack; Bei Masken kann die Texturprojektion unterbrochen werden
* &lbrack;3D-Erfassung&rbrack; Kleine Artefakte können auf dem Objekt erscheinen, wenn die Skalierung in der Gittertransformation zu klein ist
* &lbrack;3D-Erfassung&rbrack; Das exportierte Gitter kann sehr klein sein. Skalierung der Gittertransformation zurücksetzen und erneut exportieren
* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

## Version 3

### 3.4.1 Arancini

*(Freigegeben: 6. Oktober 2022)*

**Hinzugefügt:**

* &lbrack;Onboarding&rbrack; Neue Begrüßungsbildschirme und neue Funktionen
* &lbrack;Onboarding&rbrack; Aktualisierte Startseite-Benutzeroberfläche
* &lbrack;Onboarding&rbrack; Neue Trainingsinhalte auf dem Startbildschirm
* &lbrack;Skripterstellung&rbrack; Protokollieren Sie einen Fehler im Protokollfenster, wenn eine Methode nicht erkannt wird.
* &lbrack;Skripterstellung&rbrack; Neues ssa.helpers-Modul zum Aktivieren des Drucks im Protokollbedienfeld
* &lbrack;Anwendung&rbrack; Unterstützung für das neue Widget für parallele Schaltflächen in Substance 3D Designer

**Fest:**

* &lbrack;Export&rbrack; Absturz beim Exportieren einer .sbsar-Datei, die auf ein fehlendes Bild verweist
* &lbrack;Export&rbrack; Absturz beim Exportieren eines Assets, das auf eine beschädigte Bilddatei verweist
* &lbrack;Export&rbrack; Das Exportieren einer .sbsar-Datei mit einer Stickerei-Ebene führt zu einem grauen Material
* &lbrack;Export&rbrack; Beim Exportieren eines Materials in eine SBS/SBSAR-Datei kann ein vollständig transparentes Material generiert werden
* &lbrack;Export&rbrack; Der Parameter &quot;Normales Format&quot; wird in .sbs/.sbsar-Dateien nicht korrekt angezeigt
* &lbrack;Export&rbrack; SBS/SBSAR-Export eines Ebenenstapels, der auf eine .svg-Datei verweist, ist fehlgeschlagen
* &lbrack;Export&rbrack; Transformieren-Ebene wird nicht ordnungsgemäß exportiert/Enscape aktualisiert - Exportvorgabe überprüfen
* &lbrack;Verfügbare Parameter&rbrack; Absturz beim Löschen einer Ebene, die einen exponierten Parameter enthält
* &lbrack;Verfügbare Parameter&rbrack; Das Aktualisieren einer veralteten Ebene im Ebenenstapel kann zu einer beschädigten Liste der angezeigten Parameter führen
* &lbrack;Verfügbare Parameter&rbrack; Parameter, die nicht exportiert werden sollen, werden sowieso exportiert
* &lbrack;Verfügbare Parameter&rbrack; Durch das Entfernen eines Angleichungsfilters beim Löschen einer Ebene werden seine Parameter nicht wieder aufgehoben
* &lbrack;Verfügbare Parameter&rbrack; Textparameter beschädigen .sbs/.sbsar-Exporte
* &lbrack;Layers&rbrack; Absturz beim Ablegen eines Ebenenstapels in einem anderen Ebenenstapel
* &lbrack;Layers&rbrack; Absturz beim Nichtladen eines Filters
* &lbrack;Layers&rbrack; Das vorherige Bild kann beim Zurücksetzen des Bildfelds nicht neu geladen werden
* &lbrack;Layers&rbrack; Änderungen am Transformationswerkzeug können nicht rückgängig gemacht/wiederholt werden
* &lbrack;Layers&rbrack; Kopierstempel-Ebene bleibt hängen, nachdem Sie auf &quot;Alle Einstellungen zurücksetzen&quot; geklickt haben
* &lbrack;Layers&rbrack; Durch die Verwendung einer der Zurücksetzen-Schaltflächen wird verhindert, dass im Bildfeld gezeichnet wird
* &lbrack;Layers&rbrack; Die Schaltfläche &quot;Zurücksetzen&quot; löscht die Zeichnungsmaske im Bildfeld nicht
* &lbrack;Layers&rbrack; Die Schaltfläche &quot;Zurücksetzen&quot; im Bildfeld bewirkt nichts, wenn der Benutzer etwas gemalt hat
* &lbrack;Layers&rbrack; Rendering-Cache funktioniert nicht, wenn das Pinsel-Werkzeug verwendet wird
* &lbrack;Layers&rbrack; Gelöschte Ebenen können weiterhin im Eigenschaftenfenster angezeigt werden
* &lbrack;Layers&rbrack; Die Ebenenberechnung kann beim Wechseln zwischen Projektelementen blockiert werden
* &lbrack;Projekt&rbrack; Manchmal kann Sampler ein Projekt nicht von der Festplatte öffnen
* &lbrack;2D Ansicht&rbrack; Die 2D-Ansicht wird standardmäßig immer auf Materialausgabe zurückgesetzt.

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.4.0 Arancini

*(Freigegeben: 06. September 2022)*

**Hinzugefügt:**

* &lbrack;Verfügbare Parameter&rbrack; Neue Bedienfeld „Veröffentlichte Parameter“
* &lbrack;Verfügbare Parameter&rbrack; Schaltfläche &quot;Neu&quot; für Parameter, die über den Mauszeiger bewegt werden, um Parameter aus dem Bedienfeld &quot;Eigenschaften&quot; anzuzeigen oder zu entfernen
* &lbrack;Verfügbare Parameter&rbrack; Neues Kontextmenü mit der rechten Maustaste zu Parametern, die im Eigenschaftenbedienfeld angezeigt oder nicht verfügbar gemacht werden sollen
* &lbrack;Verfügbare Parameter&rbrack; Verfügbare Parameter sind auf der Bedienfeld „Veröffentlichte Parameter“ aufgelistet.
* &lbrack;Verfügbare Parameter&rbrack; Farbpunkte und Farbscheiben werden an mehreren Stellen hinzugefügt, um exponierte Parameter leicht zu identifizieren
* &lbrack;Verfügbare Parameter&rbrack; Parameterbeschriftungen können in der Bedienfeld „Veröffentlichte Parameter“ bearbeitet werden
* &lbrack;Verfügbare Parameter&rbrack; Eine Warnung für nicht exportierbare Parameter anzeigen
* &lbrack;Verfügbare Parameter&rbrack; Warnmeldung anzeigen, wenn eine Ebene mit exponierten Überblendungsparametern an eine Stelle verschoben wird, an der sie ausgeblendet werden
* &lbrack;Verfügbare Parameter&rbrack; Verfügbare Parameter werden in den Formaten SBS und SBSAR exportiert
* &lbrack;Metadaten&rbrack; Unterstützung benutzerdefinierter Metadatenvorlagen
* &lbrack;Metadaten&rbrack; Neue Vorlage für physikalische CLO-Eigenschaften für Metadaten
* &lbrack;Metadaten&rbrack; Hinzufügen von Symbolen beim Hovern, um benutzerdefinierte Metadaten hinzuzufügen/zu entfernen
* &lbrack;Python API&rbrack; Neue Python-API
* &lbrack;Python API&rbrack; API für Asset-Authoring
* &lbrack;Python API&rbrack; API für die Ebenenverwaltung
* &lbrack;Python API&rbrack; API für die Parameterverwaltung
* &lbrack;Python API&rbrack; API für das Projektmanagement
* &lbrack;Python API&rbrack; Ein Plug-in kann aktiviert und deaktiviert werden
* &lbrack;Python API&rbrack; Python-API-Dokumentation im Menü &quot;Hilfe&quot;
* &lbrack;Skripterstellung&rbrack; Neue Plug-ins und Skripte im Popup &quot;Voreinstellungen&quot;
* &lbrack;Skripterstellung&rbrack; Plug-ins zum Anpassen der Oberfläche von Sampler mit eigenen Bedienfeldern erstellen und importieren
* &lbrack;Skripterstellung&rbrack; Plug-ins werden Teil der Sampler-Oberfläche und können wie herkömmliche Sampler-Bedienfelder angedockt und verschoben werden
* &lbrack;Skripterstellung&rbrack; Dedizierte Schaltflächenleiste für die Plug-ins in der rechten Sampler-Symbolleiste
* &lbrack;Skripterstellung&rbrack; Erstellen und Importieren von Skripten zum Ausführen einer Liste von Aufgaben
* &lbrack;Skripterstellung&rbrack; Python-Skripte über das Menü &quot;Skripte&quot; starten
* &lbrack;Skripterstellung&rbrack; Plug-ins und Skripte können über das Fenster Voreinstellungen gelöscht, neu angeordnet und neu geladen werden.
* &lbrack;Skripterstellung&rbrack; —run-script-Befehlszeilenparameter hinzugefügt
* &lbrack;Logs&rbrack; Neues Protokollbedienfeld
* &lbrack;Logs&rbrack; Fenster &quot;Protokolle&quot; im Fenster &quot;Voreinstellungen&quot; aktivieren
* &lbrack;Logs&rbrack; Neue Aktionsleiste zum Löschen, Kopieren/Einfügen und Exportieren von Protokollen
* &lbrack;Eigenschaften&rbrack; Neue Schaltfläche für Parameter, die den Mauszeiger zum Zurücksetzen des Parameterwerts bewegen
* &lbrack;Eigenschaften&rbrack; Neues Kontextmenü für Parameter zum Zurücksetzen des Parameterwerts durch Rechtsklick
* &lbrack;Inhalt&rbrack; &quot;Bild zu Material&quot; (KI-gestützt) funktioniert jetzt in MacOS
* &lbrack;Motor&rbrack; Substance-Engine auf Version 8.6.0 aktualisieren

**Fest:**

* &lbrack;Anwendung&rbrack; Die Anwendung konnte beim Beenden abstürzen, wenn eine Miniaturansichtserstellung ausgeführt wurde
* &lbrack;Anwendung&rbrack; Die Anwendung stürzt möglicherweise ab, wenn &quot;Speichern unter&quot; beim Beenden verwendet wird
* &lbrack;Anwendung&rbrack; Anwendung hängt möglicherweise beim Herunterfahren von MacOS
* &lbrack;Anwendung&rbrack; Beim Speichern mit geöffnetem Farbdialogfeld werden die Änderungen nicht gespeichert
* &lbrack;Export&rbrack; Die Benennungskonvention für die Verwendung ist beim Exportieren nicht korrekt.
* &lbrack;Layers&rbrack; Das Ablegen eines Materials über einem Filter kann abstürzen
* &lbrack;Layers&rbrack; Beim Aktualisieren eines veralteten Ebenenstapels werden möglicherweise nicht zugehörige Ebenenstapel aktualisiert
* &lbrack;Metadaten&rbrack; Leere Felder werden exportiert
* &lbrack;Metadaten&rbrack; Wenn es nur ein Metadatenelement gibt, können Sie auf der Benutzeroberfläche versuchen, es neu anzuordnen
* &lbrack;Projekt&rbrack; Die Berechnung endet nie, nachdem ein Material dupliziert wurde
* &lbrack;Projekt&rbrack; Projektelement wird nach dem ersten Speichern des Projekts dupliziert
* &lbrack;Projekt&rbrack; Unnötige Berechnungen beim Wechseln des Assets
* &lbrack;Rendering&rbrack; Einige Ebenenstapel werden nach dem Löschen einer Ebene nicht richtig gerendert
* &lbrack;Sicherheit&rbrack; Problembehebung CVE-2015-20107
* &lbrack;UI&rbrack; 2D-Ausgaben können je nach Fenstergröße verschwommen sein
* &lbrack;UI&rbrack; Die Elementvorschau kann oben geöffnet bleiben, wenn die Anwendung den Fokus verliert
* &lbrack;UI&rbrack; Abgerundete Ecken des Begrüßungsbildschirms haben einen quadratischen, deckenden Hintergrund

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.2 Zucchini

*(Freigegeben: 28. Juni 2022)*

**Fest:**

* &lbrack;Anwendung&rbrack; Beheben eines potenziellen Absturzes beim Öffnen eines Projekts
* &lbrack;Export&rbrack; Neustarten von Sampler unterbricht die Liste der importierten benutzerdefinierten Exportvorgaben
* &lbrack;Interoperabilität&rbrack; Absturz beheben, wenn ein von Designer gesendetes Material gelöscht und dann von Designer erneut gesendet wird
* &lbrack;Projekt&rbrack; Das letzte Material- oder Umgebungslicht kann nicht gelöscht werden, wenn es das letzte Asset im Projekt ist
* &lbrack;Projekt&rbrack; Durch Rechtsklick auf eine Umgebungsbeleuchtung werden die Sternchen &quot;nicht gespeicherte Änderungen&quot; angezeigt.

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.1 Zucchini

*(Freigegeben: 7. Juni 2022)*

**Hinzugefügt:**

* &lbrack;Anwendung&rbrack; Native Unterstützung für Apple silicon (M1)
* &lbrack;UI&rbrack; Neue Taste &quot;C&quot; zum Wechseln zwischen Kanälen in der 2D-Ansicht
* &lbrack;Extras&rbrack; Numerisches Feld zum Bearbeiten des Graustufenfarbwerts in der Pinselsymbolleiste

**Fest:**

* &lbrack;Extras&rbrack; Wenn Sie das Pinsel-Werkzeug unter Windows mit einer fraktionierten UI-Skala (150 %) verwenden, werden die Striche versetzt
* &lbrack;Performance&rbrack; Verbessern der Speicherauslastung
* &lbrack;Physische Größe&rbrack; Informationen zur Physische Größe können fehlen, wenn die Funktion aktiviert wird
* &lbrack;UI&rbrack; Das Scrollen mit der Maus funktioniert manchmal nicht wie erwartet, wenn Sie die Alt-Taste drücken
* &lbrack;Anwendung&rbrack; Die Anwendung kann beim Öffnen eines gespeicherten Projekts abstürzen
* &lbrack;Anwendung&rbrack; Absturz beim Ziehen und Ablegen mehrerer Bilder und bei Verwendung des Texturimports im Fenster &quot;Materialerstellungsvorlage&quot;
* &lbrack;Anwendung&rbrack; Potenzieller Absturz beim Speichern eines Projekts, das einen benutzerdefinierten Filter enthält
* &lbrack;Anwendung&rbrack; Manchmal geht der Status der Strg-Taste beim Wechseln der Anwendung verloren
* &lbrack;Assets&rbrack; Absturz beim Umbenennen eines lokalen Ordners

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.0 Zucchini

*(Freigegeben: 17. Mai 2022)*

**Hinzugefügt:**

* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot; (Windows und Mac)
* &lbrack;Inhalt&rbrack; Die inhaltsbasierte Füllung bearbeitet Bilder, PBR-Materialien und Umgebungslichter
* &lbrack;Inhalt&rbrack; Hinzufügen des Parameters &quot;Kachelung beibehalten&quot; zu &quot;Bild zu Material&quot; (KI-gestützt)
* &lbrack;Inhalt&rbrack; Der Filter &quot;Perspektivisches Transformieren&quot; kann ein Raster zwischen seinen vier Punkten anzeigen
* &lbrack;Interoperabilität&rbrack; Materialien an Adobe Substance 3D Stager senden.
* &lbrack;Extras&rbrack; Transformation beim Skalieren des Transformieren- oder Freistellungswerkzeugs durch Drücken der Strg-Taste zentrieren
* &lbrack;Extras&rbrack; Sperren des Verhältnisses zum Quadrat durch Drücken der Umschalttaste bei Größenänderung des Transformieren- oder Freistellungswerkzeugs
* &lbrack;Extras&rbrack; Cursor für Kopierstempel bietet eine Vorschau dessen, was gestempelt wird
* &lbrack;Extras&rbrack; Vorschau des Originalinhalts im Radiergummi, wenn Kopierstempel verwendet werden
* &lbrack;Extras&rbrack; Strg+Klick erstellt einen neuen Stempel in der Kopierstempel-Ebene
* &lbrack;Extras&rbrack; Aufeinander folgende Kopierstempel sind jetzt auf einer Ebene gruppiert
* &lbrack;Extras&rbrack; Pinsel-Symbolleiste - UI überarbeiten
* &lbrack;Extras&rbrack; Die Position der Pinsel-Symbolleiste bleibt während einer Sitzung erhalten.
* &lbrack;Extras&rbrack; Neue Optionen für die Pinselneigung nach Achse
* &lbrack;Extras&rbrack; Überlagerung beim Malen über der 2D-Ansicht ausblenden/anzeigen
* &lbrack;Extras&rbrack; Neuer Tastaturbefehl &quot;X&quot; zum Umschalten zwischen Pinsel und Radiergummi
* &lbrack;Extras&rbrack; Neue Tastenkombination &quot;&lbrack;&quot; &quot;&rbrack;&quot; zum Ändern der Pinselgröße
* &lbrack;Extras&rbrack; Neue Taste &quot;E&quot; zum Umschalten des Radiergummis
* &lbrack;2D Ansicht&rbrack; Neuer Sphärische Projektion-Modus beim Erstellen der Umgebungsbeleuchtung
* &lbrack;2D Ansicht&rbrack; Das Pinselwerkzeug wird vom sphärische Projektion-Modus unterstützt.
* &lbrack;2D Ansicht&rbrack; Positionierungswerkzeug wird im sphärische Projektion-Modus unterstützt
* &lbrack;2D Ansicht&rbrack; Das Rückgängigmachen/Wiederholen wird mit dem sphärische Projektion-Modus unterstützt.
* &lbrack;2D Ansicht&rbrack; Legen Sie in Sphärische Projektion die Standardposition fest, sodass der Blick auf den Mittelpunkt der Umgebung gerichtet ist.
* &lbrack;2D Ansicht&rbrack; Neue Belichtungssteuerung
* &lbrack;UI&rbrack; Im Bedienfeld &quot;Eigenschaften&quot; zeigt die Bildkorrektur die Quelle des Inhalts an (Bild oder aus einer Ebene)
* &lbrack;UI&rbrack; Verbesserte Ebenen-/Materialausgabe-Dropdown-Hintergrundebene
* &lbrack;UI&rbrack; Neue Position der Auflösungsinformationen in der 2D-Ansicht
* &lbrack;UI&rbrack; Neue QuickInfo mit Tastaturbefehlen für die 3D-Ansichtsnavigation
* &lbrack;UI&rbrack; Neue QuickInfo mit Pinselsteuerungen
* &lbrack;UI&rbrack; Neue QuickInfo mit Tastaturbefehlen für die Projektionsnavigation
* &lbrack;Zusammengesetzte Filter&rbrack; Verbundfilter verarbeiten Varianten für Bilder, PBR-Materialien und Umgebungslichter
* &lbrack;Zusammengesetzte Filter&rbrack; Tweak-Reihenfolge entspricht der Knoten-Listenreihenfolge im zusammengesetzten Filter
* &lbrack;Zusammengesetzte Filter&rbrack; Zwei verschiedene Knoten mit derselben Gruppe werden in einer Gruppe im Bedienfeld &quot;Eigenschaften&quot; zusammengeführt.
* &lbrack;Anwendung&rbrack; Dedizierte Anzeigeeinstellungen für jeden Elementtyp

**Fest:**

* &lbrack;Anwendung&rbrack; Anwendung kann abstürzen, wenn zur 2D-Ansicht gewechselt wird
* &lbrack;Anwendung&rbrack; Beheben einer möglichen Deadlock oder eines Absturzes beim mehrmaligen Exportieren
* &lbrack;Anwendung&rbrack; Festlegen von Standardwerten für Kanäle für die Konsistenz mit Substance 3D Designer
* &lbrack;Anwendung&rbrack; Das Laden eines Projekts löst keine Neuberechnung des Materials aus
* &lbrack;Anwendung&rbrack; Die URL zur Dokumentation zum Texturimport wurde aktualisiert
* &lbrack;Inhalt&rbrack; Bei Verwendung eines zusammengesetzten Filters muss er beim erneuten Laden aktualisiert werden, wenn dies nicht der Fall sein sollte
* &lbrack;Inhalt&rbrack; Details in der Height-Map verschwinden bei Verwendung der Deckkraftüberblendung
* &lbrack;UI&rbrack; Im Farbdialogfeld können Sie mit den Textfeldern des Schiebereglers den Bereich verlassen
* &lbrack;UI&rbrack; Verwendungsliste enthält eine nutzlose vertikale Bildlaufleiste

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &lbrack;Inhalt&rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &lbrack;Interoperabilität&rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.2.1 Jakitori

*(Freigegeben: 08. März 2022)*

**Hinzugefügt:**

* &lbrack;Export&rbrack; Exportieren von dpi-Metadaten in Bilddateien
* &lbrack;Physische Größe&rbrack; Beim Bearbeiten physikalischer Abmessungen das Verhältnis mit nicht quadratischen Texturen beibehalten
* &lbrack;Physische Größe&rbrack; Physische Größe-Metadaten werden sofort angewendet, wenn sich die Physische Größe ändert
* &lbrack;UI&rbrack; Passen Sie den Regler &quot;Max. Skalierung des Heights&quot; an, damit er bei aktivierter Physische Größe jede Art von Material beeinflussen kann.
* &lbrack;UI&rbrack; Neue QuickInfos zu Suchfiltern im Bedienfeld &quot;Elemente&quot;
* &lbrack;UI&rbrack; QuickInfos, um zu erläutern, wann Schaltflächen im Bedienfeld &quot;Elemente&quot; deaktiviert sind
* &lbrack;Inhalt&rbrack; Aktualisierung des Helligkeitskontrastfilters

**Fest:**

* &lbrack;2D Ansicht&rbrack; Die Schaltfläche &quot;Drehung um 90 Grad&quot; in den Werkzeugen &quot;Zuschneiden und transformieren&quot; funktioniert nicht wie erwartet
* &lbrack;2D Ansicht&rbrack; Das Zuschneide-Widget fehlt manchmal
* &lbrack;Anwendung&rbrack; Durch das Löschen eines Bildparameters wird die zugrunde liegende Ebene nicht erneut verbunden.
* &lbrack;Anwendung&rbrack; Absturz beim Beenden nach dem Speichern eines Projekts
* &lbrack;Anwendung&rbrack; Absturz beim Ziehen und Ablegen des aktuellen Materials in eine Sammlung des Bedienfelds &quot;Elemente&quot;
* &lbrack;Anwendung&rbrack; Das Ziehen und Ablegen eines Assets im Viewport kann abstürzen
* &lbrack;Inhalt&rbrack; Die normale Füllmethode hat einen zufälligen Startpunkt.
* &lbrack;Inhalt&rbrack; Schneefilter hat eine falsche Normalausgabe, abhängig von den Snow- und Schneeparameterwerten
* &lbrack;Inhalt&rbrack; Parkettfilter: feste unerwartete Nähte
* &lbrack;Inhalt&rbrack; Stickfilter: Gewinde in metallischer Karte entfernen
* &lbrack;Inhalt&rbrack; Bodenfliesen-Filter: x- und y-Kachelanzahl korrigieren
* &lbrack;Inhalt&rbrack; Ziegelwandfilter: Normal-Ausgang und Height auf 16 bit
* &lbrack;Export&rbrack; Der Standarddateiname im Export-Popup ist nicht der aktuelle Materialname
* &lbrack;Export&rbrack; Beim Exportieren mit physischem Verhältnis mit einer Exportvorgabe werden falsche Abmessungen angezeigt
* &lbrack;Export&rbrack; Metallic fehlt in der CLO-Exportvorgabe
* &lbrack;Export&rbrack; Beim Ersetzen einer benutzerdefinierten Exportvorgabe wird der Anzeigename nicht aktualisiert
* &lbrack;Layers&rbrack; Benutzerdefinierte Kanäle der ersten eingefügten Ebene werden nicht erkannt.
* &lbrack;Layers&rbrack; Material wird neu bewertet, wenn Änderungen einer ausgeblendeten Ebene geändert werden
* &lbrack;Lokalisierung&rbrack; QuickInfos sind im Exportbedienfeld nicht lokalisiert
* &lbrack;Physische Größe&rbrack; Durch Deaktivieren der Physische Größe eines Assets wird die physische Skalierung nicht entfernt.
* &lbrack;Physische Größe&rbrack; Der Skalierungswert des Heights kann beim ersten Mal nicht außerhalb der Reglergrenzen festgelegt werden
* &lbrack;Physische Größe&rbrack; Das Importieren eines Bildes ohne Physische Größe verhindert das Öffnen des Projekts
* &lbrack;Physische Größe&rbrack; Physische Größe ist fälschlicherweise auf Null gesetzt, wenn sie fehlt
* &lbrack;Physische Größe&rbrack; Der Status des Kontrollkästchens &quot;Physische Skalierung der Physische Größe&quot; wird bei der ersten Anzeige nicht aktualisiert
* &lbrack;UI&rbrack; Basismaterial &amp; Normal zu Height haben keine Kategorie
* &lbrack;UI&rbrack; Der Cursor ist beim Malen eines Bildes manchmal unsichtbar
* &lbrack;UI&rbrack; Deaktivieren der Optionen &quot;Alle kopieren&quot; und &quot;Alle ausschneiden&quot; im Bearbeitungsmenü eines Textfelds, wenn es leer ist
* &lbrack;UI&rbrack; Filternamen haben falsche Zeichen
* &lbrack;UI&rbrack; Schaltfläche zum Sperren der Physische Größe hat nicht den richtigen Stil
* &lbrack;UI&rbrack; Die Schaltfläche &quot;Schließen&quot; in der Suchleiste im Bedienfeld &quot;Elemente&quot; löscht die Suchzeichenfolge nicht

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.2.0 Jakitori

*(Freigegeben: 25. Januar 2022)*

**Hinzugefügt:**

* &lbrack;Physische Größe&rbrack; Neues Bedienfeld &quot;Physische Größe&quot;
* &lbrack;Physische Größe&rbrack; Optionen für die Physische Größe im Fenster &quot;Materialerstellungsvorlage&quot; hinzufügen
* &lbrack;Physische Größe&rbrack; Werkzeug zum Messen von Physische Größen hinzufügen
* &lbrack;Physische Größe&rbrack; Automatisch messende Physische Größe hinzufügen
* &lbrack;Physische Größe&rbrack; Physische Größe hinzufügen
* &lbrack;Physische Größe&rbrack; Festlegen des z-Werts der Physische Größe zulassen
* &lbrack;Physische Größe&rbrack; Dropdown-Widget zum Festlegen der Zoomstufe in der 2D-Ansicht
* &lbrack;Physische Größe&rbrack; Neue Option &quot;Anzeige mit physischem Verhältnis&quot; auf der Ebene der Zoom-Dropdown-Liste
* &lbrack;Physische Größe&rbrack; Neue Option &quot;An Physische Größe anpassen&quot; auf der Ebene der Zoom-Dropdown-Liste
* &lbrack;Physische Größe&rbrack; Anzeigen der Physische Größe in der 2D-Ansicht
* &lbrack;Physische Größe&rbrack; Anzeigen der Physische Größe im 3D-Viewport
* &lbrack;Physische Größe&rbrack; Im Dialogfeld &quot;Bildimport&quot; Tiefe der Physische Größe anzeigen, wenn eine importierte Height-Map vorhanden ist
* &lbrack;Physische Größe&rbrack; Physische Größe im Kontextmenü des Elements anzeigen
* &lbrack;Physische Größe&rbrack; Legen Sie die Längeneinheit in den Voreinstellungen fest.
* &lbrack;Physische Größe&rbrack; Exportieren von Texturen, die das physische Verhältnis berücksichtigen
* &lbrack;Metadaten&rbrack; Möglichkeit, einem von Benutzern erstellten Asset benutzerdefinierte Metadaten hinzuzufügen
* &lbrack;Export&rbrack; Exportieren benutzerdefinierter Metadaten in .sbs(ar)-Dateien
* &lbrack;Export&rbrack; Exportieren von Beschreibungen, Kategorien, Autoren und Tagmetadaten in .sbs(ar)-Dateien
* &lbrack;Export&rbrack; Exportieren der Physische Größe in .sbs(ar)-Dateien
* &lbrack;Export&rbrack; Komprimierungseinstellung für .sbsar-Dateien festlegen
* &lbrack;Export&rbrack; Exportieren der Miniaturansicht des Elements in .sbs(ar)-Dateien
* &lbrack;Export&rbrack; Festlegen des Diagrammtyps beim Exportieren einer .sbs(ar)-Datei
* &lbrack;Anwendung&rbrack; Realtime Engine 2021 ist nicht mehr verfügbar
* &lbrack;Anwendung&rbrack; &quot;Rückgängig/Wiederholen&quot; unterstützt jetzt Änderungen an den Teilungseinstellungen (U,V) und am Height-Skalierungsregler
* &lbrack;Rendering&rbrack; Generieren des Disk-Cache beim Speichern des erstellten Assets
* &lbrack;Assets&rbrack; Mehrere Elementtypfilter im Bedienfeld &quot;Ressourcen&quot; durch Klicken bei gedrückter Strg-Taste aktivieren
* &lbrack;UI&rbrack; Funktion zum Sperren der Kachelregler (U,V)
* &lbrack;UI&rbrack; Kontextmenü mit &quot;Kopieren&quot;, &quot;Ausschneiden&quot;, &quot;Einfügen&quot;, &quot;Alle kopieren&quot; und &quot;Alle ausschneiden&quot; in Textfeldern hinzufügen
* &lbrack;UI&rbrack; Längeneinheit (Meter, Zoll, Parsec, ...) Unterstützung für Beschriftungen und Textfelder
* &lbrack;UI&rbrack; Der Benutzer kann die Dezimalpräzision festlegen, die zum Anzeigen von Zahlen verwendet wird.
* &lbrack;UI&rbrack; Maßeinheiten in Popups verwenden, wo immer es relevant ist
* &lbrack;Lokalisierung&rbrack; Der Name des neuen Standardstockmediums ist jetzt lokalisiert
* &lbrack;Inhalt&rbrack; Neuer Gewebewebgenerator
* &lbrack;Inhalt&rbrack; Neuer Kanalschalter-Filter
* &lbrack;Inhalt&rbrack; Alle relevanten Filter kennen jetzt die Physische Größe
* &lbrack;Inhalt&rbrack; Neue Icons für Wood Finish
* &lbrack;Inhalt&rbrack; Alle Filter sind jetzt mit Adobe Standard Materials (ASM) Kanälen kompatibel.
* &lbrack;Inhalt&rbrack; Filter können jetzt eine &quot;Umgebungs&quot;-Variation haben

**Fest:**

* &lbrack;2D Ansicht&rbrack; Kanal bleibt in der Liste, wenn er entfernt wird
* &lbrack;Anwendung&rbrack; Ein aus dem Dateiexplorer des Betriebssystems geladenes Asset kann nicht dupliziert werden.
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Absturz manchmal beim Klicken auf &quot;Starter-Elemente&quot; im Bedienfeld &quot;Elemente&quot;
* &lbrack;Anwendung&rbrack; Absturz beim Löschen eines Materials
* &lbrack;Anwendung&rbrack; Die Umgebungsvariable &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; ist noch aktiv, wenn sie auf &quot;0&quot; oder &quot;&quot; gesetzt ist.
* &lbrack;Anwendung&rbrack; Einfrieren beim Speichern eines Projekts mit mehreren Materialien
* &lbrack;Anwendung&rbrack; Das Importieren eines Bildes kann zu einem Absturz führen
* &lbrack;Anwendung&rbrack; Beim ersten Start fehlen einige Starter-Assets
* &lbrack;Export&rbrack; Das Exportieren eines Assets kann zu einem Absturz führen
* &lbrack;Layers&rbrack; Bilder können nicht importiert werden, wenn das Ebenenfenster geschlossen oder nicht sichtbar ist
* &lbrack;Layers&rbrack; Wenn Sie die Sprache ändern, wird das aktuelle Asset neu berechnet.
* &lbrack;Layers&rbrack; Wenn Sie die Verwendung eines importierten Bildes ändern, wird nicht aktualisiert, welche Filtervariante verwendet werden soll
* &lbrack;Layers&rbrack; &quot;Bild zu Material&quot; (AI) wird manchmal nicht berechnet, wenn Ebenen darunter angepasst werden
* &lbrack;Layers&rbrack; &quot;Bild zu Material&quot; (AI) wird manchmal neu berechnet, wenn es nicht benötigt wird
* &lbrack;Layers&rbrack; Wenn ein benutzerdefinierter Filter auf der Festplatte aktualisiert wird, wird kein Update vorgeschlagen.
* &lbrack;Layers&rbrack; Der normale Kanal hat manchmal das falsche Pixelformat
* &lbrack;Layers&rbrack; Einige Ebenen werden immer noch berechnet, auch wenn sie nicht sichtbar sind
* &lbrack;Layers&rbrack; Beim Umschalten der Ebenensichtbarkeit können die Werkzeuge der 2D-Ansicht beschädigt werden
* &lbrack;Layers&rbrack; Die Benutzeroberfläche friert ein, wenn Bild zu Material (AI) verwendet wird
* &lbrack;Layers&rbrack; Wenn Sie die Sichtbarkeit der Transformieren-Filterebene umschalten, wird das 2D-Ansichtswerkzeug beschädigt und kann zu einem Absturz führen
* &lbrack;Layers&rbrack; Zu viele Neuberechnungen beim Entfernen einer Ebene aus dem Ebenenstapel
* &lbrack;Layers&rbrack; Wenn ein zusammengesetzter Filter eine ungewöhnliche oder benutzerdefinierte Eingabe/Ausgabe enthält, wird diese von Sampler nicht berechnet
* &lbrack;Performance&rbrack; Bedienfeld &quot;Elemente&quot; lässt sich nur langsam öffnen
* &lbrack;Performance&rbrack; Vermeiden Sie unnötige Neuberechnungen des Ebenenstapels
* &lbrack;Performance&rbrack; Das Laden von Projekt-Assets dauert zu lange
* &lbrack;Performance&rbrack; Der Render-Cache auf dem Datenträger darf nicht verwendet werden.
* &lbrack;Performance&rbrack; Der Wechsel zwischen Ebenen ist langsam
* &lbrack;Performance&rbrack; Das Anpassen eines Materials oder Filters ist langsam
* &lbrack;Projekt&rbrack; Das Speichern eines Projekts beim Beenden kann zu einem Absturz führen
* &lbrack;Rendering&rbrack; Durch Entfernen eines Bildes werden möglicherweise alle Ausgaben entfernt
* &lbrack;Rendering&rbrack; Die im Viewport angezeigte Renderzeit ist beim Anpassen falsch
* &lbrack;UI&rbrack; Bei Bedarf kann im Popup &quot;Export&quot; nicht vertikal gescrollt werden
* &lbrack;UI&rbrack; Es ist möglich, das Popup &quot;Exportieren&quot; zu öffnen, wenn es nichts zu exportieren gibt
* &lbrack;UI&rbrack; Einige Popups scrollen nicht, wenn ihr Inhalt überläuft
* &lbrack;UI&rbrack; Textfelder sind nicht ausgewählt, wenn Sie darauf klicken oder ein Menü öffnen
* &lbrack;UI&rbrack; Der Name der Füllmethode im Eigenschaftenfenster ist manchmal nicht korrekt
* &lbrack;UI&rbrack; Die Option &quot;Speichern&quot; im Menü &quot;Datei&quot; ist manchmal ausgegraut.
* &lbrack;UI&rbrack; Das Textfeld verschwindet nach dem Umbenennen von zwei Materialien nicht
* &lbrack;UI&rbrack; Tippfehler im Voreinstellungs-Popup

**Bekannte Probleme:**

* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.2 Xocoatl

*(Freigegeben: 14. Dezember 2021)*

**Fest:**

* &lbrack;Interoperabilität&rbrack; Das Öffnen von .sbsar-Dateien mit Substance 3D Sampler aus Bridge kann unter Windows fehlschlagen
* &lbrack;Layers&rbrack; Das Verschieben der einzigen Ebene unter sich führt zum Absturz
* &lbrack;UI&rbrack; Schaltfläche &quot;Kanaleinstellungen&quot; verschwindet beim Ändern der Sprache
* &lbrack;UI&rbrack; Der Materialname im Eigenschaftenfenster verschwindet nach dem Speichern des Projekts
* &lbrack;Assets&rbrack; Das Klicken auf &quot;Alle Bibliotheken&quot; kann zu einem Absturz führen

**Bekannte Probleme:**

* &lbrack;Realtime Engine 2021&rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.1 Xocoatl

*(Freigegeben: 24. November 2021)*

**Hinzugefügt:**

* &lbrack;Interoperabilität&rbrack; Elemente (SBS oder SBSAR) an Substance 3D Designer senden
* &lbrack;Interoperabilität&rbrack; Festlegen des Standardformats für die Interoperabilität mit Substance 3D Designer in den Voreinstellungen
* &lbrack;Interoperabilität&rbrack; Mehrere Elemente aus Adobe Bridge erhalten
* &lbrack;UI&rbrack; Neues Widget für Zufallsverteilung
* &lbrack;UI&rbrack; Aktualisierung des Kontextmenüs
* &lbrack;Assets&rbrack; Bilder vom Bedienfeld &quot;Elemente&quot; in das Bedienfeld &quot;Eigenschaften&quot; ziehen
* &lbrack;Projekt&rbrack; Elementnamen werden bereinigt, um bestimmte Zeichen zu vermeiden
* &lbrack;Branding&rbrack; Dateisymbol für SBSAR-Dateien aktualisieren
* &lbrack;Motor&rbrack; Substance Engine 8.3.0 aktualisieren

**Fest:**

* &lbrack;Inhalt&rbrack; Freistellen - Beibehalten des Verhältnisses beim Freistellen nicht quadratischer Bilder
* &lbrack;Inhalt&rbrack; Transformieren : Die horizontale Transformation wird bei Verwendung des Widgets nicht invertiert
* &lbrack;Inhalt&rbrack; Kies - benutzerdefinierte Maskenmalerei auf allen Kanälen beheben
* &lbrack;Inhalt&rbrack; Bodenfliesen - Beheben Sie Probleme mit Musterkacheln und Wiederholung
* &lbrack;Assets&rbrack; Option &quot;Adobe Bridge grau hinterlegen&quot;, wenn diese nicht installiert ist
* &Klammer;Farbwähler&Klammer; Esc-Taste schließt Farbwähler
* &lbrack;Rendering&rbrack; Streuungsdistanzskalierung bei Verwendung von Graustufeneingaben korrigieren
* &lbrack;Share&rbrack; Optionen für &quot;Senden an&quot; sind nur mit Adobe-Lizenzen verfügbar
* &lbrack;Projekt&rbrack; Beheben eines Problems mit der Speicherleistung

**Bekannte Probleme:**

* &lbrack;Realtime Engine 2021&rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.0 Xocoatl

*(Freigegeben: 28. September 2021)*

**Hinzugefügt:**

* &Klammer;Farbwähler&Klammer; Neue Benutzeroberfläche für den Farbwähler
* &Klammer;Farbwähler&Klammer; Vorschau der aktuellen und vorherigen Farben nebeneinander
* &Klammer;Farbwähler&Klammer; Eingabe der Farbe in Hexadezimal
* &Klammer;Farbwähler&Klammer; Neue Pipette mit Farbvorschau
* &Klammer;Farbwähler&Klammer; Die Pipette kann eine Farbe außerhalb von Sampler auswählen
* &Klammer;Farbwähler&Klammer; Anpassen der Farbe im RGB- oder HSV-Farbraum
* &Klammer;Farbwähler&Klammer; Farbfelder speichern und verwalten
* &lbrack;Interoperabilität&rbrack; Bilder in Illustrator aus der Bildimportebene oder den Bildparametern bearbeiten
* &lbrack;Interoperabilität&rbrack; Bilder in Photoshop aus der Bildimportebene oder den Bildparametern bearbeiten
* &lbrack;Widget&rbrack; Neues Freistellungs-Widget
* &lbrack;Widget&rbrack; Bestätigen des Freistellungsvorgangs mit der Eingabetaste
* &lbrack;Widget&rbrack; Das Widget &quot;Zuschneiden&quot; liest die Bildgröße, um sie an das Widget anzupassen, und behält das Verhältnis bei der Größenänderung bei
* &lbrack;UI&rbrack; Neue Benutzeroberfläche für Regler im Graustufenmodus
* &lbrack;Anwendung&rbrack; Hinzufügen einer normalen Formatauswahl in den Voreinstellungen
* &lbrack;Anwendung&rbrack; Das Standardformat für Bildimportebenen entspricht dem in den Voreinstellungen festgelegten Standardformat
* &lbrack;Anwendung&rbrack; In der 2D-Ansicht wird die Normale entsprechend dem in den Voreinstellungen festgelegten Normalformat angezeigt
* &lbrack;Anwendung&rbrack; Die Normale wird in das in den Voreinstellungen festgelegte normale Format exportiert
* &lbrack;Export&rbrack; Hinzufügen eines normalen Formatparameters zu SBS- und SBSAR-Dateiexporten
* &lbrack;Export&rbrack; Shader-Einstellungen zu SBS- und SBSAR-Dateiexporten hinzufügen
* &lbrack;Export&rbrack; Standardauflösung für exportierte SBS-Diagramme festlegen
* &lbrack;Zusammengesetzte Filter&rbrack; SSA-Filter mit 7z verpacken
* &lbrack;Zusammengesetzte Filter&rbrack; Kategoriemetadaten in zusammengesetzten Filtern hinzufügen
* &lbrack;Zusammengesetzte Filter&rbrack; Verknüpfte Filter können eine eingebettete Miniaturansicht haben
* &lbrack;Zusammengesetzte Filter&rbrack; Dem Dateidialogfeld &quot;Inhalt abrufen&quot; wurde die Erweiterung &quot;Zusammengesetzte Filter&quot; (.ssafilter) hinzugefügt.
* &lbrack;Zusammengesetzte Filter&rbrack; Importieren von zusammengesetzten Filtern (.ssafilter) im Bedienfeld &quot;Elemente&quot;
* &lbrack;Motor&rbrack; Substance-Engine auf Version 8.2.0 aktualisieren

**Fest:**

* &lbrack;Anwendung&rbrack; Verbundene lokale Ordner können hängen bleiben
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Absturz beim Starten von zwei Instanzen von Sampler
* &lbrack;Inhalt&rbrack; Der Freistellungsfilter verfügt über eine zufällige Anpassung des Startwerts.
* &lbrack;Inhalt&rbrack; Einige Substance-Materialien werden manchmal nicht aktualisiert
* &lbrack;Export&rbrack; Absturz beim Exportieren mit einer neu hinzugefügten benutzerdefinierten Vorgabe
* &lbrack;Export&rbrack; Geschätzte Größe des Pakets fehlt im Export-Popup
* &lbrack;Export&rbrack; Beheben von Speicherlecks beim Exportieren von SBS- und SBSAR-Dateien
* &lbrack;Zusammengesetzte Filter&rbrack; Zusammengesetzte Filter können duplizierte Eingaben aufweisen
* &lbrack;Zusammengesetzte Filter&rbrack; Absturz, wenn ein Filter nicht erfüllt ist
* &lbrack;Zusammengesetzte Filter&rbrack; Absturz beim Neuanordnen eines Ebenenstapels mit einem zusammengesetzten Filter darin
* &lbrack;Zusammengesetzte Filter&rbrack; Das Rendering hängt manchmal
* &lbrack;Bildimport&rbrack; Beim Importieren eines Bildes werden mehrere Renderings ausgelöst
* &lbrack;Layers&rbrack; Absturz beim Rückgängigmachen/Wiederholen
* &lbrack;Layers&rbrack; Absturz beim Hinzufügen eines Basismaterials
* &lbrack;Layers&rbrack; Absturz bei Verwendung eines ungültigen Bildes als Umgebungslicht
* &lbrack;Layers&rbrack; Doppelten Import beheben, wenn ein Filter mit mehreren Graphen eingefügt wird
* &lbrack;Layers&rbrack; Das Neuanordnen von Ebenen funktioniert nicht immer
* &lbrack;Projekt&rbrack; Absturz beim Laden einer unvollständigen Projektdatei
* &lbrack;Projekt&rbrack; Absturz beim Öffnen eines beschädigten Projekts
* &lbrack;Projekt&rbrack; Einige Elemente können aus einem Projekt verschwinden
* &lbrack;Eigenschaften&rbrack; Vorgaben für fehlende Filter korrigieren
* &lbrack;UI&rbrack; Winkelparameter können nicht festgelegt werden.
* &lbrack;UI&rbrack; Filtermetadaten werden im Bedienfeld &quot;Elemente&quot; angezeigt
* &lbrack;UI&rbrack; Beim Gruppieren nach Kategorie werden Filter ausgeblendet.
* &lbrack;UI&rbrack; Bildlaufproblem im Bedienfeld &quot;Elemente&quot;
* &lbrack;UI&rbrack; Das Exportbedienfeld verfügt jetzt über eine Bildlaufleiste
* &lbrack;UI&rbrack; Die Miniaturansicht wird für einige Bildformate in der Bildauswahl nicht angezeigt

**Bekannte Probleme:**

* &lbrack;Realtime Engine 2021&rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &Klammer;Farbwähler&Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.0.1 Waffel

*(Freigegeben: 27. Juli 2021)*

**Hinzugefügt:**

* &Klammer;Pinsel&Klammer; Aktivieren von Farben im Pinselwerkzeug, wenn die Bildeingabe dies unterstützt
* &Klammer;Pinsel&Klammer; Durch Drücken der Umschalttaste im Pinselwerkzeug werden gerade Linien gezeichnet
* &Klammer;Pinsel&Klammer; Zeilenvorschau anzeigen, wenn Sie die Umschalttaste im Pinselwerkzeug gedrückt halten
* &Klammer;Pinsel&Klammer; Pinsel-Werkzeug unterstützt jetzt Rückgängig und Wiederholen
* &lbrack;2D Ansicht&rbrack; Beim Malen wird die Standardfarbe für die Bildeingabe verwendet
* &lbrack;Layers&rbrack; Lesen des Substance-Eingabestandardwerts in SBSAR-Dateien
* &lbrack;Rendering&rbrack; Height mit normalen Elementen kombinieren
* &lbrack;Rendering&rbrack; Unterstützung für Volumenstreuung (nicht verfügbar in MacOS)
* &lbrack;Assets&rbrack; SBSAR-Diagrammtyp zum Bestimmen des Elementtyps verwenden
* &lbrack;Assets&rbrack; Bessere Leistung für die Suche und die Auffindbarkeit von Elementen im Bedienfeld &quot;Elemente&quot;
* &lbrack;Assets&rbrack; Im Bedienfeld &quot;Elemente&quot; wurde der Eintrag &quot;Alle Bibliotheken&quot; hinzugefügt, in dem alle Elemente aus allen Ihren Bibliotheken angezeigt werden.
* &lbrack;Assets&rbrack; Der Benutzer kann jetzt Elemente nach Kategorie oder Typ gruppieren.
* &lbrack;Import&rbrack; Texturen in Anisotropie, Coat, Glanz und Specular edge color beim Import automatisch erkennen
* &lbrack;UI&rbrack; Titel des verbundenen Bedienfelds durch ein Symbol ersetzen
* &lbrack;UI&rbrack; Textfeldstil aktualisieren
* &lbrack;UI&rbrack; Neuer Beschreibungstext im Fenster &quot;Environment Light Template Creation&quot; (Erstellung der Umgebungslichtvorlage)
* &lbrack;Anwendung&rbrack; Elemente mit der aktuellen Auflösung exportieren, wenn sie an eine externe Anwendung gesendet werden
* &lbrack;Anwendung&rbrack; Die Materialstandardauflösung ist jetzt 2048\*2048 (1024\*1024 unter macOS).
* &lbrack;Inhalt&rbrack; Neue Muster im Bodenfliesen-Filter
* &lbrack;Inhalt&rbrack; Neuer Dual-Farbmodus im Farbaustauschfilter

**Fest:**

* &lbrack;2D Ansicht&rbrack; Der erste Strich im Pinselwerkzeug ist manchmal beschädigt
* &lbrack;2D Ansicht&rbrack; Kostenlose Ressourcen, wenn das Pinselwerkzeug nicht sichtbar ist
* &lbrack;2D Ansicht&rbrack; Verwenden des Cursors zur Größenänderung rechts im Transformieren-Widget
* &lbrack;2D Ansicht&rbrack; Widgets werden nicht angezeigt, wenn der Benutzer zuvor in der 2D-Ansicht geschwenkt hat
* &lbrack;Anwendung&rbrack; Absturz beim Öffnen eines Projekts mit beschädigtem Arbeitsablauf
* &lbrack;Anwendung&rbrack; Beheben des Herunterfahrens der Anwendung, um eine Überflutung des Protokolls mit nutzlosen Fehlern zu verhindern
* &lbrack;Anwendung&rbrack; Auf einigen Betriebssystemen funktionieren die Tastaturbefehle zum Wiederherstellen, Löschen und Speichern nicht
* &lbrack;Anwendung&rbrack; Das Rückgängigmachen/Wiederholen von Änderungen der Bildnutzung in der Importebene ist fehlgeschlagen
* &lbrack;Export&rbrack; Die exportierten Bilder der Emissionsfarbe haben einen falschen Namen
* &lbrack;Export&rbrack; Umgebung ist 8 Bit, wenn SBSAR-Export verwendet wird
* &lbrack;Export&rbrack; Entfernen zusätzlicher Leerzeichen in exportierten Bilddateinamen
* &lbrack;Export&rbrack; Das Ersetzen oder Löschen einer benutzerdefinierten Exportvorgabe stürzt ab
* &lbrack;Layers&rbrack; Absturz bei nicht übereinstimmender Eingangsanzahl vermeiden
* &lbrack;Layers&rbrack; Absturz beim Einfügen einer Basismaterial-Ebene
* &lbrack;Layers&rbrack; Die Anzahl der Filtereingaben ist auf den Standardwert begrenzt
* &lbrack;Layers&rbrack; Durch &quot;Wiederholen&quot; wird die Füllmethode fälschlicherweise in &quot;Height-Überblendung&quot; geändert
* &lbrack;Layers&rbrack; Ablagebereich über Eingabekopfzeilen entfernen
* &lbrack;Layers&rbrack; Ebenen werden an der falschen Stelle um die Kopfzeilen eingefügt.
* &lbrack;Layers&rbrack; Schaltfläche &quot;Alle Einstellungen zurücksetzen&quot; setzt die Werte der Dropdown-Widgets nicht zurück
* &lbrack;Layers&rbrack; Durch Rückgängigmachen/Wiederholen beim Ändern eines Bildes auf der Bildimportebene wird das Projekt als geändert markiert und somit gespeichert
* &lbrack;Layers&rbrack; Verwenden von Mischebenen kann gestoppt werden
* &lbrack;Projekt&rbrack; Absturz beim Laden eines älteren Projekts mit fehlenden Abhängigkeitsordnern
* &lbrack;Projekt&rbrack; Absturz bei Verwendung von Rückgängig/Wiederholen nach dem Speichern
* &lbrack;Projekt&rbrack; Durch Öffnen einer SBSAR-Datei mit einer Umgebungsbeleuchtung wird ein Materialelement erstellt.
* &lbrack;Projekt&rbrack; Das Umbenennen eines Materials kann eine Miniaturgenerierung auslösen
* &lbrack;Projekt&rbrack; Durch Speichern nach dem Umbenennen eines Materials wird das Projekt als nicht geändert markiert
* &lbrack;Projekt&rbrack; Einige Änderungen nach dem Umbenennen eines Materials werden nicht gespeichert
* &lbrack;Rendering&rbrack; Helle Punkte sind in der Umgebung mit der Echtzeit-Engine 2020 sichtbar
* &lbrack;Rendering&rbrack; Absturz beim Skalieren mit Real Time Engine 2021
* &lbrack;Rendering&rbrack; Neuberechnen von Schatten bei Änderungen auf Height-Ebene
* &lbrack;Assets&rbrack; Verbundene Ordner beenden die Indizierung neuer Assets, wenn eine ungültige Datei hinzugefügt wird
* &lbrack;Assets&rbrack; Absturz beim Verbinden eines lokalen Ordners mit vielen Materialien
* &lbrack;UI&rbrack; Schaltflächen in 2D-/3D-Ansicht fehlen QuickInfos
* &lbrack;UI&rbrack; Alle Elemente im Bedienfeld &quot;Elemente&quot; werden beim Start hervorgehoben
* &lbrack;UI&rbrack; Breadcrumbs werden beim Importieren von Materialien manchmal im Bedienfeld &quot;Elemente&quot; ausgeblendet
* &lbrack;UI&rbrack; Das Ändern der Sprache hat keine Auswirkungen auf das Projektfenster
* &lbrack;UI&rbrack; Das Bedienfeld &quot;Kanaleinstellungen&quot; zeigt ältere Workflow-Informationen an.
* &lbrack;UI&rbrack; Richten Sie den Text &quot;Keine Einstellungen für dieses Element&quot; für Filter ohne Änderungen im Eigenschaftenbedienfeld korrekt aus.
* &lbrack;UI&rbrack; Elemente werden auf dem Begrüßungsbildschirm und im Popup &quot;Voreinstellungen&quot; falsch ausgerichtet
* &lbrack;UI&rbrack; Bedienfeldtitel haben eine falsche Breite
* &lbrack;UI&rbrack; Im Bedienfeld &quot;Eigenschaften&quot; kann das Scrollen unterbrochen werden
* &lbrack;UI&rbrack; Der Begrüßungsbildschirm hat ein falsches Verhältnis und ist verschwommen.
* &lbrack;UI&rbrack; Der Vollbildmodus ist nicht Vollbildmodus.
* &lbrack;UI&rbrack; Nicht angedockte Bedienfelder sind immer oben, auch wenn die Anwendung in MacOS nicht aktiv ist
* &lbrack;UI&rbrack; Bannerbild für Begrüßungsbildschirm aktualisieren
* &lbrack;Inhalt&rbrack; Der Kachelfilter verarbeitet den Umgebungskanal für die Verdeckung nicht
* &lbrack;Inhalt&rbrack; Steppstich Problem mit der Kante Zusammenbau Nahtauswahl und Diamantmuster
* &lbrack;Inhalt&rbrack; Relief-Filter funktioniert in 256 px x 256 px
* &lbrack;Inhalt&rbrack; Problem mit Unterkacheln bei Bodenfliesen beheben, wenn der Versatz größer als 0 ist

**Bekannte Probleme:**

* &lbrack;Realtime Engine 2021&rbrack; Starke Berechnung, Absturz der Anwendung
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer mit AMD-CPU und Nvidia-GPU ab

### 3.0.0 Waffel

*(Freigegeben: 23. Juni 2021)*

**Hinzugefügt:**

* &lbrack;Branding&rbrack; Substance Alchemist wird zu Adobe Substance 3D Sampler
* &lbrack;Branding&rbrack; Neue Anwendungssymbole
* &lbrack;UI&rbrack; Neues Benutzererlebnis und neue Benutzeroberfläche
* &lbrack;UI&rbrack; Neuer Splashscreen
* &lbrack;UI&rbrack; Bedienfelder können abgedockt und an der Oberfläche angedockt werden.
* &lbrack;UI&rbrack; Andocken von bis zu drei Bedienfeldern in derselben Spalte
* &lbrack;UI&rbrack; Andocken von bis zu drei Bedienfeldern im selben Bedienfeld (Registerkarten)
* &lbrack;UI&rbrack; Abdocken von Bedienfeldern, um ein separates Fenster auf demselben oder einem anderen Bildschirm zu erstellen
* &lbrack;UI&rbrack; Geschlossene Bedienfelder, die beim Klicken auf ihre Symbole eingeblendet werden
* &lbrack;UI&rbrack; Die linke und rechte Leiste durch Verschieben der Bedienfeldsymbole neu anordnen
* &lbrack;UI&rbrack; Neue Symbolleiste für den direkten Zugriff auf bestimmte Filter (Zuschneiden, Transformieren, Perspektivisches Transformieren, Kopierstempel)
* &lbrack;UI&rbrack; Neue Schaltfläche &quot;Inhalt abrufen&quot; in der linken Leiste
* &lbrack;UI&rbrack; Importieren Sie Dateien direkt in Ihre Assets mit der Schaltfläche &quot;Inhalt abrufen&quot;
* &lbrack;UI&rbrack; Importiere Dateien über die Schaltfläche &quot;Inhalt abrufen&quot; direkt in deine Ebenen
* &lbrack;UI&rbrack; Direkter Zugriff auf die Adobe Substance 3D Assets-Website über die Schaltfläche &quot;Inhalt abrufen&quot;
* &lbrack;UI&rbrack; Das Auflösungs-Widget ist jetzt direkt im Viewport verfügbar
* &lbrack;UI&rbrack; Alle UI-Elemente werden jetzt dynamisch geladen
* &lbrack;UI&rbrack; Tastaturbefehl - Verwenden Sie &quot;2&quot;, um die Sichtbarkeit der 2D-Ansicht zu ändern.
* &lbrack;UI&rbrack; Tastaturbefehl - Verwenden Sie &quot;3&quot;, um die Sichtbarkeit der 3D-Ansicht zu ändern.
* &lbrack;Begrüßungsbildschirm&rbrack; Projekt mit der Schaltfläche &quot;Neu&quot; per Mausklick erstellen
* &lbrack;Begrüßungsbildschirm&rbrack; Neues Bildmaterial-Banner
* &lbrack;Projekt&rbrack; Alle Projekte sind jetzt einer eindeutigen Datei zugeordnet
* &lbrack;Projekt&rbrack; Neue Projektdateierweiterung .ssa
* &lbrack;Projekt&rbrack; Bei &quot;Als Projekt speichern&quot; müssen Sie auswählen, wo das Projekt gespeichert werden soll
* &lbrack;Projekt&rbrack; Wenn Sie Sampler schließen, werden Sie aufgefordert, Ihr Projekt zu speichern, falls es nicht gespeichert wurde
* &lbrack;Projekt&rbrack; Wenn Sie Sampler schließen, werden Sie aufgefordert, Ihr Projekt zu speichern, wenn seit dem letzten Speichern Änderungen vorgenommen wurden
* &lbrack;Projekt&rbrack; Der Name Ihres Projekts wird über dem Viewport angezeigt
* &lbrack;Projekt&rbrack; Der Projektname ist kursiv mit einem Stern gekennzeichnet, wenn er nicht gespeichert ist oder wenn er seit dem letzten Speichern Änderungen enthält
* &lbrack;Projekt&rbrack; Öffnen einer .ssa-Projektdatei direkt über den Betriebssystem-Explorer
* &lbrack;Projekt&rbrack; Öffnen Sie eine .sbsar-Datei auf Ihrem Betriebssystem-Explorer startet Sampler mit einem neuen Projekt mit dieser .sbsar-Datei, die Sie sofort verwenden können
* &lbrack;Projekt&rbrack; Öffnen Sie eine .alch-Datei (ältere Substance Alchemist-Datei) in Ihrem Betriebssystem-Explorer
* &lbrack;Projektfenster&rbrack; Neues Bedienfeld, das alle in einem Projekt erstellten Elemente enthält
* &lbrack;Projektfenster&rbrack; Element (Material- oder Umgebungslicht) mit dem Symbol &quot;+&quot; erstellen
* &lbrack;Projektfenster&rbrack; Durch Rechtsklick auf ein Element wird ein Kontextmenü geöffnet
* &lbrack;Projektfenster&rbrack; Im Kontextmenü können Sie ein Element löschen
* &lbrack;Projektfenster&rbrack; Über das Kontextmenü können Sie ein Element duplizieren
* &lbrack;Projektfenster&rbrack; Im Kontextmenü können Sie ein Element umbenennen
* &lbrack;Projektfenster&rbrack; Durch den Wechsel zwischen Elementen gehen Änderungen nicht verloren
* &blbrack;Auflösung&blbrack; Sie können jetzt eine nicht quadratische Auflösung für alle Ihre Assets festlegen
* &blbrack;Auflösung&blbrack; Der Auflösungswert wird von einem Asset innerhalb eines Projekts gespeichert
* &lbrack;Umgebungslicht&rbrack; Umgebungslicht in Substance 3D Sampler erstellen
* &lbrack;Umgebungslicht&rbrack; Beim Erstellen einer Umgebungsbeleuchtung wird durch Ziehen und Ablegen von Bildern das Vorlagenfenster für die Erstellung von Umgebungsbeleuchtungen angezeigt
* &lbrack;Umgebungslicht&rbrack; Wählen Sie in der Vorlage Umgebungslicht erstellen die Option Umgebungsimport aus, um das Bild der Umgebung in der 3D-Ansicht zuzuweisen.
* &lbrack;Umgebungslicht&rbrack; Wählen Sie in der Vorlage zur Erstellung von Umgebungslicht die Option HDR-Zusammenfügung aus, um ein Umgebungslicht aus mehreren 360-Grad-Bildern mit unterschiedlicher Belichtung zu erstellen
* &lbrack;Umgebungslicht&rbrack; Wählen Sie in der Vorlage für die Umgebungsbeleuchtung die Option &quot;Als Bitmap verwenden&quot; aus, um Ihre Bilder vor dem Erstellen einer Umgebungsbeleuchtung zu bearbeiten.
* &lbrack;Umgebungslicht&rbrack; Weisen Sie die Umgebungsnutzung in der Bildimportebene zu, um das Bild direkt der Umgebung in der 3D-Ansicht zuzuweisen.
* &lbrack;Umgebungslicht&rbrack; In der 2D-Ansicht für den Umgebungskanal gibt es eine automatische Farbkorrektur, damit das Rendering genauso wie in der 3D-Ansicht angezeigt wird
* &lbrack;Umgebungslicht&rbrack; Neuer dedizierter Content für die Erstellung von Umgebungslicht
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Die Ressourcen- und Filterfelder werden in einem neuen Bedienfeld &quot;Elemente&quot; zusammengeführt
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Das Bedienfeld &quot;Elemente&quot; unterstützt jetzt die folgenden Elementtypen: Materialien, Filter und Bilder
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Auf alle Starter-Assets kann im Abschnitt Starter-Assets zugegriffen werden.
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Der Abschnitt &quot;Starter-Assets&quot; ist schreibgeschützt
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Neuer Bereich &quot;Ihre Assets&quot;
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Der Bereich &quot;Ihre Assets&quot; ist der Bereich, in den Sie alle Ihre Ressourcen importieren können
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Alle Elemente unter &quot;Ihre Elemente&quot; werden einem bestimmten Ordner in Ihren Dokumenten hinzugefügt
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Lokale Ordner im Bedienfeld &quot;Elemente&quot; verbinden, um neue Abschnitte hinzuzufügen
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Die Suche erfolgt im aktuellen Ordner und seinen Unterordnern.
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Mit Breadcrumbs zwischen Ordnern und Unterordnern navigieren
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Aktuellen Ordner nach Material, Filter oder Bild filtern
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Kombiniere mehrere Filter, um nur Materialien und Bilder zu erhalten.
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Ändern der Anzeige durch Umschalten zwischen einem Raster oder einer Liste
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Filter werden durch ihr Symbol dargestellt
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Bilder werden in der Vorschau angezeigt
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Durch Erhöhen der Breite wird das Layout des Bedienfelds mit einer bestimmten Ansicht geändert, um zwischen Ordnern zu navigieren.
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; In nicht schreibgeschützten Bereichen löschen Sie ein Asset, indem Sie es auf das Ablagesymbol ziehen und dort ablegen
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Durch Rechtsklick auf ein Element wird ein Kontextmenü geöffnet
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Greifen Sie über das Kontextmenü mit der rechten Maustaste auf die Asset-Metadaten (Name, Kategorie, Speicherort) zu
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Löschen Sie das Element aus dem Kontextmenü (nur in nicht schreibgeschützten Bereichen verfügbar).
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Durchsuchen Sie das Element über das Kontextmenü in Adobe Bridge
* &lbrack;Ebenenbedienfeld&rbrack; Neues Symbol, um ein Basismaterial direkt über Ihren Ebenen hinzuzufügen
* &lbrack;Ebenenbedienfeld&rbrack; Tastaturbefehl: Mit Umschalt+B wird ein Basismaterial über den Ebenen hinzugefügt.
* &lbrack;Ebenenbedienfeld&rbrack; Ebenen verfügen jetzt über eine Miniaturvorschau (Material-Miniaturansicht, Filtersymbol oder Bildvorschau)
* &blbrack;Eigenschaftenbedienfeld&rbrack; Neues Design für den Titel des Bedienfelds &quot;Eigenschaften&quot; mit dem Elementnamen und der Miniaturansicht des Elements
* &blbrack;Eigenschaftenbedienfeld&rbrack; Filterebenen unterstützen jetzt Vorgaben
* &blbrack;Eigenschaftenbedienfeld&rbrack; Mache einen Rechtsklick bzw. Ctrl-Klick auf die Vorschau, um das Bild in Photoshop zu bearbeiten.
* &lbrack;Adobe Bridge&rbrack; Durchsuchen Sie Ihr Asset in Adobe Bridge und starten Sie Bridge am Speicherort des Assets.
* &lbrack;Adobe Photoshop&rbrack; &quot;In Adobe Photoshop bearbeiten&quot; öffnet das Bild in Photoshop und kann bearbeitet werden.
* &lbrack;Adobe Photoshop&rbrack; Bei jedem Speichern in Adobe Photoshop wird das bearbeitete Bild in Sampler neu geladen.
* &lbrack;Substance 3D Designer&rbrack; Von Adobe Substance 3D Designer gesendete Elemente werden direkt im Bereich &quot;Ihre Elemente&quot; des Bedienfelds &quot;Elemente&quot; angezeigt
* &lbrack;Export&rbrack; Elemente direkt an Adobe Substance 3D Painter und Adobe Substance 3D Stager senden
* &lbrack;Export&rbrack; Materialien und Umgebungslichter an Adobe Substance 3D Painter senden
* &lbrack;Export&rbrack; Umgebungslichter an Adobe Substance 3D Stager senden
* &lbrack;Rendering&rbrack; Neue Materialeigenschaften werden jetzt unterstützt und in 3D gerendert
* &lbrack;Rendering&rbrack; Hinzufügen von Unterstützung für Glanz (Glanzfarbe, Deckkraft des Glanzes und Raueit des Glanzes)
* &lbrack;Rendering&rbrack; Hinzufügen von Beschichtungsunterstützung (Beschichtungsfarbe, Beschichtungsrauhigkeit, Beschichtungsnormalität, Beschichtungsfarbe und Specular level-IOR)
* &lbrack;Rendering&rbrack; Hinzufügen von Anisotropie-Unterstützung (Anisotropie und Anisotropie)
* &lbrack;Rendering&rbrack; Hinzufügen von Specular edge color-Unterstützung
* &lbrack;Rendering&rbrack; Aktivieren Sie diese neuen Eigenschaften im Bedienfeld &quot;Kanaleinstellungen&quot;
* &lbrack;Rendering&rbrack; Einführung eines neuen Echtzeit-Engine (2021)-Renderers in der Beta-Version
* &lbrack;Rendering&rbrack; Wechseln zwischen den beiden Renderer-Versionen im Bedienfeld &quot;Anzeigeeinstellungen&quot;
* &lbrack;Rendering&rbrack; Der Renderer der Realtime Engine (2021) unterstützt Eigenschaften für Transparenz, Absorption und Streuung von Material.
* &lbrack;Rendering&rbrack; Der Renderer der Realtime Engine (2021) bietet eine neue Möglichkeit, Schatten aus dem Umgebungslicht zu berechnen.
* &lbrack;Rendering&rbrack; Der Renderer der Realtime Engine (2021) berechnet in Echtzeit die Bestrahlung des Umgebungslichts.
* &blbrack;Bedienfeld für Shader-Einstellungen&rbrack; Neues Bedienfeld mit Shader-Einstellungen zum Anpassen bestimmter Parameter für Material-Shader
* &blbrack;Bedienfeld für Shader-Einstellungen&rbrack; Neue Parameter (Normal-Skala, Height-Skala, Height-Level, Emissionsintensität, IOR, Coat-Normal-Intensität und Coat-IOR)
* &blbrack;Bedienfeld für Shader-Einstellungen&rbrack; Spezifische Parameter für die Realtime Engine 2021 (Subsurface Scattering, Scattering Distance, Red Shift und Rayleigh Scattering)
* &blbrack;Bedienfeld für Shader-Einstellungen&rbrack; Die Einstellungswerte werden pro Element gespeichert.
* &blbrack;Einstellungsbedienfeld der Anzeige&rbrack; Eine Vorschau der standardmäßigen Umgebungslichter wurde hinzugefügt.
* &blbrack;Einstellungsbedienfeld der Anzeige&rbrack; Eine Vorschau der Standardgitter wurde hinzugefügt
* &blbrack;Einstellungsbedienfeld der Anzeige&rbrack; Neuer Parameter für die Umgebungsdeckkraft
* &blbrack;Einstellungsbedienfeld der Anzeige&rbrack; Neuer Parameter für die Umgebungsweichzeichnung (spezifisch für den Renderer &quot;Realtime Engine 2021&quot;)
* &lbrack;Lokalisierung&rbrack; Neue Übersetzungen in Deutsch und Französisch
* &lbrack;Inhalt&rbrack; Neue Standard-Startmaterialien
* &lbrack;Inhalt&rbrack; Neue Standard-Umgebungslichter
* &lbrack;Inhalt&rbrack; Alle Filter wurden aktualisiert, bereinigt und optimiert.
* &lbrack;Inhalt&rbrack; Der Korrekturfilter wurde in mehrere Filter aufgeteilt
* &lbrack;Inhalt&rbrack; Neuer Helligkeits-/Kontrastfilter
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Farbton/Sättigung&quot;
* &lbrack;Inhalt&rbrack; Neuer Dynamikfilter
* &lbrack;Inhalt&rbrack; Neuer Scharfzeichnungsfilter
* &lbrack;Inhalt&rbrack; Neue Normal-/Height-Anpassung
* &lbrack;Inhalt&rbrack; Filter &quot;Neue Fenster&quot;
* &lbrack;Inhalt&rbrack; Neuer Verwisch-Filter
* &lbrack;Inhalt&rbrack; Neuer Webfilter
* &lbrack;Inhalt&rbrack; Neuer Verkrümmungstransformationsfilter
* &lbrack;Inhalt&rbrack; Neuer AO-Filter-Height
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Height zu Normal&quot;
* &lbrack;Inhalt&rbrack; Farbersetzung - Ersetzen in neuen unterstützten Kanälen (Glanz, Beschichtung, Anisotropie,...)
* &lbrack;Inhalt&rbrack; Farbvariation - Manueller Modus, um genau die Farben auszuwählen, die geändert werden sollen
* &lbrack;Inhalt&rbrack; Kachelung - Option zur Visualisierung der Nahtstellen
* &lbrack;Inhalt&rbrack; Kachelung - Option, um die Nähte für eine perfekte Kachelung schneiden
* &lbrack;Inhalt&rbrack; Anpassen - Option, um ein Material hinzuzufügen, das seiner Farbe und seiner Raueit entspricht
* &lbrack;Inhalt&rbrack; Anpassen - funktioniert jetzt für Bilder, die der Farbe eines anderen Bildes entsprechen
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Farbtemperaturfilter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Belichtungsfilter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Belichtungsvorschaufilter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Nadir Patch-Filter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Nadir Extract-Filter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neue Lichtfilter (Kugel, Linie, Form, Ebene)
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Panorama-Ausbesserungsfilter
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer Filter &quot;Horizont begradigen&quot;
* &lbrack;Inhalt&rbrack; Umgebungslicht - Neuer HDR-Mergefilter

**Bekannte Probleme:**

* &lbrack;Realtime Engine 2021&rbrack; Ändern des Layouts, Absturz der Anwendung
* &lbrack;Realtime Engine 2021&rbrack; Starke Berechnung, Absturz der Anwendung
* &blbrack;Panels&blbrack; MacOS - Nicht angedockte Bedienfelder befinden sich vor allen Anwendungen
* &lbrack;Widgets&rbrack; Die Widgets &quot;Transformieren&quot; und &quot;Positionen&quot; können verschwinden. Blende die Ebenen ein- und aus, um sie sichtbar zu machen.
* &lbrack;Export&rbrack; SBSAR-Export einer Umgebungsbeleuchtung verliert die 32-Bittiefen-Genauigkeit
* &blbrack;Bedienfeld &quot;Elemente&quot;&blbrack; Elemente können beim Öffnen eines Ordners hervorgehoben werden.
* &blbrack;Eigenschaftenbedienfeld&rbrack; Durch das Zurücksetzen der Parameter wird die Benutzeroberfläche des Kombinationsfelds nicht zurückgesetzt
* &lbrack;Lokalisierung&rbrack; Das Ändern der Sprache wirkt sich nicht auf das Projektfenster aus, bis es neu erstellt wurde

## Version 2

### 2.3.2 (2020.3.2) Vermicelli

*(Freigegeben: 23. Februar 2021)*

**Hinzugefügt:**

* &lbrack;Lokalisierung&rbrack; Unterstützung für Japanisch

**Fest:**

* &lbrack;Layers&rbrack; Beim Verändern eines Materials im Stickfilter geht das Stickbild verloren

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.3.1 (2020.3.1) Vermicelli

*(Freigegeben: 17. Dezember 2020)*

**Hinzugefügt:**

* &lbrack;Motor&rbrack; Substance Engine-Update
* &lbrack;Anwendung&rbrack; Umgebungsvariable zum Deaktivieren bestimmter Funktionen
* &lbrack;Inhalt&rbrack; Farbe ersetzen - Neue erweiterte Segmentierungsoption
* &lbrack;Inhalt&rbrack; Bodenfliesen - neue Muster und Optionen verfügbar
* &lbrack;Inhalt&rbrack; Stickerei - Komplette Revamp des Filters
* &lbrack;Inhalt&rbrack; Anpassung - Neuer metallischer Parameter + opazitätssichere Transformationskorrektur

**Fest:**

* &lbrack;Layers&rbrack; Doppelter Import eines benutzerdefinierten Filters nicht möglich
* &lbrack;Layers&rbrack; Bildeingabe mit dem Pinselwerkzeug kann nicht verwendet werden
* &lbrack;Export&rbrack; Exportieren Sie .jpg anstelle von .jpeg
* &lbrack;UI&rbrack; Bildnachweise für den Begrüßungsbildschirm aktualisieren
* &lbrack;UI&rbrack; Unsichtbare Trennlinie in Menüs reparieren
* &lbrack;UI&rbrack; Optionsfelder zeigen eine QuickInfo an, wenn sie abgeschnitten werden
* &lbrack;UI&rbrack; Typo: Starter-Materialien
* &lbrack;Anwendung&rbrack; UTF-8-Zeichen in Elementnamen funktionieren nicht
* &lbrack;Lokalisierung&rbrack; Kursiven Schriftstil für chinesisches Gebietsschema deaktivieren
* &lbrack;Lokalisierung&rbrack; Lokalisierte Zeichenfolge, in zwei Zeilen aufgeteilt
* &lbrack;Lokalisierung&rbrack; Ändern des Ordnernamens und Ersetzen durch Auslassungspunkte, wenn der Ordner zu lang ist
* &lbrack;Lokalisierung&rbrack; Formatieren von Zahlen mit Tausendertrennzeichen
* &lbrack;Lokalisierung&rbrack; Lokalisieren der Datums- und Zeitanzeige
* &lbrack;Lokalisierung&rbrack; Lokalisieren des Farbwählers unter Windows
* &lbrack;Inhalt&rbrack; Transformieren - Bei aktivierter sicherer Transformation dreht sich die Normale alle 45° korrekt.
* &lbrack;Inhalt&rbrack; Surface Relief - Beheben Sie Kachelprobleme mit dem fraktalen Perlin-Rauschen (erweitertes Rauschen)
* &lbrack;Inhalt&rbrack; Brickwall-Muster - Height-Eingabe in 16-Bit
* &lbrack;Inhalt&rbrack; Materialsymbol-Render - Problem mit Specular-Reflexionen
* &lbrack;Inhalt&rbrack; Farbvariation - Keine Farbverschiebung zwischen Farbeingaben und dem Ergebnis
* &lbrack;Inhalt&rbrack; Farbvariation - Leistungsaktualisierung

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.3.0 (2020.3.0) Vermicelli

*(Freigegeben: 26. Oktober 2020)*

**Hinzugefügt:**

* &lbrack;Bild zu Material&rbrack; Unterstützung für die NVIDIA RTX 3000-Serie
* &lbrack;Bild zu Material&rbrack; Neue Parameter zur Steuerung der Geometriedetails
* &lbrack;Bild zu Material&rbrack; Neue Parameter zur Steuerung der Raueit
* &lbrack;Bild zu Material&rbrack; Neue Parameter zur Steuerung der Begeisterungsintensität
* &Klammer;Miniaturen&Klammer; Neuer Miniaturbildgenerator basierend auf dem PBR-Renderer des Substance Designers
* &Klammer;Miniaturen&Klammer; Basismaterialien und Atlanten aktualisieren, um ihre Miniaturansicht einzubetten
* &Klammer;Miniaturen&Klammer; Abrufen der Miniaturansicht aus der .sbsar-Datei, sofern vorhanden
* &Klammer;Miniaturen&Klammer; Ändern der Miniaturansichtsqualität in den Voreinstellungen
* &lbrack;Motor&rbrack; Aktualisiert auf Substance Engine 8
* &lbrack;Lokalisierung&rbrack; Chinesische Lokalisierung
* &lbrack;UI&rbrack; Experimenteller Volltonfarbenwähler
* &lbrack;Inhalt&rbrack; Neue Umgebungskarte - Studio 06
* &lbrack;Inhalt&rbrack; Filter &quot;Atlas-Generator hinzufügen&quot;
* &lbrack;Inhalt&rbrack; Filter &quot;Atlas Splitter hinzufügen&quot;
* &lbrack;Inhalt&rbrack; Filter &quot;Verworfene Gummen&quot; hinzufügen
* &lbrack;Inhalt&rbrack; Fingerabdruckfilter hinzufügen
* &lbrack;Inhalt&rbrack; Filter &quot;Scratches hinzufügen
* &lbrack;Inhalt&rbrack; Surface Relief-Filter hinzufügen (Height-Modulationsfilter ersetzen)
* &lbrack;Inhalt&rbrack; Verkrümmungsfilter hinzufügen
* &lbrack;Inhalt&rbrack; Filter &quot;Umkehren&quot; hinzufügen
* &lbrack;Inhalt&rbrack; Filter &quot;Färben&quot; hinzufügen
* &lbrack;Inhalt&rbrack; Filter &quot;Ersetzen-Farbe&quot; hinzufügen
* &lbrack;Inhalt&rbrack; Transformieren - Fügen Sie die Möglichkeit hinzu, die Transformation für einen bestimmten Kanal zu deaktivieren.
* &lbrack;Inhalt&rbrack; Transformieren - Drehung hinzufügen, wenn die sichere Transformation aktiviert ist
* &lbrack;Inhalt&rbrack; Farbvariation - Fügen Sie eine Segmentierungsoption hinzu, um auszuwählen, wie die Farben verteilt werden sollen

**Fest:**

* &lbrack;Layers&rbrack; Richtige Aktualisierung der Benutzeroberfläche bei mehreren Aktionen zum Rückgängigmachen/Wiederholen
* &lbrack;Layers&rbrack; Abstürze bei mehreren Aktionen zum Rückgängigmachen/Wiederholen verhindern
* &lbrack;Layers&rbrack; Absturz bei Verwendung von Bild zu Material (KI-gestützt) mit folgendem Protokoll: ungültige Geräteordinale
* &lbrack;Filter&rbrack; Verbessern der NVIDIA-Grafikkartenerkennung für NVIDIA-spezifische Funktionen
* &lbrack;Anwendung&rbrack; Absturz beim Schließen der Anwendung
* &lbrack;Anwendung&rbrack; Beheben der VRAM-Betragserkennung auf dem MacOS
* &lbrack;Export&rbrack; Einige Exportvorgaben fehlen manchmal
* &lbrack;Inhalt&rbrack; Ölfarbeneffekt - Korrigieren des Height-Bereichs mit hoher Versatz-Amplitude
* &lbrack;Inhalt&rbrack; Make It Tile Advanced - Keine ausgewaschene Grundfarbe beim Export
* &lbrack;Inhalt&rbrack; Make It Tile Advanced - Weiße Maske auf der Grundfarbe, wenn der AO zu stark ist
* &lbrack;Inhalt&rbrack; Anpassung - Es funktioniert jetzt auf Bildern (scan1, ...)

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.2.1 (2020.2.1) Udon

*(Freigegeben: 21. Juli 2020)*

**Hinzugefügt:**

* &lbrack;Layers&rbrack; In App-Fehlermeldung, wenn Bild zu Material (KI-gestützt) nicht genügend Arbeitsspeicher hat

**Fest:**

* &lbrack;Layers&rbrack; &quot;Bild zu Material&quot; (KI-gestützt) funktioniert nicht mit Specular-/Glossiness-Workflows
* &lbrack;Layers&rbrack; Abstürze, wenn kein Videospeicher mehr vorhanden ist, während Bild zu Material verwendet wird (KI-gestützt)
* &lbrack;Layers&rbrack; Disk-Cache wird nicht für die Anzeige beim Öffnen eines Stapels verwendet
* &lbrack;Layers&rbrack; Erkennung von NVIDIA RTX 8000
* &lbrack;Layers&rbrack; Manchmal ist es unmöglich, eine Ebene außerhalb einer Splatter-Eingabe zu verschieben
* &lbrack;Layers&rbrack; Beim Einfügen eines Stapels in einen Stapel wird der Disk-Cache nicht verwendet
* &lbrack;Layers&rbrack; Einige Kanalnutzung werden berechnet, obwohl sie nicht verwendet werden.
* &lbrack;Layers&rbrack; Beim Importieren von Bildern werden manchmal leere Ausgaben erstellt
* &lbrack;2D Ansicht&rbrack; Wechseln zu einer anderen Ebene mit aktiviertem Zeichnungsmodus blockiert Schwenken und Zoomen
* &lbrack;Inhalt&rbrack; Snow - 8-Bit-Problem auf der Normalkarte
* &lbrack;Inhalt&rbrack; Pflasterbild - 8-Bit-Problem auf der normalen Karte
* &lbrack;Inhalt&rbrack; Equalizer - 8-Bit-Problem auf der normalen Karte
* &lbrack;Inhalt&rbrack; Kiesgenerator - 8-Bit-Problem auf der normalen Karte
* &lbrack;Inhalt&rbrack; Bodenfliesen - Handle-Deckkraft und Specular level
* &lbrack;Inhalt&rbrack; Mischzyklen je Exportvorgabe - Normalmap umkehren
* &lbrack;Inhalt&rbrack; Korrigieren von Problemen mit riesigen Bildern von Bild zu Material (KI-gestützt)
* &lbrack;Anwendung&rbrack; Absturz bei Auswahl von &quot;Sichern und neu starten&quot; bei Datenbankfehler
* &lbrack;Anwendung&rbrack; Absturz beim schnellen Klicken auf dasselbe Asset
* &lbrack;Anwendung&rbrack; Seltene Abstürze beim Beenden
* &lbrack;Anwendung&rbrack; Absturz beim Ablegen von Dateien auf dem Startbildschirm
* &lbrack;Anwendung&rbrack; Absturz, wenn eine beschädigte Umgebungsdatei geladen wird
* &lbrack;Anwendung&rbrack; Seltener Absturz beim schnellen Wechseln des gerenderten Assets
* &lbrack;Anwendung&rbrack; Einfrieren beim Beenden während der Datenverarbeitung eines Assets
* &lbrack;Anwendung&rbrack; Seltener Absturz beim Start auf macOS
* &lbrack;Anwendung&rbrack; Deadlock beim Schließen der Anwendung kurz nach dem Start
* &lbrack;Rendering&rbrack; 3D-Ansicht flackert manchmal
* &lbrack;UI&rbrack; Farbwähler und Widgets für Zufallsverteilung werden nicht an den restlichen Anpassungen ausgerichtet
* &lbrack;Rendering&rbrack; Falsche Berechnungszeit angezeigt
* &lbrack;Export&rbrack; Einige Exportvorgaben fehlen manchmal

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.2.0 (2020.2.0) Udon

*(Freigegeben: 15. Juni 2020)*

**Hinzugefügt:**

* &lbrack;Erstellen&rbrack; Neuer Filter &quot;Bild zu Material&quot; (KI-gestützt) für Windows und Linux verfügbar
* &lbrack;Erstellen&rbrack; Bitmap zu Material in Bild zu Material umbenennen (B2M)
* &lbrack;Bildimport&rbrack; Popupmenü &quot;Neue Materialerstellungsvorlage&quot;
* &lbrack;Bildimport&rbrack; Neue Option &quot;Basismaterial hinzufügen&quot;
* &lbrack;Bildimport&rbrack; Möglichkeit, zusätzliche Bilder per Drag &amp; Drop in die Vorlage zur Materialerstellung zu ziehen
* &lbrack;Bildimport&rbrack; Bilder in der Materialerstellungsvorlage entfernen können
* &lbrack;Bildimport&rbrack; Zuweisen von Kanälen zu importierten Bitmaps automatisch anhand ihres Dateinamens
* &lbrack;Bildimport&rbrack; In der Lage sein, Normalmaps umzukehren
* &lbrack;2D Ansicht&rbrack; Einführung des Malmodus
* &lbrack;2D Ansicht&rbrack; Die Malkacheln
* &lbrack;2D Ansicht&rbrack; Festlegen eines Graustufenwerts für die Pinselfarbe
* &lbrack;2D Ansicht&rbrack; Schwenken und Zoomen beim Malen
* &lbrack;2D Ansicht&rbrack; X-Verknüpfung zum Umkehren des Graustufenwerts des Pinsels
* &lbrack;2D Ansicht&rbrack; &lbrack; und &rbrack; Tastaturbefehle zum Ändern der Pinselgröße
* &lbrack;2D Ansicht&rbrack; Strg (bzw. Befehl) + Mausrad zum Ändern der Pinselgröße
* &lbrack;2D Ansicht&rbrack; Es ist jetzt möglich, die Quellposition bei Verwendung des Kopierpatches zu ändern
* &lbrack;Layers&rbrack; Umschalttaste + Ziehen und Ablegen, um Atlanten mit automatischer Streuung zu erstellen
* &lbrack;Layers&rbrack; Alt + Drag &amp; Drop fügt ein Material als Aufkleber ein
* &lbrack;Layers&rbrack; Transformationsmatrizen aus dem Substance Designer leicht zugänglich machen
* &lbrack;Layers&rbrack; Beim Ablegen von Texturen in einem nicht leeren Stapel werden die richtigen Kanäle automatisch zugewiesen.
* &lbrack;Layers&rbrack; Neuer Ebenentyp: Zusammengesetzte Filter
* &lbrack;Parameter&rbrack; Unterstützung von Substance-Zeichenfolgeneingaben
* &lbrack;UI&rbrack; Hinzufügen von Schlagschatten für Popups und Menüs
* &lbrack;UI&rbrack; Neues Farb-Widget mit Rechtsklick-Optionen (Löschen, Kopieren, Einfügen)
* &lbrack;UI&rbrack; Neue Bild-Widget mit Malwerkzeug-Option
* &lbrack;UI&rbrack; In einem Bild-Widget über ein importiertes Bild malen können
* &lbrack;Rendering&rbrack; Neue Standardkameraposition
* &lbrack;Export&rbrack; Substance-Dateien werden für Substance Designer 2020.1.2 (10.1.2) exportiert
* &lbrack;Performance&rbrack; Verbesserte Startzeit der Anwendung
* &lbrack;Performance&rbrack; Verbessern der Handhabung asynchroner Aufgaben
* &lbrack;Performance&rbrack; Verbessern der Leistung von Ebenenstapeln beim Hinzufügen, Entfernen oder Verschieben von Ebenen
* &lbrack;Performance&rbrack; &quot;Bild zu Material&quot; (KI-gestützt) läuft auf RTX-GPUs schneller
* &lbrack;Inhalt&rbrack; Neue Gitter: Weibliches T-Shirt, Männliches T-Shirt, Schuh
* &lbrack;Inhalt&rbrack; Neuer Mischmodus - Pro Kanal mischen
* &lbrack;Inhalt&rbrack; Korrektur des Heights der Deckkraftüberblendung mit zwei neuen Parametern (Height-Position und Height-Skala)
* &lbrack;Inhalt&rbrack; Heights im Mischmodus &quot;Heights&quot; anpassen.
* &lbrack;Inhalt&rbrack; Option &quot;Height-Informationen&quot; in der benutzerdefinierten Maskenüberblendung verwenden
* &lbrack;Inhalt&rbrack; Neues Perspektivkorrektur-Werkzeug
* &lbrack;Inhalt&rbrack; Mustergenerator - Fügen Sie einen Parameter hinzu, um das Muster umzukehren
* &lbrack;Inhalt&rbrack; Mustergenerator - Neuen Parameter hinzufügen Materialdetails überschreiben
* &lbrack;Inhalt&rbrack; Neuer Aufkleberfilter
* &lbrack;Inhalt&rbrack; Neuer Moosfilter
* &lbrack;Inhalt&rbrack; Filter &quot;Neue Risse&quot;
* &lbrack;Inhalt&rbrack; Neuer PBR-Validierung-Filter
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Bodenfliesen&quot;
* &lbrack;Inhalt&rbrack; Neuer Quilt Stich-Filter
* &lbrack;Inhalt&rbrack; Atlas Scatter - Benutzerdefinierte Maskeneingabe hinzufügen, um Maloption zu aktivieren
* &lbrack;Inhalt&rbrack; Dirt - Benutzerdefinierte Maskeneingabe hinzufügen, um Maloption zu aktivieren
* &lbrack;Inhalt&rbrack; CLO-Exportvorgabe
* &lbrack;Inhalt&rbrack; VSpitcher-Exportvorgabe
* &lbrack;Inhalt&rbrack; Unity HDRP-Vorgaben exportieren ein detailMap

**Fest:**

* &lbrack;Layers&rbrack; Importierte Bilder werden zu oft geladen
* &lbrack;Layers&rbrack; Absturz beim Erstellen eines Klonpatches am unteren Rand des Stapels
* &lbrack;Layers&rbrack; Durch Hinzufügen eines Materials am unteren Rand des Stapels wird es instabil
* &lbrack;Layers&rbrack; Filter nach Bildimport funktioniert nicht ordnungsgemäß
* &lbrack;Layers&rbrack; Der Wert workflow_type wird nicht aktualisiert, wenn der Workflow zwischen Projekten mit einem benutzerdefinierten Filter gewechselt wird.
* &lbrack;Layers&rbrack; Schaltfläche &quot;Ebene entfernen&quot; deaktivieren, wenn keine Ebene ausgewählt ist
* &lbrack;Layers&rbrack; Absturz beim Laden eines Assets, das einen Klonpatch enthält
* &lbrack;Layers&rbrack; Abstürze des Filters &quot;Normal zu Height&quot; auf MacOS
* &lbrack;Anwendung&rbrack; Absturz beim Laden von Umgebungskarten
* &lbrack;Anwendung&rbrack; Leistungsprobleme, wenn ein Grafiktabletttreiber installiert ist
* &lbrack;Anwendung&rbrack; Import von EXR 32-Bit-Dateien ist schwarz
* &lbrack;Anwendung&rbrack; Abstürze beim Laden und Entladen von Elementen
* &lbrack;Anwendung&rbrack; Absturz beim Wechsel von &quot;Durchsuchen&quot; zum Erstellen
* &lbrack;Anwendung&rbrack; Zielsammlung beim Speichern eines Materials, das nicht aus dem aktuellen Projekt stammt
* &lbrack;Anwendung&rbrack; Backup und Neustart beheben
* &lbrack;Bildimport&rbrack; Graustufenbilder richtig importieren
* &lbrack;Inhalt&rbrack; Neue Filter für die Handhabung neuer Matrizen
* &lbrack;Inhalt&rbrack; Importierte benutzerdefinierte Filter werden in der Schnellzugriffsleiste angezeigt
* &lbrack;Inhalt&rbrack; Farbverschiebung mit dem erweiterten Filter &quot;Make it tile&quot; korrigieren
* &lbrack;Performance&rbrack; Das Öffnen eines Farbdialogs ist langsam und berechnet die aktuelle Ebene neu
* &lbrack;UI&rbrack; Tastaturbefehle funktionieren manchmal nicht
* &lbrack;2D Ansicht&rbrack; Inhaltsbasierte Füllung erfordert einen nutzlosen ersten Klick
* &lbrack;Resources&rbrack; Ordner auf lokalen Datenträgern werden nach dem Entfernen immer noch auf Updates überwacht
* &lbrack;Resources&rbrack; Wenn Sie einen verknüpften Ordner aus dem Dateisystem löschen, wird er nicht entfernt
* &lbrack;Export&rbrack; Benutzerdefinierte Verwendungen in benutzerdefinierten Exportvorgaben werden nicht exportiert
* &lbrack;Export&rbrack; Fehler beim Exportieren der .sbsar-Datei mit Sonderzeichen im Pfad

**Bekannte Probleme:**

* Wiederholte Neuberechnungen von Bild zu Material (KI-gestützt) können einen Absturz auslösen (nicht genügend Arbeitsspeicher).
* Wiederholte Neuberechnungen des Delighters können einen Absturz auslösen (nicht genügend Arbeitsspeicher).
* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Die Verwendung von Bild zu Material (KI aktiviert) auf GPU mit wenig VRAM kann einen Absturz auslösen (nicht genügend Arbeitsspeicher).
* &quot;Bild zu Material&quot; (KI-gestützt) ist nicht für PBR-Specular/Glanz verfügbar.
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.1.1 (2020.1.1) Tiramisu

*(Freigegeben: 1. April 2020)*

**Hinzugefügt:**

* &lbrack;Projekt&rbrack; Metadaten exportieren und importieren
* &lbrack;Anwendung&rbrack; Strg+S speichert jetzt eine Vorgabe in Entdecken
* &lbrack;Performance&rbrack; Verwenden Sie Render-Cache, anstatt gespeicherte Materialien für Auflösungen von bis zu 2k neu zu berechnen

**Fest:**

* &lbrack;UI&rbrack; Anzeige für feste Datenverarbeitung im Darstellungsfenster
* &lbrack;UI&rbrack; Die Eingabe negativer Werte in Regler ist fest
* &lbrack;UI&rbrack; Kombinationsfelder: Die Tastaturpfeile und die Bildlaufleiste funktionieren jetzt
* &lbrack;UI&rbrack; Beibehalten des ausgewählten Kanals beim Wechsel zwischen &quot;Materialausgabe&quot; und &quot;Ebeneneingabe&quot; in der 2D-Ansicht
* &lbrack;Layers&rbrack; Absturz beim Hinzufügen benutzerdefinierter Kanäle im Basismaterial behoben
* &lbrack;Layers&rbrack; Absturz beim Bearbeiten von Ebenen
* &lbrack;Layers&rbrack; Benutzerdefinierte Kanäle werden nicht mit einem gespeicherten Material angezeigt
* &lbrack;Anwendung&rbrack; Seltene Abstürze beim Importieren eines Assets behoben
* &lbrack;Anwendung&rbrack; Absturz beim Beenden
* &lbrack;Anwendung&rbrack; Kombinationsfelder zeigen jetzt beim Wechseln von Vorgaben richtige Werte an
* &lbrack;Export&rbrack; Enscape-Voreinstellung in Enscape Revit umbenannt
* &lbrack;Export&rbrack; Importieren einer Exportvorgabe nach dem Entfernen funktioniert
* &lbrack;Export&rbrack; Absturz beim Export
* &lbrack;Rendering&rbrack; Rendering behoben, wenn die Grundfarbe im 16-Bit-Halbschwebformat ist
* &lbrack;Projekt&rbrack; Absturz beim Importieren eines beschädigten Pakets nicht
* &lbrack;Projekt&rbrack; Handle-Migration von 2019.1.4 zu 2.x.x, wenn Create noch nie geöffnet wurde
* &lbrack;Projekt&rbrack; Beheben eines Absturzes beim zweimaligen Importieren desselben Projekts
* &lbrack;Projekt&rbrack; Absturz beim Importieren von Projekten beheben
* &lbrack;Resources&rbrack; In früheren Versionen importierte benutzerdefinierte Filter funktionieren
* &lbrack;Resources&rbrack; Materialien mit demselben Namen löschen sich nicht mehr gegenseitig
* &lbrack;Resources&rbrack; Absturz beim Verknüpfen eines lokalen Ordners
* &lbrack;Resources&rbrack; Vom Benutzer erstellte Ordner für Starter-Materialien werden nach einem Neustart nicht mehr entfernt
* &lbrack;Inspire&rbrack; Korrektur des Material-/Sammlungs-Ablagebereichs und Hinzufügen einer Warnmeldung, wenn ein nicht gespeichertes Material verwendet wird

**Bekannte Probleme:**

* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

### 2.1.0 (2020.1.0) Tiramisu

*(Freigegeben: 12. März 2020)*

**Hinzugefügt:**

* &lbrack;Export&rbrack; Exportiere eine vordefinierte Auswahl an Vorlagen, um deine Strukturen für Renderer und Game-Engines zu verpacken
* &lbrack;Export&rbrack; Vorgabe in Unreal Engine 4 exportieren
* &lbrack;Export&rbrack; Vorgabe in Unity Standard exportieren
* &lbrack;Export&rbrack; Vorgabe in Unity HDRP exportieren
* &lbrack;Export&rbrack; Vorgabe in Mischzyklen/Gleichmäßig exportieren
* &lbrack;Export&rbrack; Vorgabe nach Arnold 5 exportieren
* &lbrack;Export&rbrack; Vorgabe in Corona Renderer exportieren
* &lbrack;Export&rbrack; Vorgabe in Enscape exportieren
* &lbrack;Export&rbrack; Vorgabe in Keyshot 9 exportieren
* &lbrack;Export&rbrack; Vorgabe in Redshift exportieren
* &lbrack;Export&rbrack; Vorgabe in &quot;Nächste variieren&quot; exportieren
* &lbrack;Export&rbrack; Vorgabe in Lens Studio exportieren
* &lbrack;Export&rbrack; Vorgaben in Spark AR Studio exportieren
* &lbrack;Export&rbrack; Exportieren einer Vorgabe in PBR Specular Glossiness von PBR Metallic Roughness
* &lbrack;Export&rbrack; Neue Export-Benutzeroberfläche
* &lbrack;Export&rbrack; Exporteinstellungen speichern
* &lbrack;Export&rbrack; Benutzerdefinierte Exportvorgaben importieren und verwalten
* &lbrack;Export&rbrack; Löschen und Ersetzen Ihrer benutzerdefinierten Exportvorgaben
* &lbrack;Export&rbrack; Benutzerdefinierte Exportvorgaben umbenennen
* &lbrack;Export&rbrack; Legen Sie die Standardexportauflösung auf die aktuelle Auflösung fest.
* &lbrack;Export&rbrack; Fügen Sie die Option zum Erstellen eines Unterordners zum Exportspeicherort hinzu
* &lbrack;Export&rbrack; Warnmeldung vor dem Ersetzen vorhandener Dateien
* &lbrack;Anwendung&rbrack; Neues Versionsnummerierungsschema
* &lbrack;Anwendung&rbrack; Öffnen Sie &quot;Beim Start erstellen&quot; und ändern Sie die Laborreihenfolge
* &lbrack;Begrüßungsbildschirm&rbrack; Neues Willkommensbanner
* &lbrack;Projekt&rbrack; Letztes Projekt beim Start öffnen
* &lbrack;UI&rbrack; Neuer Kombinationsfeldstil
* &lbrack;2D-Ansicht&rbrack; F-Verknüpfung zum Fokus in der 2D-Ansicht
* &lbrack;Filter&rbrack; Neue Unterstützung für das alchemist::parameterVisibility-Tag in Substance-Diagrammen
* &lbrack;Filter&rbrack; Globale Anpassung der Parametersichtbarkeit auf Basis Ihres Workflows
* &lbrack;Resources&rbrack; Neue Befehlszeilenoption zum Einrichten von Ressourcen und verknüpften Ordnern mit einer Konfigurationsdatei
* &lbrack;Versionsprüfung&rbrack; Konfiguration der Versionsprüfung
* &lbrack;Inhalt&rbrack; Neue Startmaterialien
* &lbrack;Inhalt&rbrack; Bitmap zu Material : Fügen Sie die Möglichkeit hinzu, den metallischen Kanal zu definieren (einheitlich, benutzerdefinierter Bildimport, Farbauswahl).
* &lbrack;Inhalt&rbrack; Anpassung: Fügen Sie die Unterstützung des PBR-Workflows für Specular/Glanz hinzu.
* &lbrack;Inhalt&rbrack; Atlas Scatter - Neue Parameter

**Fest:**

* &lbrack;Projekt&rbrack; Absturz beim zweimaligen Importieren desselben Projekts
* &lbrack;Projekt&rbrack; Absturz beim mehrmaligen Importieren und Öffnen von Projekten behoben
* &lbrack;Anwendung&rbrack; Absturz beim Laden eines unbenannten Materials
* &lbrack;Anwendung&rbrack; Erkennen fehlender Dateien beim erneuten Import
* &lbrack;Anwendung&rbrack; Beheben eines zufälligen Absturzes beim Herunterfahren
* &lbrack;Anwendung&rbrack; Seltene Abstürze beim Entladen eines Materials in Create wurden behoben
* &lbrack;Anwendung&rbrack; Zufälliger Absturz bei Verwendung von UI-Steuerelementen behoben
* &lbrack;Anwendung&rbrack; Der Export von Protokolldateien auf den Desktop unter Windows 10 wurde behoben.
* &lbrack;UI&rbrack; Das Exportierenbedienfeld hat die falsche Größe, wenn Sie es in Erstellen öffnen
* &lbrack;UI&rbrack; Projekt mit einem Klick öffnen
* &lbrack;UI&rbrack; Richtiges Festlegen von minimalen und maximalen Schiebereglerwerten
* &lbrack;UI&rbrack; Beschriftung der Kanalnutzung anstelle von IDs anzeigen
* &lbrack;UI&rbrack; Durch Klicken auf ein Material wird das Bedienfeld &quot;Anpassen&quot; immer geöffnet/geschlossen.
* &lbrack;UI&rbrack; Farben von ausgeblendeten Ebenen korrigieren
* &lbrack;UI&rbrack; Verbesserungen an den Begrüßungsbildschirmschaltflächen
* &lbrack;Layers&rbrack; Weniger unnötige Neuberechnungen
* &lbrack;Layers&rbrack; Absturz bei Verwendung des Klonpatches
* &lbrack;Layers&rbrack; Wenn Sie eine Bildimportebene auswählen, wird kein Computer mehr ausgelöst.
* &lbrack;Layers&rbrack; Ebenen &quot;Klonen&quot; und &quot;Inhaltsbasierte Füllung&quot; werden bei Auswahl nicht mehr neu berechnet
* &lbrack;Kanaleinstellungen&rbrack; Das Aktivieren oder Deaktivieren von Verwendungen löst jetzt ein Rendering aus
* &lbrack;Resources&rbrack; Einfrieren verhindern, wenn Sie auf einen Stapel in der Bibliothek massenhaft klicken
* &lbrack;Resources&rbrack; Leistungseinbußen beim erneuten Hinzufügen eines zuvor hinzugefügten verknüpften Ordners
* &lbrack;Resources&rbrack; Absturz beim Versuch, eine gelöschte .sbsar-Datei zu öffnen, behoben
* &lbrack;Performance&rbrack; Vermeiden Sie das Laden von Materialien, um auf deren Parameter zuzugreifen
* &lbrack;Performance&rbrack; Sichern von Assets nur bei Verwendung in einem Projekt oder in einem erstellten Material
* &lbrack;Export&rbrack; Fixierte Materialien in der Exportwarteschlange werden manchmal übersprungen oder mit falschen Parametern exportiert
* &lbrack;2D Ansicht&rbrack; Schwenken und Zoomen wiederhergestellt
* &lbrack;Inhalt&rbrack; Das Parkettmuster berücksichtigt den Umgebungskanal für die Verdeckung.
* &lbrack;Inhalt&rbrack; Malen - Maskeneingabe anzeigen, wenn benutzerdefinierte Maske aktiviert wird
* &lbrack;Inhalt&rbrack; Stonewall-Muster - Entfernen Sie mögliche Streifeneffekte in der normalen Karte
* &lbrack;Inhalt&rbrack; Height Modulation - Korrigieren Sie doppelte Grundfarbeinträge in der 2D-Ansicht

**Bekannte Probleme:**

* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

## Version 1

### 1.1.4 (2019.1.4) Sesam

*(Freigegeben: 30. Januar 2020)*

**Hinzugefügt:**

* &lbrack;Resources&rbrack; Bestätigungsaufforderung beim Löschen eines Ressourcenordners

**Fest:**

* &lbrack;Layers&rbrack; Ebenen unter oder über zwei oder mehr Ebenen verschieben
* &lbrack;Erstellen&rbrack; Zuweisung eines ausreichenden VRAM-Budgets für eine gute Leistung

**Bekannte Probleme:**

* Substance Alchemist kann durch den Import vieler Ressourcen verlangsamt werden
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 1.1.3 (2019.1.3) Sesam

*(Freigegeben: 28. Januar 2020)*

**Hinzugefügt:**

* &lbrack;Workflow&rbrack; Unterstützung mehrerer Arbeitsabläufe
* &lbrack;Workflow&rbrack; Unterstützung des PBR Specular Glossiness-Workflows
* &lbrack;Workflow&rbrack; Neues Bedienfeld &quot;Kanaleinstellungen&quot;
* &lbrack;Workflow&rbrack; Arbeitsablaufauswahl bei der Projekterstellung
* &lbrack;Kanaleinstellungen&rbrack; Bestimmte Kanalberechnung aktivieren/deaktivieren
* &lbrack;Kanaleinstellungen&rbrack; Liste der im aktuellen Material verfügbaren benutzerdefinierten Kanäle anzeigen
* &lbrack;Kanaleinstellungen&rbrack; Automatische Berechnung benutzerdefinierter Kanäle, falls erforderlich
* &lbrack;Kanaleinstellungen&rbrack; Berechnung benutzerdefinierter Kanäle erzwingen/blockieren
* &lbrack;Layers&rbrack; Neue Benutzeroberfläche für Platzhalter für Materialeingabe in den Atlas Scatter- und Farbspritzer-Filtern
* &lbrack;Layers&rbrack; Der Bildeingabeparameter eines Filters kann durch Unterschichten zugeführt werden.
* &lbrack;Layers&rbrack; Eine Benachrichtigung anzeigen, wenn einige Ebenen veraltet sind
* &lbrack;Layers&rbrack; Möglichkeit, über die Benachrichtigung auf die neueste Version veralteter Ebenen zu aktualisieren
* &lbrack;Projekt&rbrack; Neue Metadatenfelder bei der Projekterstellung
* &lbrack;Inspire&rbrack; Generierte Varianten sind projektspezifisch
* &lbrack;2D Ansicht&rbrack; Zwischen den Ebeneneingängen, Ebenenausgängen und den Materialausgängen wechseln
* &lbrack;Begrüßungsbildschirm&rbrack; Option &quot;Importprojekt (.alch) hinzufügen&quot;
* &lbrack;Voreinstellungen&rbrack; Neues Fenster &quot;Voreinstellungen&quot; zum Festlegen des Cachespeicherorts und der Datenschutzeinstellungen für die Analyse
* &lbrack;UI&rbrack; Neue UI-Schaltflächen
* &lbrack;Performance&rbrack; Gesamtverbesserung des Parallelisierungssystems
* &lbrack;Performance&rbrack; Optimierung der Anzahl der Materialrechner
* &lbrack;Motor&rbrack; Substance Engine-Update
* &Klammer;Rahmen&Klammer; Upgrade auf Qt 5.13
* &lbrack;MacOS&rbrack; Globale Verbesserungen der Unterstützung für macOS Catalina
* &lbrack;Inhalt&rbrack; Anpassungsfilter - Normale Intensität und Umkehrparameter

**Fest:**

* &lbrack;Layers&rbrack; Parameter &quot;Bildeingabe&quot; beim Löschen der Ebene aufheben
* &lbrack;Layers&rbrack; Absturz beim Hinzufügen einer Klonpatchebene beheben
* &lbrack;Layers&rbrack; Abstürze beim Mischen von Ebenen, die Materialien in anderen Ebenen stapeln, beheben
* &lbrack;Export&rbrack; Die Kanalauswahl für den Export wird jetzt berücksichtigt
* &lbrack;Resources&rbrack; Absturz beim Navigieren im Bedienfeld &quot;Ressourcen&quot; nicht
* &lbrack;Resources&rbrack; Absturz beim Importieren beschädigter Substance-Dateien beheben
* &lbrack;Resources&rbrack; Verringern der Anzahl von Abstürzen beim Laden großer Ordner
* &Klammer;Miniatur&Klammer; Bei der Berechnung der Miniaturansichten wird die Benutzeroberfläche nicht eingefroren
* &lbrack;Bildimport&rbrack; Einheitlichkeit des in der Anwendung unterstützten Bildtyps
* &lbrack;Vorgabe&rbrack; Speichern Sie die Beschreibung beim Erstellen einer Vorgabe aus einem SBSAR
* &lbrack;Inspire&rbrack; Bild per Drag-and-Drop korrigieren
* &lbrack;Anwendung&rbrack; Abstürze beim Beenden beheben
* &lbrack;Anwendung&rbrack; Abstürze am Ausgang beim Exportieren von Materialien beheben
* &lbrack;UI&rbrack; Korrekturen und Verbesserungen
* &lbrack;UI&rbrack; Temporäres Element in &quot;nicht gespeichertes Material&quot; umbenennen
* &lbrack;Inhalt&rbrack; Globale Aktualisierung und Bereinigung aller Filter

**Bekannte Probleme:**

* Substance Alchemist kann durch den Import vieler Ressourcen verlangsamt werden
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 1.1.2 (2019.1.2) Sesam

*(Freigegeben: 11. Dezember 2019)*

**Hinzugefügt:**

* &lbrack;Layers&rbrack; Optionen zum Speichern und Speichern unter sind über die Benutzeroberfläche in der Symbolleiste &quot;Ebenenstapel&quot; verfügbar.
* &lbrack;Resources&rbrack; Klarere Breadcrumbs im Ressourcenfenster zum Navigieren durch Ordner
* &lbrack;Resources&rbrack; Schaltfläche &quot;Zurück halten&quot; gedrückt, um auf alle oberen Ordner zuzugreifen
* &lbrack;Resources&rbrack; Option &quot;Importierten Materialien neu laden&quot; hinzufügen, um sie auf die neueste Version zu aktualisieren
* &lbrack;Layers&rbrack; Möglichkeit, das Bild in der Bildimportebene zu ändern
* &lbrack;Layers&rbrack; Möglichkeit, ein Bild als Kanal zu definieren (Grundfarbe, Normal, Height,...) in der Bildimportebene
* &lbrack;Inhalt&rbrack; Neuer Atlas Scatter-Filter zur Streuung neuer Atlaselemente aus Substance Source
* &lbrack;Inhalt&rbrack; Neuer Ölfarben-Effektfilter
* &lbrack;Inhalt&rbrack; Neuer Kanalgenerierungsfilter zum Generieren von Height, Verdeckung und Raueit aus Grundfarben- und Normalmaps

**Fest:**

* &lbrack;UI&rbrack; QuickInfos in der Symbolleiste &quot;Ebenenstapel&quot; erneut aktivieren
* &lbrack;UI&rbrack; Problem bei der Eingabe von zwei Dezimalstellen in einem Schiebereglerwert beheben
* &lbrack;Performance&rbrack; Absturz beim schnellen Wechsel zwischen Materialien beheben
* &lbrack;Export&rbrack; Das Wechseln zu einem anderen Material vor dem Ende eines Exports stürzt nicht mehr ab
* &lbrack;Resources&rbrack; Kontextmenü wird über dem Material angezeigt, wenn Sie mit der rechten Maustaste darauf klicken
* &lbrack;Layers&rbrack; Der Link &quot;Klicken Sie hier&quot; funktioniert, wenn der Ebenenstapel leer ist
* &blbrack;Vorgaben&blbrack; Schaltfläche &quot;Speichern entfernen&quot; im Bedienfeld &quot;Anpassen&quot;, wenn es sich um ein auf einem Alchemist erstelltes Material handelt
* &lbrack;Tweak&rbrack; Informationsmeldung, die angezeigt wird, wenn es sich um ein in Alchemist erstelltes Material handelt
* &lbrack;Viewport&rbrack; Der Standardwert der Specular level-Textur wurde auf 0,04 korrigiert.
* &lbrack;Dateimenü&rbrack; Korrigieren und Umbenennen Speichern und Speichern unter
* &lbrack;Motor&rbrack; Aktualisieren Sie die Substance-Engine-Version, um einen Absturz einiger SBSAR-Dateien während des Imports zu vermeiden.
* &lbrack;Inhalt&rbrack; Kachelfilter funktioniert auf dem Umgebungskanal der Verdeckung
* &lbrack;Inhalt&rbrack; Der Freistellungsfilter arbeitet auf dem Kanal für die umgebende Verdeckung
* &lbrack;Inhalt&rbrack; Wasserfilter modifiziert die Verstärkung des Heights map
* &lbrack;Inhalt&rbrack; Korrigieren der Kachelung des oberen Materials im Deckkraft-Mischmodus
* &lbrack;Inhalt&rbrack; Height des oberen Materials wird im Deckkraftmischmodus beibehalten
* &lbrack;Inhalt&rbrack; Es ist möglich, eine benutzerdefinierte Maske, ein benutzerdefiniertes Muster oder eine Skalierungsmaske im Perforationsfilter hinzuzufügen.
* &lbrack;Inhalt&rbrack; Height Modulation-Filter erzwingt Height- und Normalmaps in 16 bit
* &lbrack;Inhalt&rbrack; Korrekturfilter erzwingt Height- und Normalmaps in 16 Bit

**Bekannte Probleme:**

* Substance Alchemist kann durch den Import vieler Ressourcen verlangsamt werden
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 1.1.1 (2019.1.1) Sesam

*(Freigegeben: 26. November 2019)*

**Hinzugefügt:**

* &lbrack;Angleichen&rbrack; Neue Füllmethode für Deckkraft
* &lbrack;Motor&rbrack; Neue Substance Engine-Version

**Fest:**

* &lbrack;Layers&rbrack; Beheben von Abstürzen beim Löschen einer Ebene, die noch berechnet wird
* &lbrack;Layers&rbrack; Absturz beim Entfernen der unteren Ebene beheben
* &lbrack;Layers&rbrack; Absturz beheben, während der Materialname Sonderzeichen enthält
* &lbrack;Layers&rbrack; Berechnung aller Filter, die ein Widget verwenden, beenden
* &lbrack;Layers&rbrack; Vermeiden Sie Abstürze bei der Verwendung von Kopierpatch- und inhaltsbasierten Füllfiltern
* &lbrack;Layers&rbrack; Beheben von Abstürzen beim Ziehen und Ablegen eines Filters in einem Splätter-Eingabebereich
* &lbrack;Resources&rbrack; Absturz beim Verknüpfen lokaler Ordner oder Importieren von Ressourcen auf dem Substance Alchemist beheben
* &lbrack;Sammlung&rbrack; Beheben von Abstürzen beim schnellen Wechsel zwischen Materialien
* &lbrack;UI&rbrack; Absturz beheben, während der Wert null ist oder nicht gültig in Untertiteln, Versatz-Schieberegler im Viewport
* &lbrack;Inspire&rbrack; Absturz beim Zugriff auf die Registerkarte &quot;Inspiration&quot; beheben
* &lbrack;Inspire&rbrack; Beheben Sie einen Absturz, während Sie an gerade gespeicherten Ebenen inspirieren.
* &lbrack;Performance&rbrack; Schneller berechnen schwere Substance-Materialien und -Filter (Kacheln)
* &lbrack;Hilfe&rbrack; Exportprotokolldatei korrigieren
* &lbrack;Inhalt&rbrack; Randomizer-Filter funktioniert auf allen Kanälen
* &lbrack;Inhalt&rbrack; Multiangle-Arbeitsablauf berücksichtigt alle Scans
* &lbrack;Inhalt&rbrack; AO Korrekte Füllmethode
* &lbrack;Inhalt&rbrack; Kurvenüberblendung korrigieren.
* &lbrack;Inhalt&rbrack; Farb-ID Füllmethode
* &lbrack;Inhalt&rbrack; Benutzerdefinierte Maskenüberblendung - korrekte Überblendung
* &lbrack;Inhalt&rbrack; Korrekturanpassungsfilter für die Raueitsänderung
* &lbrack;Inhalt&rbrack; Basismaterial-Filter für benutzerdefinierten Upload über normale Kanäle beheben
* &lbrack;Inhalt&rbrack; Benutzerdefiniertes Importmuster des Prägefilters korrigieren

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 1.1.0 (2019.1.0) Sesam

*(Freigegeben: 04. November 2019)*

**Hinzugefügt:**

* &lbrack;Projekt&rbrack; Projekterstellung
* &lbrack;Projekt&rbrack; Einführung des .alch-Dateiformats, das Projektdaten enthält
* &lbrack;Projekt&rbrack; Exportieren eines .alch-Projekts mit den Sammlungen und ihren Materialien
* &lbrack;Projekt&rbrack; Importieren eines .alch-Projekts
* &lbrack;Projekt&rbrack; Öffnen aktueller Projekte
* &lbrack;Begrüßungsbildschirm&rbrack; Ein Begrüßungsbildschirm wird beim Start angezeigt
* &lbrack;Begrüßungsbildschirm&rbrack; Erstellen eines Projekts über den Begrüßungsbildschirm
* &lbrack;Begrüßungsbildschirm&rbrack; Zugriff auf die Liste all Ihrer Projekte auf dem Begrüßungsbildschirm
* &lbrack;Begrüßungsbildschirm&rbrack; Quick-Links zum Zugriff auf die Dokumentation, das Info-Popup und die Lizenzverwaltung
* &lbrack;Dateimenü&rbrack; Integration eines Dateimenüs
* &lbrack;Dateimenü&rbrack; Auf die Projektbefehle über die Registerkarte &quot;Datei&quot; und das Speichern des Ebenenstapels zugreifen
* &lbrack;Dateimenü&rbrack; Auf die Befehle &quot;Rückgängig&quot; und &quot;Wiederholen&quot; auf der Registerkarte &quot;Bearbeiten&quot; zugreifen
* &lbrack;Dateimenü&rbrack; Das vorherige Hilfemenü wurde in das Dateimenü auf der Registerkarte Hilfe verschoben.
* &lbrack;Layers&rbrack; Neue Architektur des Ebenenstapels
* &lbrack;Layers&rbrack; Neue Benutzeroberfläche des Ebenenstapels
* &lbrack;Layers&rbrack; Wählen Sie den Mischmodus direkt in der Symbolleiste aus
* &lbrack;Layers&rbrack; Separater Zugriff auf die Überblendungsparameter und die Materialparameter
* &lbrack;Layers&rbrack; Fügen Sie Materialien direkt in die dedizierten Eingaben des Splatter-Filters im Ebenenstapel hinzu
* &lbrack;Layers&rbrack; Ändern der Scanreihenfolge direkt in der Bildimportebene
* &lbrack;Viewport&rbrack; Steuerung des Kamerafelds
* &lbrack;Viewport&rbrack; Möglichkeit, zwischen orthogonaler oder perspektivischer Kamera zu wechseln
* &lbrack;Viewport&rbrack; Informationen zur Auflösung und Bittiefe für jeden Kanal anzeigen
* &lbrack;Resources&rbrack; Basismaterialien werden standardmäßig geöffnet
* &lbrack;Zwischenspeichern&rbrack; Ordner mit Miniaturansichten im Cache
* &lbrack;Zwischenspeichern&rbrack; Finden Sie Ihren Render-Cache-Ordner
* &blbrack;Panels&blbrack; Das Bedienfeld &quot;Materialeinstellungen&quot; ist vorübergehend ausgeblendet
* &lbrack;Workflow&rbrack; Specular/Glanzgrad vorübergehend deaktiviert
* &lbrack;MacOS&rbrack; Beglaubigung der Catalina OS-Version
* &lbrack;Inhalt&rbrack; Neue Version des Delighter-Filters
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot;
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot;
* &lbrack;Inhalt&rbrack; Der Transformationsfilter verfügt über eine sichere Transformationsoption

**Fest:**

* Alle vorherigen Fehler im Zusammenhang mit Create sind heute mit der neuen Benutzeroberfläche und dem neuen Architekturrelease ungültig.
* QuickInfos blenden die Symbole in der oberen Leiste nicht aus (3D, 2D, 2D/3D)
* &lbrack;Inhalt&rbrack; Splatter-Filter akzeptiert Atlas mit vollständiger Height-Map
* &lbrack;Inhalt&rbrack; Der Transformieren-Filter funktioniert für Bilder (scan1, scan2,...)

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

## Beta

### 0.8.1-beta Quinoa

*(Freigegeben: 19. August 2019)*

**Hinzugefügt:**

* Möglichkeit zum Senden von Substance Source-Assets vom Launcher an die Projekt-Substance Alchemist

**Fest:**

* &lbrack;Erstellen&rbrack; Einige Filter wurden im Schnellzugriff, aber nicht im Filterbereich aufgeführt
* &lbrack;MacOS&rbrack; Einige Abstürze beim Beenden behoben

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen
* Kann beim Beenden auf MacOS immer noch willkürlich abstürzen

### 0.8.0-beta Quinoa

*(Freigegeben: 08. August 2019)*

**Hinzugefügt:**

* &lbrack;Resources&rbrack; Verbinden und Spiegeln Ihrer Materialordner auf Ihren lokalen Festplatten
* &lbrack;Resources&rbrack; Durchsuchen Sie Ihre Materialordner und deren Unterordner
* &lbrack;Resources&rbrack; Lösen Sie das Bedienfeld &quot;Materialressourcen&quot; in einem separaten Fenster, um Ihre Ressourcen im Vollbildmodus anzuzeigen.
* &lbrack;Resources&rbrack; Neues Layout des Bedienfelds &quot;Ressourcen&quot; zur Unterstützung der Navigation von Ordnern und Unterordnern
* &lbrack;Resources&rbrack; Verwenden Sie das Breadcrumb, um durch Ihre Ordner zu navigieren
* &lbrack;Resources&rbrack; Erzwingen der Synchronisierung Ihres lokalen Ordners mit der Option Synchronisieren , die per Rechtsklick aufgerufen werden kann
* &lbrack;Resources&rbrack; Trennen Sie den lokalen Ordner mit der Option &quot;Trennen&quot;, die per Rechtsklick zugänglich ist
* &lbrack;Verwalten&rbrack; Anzeigen eingebetteter Tags von Substance-Dateien
* &lbrack;Verwalten&rbrack; Hinzufügen, Bearbeiten und Löschen von Tags Ihrer Materialien
* &lbrack;Verwalten&rbrack; Material bewerten.
* &lbrack;Layers&rbrack; Panorama-Ausgabe unterstützen
* &lbrack;Layers&rbrack; Sie können Bildeingaben in der Bildimportebene löschen
* &lbrack;Layers&rbrack; Automatische Auswahl der neuen hinzugefügten Ebene
* &lbrack;Layers&rbrack; Automatische Auswahl der Ebene darunter nach dem Löschen einer Ebene
* &lbrack;UX&rbrack; Sichtbarkeit des linken Bereichs beim Wechsel zu einem anderen Labor beibehalten
* &lbrack;UX&rbrack; Erstellen Sie keine Basisebene oder öffnen Sie das Popup &quot;Material-Arbeitsablauf&quot; nicht, wenn Sie Bilder in einen nicht leeren Ebenenstapel importieren.
* &lbrack;UI&rbrack; Neuer Textfeldstil
* &lbrack;UI&rbrack; Neue Suchfeld-Formatvorlage
* &lbrack;UI&rbrack; Neuer Kopfzeilenstil für Bedienfelder
* &lbrack;UI&rbrack; Neuer Anzeigestil &quot;Gebucht&quot;
* &lbrack;UI&rbrack; Neues Hintergrundformat für Ebenenstapel
* &lbrack;UI&rbrack; Adobe Clean-Schrift verwenden
* &lbrack;UI&rbrack; Entfernen des Platzhalters für das Pipettensymbol des Farbeingabeparameters
* &lbrack;Performance&rbrack; Optimierung der Belegungsanzeige
* &lbrack;Inhalt&rbrack; Neuer Mustergenerator-Filter
* &lbrack;Inhalt&rbrack; Neuer Weichzeichnungsfilter

**Fest:**

* &lbrack;Inspire&rbrack; Absturz bei Verwendung von mehr als 10 Farben beheben
* &lbrack;2D Ansicht&rbrack; Fixieren der Bildlaufleiste in der Kanalliste der 2D-Ansicht
* &blbrack;Viewer&rbrack; Absturz beim Importieren einer Umgebungskarte ohne Stromversorgung von 2 beheben
* &lbrack;Inhalt&rbrack; PNG-Import für benutzerdefiniertes Muster von Präge- und Perforationsfiltern korrigieren
* &lbrack;Export&rbrack; Normal- und Height-Export mit 16 Bit pro Kanal
* Korrigieren einer Endlosschleife beim Importieren eines Materials mit zwei Vorgaben mit demselben Namen
* Korrektur der langen Dateipfadanzeige in der Basismaterial-Ebene

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen
* Kann beim Beenden auf MacOS willkürlich abstürzen

### 0.7.0-beta Pepper

*(Freigegeben: 13. Juni 2019)*

**Hinzugefügt:**

* &lbrack;Filter&rbrack; Per Leertaste schnell auf Filter zugreifen
* &lbrack;Filter&rbrack; Neues spezielles Bedienfeld zum Verwalten, Durchsuchen und Importieren Ihrer Filter
* &lbrack;Metadaten&rbrack; Rechtsklick auf ein Material, um seine Metadaten anzuzeigen
* &lbrack;Metadaten&rbrack; Klicken Sie mit der rechten Maustaste auf ein Material, um seinen Speicherort auf der Festplatte anzuzeigen.
* &blase;Regler&blase; Animieren Sie die Schieberegler, wenn Sie mit der Maus darauf zeigen, indem Sie Strg drücken
* &blase;Regler&blase; Die Animation der Regler anhalten und neu starten, indem Sie P drücken.
* &lbrack;Export&rbrack; SBSAR-Export folgt den Richtlinien für die Substance Source
* &lbrack;Lizenz&rbrack; Substance Alchemist mit einer Umgebungsvariablen aktivieren
* &lbrack;UX&rbrack; Dateidialogfeld merkt sich den zuletzt ausgewählten Dateipfad
* &lbrack;UX&rbrack; Ordnerdialog merkt sich den zuletzt ausgewählten Ordnerpfad
* &lbrack;UI&rbrack; Benutzeroberfläche des Bedienfelds &quot;Ressourcen aktualisieren&quot;
* &lbrack;UI&rbrack; Benutzeroberfläche der Suchleiste aktualisieren
* &lbrack;UI&rbrack; Symbol &quot;Neues Material erstellen&quot; wurde aktualisiert
* &lbrack;Hilfe&rbrack; URLs werden auf substance3d.com Domäne aktualisiert
* &lbrack;Mesh&rbrack; Ein Tuchgeflecht ist jetzt verfügbar
* &lbrack;Inhalt&rbrack; Neuer Korrosionsfilter
* &lbrack;Inhalt&rbrack; Neuer Oxydationsfilter
* &lbrack;Inhalt&rbrack; Neuer Moosfilter
* &lbrack;Inhalt&rbrack; Neuer Dust-Filter
* &lbrack;Inhalt&rbrack; Neuer Brickwall-Musterfilter
* &lbrack;Inhalt&rbrack; Neuer Steinmauer-Musterfilter
* &lbrack;Inhalt&rbrack; New Wood Finish Filter
* &lbrack;Inhalt&rbrack; Neuer Metal-Finish-Filter
* &lbrack;Inhalt&rbrack; Neuer Snow-Filter
* &lbrack;Inhalt&rbrack; Neuer Randomizer-Filter
* &lbrack;Inhalt&rbrack; Sie können Ihre Texturen jetzt direkt in den Basismaterial-Filter importieren

**Fest:**

* Absturz beim Speichern des Ebenenstapels beheben
* Es ist möglich, einen Wert über 1 im Umgebungsdrehungsregler hinzuzufügen.
* Verlieren Sie die Überblendungsparameter nicht, wenn eine Überblendungsebene von der Überblendungsebene in die Materialebene hin- und hertransformiert wird
* Duplikate beheben, wenn Variationen desselben Ebenenstapels mehrmals generiert werden
* Beim erneuten Öffnen eines Materials merkt sich Alchemist die geänderten Bereiche (min und max) Ihrer Schieberegler

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 0.6.1-beta Orange

*(Freigegeben: 13. Juni 2019)*

**Hinzugefügt:**

* &lbrack;Motor&rbrack; Substance Engine-Update, um mit der neuesten Substance Designer-Version kompatibel zu sein
* &lbrack;Lizenz&rbrack; Aktualisieren des Lizenzordners für die erste Installation
* &lbrack;Layers&rbrack; Sie können den Ebenenstapel jederzeit neu laden, um Ihre benutzerdefinierten Filter zu aktualisieren

**Fest:**

* &lbrack;Datenkompatibilität&rbrack; Präventive Korrektur zur Begrenzung der Datenbeschädigung zum Zeitpunkt des Upgrades

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

### 0.6.0-beta Orange

*(Freigegeben: 18. April 2019)*

**Hinzugefügt:**

* &lbrack;Metadaten&rbrack; Metadaten in einem speziellen Register anzeigen und ausfüllen
* &lbrack;Sammlung&rbrack; Erstellen einer Sammlung direkt aus den Suchergebnissen
* &lbrack;Media Publishing&rbrack; Exportieren eines Dashboards einer Sammlung
* &lbrack;UX&rbrack; Vorgenommene Änderungen oder Bildimport durch Drücken von Strg+Z rückgängig machen
* &lbrack;UX&rbrack; Änderungen oder Bildimport mit Strg+Umschalt+Z wiederherstellen
* &lbrack;UI&rbrack; Neue Icons mit neuem Stil
* &lbrack;Performance&rbrack; Neuer Sitzungs-Manager, der das Wechseln der Registerkarten verbessert
* &lbrack;Performance&rbrack; Schnelleres Öffnen der Bildimportebene
* &lbrack;Inhalt&rbrack; Neues Metal-Generikum
* &lbrack;Inhalt&rbrack; Neues Material für Rost
* &lbrack;Inhalt&rbrack; Neues Stone-Generikum
* &lbrack;Inhalt&rbrack; Aktualisierung des Prägefilters
* &lbrack;Inhalt&rbrack; Stickerei Filter Update
* &lbrack;Inhalt&rbrack; Aktualisierung des Malfilters
* &lbrack;Inhalt&rbrack; Delighter-Filteraktualisierung

**Fest:**

* &lbrack;Inhalt&rbrack; Wasserfilter funktioniert im Specular-/Glossiness-Workflow
* Das Optionsfeld &quot;Graustufen&quot; im Aktivierungs-Popup reparieren
* Akzeptieren von Dateien, die Coma-Zeichen enthalten
* Kleine Schriftprobleme in Popup-Fenstern beheben
* Beheben von Problemen mit der Transparenz-Benutzeroberfläche aufgrund eines Konflikts mit dem FXAA-Parameter einiger NVIDIA-Karten
* Entfernen des Fokus des Felds nach dem Festlegen eines Werts in einem Schieberegler
* Weisen Sie dem Entdecker die Mindestmenge an VRAM zu, um Abstürze zu reduzieren
* Beheben des Einfrierens von Fenstern beim Ändern der Größe des Anwendungsfensters
* Es wurde ein Absturz behoben, der auftrat, wenn der Ebenenstapel während der Auswertung gelöscht wurde.

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

### 0.5.4-beta Nacho

*(Freigegeben: 26. März 2019)*

**Fest:**

* &lbrack;Stapel&rbrack; Absturz beim Entfernen einer Spritzschicht
* &lbrack;Daten&rbrack; Asset-Datenbank wird beschädigt, wenn die Anwendung abstürzt
* &lbrack;Daten&rbrack; Substance Alchemist kann nicht gestartet werden, wenn die Elementdatenbank beschädigt ist
* Zufälliger Absturz beim Importieren von Substance-Materialien

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Die Standardsammlung, in der gespeichert werden soll, kann leer sein

### 0.5.3-beta Nacho

*(Freigegeben: 19. März 2019)*

**Hinzugefügt:**

* Suchen Sie im Bedienfeld &quot;Ressourcen&quot; nach dem Materialnamen
* &lbrack;UI&rbrack; Kopierwerkzeug: neue Benutzeroberfläche mit Visualisierung der Pinselgröße
* &lbrack;UI&rbrack; Ausgeblendete Phasen auswählen und löschen
* &lbrack;UI&rbrack; Neue Textfeld-Benutzeroberfläche
* &lbrack;Hilfe&rbrack; Zugriff auf Websites von Substance Source, Substance share und Substance Academy
* &lbrack;Inhalt&rbrack; Neue Standardmaterialien mit Generatoren und Atlas
* &lbrack;Inhalt&rbrack; Bitmap zu Materialaktualisierung
* &lbrack;Inhalt&rbrack; Dirt-Update
* &lbrack;Inhalt&rbrack; Rost-Update
* &lbrack;Inhalt&rbrack; Neuer Prägefilter
* &lbrack;Inhalt&rbrack; Neuer Stickereifilter
* &lbrack;Inhalt&rbrack; Neuer Erosionsfilter
* &lbrack;Inhalt&rbrack; Neuer Kiesgenerator
* &lbrack;Inhalt&rbrack; Neuer Malfilter
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Parkettmuster&quot;
* &lbrack;Inhalt&rbrack; Neuer Filter &quot;Pflastermuster&quot;
* &lbrack;Inhalt&rbrack; Neuer Perforationsfilter
* &lbrack;Inhalt&rbrack; Neuer Farbspritzer-Filter
* &lbrack;Inhalt&rbrack; Neuer Textilverschleißfilter
* &lbrack;Inhalt&rbrack; Neuer Transformierenfilter

**Fest:**

* &lbrack;Viewport&rbrack; Sphäre-Gitter mit X2-Kacheln auf X
* &lbrack;Viewport&rbrack; Absturz beim Laden der eigenen Umgebung
* &lbrack;Viewport&rbrack; Die Umgebungskarte verwendet jetzt auch den Belichtungswert.
* &lbrack;Viewport&rbrack; F-Verknüpfung setzt Kamerawinkel nicht zurück
* &lbrack;Export&rbrack; SBS-Export funktioniert mit dem neuesten Substance Designer 2018.3.3
* &lbrack;Export&rbrack; SBSAR-Export entspricht den gleichen Richtlinien wie Substance Source
* &lbrack;UI&rbrack; Bildlaufleisten können gezogen werden
* Sonderzeichen werden für Ordner- und Dateipfade unterstützt
* Die Miniaturansicht wird neu generiert, wenn Sie Ihr Material speichern

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Die Standardsammlung, in der gespeichert werden soll, kann leer sein

### 0.5.2-beta Nacho

*(Freigegeben: 07. März 2019)*

**Hinzugefügt:**

* Erkennung und Nutzung der hochkarätigen GPU

**Fest:**

* Der Drehungsparameter verfügt über ein entsprechendes Schieberegler-Widget.
* Blauen Farbverlauf beim Ziehen und Ablegen von Materialien korrigieren
* Materialüberblendung beim Ablegen eines Materials unter die erste Ebene korrigieren
* Bildeingaben nur dann anschließen, wenn kein benutzerdefinierter Bildpfad festgelegt wurde

**Bekannte Probleme:**

* Sonderzeichen im Dateipfad verhindern das Speichern eines Materials
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Absturz beim Laden der eigenen Umgebung

### 0.5.1-beta Nacho

*(Freigegeben: 04. März 2019)*

**Fest:**

* Absturzbericht, Fehlerbericht und Lizenzen-Popups beheben

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Absturz beim Laden der eigenen Umgebung

### 0.5.0-beta Nacho

*(Freigegeben: 28. Februar 2019)*

**Hinzugefügt:**

* &lbrack;Ebenenstapel&rbrack; Neuanordnung von Ebenen
* &lbrack;Ebenenstapel&rbrack; Ausgeblendete Ebenen löschen
* &lbrack;Ebenenstapel&rbrack; Importieren Sie ein Material direkt an einer Position Ihrer Wahl
* &lbrack;Ebenenstapel&rbrack; Materialeingabe als neuer Filterparametertyp
* &lbrack;Performance&rbrack; Leistungssteigerung durch dynamisches Substance Engine-Budget
* &lbrack;Performance&rbrack; Bessere OpenGL-Leistung, insbesondere auf MacOS
* &lbrack;Daten&rbrack; Schnelleres Daten-Upgrade nach Veröffentlichung einer neuen Version
* &lbrack;Inhalt&rbrack; AI Delighter für Windows 7 und Windows 8
* &lbrack;Inhalt&rbrack; AI Delighter auf RTX-GPU verfügbar

**Fest:**

* Mögliche Abstürze beim Beenden der Anwendung beheben
* Popup-Fenster &quot;Exportieren&quot; wird beim Exportieren großer Sammlungen schneller geöffnet

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Absturz beim Laden der eigenen Umgebung

### 0.4.0-beta Muffin

*(Freigegeben: 17. Januar 2019)*

**Hinzugefügt:**

* &lbrack;Export&rbrack; Substance-Archiv (sbsar) exportieren Ihrer Sammlung
* &lbrack;Export&rbrack; Substance-Dateiexport (sbs) Ihrer Sammlung
* &lbrack;Export&rbrack; Exportwarteschlange im Exportbedienfeld sichtbar
* &lbrack;Export&rbrack; Benennen Sie Ihre Sammlung oder Ihr Material vor dem Export
* &lbrack;Daten&rbrack; Als Material speichern durch Drücken von Strg+Umschalt+S
* &lbrack;Daten&rbrack; Material durch Drücken von Strg+S speichern.
* &lbrack;Daten&rbrack; Sammlungen und Materialien sind versionsübergreifend kompatibel.
* &lbrack;Daten&rbrack; Aktualisiere deinen Materialebenen-Stapel mit aktuellen Filtern.
* &lbrack;Daten&rbrack; Hot Reload importierter benutzerdefinierter Filter
* &lbrack;UI&rbrack; Visuelles Feedback im Viewport während der Datenverarbeitung
* &lbrack;UI&rbrack; Neuer Schaltflächenstil
* &lbrack;UI&rbrack; Popup &quot;Speichern&quot; zeigt den Namen der aktiven Sammlung an
* &lbrack;UI&rbrack; Quellbilder einer Bildimportebene ändern
* &lbrack;Inhalt&rbrack; Benutzerdefinierte Verwendungen werden jetzt unterstützt
* &lbrack;Inhalt&rbrack; In den Bildeingabeparametern werden mehr Bildformate unterstützt
* &lbrack;Inhalt&rbrack; Neuer Kachelfilter mit dem Namen &quot;Make It Tile Advanced&quot;
* &lbrack;Inhalt&rbrack; Aktualisierung des Wasserfilters

**Fest:**

* &quot;Bitmap zu Material&quot; übernimmt den Workflow für Specular/Glanz

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Delighter wird auf RTX-GPU-Karten nicht unterstützt
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus

### 0.3.1-beta Lasagne

*(Freigegeben: 17. Dezember 2018)*

**Fest:**

* Generieren einer Farbvariante mit 10 farbextrahierten Abstürzen
* Generieren einer Farbvariante mit einem gerade gespeicherten Ebenenstapel stürzt ab
* Falsche Links im Popup-Fenster &quot;Substance Alchemist-Versionsupdate&quot;

**Bekannte Probleme:**

* Die Bitmap zu Material verarbeitet den Workflow für Specular/Raueit nicht
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus

### 0.3.0-beta Lasagne

*(Freigegeben: 12. Dezember 2018)*

**Hinzugefügt:**

* &lbrack;Export&rbrack; Neues Popup-Fenster &quot;Export&quot;
* &lbrack;Export&rbrack; Gesamte Sammlung exportieren
* &lbrack;Export&rbrack; Exportieren von Bitmaps im gewünschten Format
* &lbrack;Export&rbrack; Bitmaps mit der gewählten Auflösung exportieren
* &lbrack;Export&rbrack; Nur die Kanäle Ihrer Wahl exportieren
* &lbrack;Export&rbrack; Vorschau der Schätzgröße Ihres Exports
* &lbrack;Export&rbrack; Verfügbare Größe auf der Festplatte vor dem Export in der Vorschau anzeigen
* &lbrack;UX&rbrack; Aktionen für Sammlung, auf die per Rechtsklick zugegriffen werden kann
* &lbrack;UX&rbrack; Löschen eines Bildes oder eines Elements in &quot;Inspiration&quot; zulassen
* &lbrack;UX&rbrack; Substance Alchemist wird maximiert gestartet
* &lbrack;Assets&rbrack; Neue Möglichkeit zum Speichern von Materialien, um sie in nächsten Versionen dauerhaft zu halten
* &lbrack;Hilfe&rbrack; Zugriff auf die Online-Dokumentation über das Hilfemenü
* &lbrack;Performance&rbrack; Schnellere Farbvariationen auf komplexen Materialien, die mit Substance Alchemist erstellt wurden
* &lbrack;Performance&rbrack; Verringern von Speicherlecks beim Wechseln von Labs
* &lbrack;Inhalt&rbrack; Skalierungsprüfer zur Diagnose der Physische Größe Ihres Materials
* &lbrack;Inhalt&rbrack; Update Italien Venice Mosaik Fliesenmaterial
* &lbrack;Inhalt&rbrack; Moosspritzer aktualisieren

**Fest:**

* Kein Standardname mehr beim Speichern eines Materials
* Filterparameter gehen nach dem Speichern eines Materials und dem erneuten Öffnen von Substance Alchemist verloren
* &lbrack;Inhalt&rbrack; Korrektur von unten und von oben für AO- und Krümmungs-Überblendung

**Bekannte Probleme:**

* Mit einer früheren Version erstellte Materialien sind in der neuen Version nicht verfügbar.
* Die Bitmap zu Material verarbeitet den Workflow für Specular/Raueit nicht
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus

### 0.2.0-beta Kiwi

*(Freigegeben: 9. November 2018)*

**Hinzugefügt:**

* Viewer-Einstellungen werden von einer Sitzung in einer anderen gespeichert
* Materialeinstellungen werden von einer Sitzung in einer anderen gespeichert
* Schnelles Laden des Eigenschaftenbedienfelds
* &lbrack;Log&rbrack; Protokolldatei über das Hilfemenü exportieren
* &blbrack;UI&rbrack;Neuer Reglerstil
* &blbrack;UI&rbrack;Vorgaben- und Tweak-Bedienfelder werden zusammengeführt
* &lbrack;UI&rbrack;Neues Miniaturenformat
* Einstellungen für Versatz, Kacheln und Schatten, auf die direkt im Viewport zugegriffen werden kann
* &lbrack;Inhalt&rbrack; Neue Standardmaterialien
* &lbrack;Inhalt&rbrack; Update für Moos-Farbspritzer
* &Klammer;Rahmen&Klammer; Update Substance Engine Framework

**Fest:**

* Das Löschen Ihres Ebenenstapels durch Wechseln der Labs ist fest
* Die im Viewport angezeigten Zeitwerte werden korrekt geladen.
* Standardkanäle des Material-Workflows sind korrekt initialisiert
* Benutzerdefinierten Gitterimport deaktivieren
* Bitmapexport
* &lbrack;MacOS&rbrack; Das Schließen des Substance Alchemist kann ein &quot;Beenden erzwingen&quot; erfordern

**Bekannte Probleme:**

* Mit einer früheren Version erstellte Materialien sind in der neuen Version nicht verfügbar.
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus

### 0.1.1-beta Jam

*(Freigegeben: 24. Oktober 2018)*

**Hinzugefügt:**

* BaseColor Delighter ist jetzt verfügbar
* Zugriff auf Substance Alchemist-Informationen über das Hilfemenü
* Benachrichtigung erhalten, wenn eine neue Version von Substance Alchemist verfügbar ist
* Die Konsole ist unter Windows nicht mehr sichtbar.
* Neue Miniaturansichtenformatvorlage
* &lbrack;MacOS&rbrack; Substance Alchemist kann im Vollbildmodus eingestellt werden
* &lbrack;Filter&rbrack; Benutzerdefinierte Maske importieren , um die Überblendung zwischen zwei Materialien zu verwalten
* &lbrack;Filter&rbrack; Moos-Skala steuern
* &lbrack;Filter&rbrack; Kopierpatchaktualisierung

**Fest:**

* Bild in einer Bildeingabe in der Parameterliste hinzufügen aktualisiert Ausgaben
* Beim Import eines benutzerdefinierten Filters werden keine schwarze Umgebungsfilter und keine schwarze Deckkraft hinzugefügt.

**Bekannte Probleme:**

* Mit einer früheren Version erstellte Materialien sind in der neuen Version nicht verfügbar.
* &lbrack;MacOS&rbrack; Das Schließen des Substance Alchemist kann ein &quot;Beenden erzwingen&quot; erfordern
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Der schnelle Wechsel der Sichtbarkeit einer Delighter-Bühne wirkt sich auf die Leistung aus
* Der Materialexport kann abstürzen

### 0.1.0-beta IceCream

*(Freigegeben: 17. Oktober 2018)*

**Hinzugefügt:**

* Materialüberblendung mit 4 Überblendungstypen (Height-Überblendung, Sample-Überblendung, Kurvenüberblendung, AO-Überblendung)
* Einführung eines Caching-Mechanismus zur Optimierung von Neuberechnungen von Ebenenstapeln
* Automatische Auswahl eines Materials in Inspire, wenn im Viewport angezeigt
* Normales Format zentralisiert im Bedienfeld &quot;Materialeinstellungen&quot;
* Steuerelemente zum Zuschneiden und Kacheln von Widgets (-90xB0,+90xB0, Quadrat erstellen,...) reinigen
* Neuer Snow-Filter

**Fest:**

* Bereinigung der Benutzeroberfläche von Bedienfeldern
* Viewport flackert beim Ändern der Größe von Fenstern und Bedienfeldern
* Ebenenstapel wird beim Speichern nicht neu berechnet
* Bei der Benennung von Elementen in der Benutzeroberfläche werden Beschriftungen anstelle von Diagrammnamen verwendet

**Bekannte Probleme:**

* Gestreckte Farbe durch schnelles Umschalten der Ebenensichtbarkeit
* Fokus setzt Kamerawinkel zurück
