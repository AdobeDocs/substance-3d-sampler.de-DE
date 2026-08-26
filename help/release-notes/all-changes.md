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

* &amp;lbrack;Assets&amp;rbrack; Überprüfen Sie die sbsar-Version und warnen Sie Benutzer ist die Engine zu alt, um sie zu lesen
* &amp;lbrack;Captis&amp;rbrack; Option &quot;Zurück&quot; hinzufügen, um die Kapitelphotometrie in den Voreinstellungen zu speichern

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Nicht mit physischem Verhältnis anzeigen, wenn Physische Größe deaktiviert ist
* &amp;lbrack;Analyse&amp;rbrack; Fehlende Analyseereignisse
* &amp;lbrack;Analyse&amp;rbrack; Verhindern Sie Abstürze, um einen Absturz auf vk-Geräten zu meldenListe
* &amp;lbrack;Anwendung&amp;rbrack; Zerstören Sie keine vkdevices beim Beenden, um einen Absturz des nvidia-Treibers zu vermeiden
* &amp;lbrack;Anwendung&amp;rbrack; Verknüpfte Sammlungs-Watcher-Ausgang + Kanal-Manager reparieren
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden verhindern
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Metal-Finish&quot; wirkt sich nicht auf die Metallisierung aus
* &amp;lbrack;Inhalt&amp;rbrack; Physische Größe zu dynamischen Filtern hinzufügen, wenn sie fehlt
* &amp;lbrack;Filter&amp;rbrack; Entfernen des inhaltsbasierten Füllens aus der Liste &quot;Ausgeblendete Elemente&quot;
* &amp;lbrack;Layers&amp;rbrack; Durch Klicken auf &quot;Alle Einstellungen zurücksetzen&quot; wird die Dropdown-Liste &quot;Betrifft&quot; nicht zurückgesetzt
* &amp;lbrack;Layers&amp;rbrack; Minimale und maximale Anpassung für Positions-Widget
* &amp;lbrack;Layers&amp;rbrack; Filter richtig aktualisieren
* &amp;lbrack;Physische Größe&amp;rbrack; Sorgen Sie mit dynamischen Filtern dafür, dass die physische Skalierung überall funktioniert, und machen Sie die physische Größe ok.
* &amp;lbrack;Projekt&amp;rbrack; Sicherstellen, dass die Standardauflösung für Assets (2K x 2K) beim Erstellen eines neuen Assets festgelegt ist
* &amp;lbrack;Projekt&amp;rbrack; Aktuelles Projekt, mit dem die vorherige Version geöffnet wurde, erneut öffnen
* &amp;lbrack;Projekt&amp;rbrack; Sampler bietet nicht mehr an, eine Sicherung beschädigter Projekte wiederherzustellen.
* &amp;lbrack;Rendering&amp;rbrack; Miniaturansicht des Materials mit einer maximalen Auflösung von 2k rendern
* &amp;lbrack;UI&amp;rbrack; Defensiver Code zur Vermeidung von Abstürzen, wenn der Benutzer schneller als die Benutzeroberfläche ist

### **6.0.1**

*(Freigegeben: 21. Mai 2026)*

**Hinzugefügt:**

* &amp;lbrack;Anwendung&amp;rbrack; Benutzer beim Öffnen eines Projekts mit 3D-Objekten oder Umgebungslichtern warnen
* &amp;lbrack;Captis&amp;rbrack; Anpassen der Benutzeroberfläche an kleine Bildschirme
* &amp;lbrack;Captis&amp;rbrack; Captis-Benutzeroberfläche aktualisieren
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Automatisches Aktivieren von SSS bei Verwendung des SSS-Kanals in ASM
* &amp;lbrack;Motor&amp;rbrack; Substance Engine auf Version 9.4.3 aktualisieren
* &amp;lbrack;Vorgabe&amp;rbrack; Option &quot;Vorgabewerte für Miniaturansichten anwenden&quot; standardmäßig aktiviert
* &amp;lbrack;Resources&amp;rbrack; Standardmäßig &quot;alle Bibliotheken&quot; anstelle von &quot;Starter-Assets&quot; im Ressourcenbedienfeld anzeigen
* &amp;lbrack;Skripterstellung&amp;rbrack; Hinzufügen von Python-Funktionen zum Verwalten von &quot;Angewendet auf&quot; einer Ebene
* &amp;lbrack;UI&amp;rbrack; Die Elementliste reagiert jetzt: Größe des Assets passt sich an den Container an
* &amp;lbrack;UI&amp;rbrack; 3D-/2D-Ansicht standardmäßig anzeigen
* &amp;lbrack;UI&amp;rbrack; Popup-Fenster zur Materialoptimierung beim Ablegen eines Materials aus dem Explorer anzeigen
* &amp;lbrack;UI&amp;rbrack; Kippen von Gerätestangenschaltflächen aktivieren - QuickInfo

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Beheben von Farbraumproblemen
* &amp;lbrack;Anwendung&amp;rbrack; Anpassen der Einstellungen
* &amp;lbrack;Anwendung&amp;rbrack; Scankanäle aktivieren, wenn sie auf &quot;Automatisch&quot; eingestellt sind
* &amp;lbrack;Anwendung&amp;rbrack; Die Schaltfläche &quot;Neues Projekt&quot; auf dem Startbildschirm löscht nicht mehr das vorherige Projekt mit demselben Namen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden von macOS verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Zugriff auf Assets mit ungültigen Asset-Referenzen verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Zugriff auf die Oberfläche aus VersionedImage in einer Optimierung verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Löschen einer Bühne verhindern, wenn keine vorhanden ist
* &amp;lbrack;Captis&amp;rbrack; Stellen Sie sicher, dass Captis getrennt ist, bevor Sie Sampler schließen.
* &amp;lbrack;Captis&amp;rbrack; Doppelte Anzeige der USB-2-Warnung verhindern
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; OpenPBR-Kanalnamen korrigieren
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Aktualisieren langer Beschriftungen für OpenPBR-Kanäle
* &amp;lbrack;Inhalt&amp;rbrack; Alle Gittereinheiten von Meter auf Zentimeter für SSS-Werte aktualisieren
* &amp;lbrack;Export&amp;rbrack; Sicherstellen, dass Standardwerte an dynamische Filter angeschlossen sind
* &amp;lbrack;Export&amp;rbrack; Bilder werden jetzt in einem Arbeitsthread gespeichert, um die Leistung zu verbessern
* &amp;lbrack;Filter&amp;rbrack; Inhaltsbasierte Füllung stürzt ab, wenn die Skalierung aktiviert wird
* &amp;lbrack;Filter&amp;rbrack; Der Speicherort eines dynamischen Filters konnte nicht aus dem Bedienfeld &quot;Elemente&quot; geöffnet werden.
* &amp;lbrack;Filter&amp;rbrack; Fixieren Sie alle im AutoTiling-Anpassungsschritt zurücksetzen
* &amp;lbrack;Filter&amp;rbrack; Wiederherstellen Deaktivieren der Verarbeitung der Verwendung bei der Erstellung von Baumstrukturen
* &amp;lbrack;Filter&amp;rbrack; Festlegen des richtigen Standardwerts für den Parameter &quot;upscale&quot;
* &amp;lbrack;Filter&amp;rbrack; Generatoren aktualisieren, auch wenn sie sich in einer Füllebene befinden
* &amp;lbrack;Layers&amp;rbrack; Umbenennen der Kopfzeile einer Eingabeebene oder der Platzhalterebenen ist untersagt
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Einfügen von Ebenen durch baumelnde Zeiger verhindern
* &amp;lbrack;Layers&amp;rbrack; Falsche Anzahl von Bildern im flachen Ebenennamen
* &amp;lbrack;Lokalisierung&amp;rbrack; Stellen Sie sicher, dass Vorgabennamen beim Wechseln der Sprachen aktualisiert werden.
* &amp;lbrack;Lokalisierung&amp;rbrack; Mehrere Übersetzungsprobleme im Ressourcenbereich
* &amp;lbrack;Lokalisierung&amp;rbrack; Schnellaktionen - Kategorien Lokalisierungsprobleme
* &amp;lbrack;Performance&amp;rbrack; Laden von Änderungen nur im geöffneten Abschnitt
* &amp;lbrack;Voreinstellungen&amp;rbrack; Das Löschen des Voreinstellungs-Cache-Pfads wird auf den vorherigen Wert zurückgesetzt
* &amp;lbrack;Rendering&amp;rbrack; Speicherverlust bei Verwendung des Pfadverfolgung
* &amp;lbrack;Rendering&amp;rbrack; Löschen von Texturen verhindern, solange Vulkan noch auf sie zugreifen kann
* &amp;lbrack;Rendering&amp;rbrack; Die Texturdrehung wurde nicht von 0-1 auf 0-360 konvertiert.
* &amp;lbrack;Skripterstellung&amp;rbrack; Entfernen nicht vorhandener Klassen aus der Python-Dokumentation
* &amp;lbrack;Skripterstellung&amp;rbrack; selectedAsset gibt Keine zurück, wenn kein ausgewähltes Asset vorhanden ist
* &amp;lbrack;Extras&amp;rbrack; Durch das Zurücksetzen eines Texturwerts wird das Malen beendet und die Patch-Ansicht gelöscht.
* &amp;lbrack;UI&amp;rbrack; Schließen Sie die Abschnitte im Eigenschaftenfenster nicht, wenn etwas geändert wird
* &amp;lbrack;UI&amp;rbrack; Sichtbares Farb-Tweak-Label beim Bewegen des Mauszeigers nicht sichtbar
* &amp;lbrack;UI&amp;rbrack; Verhalten &quot;Responsive&quot; für Elementliste korrigieren
* &amp;lbrack;UI&amp;rbrack; Bindungsschleife in der QuickInfo für AssetItem reparieren
* &amp;lbrack;UI&amp;rbrack; Doppelklick auf ausgewählte Vorgabengruppe korrigieren
* &amp;lbrack;UI&amp;rbrack; Ablagebereich im Bildmoderator korrigieren
* &amp;lbrack;UI&amp;rbrack; Beschriftung mit Schaltfläche für alle Sprachen korrigieren
* &amp;lbrack;UI&amp;rbrack; Height &quot;Line&quot; für Japanisch im Kanallisten-Popup korrigieren
* &amp;lbrack;UI&amp;rbrack; Behebung eines akzeptierten Signals im Längenfeld
* &amp;lbrack;UI&amp;rbrack; Popupbreite mit langem linken Steuerelement korrigieren
* &amp;lbrack;UI&amp;rbrack; Popup-Vorschau in Elementelementen korrigieren
* &amp;lbrack;UI&amp;rbrack; Reparieren des groben/reflektierenden Pflückers
* &amp;lbrack;UI&amp;rbrack; Stringellipse fixieren
* &amp;lbrack;UI&amp;rbrack; Problem beim Abschneiden von Zeichenfolgen beheben
* &amp;lbrack;UI&amp;rbrack; Reset-Taste für Schalteroptimierung beheben
* &amp;lbrack;UI&amp;rbrack; Ausblenden der Dropdown-Liste &quot;Materialmodell&quot;, wenn eine benutzerdefinierte Exportvorgabe ausgewählt ist
* &amp;lbrack;UI&amp;rbrack; Auflösung in der Kanalliste des Export-Popup entfernen
* &amp;lbrack;UI&amp;rbrack; Auf Standardlayout zurücksetzen behält die Projektionsanzeige bei
* &amp;lbrack;UI&amp;rbrack; Menüelemente &quot;In Photoshop bearbeiten&quot; und &quot;In Illustrator bearbeiten&quot; wiederherstellen

**Entfernt:**

* &amp;lbrack;UI&amp;rbrack; Entfernen des Abschnitts &quot;Angewendet auf&quot; für Bildimportebenen
* &amp;lbrack;UI&amp;rbrack; QuickInfo zum automatischen Öffnen beim ersten Start entfernen

## Version 5

### **5.1.3 ÎLE FLOTTANTE**

*(Freigegeben: 6. Januar 2026)*

**Hinzugefügt:**

* &amp;lbrack;Captis&amp;rbrack; Warnmeldung anzeigen, wenn das FTP-Protokoll von der Firewall deaktiviert wurde

**Fest:**

* &amp;lbrack;Captis&amp;rbrack; Abbrechen während einer Aufnahme kann zu Fehlern führen
* &amp;lbrack;Captis&amp;rbrack; Das Herunterladen der Ergebnisse am Ende einer Aufnahme beansprucht zu viel RAM
* &amp;lbrack;Captis&amp;rbrack; Das Ausführen eines Autofokus direkt nach einer Autointensität kann zu Fehlern führen
* &amp;lbrack;Captis&amp;rbrack; Die Anzeige von HDR-Ergebnissen im Bedienfeld &quot;Zusammenfassung&quot;
* &amp;lbrack;UI&amp;rbrack; In einigen Fällen wählt das Ordnerdialogfeld auf MacOS nicht den richtigen Ordner aus

### **5.1.2 ÎLE FLOTTANTE**

*(Freigegeben: 20. November 2025)*

**Hinzugefügt:**

* &amp;lbrack;Anwendung&amp;rbrack; Grafikgeräteverlust erkennen, Benutzer warnen und ordnungsgemäß beenden
* &amp;lbrack;Layers&amp;rbrack; Verbesserte Messaging-Funktion beim Reduzieren von Ebenen
* &amp;lbrack;Layers&amp;rbrack; Verbesserte Miniaturen für Bildimport- und abgeflachte Ebenen
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisierte Lerninhalte auf dem Startbildschirm
* &amp;lbrack;Projekt&amp;rbrack; Wiederherstellen des zuletzt gespeicherten Sitzungszustands vor dem Absturz
* &amp;lbrack;UI&amp;rbrack; Aktualisierung des Applikationssymbols

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Das Einfügen eines Materials in den Ebenenstapel kann in macOS zu einem Absturz führen
* &amp;lbrack;Anwendung&amp;rbrack; Möglicher Absturz bei hoher Belastung auf macOS
* &amp;lbrack;Anwendung&amp;rbrack; Mögliche Abstürze beim Hinzufügen von Ebenen, wenn der Videospeicher voll ist
* &amp;lbrack;Anwendung&amp;rbrack; Möglicher Absturz beim Öffnen eines Projekts
* &amp;lbrack;Captis&amp;rbrack; Fehler, wenn der Autofokus kurz nach der automatischen Intensitätskalibrierung ausgeführt wird
* &amp;lbrack;Captis&amp;rbrack; Zuverlässigkeits- und Leistungsprobleme nach der ersten Aufnahme
* &amp;lbrack;Captis&amp;rbrack; Verzögerungen und Fehler beim Kopieren von Dateien am Ende einer Aufnahme
* &amp;lbrack;Captis&amp;rbrack; Kleines Speicherleck bei der Abfrage von Captis-Geräteinformationen
* &amp;lbrack;Export&amp;rbrack; Durch mehrere Regler exponierte Parameter werden beschädigte .sbsar-Dateien erzeugt
* &amp;lbrack;Layers&amp;rbrack; Das Muster für die automatische Unterteilung wird beim Wechseln von Elementen auf die Standardwerte zurückgesetzt
* &amp;lbrack;Layers&amp;rbrack; Standardmäßige benutzerdefinierte Grundfarbe wird rot angezeigt
* &amp;lbrack;Layers&amp;rbrack; Die teilweise Reduzierung der untergeordneten Ebenen des Kopierstempels ist möglich und verursacht Renderprobleme
* &amp;lbrack;Layers&amp;rbrack; Möglicher Absturz beim Anpassen eines Ebenenstapels während des Renderns
* &amp;lbrack;Layers&amp;rbrack; Unerwarteter Fehler beim Schritt zum automatischen Anordnen von Fokusbereichen beim Ändern der Quellkanäle
* &amp;lbrack;Projekt&amp;rbrack; Manchmal falsche Miniaturansicht beim Erstellen eines neuen Materials
* &amp;lbrack;Schnellaktionen&amp;rbrack; Einige Schnellaktionen haben eine falsche Eingabeanzahl.
* &amp;lbrack;UI&amp;rbrack; Aktionsgruppen-Schaltfläche hat unterschiedliche Breiten
* &amp;lbrack;UI&amp;rbrack; Schaltfläche &quot;Löschen&quot; in Textfeldern löst manchmal Fokusverlust aus
* &amp;lbrack;UI&amp;rbrack; Kombinationsfelder und Textfelder sind zu groß
* &amp;lbrack;UI&amp;rbrack; Symbole und Beschriftungen sind falsch ausgerichtet
* &amp;lbrack;UI&amp;rbrack; Namensfeldbeschriftung ist falsch platziert
* &amp;lbrack;UI&amp;rbrack; Schaltflächenbeschriftungen für Schnellaktionen sind falsch ausgerichtet
* &amp;lbrack;UI&amp;rbrack; Schieberegler zeigen zu lange nachgestellte 0s an

**Entfernt:**

* &amp;lbrack;Generative KI&amp;rbrack; Generative AI-Funktionen werden entfernt. *Diese Funktion wurde aus der Anwendung entfernt und der Dienst funktioniert in früheren Versionen von Sampler am 5. März nicht mehr.*

### **5.1.1 ÎLE FLOTTANTE**

*(Freigegeben: 18. September 2025)*

**Hinzugefügt:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Vergrößern der 2D-Ansicht für hochauflösende Texturen
* &amp;lbrack;Captis&amp;rbrack; Benutzer über Probleme beim Kopieren von Dateien warnen
* &amp;lbrack;Layers&amp;rbrack; Verwenden Sie beim Duplizieren einer Ebene eine inkrementelle Nummer im Namen der neuen Ebene

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Beim Malen von Strichen nach dem Zurücksetzen aller Eigenschaften des Kopierstempels werden zuvor erstellte Striche wieder angezeigt
* &amp;lbrack;Anwendung&amp;rbrack; Aktuelles Projekt speichern? popup verwendet falschen Projektnamen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Potenzieller Absturz
* &amp;lbrack;Anwendung&amp;rbrack; Manchmal wird eine Miniaturansicht mit einem falschen Material generiert
* &amp;lbrack;Captis&amp;rbrack; Auf einigen Geräten wird beim Scannen in hoher Auflösung das Height schwarz angezeigt
* &amp;lbrack;Captis&amp;rbrack; Die Schaltfläche &quot;Aufnahme starten&quot; ist nicht mehr deaktiviert, wenn kein Aufnahmename festgelegt ist und wenn eine Kalibrierung ausgeführt wird
* &amp;lbrack;Export&amp;rbrack; Beim Exportieren einer .sbsar-Datei kann der Export fehlschlagen, ohne dass der Benutzer benachrichtigt wird
* &amp;lbrack;Filter&amp;rbrack; Bildschirm &quot;Erweiterte Parameter&quot; für den Filter &quot;Automatische Kachelung&quot; flackert manchmal, wenn Parameter angepasst werden
* &amp;lbrack;Filter&amp;rbrack; Standardparameter für den Musterfilter erzeugen graue Artefakte in der Ausgabe
* &amp;lbrack;Filter&amp;rbrack; Bei Eingaben mit hoher Auflösung zeigen die erweiterten Einstellungen des Filters &quot;Automatische Kachelung&quot; manchmal nicht die einzelnen Musterpunkte an
* &amp;lbrack;Filter&amp;rbrack; Die Mustergröße für den Parameter &quot;Automatische Kachelung&quot; der benutzerdefinierten Größe hat einen falschen Standardwert.
* &amp;lbrack;Layers&amp;rbrack; Gelegentliche Farbprobleme mit dem automatischen Kachelfilter, die meistens auf roten Materialien sichtbar sind
* &amp;lbrack;Layers&amp;rbrack; Manchmal werden durch das Hinzufügen von Ebenen einige Änderungen auf ihren Standardwert zurückgesetzt
* &amp;lbrack;Physische Größe&amp;rbrack; Miniaturansicht von Elementen mit einer Physische Größe haben eine falsche Height-Skala
* &amp;lbrack;UI&amp;rbrack; Belichtete Parameter können nicht umbenannt werden
* &amp;lbrack;UI&amp;rbrack; Kanalaktivierungstaste ist nicht quadratisch
* &amp;lbrack;UI&amp;rbrack; Wenn eine Reglerbeschriftung zu lang ist, ist die Schaltfläche &quot;Zurücksetzen&quot; nicht verfügbar.
* &amp;lbrack;UI&amp;rbrack; Durch Drücken der Eingabetaste oder Klicken auf den Out-Point wird der Fokus nicht aus den Textfeldern entfernt.
* &amp;lbrack;UI&amp;rbrack; Manchmal wird eine unerwünschte QuickInfo im Bedienfeld &quot;Physische Größe&quot; angezeigt
* &amp;lbrack;UI&amp;rbrack; In der 3D-Ansicht wird beim Erstellen eines leeren Projekts ein falsches Gitter angezeigt
* &amp;lbrack;UI&amp;rbrack; Wenn eine Farbwählereingabe angezeigt wird, verschwindet ihre Beschriftung beim Bewegen der Maus
* &amp;lbrack;UI&amp;rbrack; Beim Belichten von Parametern wird der Farbpunkt manchmal falsch positioniert

### **5.1.0 ÎLE FLOTTANTE**

*(Freigegeben: 7. August 2025)*

**Hinzugefügt:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Die Pinselgröße passt sich jetzt der aktuellen Texturauflösung an
* &amp;lbrack;3D-Ansicht&amp;rbrack; Native Anzeigeskalierung für 3D-Rendering in den Voreinstellungen aktivieren/deaktivieren
* &amp;lbrack;Anwendung&amp;rbrack; Aktualisierung der Rendering-Engine
* &amp;lbrack;Captis&amp;rbrack; Hinzufügen der Option &quot;Quadrat erstellen&quot; während der Vorschau
* &amp;lbrack;Captis&amp;rbrack; Automatische Erkennung von Physische Größen
* &amp;lbrack;Captis&amp;rbrack; Durch das Erfassen eines neuen Materials wird ein neues Asset erstellt.
* &amp;lbrack;Captis&amp;rbrack; Ändern Sie die Auflösungsauswahl im Dropdown in Pixel pro Zoll oder Zentimeter anstelle der Pixelauflösung des maximalen Bereichs
* &amp;lbrack;Captis&amp;rbrack; Kontextbezogene Hilfe für die Ausrichtungskalibrierung
* &amp;lbrack;Captis&amp;rbrack; Raueitskarte generieren
* &amp;lbrack;Captis&amp;rbrack; Benutzer warnen, wenn die Standardkalibrierungsdateien fehlen
* &amp;lbrack;Filter&amp;rbrack; Auto-Kachelfilter für strukturierte Materialien und Scans
* &amp;lbrack;Filter&amp;rbrack; Neuer Falten-Entferner-Filter
* &amp;lbrack;Filter&amp;rbrack; Neue Funktionen im Filter &quot;Kopierstempel&quot;
* &amp;lbrack;Filter&amp;rbrack; Neue Funktionen im Filter &quot;Tonwertangleichung&quot;
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit zum Reduzieren von Ebenen
* &amp;lbrack;Layers&amp;rbrack; Kontextmenü beim Klicken mit der rechten Maustaste auf eine Ebene zum Umbenennen, Duplizieren, Löschen oder Reduzieren der Ebene
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisieren des Begrüßungsbildschirms und des Inhalts der neuen Bildschirme
* &amp;lbrack;Performance&amp;rbrack; Bessere Leistung bei Verwendung des Zuschneidefilters
* &amp;lbrack;Performance&amp;rbrack; Verbessern der Speichernutzung für die 3D-Ansicht
* &amp;lbrack;Performance&amp;rbrack; Die 3D-Ansicht wird schneller aktualisiert
* &amp;lbrack;Physische Größe&amp;rbrack; Aktivieren Sie &quot;Anzeige mit physischem Verhältnis&quot;, wenn Sie an Substance-Filtern arbeiten, wenn Physische Größe aktiviert ist.
* &amp;lbrack;Physische Größe&amp;rbrack; Wenn Sie Bilder in einen leeren Stapel importieren, schlagen Sie eine Auflösung vor, die dem Bildverhältnis besser entspricht.
* &amp;lbrack;Schnellaktionen&amp;rbrack; 3 neue Schnellaktionen für die Scanverarbeitung
* &amp;lbrack;Skripterstellung&amp;rbrack; API zum Reduzieren von Ebenen
* &amp;lbrack;Skripterstellung&amp;rbrack; Abrufen des Dateinamens für jedes Bild einer Bildimportebene
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Funktion zum Aktivieren/Deaktivieren eines bestimmten Kanals eines Elements
* &amp;lbrack;UI&amp;rbrack; Symbole und Schaltflächen im Ebenenbedienfeld überarbeiten, um Platz für die neuen Funktionen zu schaffen
* &amp;lbrack;UI&amp;rbrack; Warnung vor dem Verfall der Erstellung von Umgebungslicht

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Die Auswahl von &quot;Anzeige mit physischem Verhältnis&quot; funktioniert möglicherweise nicht, wenn Substance-Filter verwendet werden
* &amp;lbrack;3D-Erfassung&amp;rbrack; SVG-Dateien werden in der Dateiauswahl aufgeführt, aber nicht unterstützt.
* &amp;lbrack;3D-Ansicht&amp;rbrack; Der Parameter für die Emissionsintensität in den Shader-Einstellungen funktioniert nicht
* &amp;lbrack;3D-Ansicht&amp;rbrack; Manchmal ist die Gitterposition beim Erstellen eines neuen Elements falsch
* &amp;lbrack;3D-Ansicht&amp;rbrack; Das Wechseln zum Rendering der Pfadverfolgung stürzt auf nicht unterstützter Hardware ab
* &amp;lbrack;Anwendung&amp;rbrack; Anwendung bleibt hängen, wenn das Popup für manuelle Messungen geschlossen wird, ohne eine Größe festzulegen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz
* &amp;lbrack;Anwendung&amp;rbrack; Einfrieren unter Windows bei Anzeige des Desktops (Windows-Taste + D-Tastaturbefehl)
* &amp;lbrack;Anwendung&amp;rbrack; Mögliche Abstürze beim Wechseln der Sprache
* &amp;lbrack;Captis&amp;rbrack; Absturz, wenn die Vorschaudaten nicht gültig sind
* &amp;lbrack;Captis&amp;rbrack; Nach dem Einzoomen ist das Auszoomen nicht möglich
* &amp;lbrack;Captis&amp;rbrack; Fehlende Lokalisierung in einigen Schritten des Assistenten
* &amp;lbrack;Captis&amp;rbrack; Möglicher Absturz beim Beenden bei Verwendung von Captis
* &amp;lbrack;Captis&amp;rbrack; Das Scannen funktioniert nicht, wenn auf dem Gerät Kalibrierungsdateien fehlen
* &amp;lbrack;Filter&amp;rbrack; Die Pinselvorschau bei Verwendung des Kopierstempelfilters kann je nach Struktur und Pinselgröße falsch sein
* &amp;lbrack;Filter&amp;rbrack; Fehlerhafte Ausgabegröße nach Verwendung des Filters &quot;Hochskalieren&quot;
* &amp;lbrack;Filter&amp;rbrack; Fehlende Symbole für Umgebungsdrehung und Stilisierungsfilter
* &amp;lbrack;Filter&amp;rbrack; Die Aktualisierung einiger Filter kann zu falschem Rendering führen
* &amp;lbrack;Layers&amp;rbrack; Falsches erstes Rendering beim Mischen von zwei Materialien
* &amp;lbrack;Layers&amp;rbrack; Die Schaltfläche zum Aktualisieren von Ebenen zeigt &quot;Alle aktualisieren&quot; an, auch wenn nur ein Update vorhanden ist
* &amp;lbrack;Layers&amp;rbrack; Unnötige Berechnungen beim Importieren von Bildern im Ebenenstapel
* &amp;lbrack;Performance&amp;rbrack; Verbessern der Normalen-Map-Format-Handhabung zur Reduzierung der Rendering-Zeiten
* &amp;lbrack;Physische Größe&amp;rbrack; Das Popup für manuelle Messungen funktioniert nur nach einer automatischen Messung
* &amp;lbrack;Physische Größe&amp;rbrack; Falsche Exportauflösung im Popup &quot;Exportieren&quot;, wenn Physische Größe aktiviert ist
* &amp;lbrack;Schnellaktionen&amp;rbrack; Fehlende Lokalisierung generierter Elementnamen
* &amp;lbrack;UI&amp;rbrack; Asset-Vorschau beim Hovern wird möglicherweise nicht angezeigt
* &amp;lbrack;UI&amp;rbrack; Durch Klicken auf die Schaltfläche Auf Standardwert zurücksetzen können einige der Steuerelemente beschädigt werden
* &amp;lbrack;UI&amp;rbrack; Fehlermeldungen werden beim Wechseln von Projekten nicht gelöscht
* &amp;lbrack;UI&amp;rbrack; Stellen Sie sicher, dass der Materialname im Bedienfeld &quot;Viewport &amp; Eigenschaften&quot; leer ist, wenn kein Element vorhanden ist.
* &amp;lbrack;UI&amp;rbrack; Die Schaltfläche &quot;Auf Standardwert zurücksetzen&quot; für den Parameter &quot;Point of View&quot; funktioniert nicht
* &amp;lbrack;UI&amp;rbrack; Schaltflächenüberlappung auf Standardwert zurücksetzen
* &amp;lbrack;UI&amp;rbrack; Einige Schaltflächen sind nicht anklickbar, wenn ein Bedienfeld abgedockt ist
* &amp;lbrack;UI&amp;rbrack; Texturbearbeitung - V-Parameter teilweise ausgeblendet in den Anzeigeeinstellungen und der 3D-Ansicht

**Entfernt:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Unterstützung zum Entfernen von 3D-Erfassungen
* &amp;lbrack;Anwendung&amp;rbrack; Unterstützung für macOS x86 entfernen

### **5.0.3 HAZELNUT**

*(Freigegeben: 3. Juni 2025)*

**Hinzugefügt:**

* &amp;lbrack;Captis&amp;rbrack; Einem Material denselben Namen wie einem bereits vorhandenen Material zuweisen
* &amp;lbrack;Captis&amp;rbrack; Fehlermeldungen in Popups statt in Toasts verschieben
* &amp;lbrack;Filter&amp;rbrack; Stickerei aktualisieren
* &amp;lbrack;Voreinstellungen&amp;rbrack; Hinzufügen von &quot;Zurücksetzen&quot; in den Anzeigeeinstellungen und in den Shader-Einstellungen
* &amp;lbrack;UI&amp;rbrack; Zeigen Sie in Projektelementen nicht die Menüoption &quot;Speicherort anzeigen&quot; an.

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Der Netznachbearbeitungsfilter gibt keine erwarteten Zuordnungen aus
* &amp;lbrack;3D-Ansicht&amp;rbrack; 3D-Ansicht funktioniert aufgrund einer Beschädigung des Shader-Caches nicht
* &amp;lbrack;3D-Ansicht&amp;rbrack; Grundebene und Raster sind vertikal, wenn die Szene Z-förmig ist
* &amp;lbrack;3D-Ansicht&amp;rbrack; Das Gitter verschwindet manchmal
* &amp;lbrack;Anwendung&amp;rbrack; Wenn Sie das Anmeldefenster beim Start schließen, ohne sich anzumelden, stürzt die App manchmal ab
* &amp;lbrack;Anwendung&amp;rbrack; Absturz, wenn der Zugriff auf die Plug-in-Konfigurationsdatei verweigert wird
* &amp;lbrack;Anwendung&amp;rbrack; Die Auswahl des aktuellen Materials wird aufgehoben, wenn das Projekt gespeichert wird
* &amp;lbrack;Anwendung&amp;rbrack; Durch Zurücksetzen auf das Standardlayout wird die Auflösung auf 64x64 eingestellt.
* &amp;lbrack;Anwendung&amp;rbrack; Sampler stürzt manchmal beim Rendern eines Ebenenstapels ab
* &amp;lbrack;Export&amp;rbrack; Die Exportauflösung wird manchmal auf 64x64 zurückgesetzt
* &amp;lbrack;Export&amp;rbrack; Manchmal ist es nicht möglich, .sbs/.sbsar-Dateien zu exportieren
* &amp;lbrack;Layers&amp;rbrack; Die Schaltfläche &quot;Basismaterial hinzufügen&quot; hat keine Wirkung, wenn das Material leer ist
* &amp;lbrack;Layers&amp;rbrack; Beim Duplizieren eines Materials wird die Kachelung geändert.
* &amp;lbrack;Physische Größe&amp;rbrack; Das automatische Messen funktioniert nicht, wenn das Bedienfeld &quot;Physische Größe&quot; vor dem Importieren des Bildes angedockt wurde
* &amp;lbrack;Skripterstellung&amp;rbrack; Modul zum automatischen Speichern ist defekt
* &amp;lbrack;UI&amp;rbrack; Falscher Abstand im Dialogfeld &quot;Exportieren&quot;
* &amp;lbrack;UI&amp;rbrack; Schieberegler-Animationen von Änderungen funktionieren nicht mehr
* &amp;lbrack;UI&amp;rbrack; Schieberegler rasten bei Bedarf nicht an Ganzzahlwerten ein
* &amp;lbrack;UI&amp;rbrack; Einige Dropdown-Menüs sind beschnitten

### **5.0.2 HAZELNUT**

*(Freigegeben: 22. April 2025)*

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Schaltfläche &quot;Zurück&quot; auf der Startseite ist defekt
* &amp;lbrack;Anwendung&amp;rbrack; Sampler wird manchmal nicht gestartet, wenn beschädigte Daten aus früheren Versionen auf der Festplatte vorhanden sind
* &amp;lbrack;Anwendung&amp;rbrack; Das importierte Bild wird nicht im Darstellungsfenster oder im Ebenenstapel angezeigt
* &amp;lbrack;Captis&amp;rbrack; Das Feld &quot;Captivate IP-Adresse&quot; bleibt auch nach dem Neustart von Sampler leer.
* &amp;lbrack;Captis&amp;rbrack; Die Live-Kameravorschau funktioniert nur, wenn die Anwendungssprache auf Englisch festgelegt ist
* &amp;lbrack;Export&amp;rbrack; Absturz beim Export &amp;blbrack;Layers&amp;rbrack; Das Malen funktioniert manchmal nicht in zuvor gespeicherten Projekten
* &amp;lbrack;Layers&amp;rbrack; Sampler aktualisiert manchmal alle Texturen, wenn nur ein Kanal aktualisiert wird
* &amp;lbrack;Layers&amp;rbrack; Nach dem Upgrade auf 5.0.x können keine Materialüberblendungen im Ebenenstapel verwendet werden
* &amp;lbrack;Layers&amp;rbrack; Durch die Aktualisierung eines Projekts mit einer vorherigen Version von &quot;Bild zu Material&quot; (AI) wird das Material vollständig schwarz.
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie versuchen, ein nicht unterstütztes Bild zu importieren, erstellt Sampler eine fehlerhafte Ebene
* &amp;lbrack;Skripterstellung&amp;rbrack; Ein Teil der Python-API funktioniert nicht mit einem leeren Projekt
* &amp;lbrack;UI&amp;rbrack; Menüelemente überlaufen manchmal das Menü &quot;Datei&quot;.

### **5.0.1 HAZELNUT**

*(Freigegeben: 20. März 2025)*

**Hinzugefügt**

* &amp;lbrack;Anwendung&amp;rbrack; Aktualisierte Grafiktreiber-Kompatibilitätsliste
* &amp;lbrack;Captis&amp;rbrack; Popup anzeigen, wenn die Verwendung von HP Z Captis durch Betriebssystemrichtlinien blockiert wird
* &amp;lbrack;Schnellaktionen&amp;rbrack; Erklären, warum eine Schnellaktion in einer QuickInfo deaktiviert ist
* &amp;lbrack;UI&amp;rbrack; UI-Styling für Absturzberichtsfenster
* &amp;lbrack;UI&amp;rbrack; Wenn du in die Zwischenablage kopierst, gib einen Hinweis an, dass der Vorgang abgeschlossen wurde

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Der Belichtungsregler hat keine Wirkung, wenn die sphärische Projektion deaktiviert ist
* &amp;lbrack;2D Ansicht&amp;rbrack; Durch Malen außerhalb der Textur wird ein eingestellter Strich erstellt
* &amp;lbrack;2D Ansicht&amp;rbrack; Die Belichtungstaste hat keine QuickInfo.
* &amp;lbrack;2D Ansicht&amp;rbrack; Das Zoomen auf der Seite eines nicht quadratischen Bildes folgt nicht der Maus
* &amp;lbrack;3D-Erfassung&amp;rbrack; 3D-Erfassung funktioniert nicht unter Windows 11 24H2
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz, wenn Sampler während des Netzrekonstruktionsschritts beendet wird
* &amp;lbrack;3D-Ansicht&amp;rbrack; Die Rechenzeit wird manchmal als 0ms angezeigt
* &amp;lbrack;3D-Ansicht&amp;rbrack; Wenn Sie die Projektion von orthografisch in perspektivisch ändern, wird das Viewport grau.
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Start beim Überprüfen der GPU-Funktionen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz während der Installation
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden nach dem Rechtsklick auf ein Metadatenfeld
* &amp;lbrack;Anwendung&amp;rbrack; Umgebungslicht fehlt beim Öffnen eines SBSAR im Dateiexplorer des Betriebssystems
* &amp;lbrack;Anwendung&amp;rbrack; Wenn Sie eine .sbsar-Datei öffnen, während Sampler ausgeführt wird, ändert sich die Einstellung für die Strukturaufteilung.
* &amp;lbrack;Captis&amp;rbrack; Einige Metadaten werden möglicherweise nicht zwischen den Erfassungsschritten übertragen
* &amp;lbrack;Captis&amp;rbrack; Der Name des erstellten Assets ist nicht der, der im Metadatenfeld eingegeben wurde
* &amp;lbrack;Inhalt&amp;rbrack; Beispielprojekt fordert zur Aktualisierung eines Filters auf, ist aber bereits auf dem neuesten Stand
* &amp;lbrack;Filter&amp;rbrack; Der Korrekturfilter für Normal/Height hat kein Symbol
* &amp;lbrack;Layers&amp;rbrack; Bilder in einer Bildimportebene können nicht geändert werden
* &amp;lbrack;Layers&amp;rbrack; Absturz bei Verwendung des Filters &quot;Hochskalieren&quot;
* &amp;lbrack;Layers&amp;rbrack; Durch Aktualisieren eines Projekts mit einem alten Bild auf Material wird das Material schwarz.
* &amp;lbrack;Rendering&amp;rbrack; Wenn Sie einen Ebenenstapel direkt nach dem Erstellen eines Elements anpassen, wird das Rendering unterbrochen
* &amp;lbrack;Skripterstellung&amp;rbrack; Das Plug-In zum automatischen Speichern stürzt ab, wenn kein Asset im Projekt vorhanden ist
* &amp;lbrack;Extras&amp;rbrack; In der Pinselsymbolleiste fehlt ein Wert für die Pinselgröße
* &amp;lbrack;UI&amp;rbrack; Wenn Sie die Anwendungssprache ändern, werden einige der Beschriftungen auf dem Startbildschirm nicht aktualisiert
* &amp;lbrack;UI&amp;rbrack; Durch Drücken der Esc-Taste oder der Eingabetaste in den Schieberegler-Textfeldern wird der Fokus nicht verloren
* &amp;lbrack;UI&amp;rbrack; Im Bedienfeld &quot;Eigenschaften&quot; überlappen sich die Schaltfläche &quot;Alle zurücksetzen&quot; und die Bezeichnung des Elementnamens.
* &amp;lbrack;UI&amp;rbrack; Probleme beim Andocken und Abdocken von Bedienfeldern
* &amp;lbrack;UI&amp;rbrack; Wenn Sie in einem Überlagerungsfenster scrollen, wird auch das darunter liegende Fenster durchlaufen
* &amp;lbrack;UI&amp;rbrack; Das Wechseln zur Listenansicht im Abschnitt &quot;Zuletzt verwendete Projekte&quot; auf dem Startbildschirm funktioniert nicht
* &amp;lbrack;UI&amp;rbrack; Symbol für Viewport-Anzeigemodus zeigt immer 2D/3D an

### **5.0.0 HAZELNUT**

*(Freigegeben: 20. Februar 2025)*

**Hinzugefügt**

* &amp;lbrack;Onboarding&amp;rbrack; Neue Startseite mit schnellem Zugriff auf Lerninhalte, Beispielprojekt, Schnellaktionen und aktuelle Projekte.
* &amp;lbrack;Onboarding&amp;rbrack; Schnell loslegen mit den neuen Schnellaktionen, die über die Startseite und das spezielle Bedienfeld zugänglich sind
* &amp;lbrack;Onboarding&amp;rbrack; &amp;lbrack;Inhalt&amp;rbrack; Schnellaktionen sind vordefinierte Arbeitsabläufe, die den Ebenenstapel mit den am häufigsten verwendeten Ebenen füllen.
* &amp;lbrack;Onboarding&amp;rbrack; Möglichkeit, ein neues Projekt über ein neues Schnellstartmenü, über Schnellaktionen oder über ein benutzerdefiniertes Projekt zu erstellen
* &amp;lbrack;Onboarding&amp;rbrack; Möglichkeit, leeres Projekt direkt von der Startseite über eine spezielle Schaltfläche zu erstellen
* &amp;lbrack;3D-Ansicht&amp;rbrack; Neuer erweiterter Raster- und Pathtracer, der neue Rendering-Funktionen (Eigenschaften wie Beschichtung, Glanz, Transparenz, Volumenstreuung) und visuelle Konsistenz im Substance-Ökosystem bietet
* &amp;lbrack;3D-Ansicht&amp;rbrack; Viewer-Einstellungen sind jetzt direkt in der 3D-Ansicht verfügbar
* &amp;lbrack;3D-Ansicht&amp;rbrack; Möglichkeit zum Speichern eines Renderschnappschusses in der Zwischenablage oder in Dateien
* &amp;lbrack;3D-Ansicht&amp;rbrack; Anzeigen eines Rasters zur Visualisierung des Szenenursprungs
* &amp;lbrack;3D-Ansicht&amp;rbrack; Schatten und Spiegelungen mit der Grundebene erfassen.
* &amp;lbrack;3D-Ansicht&amp;rbrack; Steuern Sie, wie reflektierend und undurchsichtig Ihre Grundebene ist
* &amp;lbrack;3D-Erfassung&amp;rbrack; Positionieren von Maschen auf dem Boden
* &amp;lbrack;Anwendung&amp;rbrack; Überprüfen der Hardwarekompatibilität beim Starten der Anwendung
* &amp;lbrack;Anwendung&amp;rbrack; Das Fenster für Absturzberichte wird jetzt direkt nach einem Absturz geöffnet
* &amp;lbrack;Inhalt&amp;rbrack; Beispielprojekt öffnen, um den Einstieg zu erleichtern
* &amp;lbrack;Export&amp;rbrack; Exportieren von Adobe Standard Material Shader in USD-Dateien
* &amp;lbrack;Generative KI&amp;rbrack; Aktivieren Sie das Tag &quot;Nicht ableiten&quot;, wenn Sie ein Bild als Eingabe in den Arbeitsabläufen &quot;Bild zu Textur&quot; verwenden.
* &amp;lbrack;Projekt&amp;rbrack; Miniaturen werden in der Projektdatei gespeichert, um das Öffnen von Projekten zu beschleunigen
* &amp;lbrack;Projekt&amp;rbrack; Festlegen in den Voreinstellungen zum Speichern von Cache-Daten innerhalb der Projektdatei mit verschiedenen Modi (kein Cache, heller Cache, voller Cache)
* &amp;lbrack;Skripterstellung&amp;rbrack; &amp;Klammer;Änderung&amp;Klammer; Qt-Migration zu Qt6.15 - Auswirkungen auf die Kompatibilität vorhandener Plug-ins
* &amp;lbrack;Skripterstellung&amp;rbrack; Standard-Plug-ins und -Skriptordner befinden sich jetzt im Ordner &quot;Dokumente&quot;
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Benutzeroberfläche für Plug-ins, um die optische Konsistenz mit den Hauptbedienfeldern von Sampler zu gewährleisten
* &amp;lbrack;Skripterstellung&amp;rbrack; Beispiele für 2 Plug-ins, um die Funktionen von Sampler Plug-ins kennenzulernen
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue open_3d_capture()-Funktion
* &amp;lbrack;Skripterstellung&amp;rbrack; Beim Einfügen einer Ebene können Sie steuern, ob diese über oder unter der Zielposition eingefügt wird

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz, wenn die Objekterfassung auf macOS nicht gestartet werden kann
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Hängenbleiben beim Hinzufügen von Elementen zum Projektfenster
* &amp;lbrack;Anwendung&amp;rbrack; Das Umbenennen eines Projektelements funktioniert nur, wenn Sie die Eingabetaste drücken
* &amp;lbrack;Anwendung&amp;rbrack; Menüeinträge zum Rückgängigmachen und Wiederholen sind nicht deaktiviert, wenn sie
* &amp;lbrack;Assets&amp;rbrack; Elemente können nicht aus dem Abschnitt &quot;Alle Bibliotheken&quot; des Bedienfelds &quot;Elemente&quot; gelöscht werden
* &amp;lbrack;Inhalt&amp;rbrack; Atlasersteller - Vorhandene Deckkraftmap verwenden, sofern vorhanden
* &amp;lbrack;Inhalt&amp;rbrack; Farb-ID-Überblendung - Korrigieren Sie die Farbauswahl in der Grundfarbe
* &amp;lbrack;Layers&amp;rbrack; Vermeiden Sie nutzlose Berechnungen bei der Verwendung von Generatoren
* &amp;lbrack;Layers&amp;rbrack; Das Tweaking eines Generators kann dazu führen, dass zu viele Computer ausgelöst werden.
* &amp;lbrack;Performance&amp;rbrack; Verbessern der GPU-Speicherverwaltung
* &amp;lbrack;Performance&amp;rbrack; Der Render-Cache darf beim Neustart der Anwendung nicht verwendet werden
* &amp;lbrack;Resources&amp;rbrack; Schreibgeschützte Dateien werden im Bedienfeld &quot;Elemente&quot; nicht angezeigt
* &amp;lbrack;Skripterstellung&amp;rbrack; Wiederverwenden einer Ebene nach dem Hinzufügen einer anderen Ebene zulassen
* &amp;lbrack;Skripterstellung&amp;rbrack; Das mehrmalige Ändern der Ebenenstapelstruktur in einem Skript kann fehlschlagen

**Entfernt:**

* &amp;lbrack;Anwendung&amp;rbrack; Entfernen der Unterstützung für .dng- und .nef-Bilddateien

## Version 4

### **4.5.2 GRUYERE**

*(Freigegeben: 07. November 2024)*

**Fest:**

* &amp;lbrack;Inhalt&amp;rbrack; Filter zum Zuschneiden, Sticken und Mischen von Heights

### **4.5.1 GRUYERE**

*(Freigegeben: 30. Juli 2024)*

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Das Malen von Graustufenmasken funktioniert nicht, was sich auf Werkzeuge wie Kopierstempel, Formverkrümmung und inhaltsbasierte Füllung auswirkt

### **4.5.0 GRUYERE**

*(Freigegeben: 18. Juli 2024)*

**Hinzugefügt**

* &amp;lbrack;Interoperabilität&amp;rbrack; Materialien an UE5, Blender, Maya, 3DsMax Unity senden
* &amp;lbrack;Inhalt&amp;rbrack; Neue Texturgenerator-Kategorie - Verläufe
* &amp;lbrack;Inhalt&amp;rbrack; HDRI-Werkzeug - Neuer Umgebungsdrehungsfilter

**Fest:**

* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Das Freigeben von .sbsar-Eingabewerten funktioniert nicht
* &amp;lbrack;Layers&amp;rbrack; Grundfarbe wird bei Graustufenbildern rot
* &amp;lbrack;Rendering&amp;rbrack; In Farbkanälen verwendete Graustufenbilder weisen einen falschen Farbraum auf
* &amp;lbrack;Skripterstellung&amp;rbrack; Bei Verwendung einer Exportvorgabe werden die erwarteten Kanäle möglicherweise nicht exportiert.
* &amp;lbrack;Inhalt&amp;rbrack; Dirt - Durch Anwenden eines Dirt-Filters über dem Bild auf Material wird eine schwarze Normalität erzeugt.
* &amp;lbrack;Inhalt&amp;rbrack; Relief - Die Skalierung eines Musters im Relief-Filter ist nicht linear zwischen 0 und 1
* &amp;lbrack;Inhalt&amp;rbrack; Kachel erstellen - Verbesserte Konsistenz von Normal- und Heights

### **4.4.1 FONDUE**

*(Freigegeben: 6. Juni 2024)*

**Fest:**

* &amp;lbrack;Inhalt&amp;rbrack; Dirt-Filter fehlt
* &amp;lbrack;Generative KI&amp;rbrack; Bei der Verwendung von Bild zu Textur kann ein Netzwerkfehler auftreten

### **4.4.0 FONDUE**

*(Freigegeben: 23. Mai 2024)*

**Hinzugefügt:**

* &amp;lbrack;Anwendung&amp;rbrack; 3D-Erfassungen-Cache ist jetzt in einem separaten Unterordner abgelegt
* &amp;lbrack;Generative KI&amp;rbrack; Bild zu Struktur (Beta)
* &amp;lbrack;Generative KI&amp;rbrack; Text zu Muster (Beta)
* &amp;lbrack;Generative KI&amp;rbrack; Text zu Textur (Beta)
* &amp;lbrack;Skripterstellung&amp;rbrack; Assets verfügen jetzt über eine Ressourceneigenschaft.
* &amp;lbrack;Skripterstellung&amp;rbrack; Ebenen verfügen jetzt über die Eigenschaft &quot;output_usages&quot;

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Öffnen einer beschädigten Projektdatei
* &amp;lbrack;Anwendung&amp;rbrack; Absturz, wenn das Projekt beschädigte Elemente enthält
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Trennen eines Monitors unter Windows
* &amp;lbrack;Anwendung&amp;rbrack; Falsches Anwendungssymbol auf der Windows-Taskleiste
* &amp;lbrack;Anwendung&amp;rbrack; Beschädigung der Hauptkonfigurationsdatei kann zum Löschen von Dateien führen
* &amp;lbrack;Anwendung&amp;rbrack; Bedienfelder erscheinen vor Popups
* &amp;lbrack;Inhalt&amp;rbrack; Texturgeneratoren haben unscharfe Miniaturen
* &amp;lbrack;Export&amp;rbrack; Aus einem importierten Bild generierter Deckkraftkanal bricht beim Exportieren von .sbs/.sbsar ab
* &amp;lbrack;Filter&amp;rbrack; Upscale kann je nach Eingabeebenen abstürzen
* &amp;lbrack;Generative KI&amp;rbrack; Mögliche Abstürze beim Empfangen unerwarteter Ergebnisse vom Dienst
* &amp;lbrack;Skripterstellung&amp;rbrack; Absturz beim automatischen Laden eines Plug-ins aus der Umgebungsvariablen
* &amp;lbrack;Skripterstellung&amp;rbrack; Möglicher Absturz beim Zuweisen der Ausgabenutzung mit der API

### **4.3.3 EMPANADA**

*(Freigegeben: 26. März 2024)*

**Hinzugefügt:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Neue erweiterte Auto-UV-Parameter während des Nachbearbeitungsprozesses
* &amp;lbrack;Filter&amp;rbrack; Perforationsfilter: Möglichkeit zum Umkehren und Ändern der Größe des benutzerdefinierten Musters

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Die Grundfarbe kann in macOS falsch sein
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Verarbeiten einer neuen Version
* &amp;lbrack;3D-Erfassung&amp;rbrack; Der Nachbearbeitungsschritt kann auf macOS abstürzen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Die Ebene &quot;Gittertransformation&quot; kann zu falschem Rendering führen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Starten von Sampler, während eine vorherige Instanz noch exportiert wird
* &amp;lbrack;Anwendung&amp;rbrack; Sampler reagiert keinen Moment, wenn es zum ersten Mal gestartet wird
* &amp;lbrack;Export&amp;rbrack; Anisotropie Winkelzuordnung wird nicht exportiert
* &amp;lbrack;Filter&amp;rbrack; Das Hinzufügen von Stoffgewebe zum Ebenenstapel kann zu einem Absturz führen
* &amp;lbrack;Filter&amp;rbrack; Das Hinzufügen von Relief zum Ebenenstapel kann zu einem Absturz führen
* &amp;lbrack;Filter&amp;rbrack; Inhaltsbasierte Füllung stürzt ab, wenn 32-Bit-Bilder verwendet werden
* &amp;lbrack;Filter&amp;rbrack; Relief: Die Deckkraft der folgenden Ebenen wird nicht vollständig überschrieben
* &amp;lbrack;Filter&amp;rbrack; Füllung: Der Mischmodus funktioniert nicht in Designer und Painter
* &amp;lbrack;Filter&amp;rbrack; Stickerei: automatische Farbauswahl funktioniert nicht
* &amp;lbrack;Voreinstellungen&amp;rbrack; Festlegen eines nicht unterstützten Pfads für den 3D-Erfassung-Cache verhindern
* &amp;lbrack;Voreinstellungen&amp;rbrack; Die Voreinstellung &quot;Normales Format&quot; funktioniert nicht
* &amp;lbrack;Skripterstellung&amp;rbrack; Bei den Kanalparametern von Asset.export_material wird Groß- und Kleinschreibung unterschieden

### **4.3.2 EMPANADA**

*(Freigegeben: 22. Februar 2024)*

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Das Speichern eines Projekts in einer Netzwerkfreigabe unter Windows beschädigt die Projektdatei.

### **4.3.1 EMPANADA**

*(Freigegeben: 15. Februar 2024)*

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz, wenn Bilddateien beim Generieren von Masken im Stapel nicht mehr zugänglich sind
* &amp;lbrack;Export&amp;rbrack; Beim Exportieren eines Materials mit &quot;Zuschneiden&quot; oder relativ zur Eingaberichtlinienebene werden ungültige Ergebnisse angezeigt
* &amp;lbrack;Layers&amp;rbrack; Seltener Absturz beim Rendern eines Ebenenstapels
* &amp;lbrack;Filter&amp;rbrack; Stickerei - Problem bei der Verwendung von Materialeingaben auf MacOS beheben
* &amp;lbrack;Filter&amp;rbrack; Stilisierung - Unterstützung von Texturgeneratoren
* &amp;lbrack;Filter&amp;rbrack; Muster - Festlegen der Parameternamen
* &amp;lbrack;Lokalisierung&amp;rbrack; Speichern unter... im Fenster mit Hardware-Informationen im Hilfemenü wird nicht lokalisiert angezeigt

### **4.3.0 EMPANADA**

*(Freigegeben: 25. Januar 2024)*

**Hinzugefügt**

* &amp;lbrack;Assets&amp;rbrack; Neuer Elementtyp: Texturgeneratoren
* &amp;lbrack;Assets&amp;rbrack; Neue Materialien in den Starter-Elementen
* &amp;lbrack;Assets&amp;rbrack; Neue Bildauswahl für Bildparameter im Eigenschaftenbedienfeld
* &amp;lbrack;Assets&amp;rbrack; Ziehen Sie Texturgeneratoren per Drag-and-Drop aus dem Bedienfeld Elemente auf die Bildwähler im Bedienfeld Eigenschaften .
* &amp;lbrack;Assets&amp;rbrack; Ziehen Sie Texturgeneratoren per Drag &amp; Drop aus dem Dateiexplorer des Betriebssystems.
* &amp;lbrack;Assets&amp;rbrack; Filter können Anpassungsgeneratoren über ein Benutzer-Tag an der Bildeingabe vorschlagen
* &amp;lbrack;Assets&amp;rbrack; Texturgeneratoren können festlegen, welcher Filter sie über ein Benutzer-Tag vorschlagen soll
* &amp;lbrack;Inhalt&amp;rbrack; Neuer perspektivischer Freistellungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Stilisierungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Füllmethode beim Füllfilter
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierter Stickereifilter
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierter Farbumflussfilter
* &amp;lbrack;Inhalt&amp;rbrack; Alle Filter wurden aktualisiert, um Texturgeneratoren zu unterstützen
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit, einen Texturgenerator-Ausgabekanal auszuwählen, wenn er dem Ebenenstapel hinzugefügt wird
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit, Vorgaben auf Texturgeneratoren einfach aufzulisten und anzuwenden
* &amp;lbrack;Layers&amp;rbrack; Anzeigen einer Vorschau des Texturgenerators in den Bildwählern
* &amp;lbrack;Layers&amp;rbrack; Texturgenerator-Parameter können angezeigt und exportiert werden
* &amp;lbrack;Layers&amp;rbrack; Weisen Sie beim Importieren eines einzelnen Bildes mit der Texturimport-Erstellungsvorlage die Grundfarbverwendung zu.
* &amp;lbrack;Layers&amp;rbrack; Feedback beim Versuch, inkompatible Dateien per Drag &amp; Drop in die Bildauswahl im Eigenschaftenfenster zu ziehen
* &amp;lbrack;Layers&amp;rbrack; Generieren eines Deckkraftkanals aus dem Alphakanal eines importierten Bildes
* &amp;lbrack;Layers&amp;rbrack; &quot;Bild zu Material&quot; (AI) ist beim Ändern der Kategorie schneller zu berechnen
* &amp;lbrack;Layers&amp;rbrack; Wählen Sie die relevanteste Ebene nach Verwendung einer Erstellungsvorlage aus.
* &amp;lbrack;Layers&amp;rbrack; Die Positions-Widgets können jetzt mit einem Schieberegler in der Gruppe &quot;Erweiterte Parameter&quot; angepasst werden.
* &amp;lbrack;Export&amp;rbrack; Zeigt einen Prozentsatz in der Warteschlange anstelle von Raw-Zahlen an.
* &amp;lbrack;Interoperabilität&amp;rbrack; Beim Senden an Painter wird jetzt der Deckkraftkanal als Alphakanal erkannt
* &amp;lbrack;Anwendung&amp;rbrack; Neues Dialogfeld zum Anzeigen und Speichern von Hardwareinformationen
* &amp;lbrack;Anwendung&amp;rbrack; Neue Voreinstellung zum Ändern der Standardprojektskalierung für jedes Height
* &amp;lbrack;Anwendung&amp;rbrack; Verbesserung der Darstellung veralteter Assets
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Funktionen asset.documentResolution() und asset.setDocumentResolution()
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Funktion select_asset()
* &amp;lbrack;Skripterstellung&amp;rbrack; Python-API für Texturgeneratoren
* &amp;lbrack;Skripterstellung&amp;rbrack; get_project_assets() gibt jetzt 3D-Objekte zurück
* &amp;lbrack;UI&amp;rbrack; Die Größe der Miniaturansichten von Elementen kann im Bedienfeld &quot;Elemente&quot; geändert werden
* &amp;lbrack;UI&amp;rbrack; Aktualisierte Viewport-Anzeigesymbole

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Zoom mit Mausrad ist bei 244 % blockiert
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Start beim Initialisieren der Grafik-API
* &amp;lbrack;Anwendung&amp;rbrack; Absturz, wenn der Projektname das Zeichen # enthält
* &amp;lbrack;Anwendung&amp;rbrack; Mögliche Abstürze beim Öffnen eines alten Projekts
* &amp;lbrack;Anwendung&amp;rbrack; Das erneute Öffnen des aktuellen Projekts kann zu einem Absturz führen
* &amp;lbrack;Anwendung&amp;rbrack; Einige Projektänderungen sind nicht registriert und gehen beim Schließen des Projekts ohne Warnung verloren, wenn sie nicht gespeichert wurden.
* &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar-Exportprobleme bei der Verwendung mehrerer Dateien mit demselben Namen
* &amp;lbrack;Export&amp;rbrack; Falscher Farbraum für exportierte Graustufenbilder .sbs/.sbsar-Datei
* &amp;lbrack;Filter&amp;rbrack; Probleme mit dem Verhalten &quot;Deckkraftüberblendung&quot;
* &amp;lbrack;Layers&amp;rbrack; SVG-Dateien werden manchmal nicht mit der richtigen Auflösung gerendert
* &amp;lbrack;Performance&amp;rbrack; Einige Projektspeicherungen auf der Festplatte sind nicht erforderlich.
* &amp;lbrack;Projekt&amp;rbrack; Beim Importieren eines alten Projekts werden die zugehörigen Vorgaben nicht geladen.
* &amp;lbrack;Skripterstellung&amp;rbrack; Parameter der ersten eingefügten Ebene können nicht abgerufen werden
* &amp;lbrack;UI&amp;rbrack; Das Popup-Fenster für die Vorschau kann sich beim Zeigen auf ein Element an der falschen Stelle oder auf dem falschen Bildschirm befinden
* &amp;lbrack;UI&amp;rbrack; Nicht angedockte Bedienfelder sind sichtbar und können oben im Begrüßungsbildschirm angezeigt werden.

### **4.2.2 DORAYAKI**

*(Freigegeben: 5. Dezember 2023)*

**Hinzugefügt:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; 3D-Erfassungen sind jetzt unter Windows 5 % bis 10 % schneller
* &amp;lbrack;3D-Erfassung&amp;rbrack; Verbessern der Netzbereinigung vor der Dezimierung
* &amp;lbrack;Motor&amp;rbrack; Substance Engine auf Version 9.0.3 aktualisieren
* &amp;lbrack;Layers&amp;rbrack; Inhaltsbasierte Füllung: Upstream-Update, verschiedene Fehlerbehebungen für Anwendungsfälle und Linux-Unterstützung

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Durch Klicken auf &quot;Zurück&quot; nach der Ausrichtung und dann auf &quot;Weiter&quot; wird die Punktwolke nicht aktualisiert
* &amp;lbrack;3D-Erfassung&amp;rbrack; Gitter mit Löchern nach dem Hinzufügen zum Projekt
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden des Vollbildmodus nach einer 3D-Erfassung
* &amp;lbrack;Anwendung&amp;rbrack; Absturz mit erstellten Bilddateien
* &amp;lbrack;Anwendung&amp;rbrack; Wenn beim Beenden von Sampler das Bedienfeld &quot;Elemente&quot; in &quot;Alle Bibliotheken&quot; leer ist, wird es beim Neustart neu gestartet
* &amp;lbrack;Anwendung&amp;rbrack; Speicherverlust beim Exportieren von Material
* &amp;lbrack;Anwendung&amp;rbrack; Das Öffnen eines mit einer früheren Sampler-Version gespeicherten Projekts kann zu einem Absturz führen
* &amp;lbrack;Anwendung&amp;rbrack; Potenzielle Abstürze bei fehlender Konvertierung von 3D-Netzen
* &amp;lbrack;Anwendung&amp;rbrack; Automatischer Absturz beim Öffnen einer .sbsar-Datei, während Sampler ausgeführt wird
* &amp;lbrack;Export&amp;rbrack; Absturz beim Exportieren einer .sbs/.sbsar-Datei mit einer benutzerdefinierten Verwendung
* &amp;lbrack;Export&amp;rbrack; Exportierte Normalmaps sind immer DirectX, unabhängig von der Benutzereinstellung
* &amp;lbrack;Export&amp;rbrack; Das Exportieren eines 3D-Objekts in eine FBX-Datei unter macOS funktioniert nicht
* &amp;lbrack;Export&amp;rbrack; Inkonsistenzen beim Exportieren eines Ebenenstapels mit einem Stickfilter als SBS-/.sbsar-Datei
* &amp;lbrack;Export&amp;rbrack; Manchmal funktioniert das Exportieren von .sbs/.sbsar-Dateien nicht
* &amp;lbrack;Export&amp;rbrack; Manchmal beim Exportieren einer .sbs/.sbsar-Datei haben Bilder nicht die richtige Bittiefe
* &amp;lbrack;Layers&amp;rbrack;  Wenn Sie eine Spritzer-Ebene ausblenden, wird stattdessen das erste untergeordnete Element gerendert
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Laden der Maske in der Helligkeits-/Kontrastebene
* &amp;lbrack;Layers&amp;rbrack; Nach dem Löschen der Ebene werden irreführende Fehlermeldungen angezeigt
* &amp;lbrack;Layers&amp;rbrack; Möglicher Absturz beim Herunterstufen eines Assets
* &amp;lbrack;Layers&amp;rbrack; Einige Ausgänge sind nur dann mit Eingängen verbunden, wenn die Verwendung im Bedienfeld &quot;Kanaleinstellungen&quot; erzwungen wird
* &amp;lbrack;Physische Größe&amp;rbrack; Das Dropdown der Referenzebene kann versehentlich zurückgesetzt werden
* &amp;lbrack;UI&amp;rbrack; Symbol &quot;Vorlageninfo importieren&quot; muss aktualisiert werden
* &amp;lbrack;UI&amp;rbrack; Ein Tipp für einen Viewport-Tastaturbefehl wird immer angezeigt, wenn sich das Viewport-Layout ändert

### **4.2.1 DORAYAKI**

*(Freigegeben: 21. September 2023)*

**Hinzugefügt:**

* &amp;lbrack;Inhalt&amp;rbrack; Bild zu Material - Verbessern der Generierung von Mikrodetails in normalen Karten
* &amp;lbrack;Inhalt&amp;rbrack; Bild zu Material - Neuer Parameter für die Begeisterungsintensität
* &amp;lbrack;Layers&amp;rbrack; Bilder können in den Bildimportebenen hinzugefügt werden.
* &amp;lbrack;Layers&amp;rbrack; Bilder können in den Bildimportebenen entfernt werden.
* &amp;lbrack;Layers&amp;rbrack; Ungültige Ebenen können jetzt gelöscht werden.
* &amp;lbrack;2D Ansicht&amp;rbrack; Umschalt+C-Verknüpfung zum Zurückblättern der Kanäle
* &amp;lbrack;3D-Erfassung&amp;rbrack; Warntoast anzeigen, wenn Benutzer weniger als 20 Bilder importieren
* &amp;lbrack;Anwendung&amp;rbrack; Neue Voreinstellungen zum Festlegen des Standardwerts für die Kachelung der Materialtextur
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisierte Tutorial-Benutzeroberfläche für Bild-zu-Material (AI) und Hochskalieren
* &amp;lbrack;Skripterstellung&amp;rbrack; 3D-Erfassung-API: DatasetInfo verfügt über mehr Daten, wenn Capture3dState auf align festgelegt ist.
* &amp;lbrack;Skripterstellung&amp;rbrack; Neues select_asset-Argument für create_asset(). Neue Funktionen: wait_for_computation() und clear_render_cache()

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Absturz, wenn der Zuschneidebereich sehr klein ist
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Hinzufügen oder Anpassen des Zuschneidefilters
* &amp;lbrack;Layers&amp;rbrack; Die Quadratur des Zuschneidebereichs führt zu einer falschen Auflösung der Materialausgabe
* &amp;lbrack;Layers&amp;rbrack; Die Ausgaben verschwinden manchmal, wenn mehrere Ebenen deaktiviert sind
* &amp;lbrack;Layers&amp;rbrack; Der Render-Cache wird mit den Filtern &quot;Bild zu Material&quot; (AI) und &quot;Hochskalieren&quot; möglicherweise nicht ordnungsgemäß ungültig
* &amp;lbrack;Layers&amp;rbrack; Hochskalierungsfilter kann nicht hinzugefügt werden, wenn Sie im Warnpopup &quot;Diese Meldung nicht mehr anzeigen&quot; auswählen
* &amp;lbrack;Layers&amp;rbrack; Das Bild kann nach der Änderung nicht im Stickereifilter wiederhergestellt werden
* &amp;lbrack;Export&amp;rbrack; Die exportierte normale Kartenauflösung ändert sich, wenn das normale Format geändert wird
* &amp;lbrack;Export&amp;rbrack; Entfernen Sie das Dateinamensuffix &quot;\_environment&quot; beim Exportieren einer Umgebung
* &amp;lbrack;Export&amp;rbrack; Eine .sbsar-Datei kann nicht exportiert werden, wenn sich eine Verkrümmungstransformationsebene im Ebenenstapel befindet
* &amp;lbrack;2D Ansicht&amp;rbrack; &quot;An Bildschirm anpassen&quot; funktioniert nicht, wenn sich die Auflösung ändert
* &amp;lbrack;Anwendung&amp;rbrack; Nachdem das Anwendungsfenster während der Berechnung geschlossen wurde, kann der Anwendungsprozess noch ausgeführt werden
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Render-Cache beim Umschalten GPU-beschleunigter neuronaler Netzwerke ungültig
* &amp;lbrack;Skripterstellung&amp;rbrack; Das Benennen eines Plug-ins als vorhandener Bedienfeldname führt zu unerwarteten Verhalten
* &amp;lbrack;UI&amp;rbrack; Wenn Sie auf ein Element mit einer QuickInfo klicken, wird die QuickInfo bis zum Neustart ausgeblendet
* &amp;lbrack;UI&amp;rbrack; Der Skalierungswert des Heights kann sich beim Wechseln von Elementen ändern
* &amp;lbrack;UI&amp;rbrack; Falscher Rand in Kombinationsfeldern

### **4.2 DORAYAKI**

*(Freigegeben: 05. September 2023)*

**Hinzugefügt:**

* &amp;lbrack;Inhalt&amp;rbrack; Wesentlich verbesserte Bild-zu-Material (AI)- und Delighter-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Hochskalierungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Der Freistellungsfilter hat jetzt eine dynamische Ausgabeauflösung.
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Einstellung &quot;Dokumentgröße hinzufügen&quot;.
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Neue Umschalttaste &quot;Zuschnitt hinzufügen&quot;.
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Neuer Schalter &quot;Material hochskalieren&quot;
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Anzeigen der importierten Bildgröße
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Feedback geben, wenn einige importierte Bilder nicht verwendet werden können
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Warnung bei inkonsistenten Bildgrößen
* &amp;lbrack;Materialerstellungsvorlage&amp;rbrack; Neue Warnungen und QuickInfos
* &amp;lbrack;Layers&amp;rbrack; Anzeigen der Auflösung der Ebenen im Ebenenstapel
* &amp;lbrack;Layers&amp;rbrack; Die Ebenenberechnungsauflösung kann jetzt entweder auf Dokumentgröße oder Eingabegröße eingestellt werden.
* &amp;lbrack;Layers&amp;rbrack; Ebenenauflösung im Ebenenstapel anzeigen
* &amp;lbrack;Layers&amp;rbrack; Ändern Sie ggf. eine Richtlinie zur Ebenenauflösung in Dokument- oder Ebeneneingabe .
* &amp;lbrack;Layers&amp;rbrack; Benutzer warnen, wenn manuell ein Hochskalieren-Filter hinzugefügt wird, und Dokumentation bereitstellen
* &amp;lbrack;Layers&amp;rbrack; Warnen Sie den Benutzer, wenn eine lineare Hochskalierung durchgeführt wird, und bieten Sie an, stattdessen den Filter Hochskalieren zu verwenden.
* &amp;lbrack;Layers&amp;rbrack; Die Berechnung einer Bild-zu-Material-Ebene (AI) kann jetzt schneller abgebrochen werden, um die Renderzeiten beim Anpassen des Ebenenstapels zu verbessern
* &amp;lbrack;Layers&amp;rbrack; Die Berechnung einer Hochskalierungsebene kann jetzt schneller abgebrochen werden, um die Renderzeiten beim Anpassen des Ebenenstapels zu verbessern
* &amp;lbrack;Export&amp;rbrack; Überschreiben der Auflösung exportierter Texturen zulassen
* &amp;lbrack;Export&amp;rbrack; Kanäle für die Exportliste sind jetzt sortiert
* &amp;lbrack;Export&amp;rbrack; Kanalauflösung in der Liste der zu exportierenden Kanäle anzeigen
* &amp;lbrack;Anwendung&amp;rbrack; Neue Voreinstellung zum Aktivieren oder Deaktivieren von GPU-beschleunigten neuronalen Netzwerken
* &amp;lbrack;UI&amp;rbrack; Dropdown-Listen mit verbesserter Auflösung
* &amp;lbrack;UI&amp;rbrack; Neue Symbole für die Filter &quot;Gittertransformation&quot;, &quot;Gitternachbearbeitung&quot; und &quot;Weben&quot;
* &amp;lbrack;UI&amp;rbrack; Bedienfeld &quot;Freigeben&quot; in &quot;Exportieren&quot; umbenennen
* &amp;lbrack;Skripterstellung&amp;rbrack; Unterstützung der Ausgabeauflösung für Ebenen zur Export-API hinzufügen
* &amp;lbrack;Skripterstellung&amp;rbrack; Der Bild-Import-API wurden die Optionen &quot;Zuschneiden&quot;, &quot;Hochskalieren&quot; und &quot;Dokumentgröße&quot; hinzugefügt
* &amp;lbrack;Onboarding&amp;rbrack; Neue Tutorials
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisieren des Begrüßungsbildschirms und des Inhalts der neuen Bildschirme
* &amp;lbrack;Motor&amp;rbrack; Substance Engine auf Version 9.0.1 aktualisieren

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Verbessern der Benennung von Genauigkeits-Optionen in den Parametern der Ausrichtungseinstellungen
* &amp;lbrack;Anwendung&amp;rbrack; Das Importieren von Bildern mit nicht mehreren 16 Dimensionen kann zu einem Absturz führen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Duplizieren eines Assets im Projektfenster
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Wechseln von Elementen im Projektfenster
* &amp;lbrack;Inhalt&amp;rbrack; Das Malen einer benutzerdefinierten Maske für den Snow-Filter funktioniert nicht richtig
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Änderungen der exponierten Parameter können beim Materialwechsel verloren gehen
* &amp;lbrack;Interoperabilität&amp;rbrack; Das Senden eines Materials über das Exportierenbedienfeld kann zu einem Absturz führen
* &amp;lbrack;Layers&amp;rbrack; Inhaltsbasierte Füllung wird nicht mehr berechnet, wenn von einer einzelnen Bildeingabe zu einer Materialeingabe gewechselt wird
* &amp;lbrack;Layers&amp;rbrack; Absturz nach dem Duplizieren eines Umgebungslichts, das ein Material enthält
* &amp;lbrack;Layers&amp;rbrack; Bildimportebene zeigt falschen Bildnamen im Eigenschaftenfenster an, wenn die Bilddatei umbenannt wurde
* &amp;lbrack;Layers&amp;rbrack; Manchmal wird ein Drehfeld auf einer inaktiven Ebene angezeigt
* &amp;lbrack;Layers&amp;rbrack; Manchmal funktioniert das Ändern der Ausgabenutzung eines Bildes in einer Bildimportebene nicht
* &amp;lbrack;Layers&amp;rbrack; Tippfehler im Fenster &quot;Erstellungsvorlage&quot;
* &amp;lbrack;UI&amp;rbrack; 3D-Ansichtsport-Onboarding-QuickInfo hat Fokusprobleme
* &amp;lbrack;UI&amp;rbrack; Der Bildname kann überlaufen, wenn der Dateiname zu lang ist
* &amp;lbrack;UI&amp;rbrack; Geringfügige Probleme mit dem Layout der Pinselsymbolleiste bei Verwendung des Radiergummis
* &amp;lbrack;UI&amp;rbrack; Zeichenfolgen werden in einigen Sprachen im Bedienfeld &quot;Anzeigeeinstellungen&quot; abgeschnitten
* &amp;lbrack;UI&amp;rbrack; Wenn die QuickInfo für das Ansichtsfenster angezeigt wird, wird durch Drücken der Leertaste ein neues Projekt erstellt.

### **4.1.2 CANNOLI**

*(Freigegeben: 20. Juni 2023)*

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Speicherlecks beim Anpassen von Substance-Materialien und Filtern, die zu Abstürzen führen

### **4.1.1 CANNOLI**

*(Freigegeben: 6. Juni 2023)*

**Hinzugefügt**

* &amp;lbrack;Motor&amp;rbrack; Substance Engine auf Version 9.0 aktualisieren
* &amp;lbrack;Interoperabilität&amp;rbrack; 3D-Objekte an Stager und Painter senden

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Anwendungen stürzt ab, wenn der 3D-Erfassung-Renderer fehlschlägt
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz, wenn ein Bild nicht geladen werden kann
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Erreichen des Schritts &quot;Gitterrekonstruktion&quot;
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Ändern der Größe des Begrenzungsrahmens
* &amp;lbrack;3D-Erfassung&amp;rbrack; Beim Importieren von Masken, die der Konvention folgen, wird die Maske nicht ordnungsgemäß zugewiesen.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Renderfehler beim Anpassen des Begrenzungsrahmens
* &amp;lbrack;3D-Erfassung&amp;rbrack; Der Wechsel zwischen Versions- und Umschalt-Rendering-Optionen während des 3D-Erfassung-Nachbearbeitungsprozesses ist langsam
* &amp;lbrack;3D-Erfassung&amp;rbrack; Das Wechseln zwischen Versionen während des 3D-Erfassung-Nachbearbeitungsschritts ist manchmal unterbrochen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Start
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Duplizieren eines umbenannten Materials
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Öffnen eines älteren .alch-Projekts ohne seinen Abhängigkeitsordner
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Anschließen/Abziehen eines Bildschirms, Computer geht in den Ruhemodus oder wird remote aufgerufen
* &amp;lbrack;Anwendung&amp;rbrack; Abstürze und Speicherlecks im Zusammenhang mit der Verwaltung nicht dauerhafter Elemente
* &amp;lbrack;Export&amp;rbrack; Die Auswahl des Materialformats für 3D-Objektdateitypen, in die Texturen eingebettet oder referenziert werden, sollte deaktiviert sein.
* &amp;lbrack;Export&amp;rbrack; Absturz, wenn beim Exportieren von 3D-Objekten etwas schief geht
* &amp;lbrack;Export&amp;rbrack; Absturz beim Exportieren einer .sbs/.sbsar-Datei
* &amp;lbrack;Export&amp;rbrack; Absturz beim Importieren einer benutzerdefinierten Vorgabe, die dieselbe Bezeichnung, aber nicht denselben Dateinamen aufweist
* &amp;lbrack;Export&amp;rbrack; Das Exportieren einer Umgebungsbeleuchtung in eine .sbs/.sbsar-Datei funktioniert manchmal nicht
* &amp;lbrack;Export&amp;rbrack; Der Gltf/Glb-Export codiert Texturen in base64
* &amp;lbrack;Export&amp;rbrack; Das Namenstextfeld funktioniert beim erneuten Fokussieren nicht
* &amp;lbrack;Export&amp;rbrack; Kachelung beibehalten funktioniert beim Exportieren einer Bild-zu-Material-Ebene (AI-gestützt) in eine SBS-/.sbsar-Datei nicht
* &amp;lbrack;Export&amp;rbrack; Beim Exportieren von gltf und Ersetzen von Dateien ist die Liste der zu ersetzenden Dateien nicht korrekt
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Zufällige Seed-Dateien funktionieren nicht in exportierten .sbs/.sbsar-Dateien
* &amp;lbrack;Layers&amp;rbrack; Die inhaltsbasierte Füllung stürzt manchmal ab, wenn sie zum zweiten Mal hinzugefügt wird
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Berechnen eines Ebenenstapels
* &amp;lbrack;Layers&amp;rbrack; Disk-Cache für Image-to-Material (AI) funktioniert nicht
* &amp;lbrack;Layers&amp;rbrack; Möglicher Absturz beim Anpassen einer Ebene
* &amp;lbrack;Performance&amp;rbrack; Speicherlecks
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Speichern eines Projekts
* &amp;lbrack;Projekt&amp;rbrack; Wenn Sie dasselbe Projekt zweimal hintereinander importieren, werden die Elemente dupliziert
* &amp;lbrack;UI&amp;rbrack; Abgerundete Schaltflächen mit nur einem Symbol werden nicht korrekt gerendert

### 4.1.0 Cannoli

*(Freigegeben: 28. März 2023)*

**Hinzugefügt:**

* &amp;lbrack;Inhalt&amp;rbrack; Neuer Stickereifilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Farbverkrümmungsfilter
* &amp;lbrack;UI&amp;rbrack; Exportoption &quot;Datei&quot; hinzufügen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Schaltfläche &quot;Zurück&quot; ist jetzt für den Ausrichtungsschritt verfügbar
* &amp;lbrack;3D-Erfassung&amp;rbrack; Bilder behandeln JPEG EXIF-Ausrichtung
* &amp;lbrack;3D-Erfassung&amp;rbrack; Scripting - Neue dataset_info.camera-Eigenschaft
* &amp;lbrack;3D-Erfassung&amp;rbrack; Unterstützung für Linux hinzufügen (siehe Dokumentation)
* &amp;lbrack;3D-Erfassung&amp;rbrack; Lesezugriff der importierten Bilder überprüfen
* &amp;lbrack;Onboarding&amp;rbrack; Lernen - 2 neue Tutorials (Sticken und Malen verformen)
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisierter Inhalt zu neuen Funktionen

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Kameraposition beim Ändern der Version beibehalten
* &amp;lbrack;3D-Erfassung&amp;rbrack; Alle Gruppen eines Objekts in einem Objekt zusammenführen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Generierte Gitter in Original umbenannt
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Generieren der Miniaturansicht eines nicht vorhandenen Bildes
* &amp;lbrack;Assets&amp;rbrack; Das Papierkorbsymbol im Bedienfeld &quot;Elemente&quot; hat keine Wirkung
* &amp;lbrack;Inhalt&amp;rbrack; Das Aktualisieren von Filtern mit Materialsteckplätzen funktioniert nicht wie erwartet
* &amp;lbrack;Export&amp;rbrack; Mögliche Abstürze beim Exportieren eines Assets mit bestimmten Filtern
* &amp;lbrack;Export&amp;rbrack; SBS/SBSAR-Export - Bildimportebenen hatten Priorität vor Bildparametern
* &amp;lbrack;Export&amp;rbrack; Die UE4-Exportvorgabe funktioniert nicht mit PNG
* &amp;lbrack;Layers&amp;rbrack; Absturz beim gleichzeitigen Ablegen eines Materials und eines Filters aus dem Betriebssystem-Explorer
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Ziehen einer SBSAR-Datei mit einer Bilddatei
* &amp;lbrack;Layers&amp;rbrack; Der Kanal für die Deckkraft der Stickerei kann vollständig weiß sein.
* &amp;lbrack;Lokalisierung&amp;rbrack; Die chinesische Sprache wird unter Linux möglicherweise standardmäßig angezeigt
* &amp;lbrack;Performance&amp;rbrack; Es wurde ein Speicherproblem beim Entfernen einer Ebene aus einem Asset behoben.
* &amp;lbrack;Projekt&amp;rbrack; Möglicher Absturz beim Speichern
* &amp;lbrack;UI&amp;rbrack; Fehlenden Abstand auf der Menüschaltfläche &quot;Version&quot; hinzufügen
* &amp;lbrack;UI&amp;rbrack; Schaltfläche &quot;Abbrechen&quot; wird nicht richtig angezeigt
* &amp;lbrack;UI&amp;rbrack; Deaktivieren der Schieberegleranimation für die 3D-Erfassung von Nachbearbeitungsparametern
* &amp;lbrack;UI&amp;rbrack; Das Fenster Materialerstellungsvorlage wird nicht geschlossen, wenn Sie außerhalb des Fensters klicken.
* &amp;lbrack;UI&amp;rbrack; Der Schnellzugriff auf den Filter schließt sich, wenn Sie außerhalb klicken

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.2 Bananen

*(Freigegeben: 09. März 2023)*

**Hinzugefügt:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Datenträgernutzung zeigt die verwendete Menge an
* &amp;lbrack;3D-Erfassung&amp;rbrack; Der Import von Fotos erfolgt asynchron und schneller
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Klassen und Funktionen zum Skripten der 3D-Erfassung-Funktion
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue ExportController-Klasse zum Ausführen von Aktionen, wenn der Export abgeschlossen, fehlgeschlagen oder abgebrochen wird
* &amp;lbrack;Skripterstellung&amp;rbrack; Übergabe-Argumente Python-Skripte, die mit —run-script ausgeführt werden
* &amp;lbrack;UI&amp;rbrack; UI-Feedback beim Ziehen eines Elements über das Ebenenbedienfeld
* &amp;lbrack;Inhalt&amp;rbrack; Farbtemperaturfilter arbeitet jetzt an Materialien
* &amp;lbrack;Inhalt&amp;rbrack; &quot;Normal zu Height&quot;-Filter bieten eine neue Option zum Beibehalten der Unterteilung

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Korrigierte Bildgröße im Schritt zur Datensatzausrichtung
* &amp;lbrack;3D-Erfassung&amp;rbrack; Entfernen duplizierter Scheitelpunkte nach dem Ausgliedern von UVs
* &amp;lbrack;3D-Erfassung&amp;rbrack; MacOS - Bessere Erkennung, wenn 3D-Erfassungen verfügbar sind
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Schließen des Datenfensters beim Importieren von 3D-Erfassungen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Generieren einer neuen Version
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Versuch, das 3D-Objekt im Viewer zu laden
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz bei Verwendung eines Pfads mit Nicht-UTF8-Zeichen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Tipps &amp; Klicks Tippfehler
* &amp;lbrack;3D-Erfassung&amp;rbrack; Gitter werden nicht mehr so skaliert, dass sie in den Einheitswürfel passen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz beim Schließen der 3D-Erfassung beim Rendern verhindern
* &amp;lbrack;3D-Erfassung&amp;rbrack; Durch Entfernen einer Maske verschwindet das Bild
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim gleichzeitigen Importieren von zwei Elementen
* &amp;lbrack;Anwendung&amp;rbrack; Sichern früherer Versionen von Elementen beim Öffnen eines Projekts, wenn diese nie gesichert wurden
* &amp;lbrack;Anwendung&amp;rbrack; Durch Baking erzeugte Map richtig zwischenspeichern, wenn nicht alle Maps bereits vorhanden sind
* &amp;lbrack;Anwendung&amp;rbrack; Vollbild stürzt ab, wenn ein 3D-Objekt angezeigt wird.
* &amp;lbrack;Anwendung&amp;rbrack; Letztes Material wird beim Speichern des Projekts dupliziert
* &amp;lbrack;Anwendung&amp;rbrack; Absturz verhindern, wenn der Mesh-Nachbearbeitungscomputer während des Backvorgangs abgebrochen wird
* &amp;lbrack;Anwendung&amp;rbrack; Beim erneuten Öffnen des aktuellen Projekts werden die Änderungen nicht verworfen
* &amp;lbrack;Anwendung&amp;rbrack; Generieren von Miniaturen für 3D-Objekte anhalten
* &amp;lbrack;2D Ansicht&amp;rbrack; Absturz bei Verwendung des Pinselwerkzeugs
* &amp;lbrack;Inhalt&amp;rbrack; Inhaltsbasierte Füllung - Berechnung bleibt möglicherweise hängen
* &amp;lbrack;Inhalt&amp;rbrack; Der Atlas-Erstellungsfilter verkleinert den Deckkraftkanal
* &amp;lbrack;Export&amp;rbrack; Korrektur der Exportwarteschlange für fehlgeschlagene Exporte
* &amp;lbrack;Export&amp;rbrack; OBJ-Export erstellt Objekt 100-mal kleiner als erwartet
* &amp;lbrack;Layers&amp;rbrack; Farbbilder, die als Graustufen-Kanäle importiert wurden, werden jetzt als Graustufen betrachtet
* &amp;lbrack;Export&amp;rbrack; FBX-Dateien können nicht in Anwendungen von Drittanbietern importiert werden
* &amp;lbrack;Export&amp;rbrack; Shader-Ausgabenamen in USD-Dateien sind nicht korrekt
* &amp;lbrack;Layers&amp;rbrack; Der Bildname wird nicht aktualisiert, wenn sein Name im Betriebssystem-Explorer geändert wird
* &amp;lbrack;Skripterstellung&amp;rbrack; Fehlermeldung beim erneuten Laden eines ungültigen Skripts anzeigen
* &amp;lbrack;UI&amp;rbrack; Basismaterial-Schaltfläche deaktiviert, wenn nicht verfügbar
* &amp;lbrack;UI&amp;rbrack; Absturz beim Zugriff auf das Dateidialogfeld im Fenster &quot;Materialerstellungsvorlage&quot;
* &amp;lbrack;UI&amp;rbrack; Der Schnellzugriff ist auch bei geschlossenem Ebenenbedienfeld möglich
* &amp;lbrack;UI&amp;rbrack; Symbole für &quot;Senden an&quot; sind falsch ausgerichtet
* &amp;lbrack;UI&amp;rbrack; Das Ebenensymbol ändert sich, wenn Sie auf das Symbol &quot;Angleichen&quot; klicken

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.1 Bananen

*(Freigegeben: 07. Februar 2023)*

**Fest:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Bei Masken kann die Texturprojektion unterbrochen werden
* &amp;lbrack;3D-Erfassung&amp;rbrack; Auf dem Objekt können Artefakte erscheinen.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Das exportierte Gitter kann sehr klein sein

**Bekannte Probleme:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; FBX- und OBJ-Exporte skalieren das Ergebnis herunter
* &amp;lbrack;3D-Erfassung&amp;rbrack; 3D-Erfassungen sind auf MacOS verfügbar, auch wenn Ihre Hardware nicht kompatibel ist. Lesen Sie die Dokumentation.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Absturz, wenn die Gitterrekonstruktion abgeschlossen ist.
* &amp;lbrack;Layers&amp;rbrack; Die inhaltsbasierte Füllung kann hängen bleiben, wenn Sie die Ebenen unten anpassen
* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 4.0.0 Bananen

*(Freigegeben: 31. Januar 2023)*

**Hinzugefügt:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Erstellen von 3D-Objekten aus Bildern
* &amp;lbrack;3D-Erfassung&amp;rbrack; Assistent für dedizierte 3D-Erfassungen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Importieren oder Generieren von Schwarzweißmasken in Ihrem Datensatz
* &amp;lbrack;3D-Erfassung&amp;rbrack; Ausrichtungsergebnis - Alle übereinstimmenden Funktionen als Punktwolke anzeigen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Ausrichtungsergebnis - Kameras anzeigen und mit ihnen interagieren, die jedem ausgerichteten Foto zugeordnet sind
* &amp;lbrack;3D-Erfassung&amp;rbrack; Definieren des Wiederaufbaubereichs mithilfe eines Begrenzungsrahmen-Widgets
* &amp;lbrack;3D-Erfassung&amp;rbrack; Skalieren, Verschieben und Drehen auf allen Achsen des Begrenzungsrahmen-Widgets
* &amp;lbrack;3D-Erfassung&amp;rbrack; Festlegen der Geometriepräzision für das rekonstruierte Gitter
* &amp;lbrack;3D-Erfassung&amp;rbrack; Gitter und Strukturen mit einer neuen Version optimieren.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Jede der Versionen wird automatisch auf den Zielflächennummernsatz dezimiert.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Bei der Nachbearbeitung werden Texturen automatisch ausgepackt, neu projiziert und die Height- und AO-Informationen aus dem High-Poly-Gitter entfernt.
* &amp;lbrack;3D-Erfassung&amp;rbrack; Originalergebnis oder Originalversion zum Sampler-Projekt hinzufügen
* &amp;lbrack;3D-Erfassung&amp;rbrack; Neue Mesh-Nachbearbeitungsebene zum automatischen Dezimieren, Ausgliedern, Neuprojektieren von Texturen und Backen von Details der zugrunde liegenden Mesh-Ebene
* &amp;lbrack;3D-Erfassung&amp;rbrack; Neue Ebene &quot;Gittertransformation&quot; zum Skalieren, Drehen oder Verschieben der zugrunde liegenden Gitterebene
* &amp;lbrack;Export&amp;rbrack; Neues Exportfenster
* &amp;lbrack;Export&amp;rbrack; Spezielle Einstellungen und Benutzeroberfläche je nach Elementtyp (Material, Umgebungslicht, Gitter)
* &amp;lbrack;Export&amp;rbrack; Exportieren Sie das Gitter als USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &amp;lbrack;Export&amp;rbrack; Materialart beim Exportieren von Substance-Dateien definieren (SBSAR, SBS)
* &amp;lbrack;UI&amp;rbrack; Cache-Einstellungen auf eine neue Registerkarte im Popup &quot;Voreinstellungen&quot; verschieben
* &amp;lbrack;Anwendung&amp;rbrack; Die Größe von 2D- und 3D-Viewports kann jetzt geändert, ausgetauscht und vertikal gestapelt werden
* &amp;lbrack;Anwendung&amp;rbrack; Neue Umgebungsvariable SAMPLER_RESOURCES_PATH zum Hinzufügen zusätzlicher Starter-Assets
* &amp;lbrack;Skripterstellung&amp;rbrack; Die Umgebungsvariablen SAMPLER_PLUGIN_PATH und SAMPLER_SCRIPT_PATH wurden hinzugefügt, um Plug-ins und Skripte beim Start zu importieren.
* &amp;lbrack;Skripterstellung&amp;rbrack; Exportfunktionen für Materialien, Umgebungslichter und 3D-Objekte hinzugefügt
* &amp;lbrack;Skripterstellung&amp;rbrack; Bezeichner, Standardwert, Minimal- und Maximalwerte, Beschriftungen und Enumerationswerte zu Parametern hinzugefügt
* &amp;lbrack;Skripterstellung&amp;rbrack; Funktion import_textures hinzugefügt, um beim Importieren von Bildern eine benutzerdefinierte Verwendung einzugeben

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Öffnen eines zuletzt verwendeten Projekts und Speichern im Bestätigungsdialogfeld
* &amp;lbrack;Anwendung&amp;rbrack; Dateidialog verhindert das Öffnen von .ssa-Dateien
* &amp;lbrack;Anwendung&amp;rbrack; Dateidialoge können in einem Hintergrundfenster in macOS angezeigt werden
* &amp;lbrack;Anwendung&amp;rbrack; Potenzieller Absturz beim Öffnen von 3.2-Projekten
* &amp;lbrack;Anwendung&amp;rbrack; Beim Auswählen einer Datei wird das Dialogfeld &quot;Datei&quot; geschlossen, bevor Warnungen angezeigt werden.
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Das Exportieren von parametrischen Umgebungslichtern funktioniert nicht
* &amp;lbrack;Layers&amp;rbrack; Der Link &quot;Zum Durchsuchen hier klicken&quot; im Ebenenstapel funktioniert nicht mehr
* &amp;lbrack;Layers&amp;rbrack; Das Malen mehrerer Bilder innerhalb einer Ebene funktioniert manchmal nicht
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie ein Bild in den Ebeneneigenschaften festlegen, wird die Miniaturansicht der Bildauswahl nicht aktualisiert
* &amp;lbrack;Layers&amp;rbrack; Das Tweenen eines Sampler-Elements, das als Ebene hinzugefügt wurde, funktioniert nicht
* &amp;lbrack;Projekt&amp;rbrack; Unerwünschte Aktualisierung von Elementen beim Öffnen eines Projekts
* &amp;lbrack;Skripterstellung&amp;rbrack; Das Durchsuchen des Plug-in-Ordners schlägt unter Windows manchmal fehl
* &amp;lbrack;Skripterstellung&amp;rbrack; Absturz bei Verwendung von &quot;open_project()&quot; in einem Python-Skript
* &amp;lbrack;Skripterstellung&amp;rbrack; JPEG-Export fehlt in der API
* &amp;lbrack;Skripterstellung&amp;rbrack; Der Protokollbereich ist nicht schreibgeschützt
* &amp;lbrack;Skripterstellung&amp;rbrack; Der Parameterwert image_picker funktioniert nicht
* &amp;lbrack;UI&amp;rbrack; Symbol &quot;Fehlendes Element&quot; für Umgebungslichter im Projektfenster
* &amp;lbrack;UI&amp;rbrack; Dropdown-Liste &quot;An Designer-Format senden&quot; im Popup &quot;Voreinstellungen&quot; kann leer sein
* &amp;lbrack;UI&amp;rbrack; Einige Schaltflächen haben einen falschen Stil
* &amp;lbrack;UI&amp;rbrack; Die Beschriftung überlappt die Schaltflächen in Schaltflächengruppen-Widgets.
* &amp;lbrack;UI&amp;rbrack; Die QuickInfo-Position für &quot;Tools&quot; im Menü &quot;Physische Größe festlegen&quot; ist falsch
* &amp;lbrack;UI&amp;rbrack; Beim Ändern der Sprache ist das Menü &quot;Datei&quot; falsch ausgerichtet

**Bekannte Probleme:**

* &amp;lbrack;3D-Erfassung&amp;rbrack; Bei Masken kann die Texturprojektion unterbrochen werden
* &amp;lbrack;3D-Erfassung&amp;rbrack; Kleine Artefakte können auf dem Objekt erscheinen, wenn die Skalierung in der Gittertransformation zu klein ist
* &amp;lbrack;3D-Erfassung&amp;rbrack; Das exportierte Gitter kann sehr klein sein. Skalierung der Gittertransformation zurücksetzen und erneut exportieren
* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

## Version 3

### 3.4.1 Arancini

*(Freigegeben: 6. Oktober 2022)*

**Hinzugefügt:**

* &amp;lbrack;Onboarding&amp;rbrack; Neue Begrüßungsbildschirme und neue Funktionen
* &amp;lbrack;Onboarding&amp;rbrack; Aktualisierte Startseite-Benutzeroberfläche
* &amp;lbrack;Onboarding&amp;rbrack; Neue Trainingsinhalte auf dem Startbildschirm
* &amp;lbrack;Skripterstellung&amp;rbrack; Protokollieren Sie einen Fehler im Protokollfenster, wenn eine Methode nicht erkannt wird.
* &amp;lbrack;Skripterstellung&amp;rbrack; Neues ssa.helpers-Modul zum Aktivieren des Drucks im Protokollbedienfeld
* &amp;lbrack;Anwendung&amp;rbrack; Unterstützung für das neue Widget für parallele Schaltflächen in Substance 3D Designer

**Fest:**

* &amp;lbrack;Export&amp;rbrack; Absturz beim Exportieren einer .sbsar-Datei, die auf ein fehlendes Bild verweist
* &amp;lbrack;Export&amp;rbrack; Absturz beim Exportieren eines Assets, das auf eine beschädigte Bilddatei verweist
* &amp;lbrack;Export&amp;rbrack; Das Exportieren einer .sbsar-Datei mit einer Stickerei-Ebene führt zu einem grauen Material
* &amp;lbrack;Export&amp;rbrack; Beim Exportieren eines Materials in eine SBS/SBSAR-Datei kann ein vollständig transparentes Material generiert werden
* &amp;lbrack;Export&amp;rbrack; Der Parameter &quot;Normales Format&quot; wird in .sbs/.sbsar-Dateien nicht korrekt angezeigt
* &amp;lbrack;Export&amp;rbrack; SBS/SBSAR-Export eines Ebenenstapels, der auf eine .svg-Datei verweist, ist fehlgeschlagen
* &amp;lbrack;Export&amp;rbrack; Transformieren-Ebene wird nicht ordnungsgemäß exportiert/Enscape aktualisiert - Exportvorgabe überprüfen
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Absturz beim Löschen einer Ebene, die einen exponierten Parameter enthält
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Das Aktualisieren einer veralteten Ebene im Ebenenstapel kann zu einer beschädigten Liste der angezeigten Parameter führen
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Parameter, die nicht exportiert werden sollen, werden sowieso exportiert
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Durch das Entfernen eines Angleichungsfilters beim Löschen einer Ebene werden seine Parameter nicht wieder aufgehoben
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Textparameter beschädigen .sbs/.sbsar-Exporte
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Ablegen eines Ebenenstapels in einem anderen Ebenenstapel
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Nichtladen eines Filters
* &amp;lbrack;Layers&amp;rbrack; Das vorherige Bild kann beim Zurücksetzen des Bildfelds nicht neu geladen werden
* &amp;lbrack;Layers&amp;rbrack; Änderungen am Transformationswerkzeug können nicht rückgängig gemacht/wiederholt werden
* &amp;lbrack;Layers&amp;rbrack; Kopierstempel-Ebene bleibt hängen, nachdem Sie auf &quot;Alle Einstellungen zurücksetzen&quot; geklickt haben
* &amp;lbrack;Layers&amp;rbrack; Durch die Verwendung einer der Zurücksetzen-Schaltflächen wird verhindert, dass im Bildfeld gezeichnet wird
* &amp;lbrack;Layers&amp;rbrack; Die Schaltfläche &quot;Zurücksetzen&quot; löscht die Zeichnungsmaske im Bildfeld nicht
* &amp;lbrack;Layers&amp;rbrack; Die Schaltfläche &quot;Zurücksetzen&quot; im Bildfeld bewirkt nichts, wenn der Benutzer etwas gemalt hat
* &amp;lbrack;Layers&amp;rbrack; Rendering-Cache funktioniert nicht, wenn das Pinsel-Werkzeug verwendet wird
* &amp;lbrack;Layers&amp;rbrack; Gelöschte Ebenen können weiterhin im Eigenschaftenfenster angezeigt werden
* &amp;lbrack;Layers&amp;rbrack; Die Ebenenberechnung kann beim Wechseln zwischen Projektelementen blockiert werden
* &amp;lbrack;Projekt&amp;rbrack; Manchmal kann Sampler ein Projekt nicht von der Festplatte öffnen
* &amp;lbrack;2D Ansicht&amp;rbrack; Die 2D-Ansicht wird standardmäßig immer auf Materialausgabe zurückgesetzt.

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.4.0 Arancini

*(Freigegeben: 06. September 2022)*

**Hinzugefügt:**

* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Neue Bedienfeld „Veröffentlichte Parameter“
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Schaltfläche &quot;Neu&quot; für Parameter, die über den Mauszeiger bewegt werden, um Parameter aus dem Bedienfeld &quot;Eigenschaften&quot; anzuzeigen oder zu entfernen
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Neues Kontextmenü mit der rechten Maustaste zu Parametern, die im Eigenschaftenbedienfeld angezeigt oder nicht verfügbar gemacht werden sollen
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Verfügbare Parameter sind auf der Bedienfeld „Veröffentlichte Parameter“ aufgelistet.
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Farbpunkte und Farbscheiben werden an mehreren Stellen hinzugefügt, um exponierte Parameter leicht zu identifizieren
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Parameterbeschriftungen können in der Bedienfeld „Veröffentlichte Parameter“ bearbeitet werden
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Eine Warnung für nicht exportierbare Parameter anzeigen
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Warnmeldung anzeigen, wenn eine Ebene mit exponierten Überblendungsparametern an eine Stelle verschoben wird, an der sie ausgeblendet werden
* &amp;lbrack;Verfügbare Parameter&amp;rbrack; Verfügbare Parameter werden in den Formaten SBS und SBSAR exportiert
* &amp;lbrack;Metadaten&amp;rbrack; Unterstützung benutzerdefinierter Metadatenvorlagen
* &amp;lbrack;Metadaten&amp;rbrack; Neue Vorlage für physikalische CLO-Eigenschaften für Metadaten
* &amp;lbrack;Metadaten&amp;rbrack; Hinzufügen von Symbolen beim Hovern, um benutzerdefinierte Metadaten hinzuzufügen/zu entfernen
* &amp;lbrack;Python API&amp;rbrack; Neue Python-API
* &amp;lbrack;Python API&amp;rbrack; API für Asset-Authoring
* &amp;lbrack;Python API&amp;rbrack; API für die Ebenenverwaltung
* &amp;lbrack;Python API&amp;rbrack; API für die Parameterverwaltung
* &amp;lbrack;Python API&amp;rbrack; API für das Projektmanagement
* &amp;lbrack;Python API&amp;rbrack; Ein Plug-in kann aktiviert und deaktiviert werden
* &amp;lbrack;Python API&amp;rbrack; Python-API-Dokumentation im Menü &quot;Hilfe&quot;
* &amp;lbrack;Skripterstellung&amp;rbrack; Neue Plug-ins und Skripte im Popup &quot;Voreinstellungen&quot;
* &amp;lbrack;Skripterstellung&amp;rbrack; Plug-ins zum Anpassen der Oberfläche von Sampler mit eigenen Bedienfeldern erstellen und importieren
* &amp;lbrack;Skripterstellung&amp;rbrack; Plug-ins werden Teil der Sampler-Oberfläche und können wie herkömmliche Sampler-Bedienfelder angedockt und verschoben werden
* &amp;lbrack;Skripterstellung&amp;rbrack; Dedizierte Schaltflächenleiste für die Plug-ins in der rechten Sampler-Symbolleiste
* &amp;lbrack;Skripterstellung&amp;rbrack; Erstellen und Importieren von Skripten zum Ausführen einer Liste von Aufgaben
* &amp;lbrack;Skripterstellung&amp;rbrack; Python-Skripte über das Menü &quot;Skripte&quot; starten
* &amp;lbrack;Skripterstellung&amp;rbrack; Plug-ins und Skripte können über das Fenster Voreinstellungen gelöscht, neu angeordnet und neu geladen werden.
* &amp;lbrack;Skripterstellung&amp;rbrack; —run-script-Befehlszeilenparameter hinzugefügt
* &amp;lbrack;Logs&amp;rbrack; Neues Protokollbedienfeld
* &amp;lbrack;Logs&amp;rbrack; Fenster &quot;Protokolle&quot; im Fenster &quot;Voreinstellungen&quot; aktivieren
* &amp;lbrack;Logs&amp;rbrack; Neue Aktionsleiste zum Löschen, Kopieren/Einfügen und Exportieren von Protokollen
* &amp;lbrack;Eigenschaften&amp;rbrack; Neue Schaltfläche für Parameter, die den Mauszeiger zum Zurücksetzen des Parameterwerts bewegen
* &amp;lbrack;Eigenschaften&amp;rbrack; Neues Kontextmenü für Parameter zum Zurücksetzen des Parameterwerts durch Rechtsklick
* &amp;lbrack;Inhalt&amp;rbrack; &quot;Bild zu Material&quot; (KI-gestützt) funktioniert jetzt in MacOS
* &amp;lbrack;Motor&amp;rbrack; Substance-Engine auf Version 8.6.0 aktualisieren

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Die Anwendung konnte beim Beenden abstürzen, wenn eine Miniaturansichtserstellung ausgeführt wurde
* &amp;lbrack;Anwendung&amp;rbrack; Die Anwendung stürzt möglicherweise ab, wenn &quot;Speichern unter&quot; beim Beenden verwendet wird
* &amp;lbrack;Anwendung&amp;rbrack; Anwendung hängt möglicherweise beim Herunterfahren von MacOS
* &amp;lbrack;Anwendung&amp;rbrack; Beim Speichern mit geöffnetem Farbdialogfeld werden die Änderungen nicht gespeichert
* &amp;lbrack;Export&amp;rbrack; Die Benennungskonvention für die Verwendung ist beim Exportieren nicht korrekt.
* &amp;lbrack;Layers&amp;rbrack; Das Ablegen eines Materials über einem Filter kann abstürzen
* &amp;lbrack;Layers&amp;rbrack; Beim Aktualisieren eines veralteten Ebenenstapels werden möglicherweise nicht zugehörige Ebenenstapel aktualisiert
* &amp;lbrack;Metadaten&amp;rbrack; Leere Felder werden exportiert
* &amp;lbrack;Metadaten&amp;rbrack; Wenn es nur ein Metadatenelement gibt, können Sie auf der Benutzeroberfläche versuchen, es neu anzuordnen
* &amp;lbrack;Projekt&amp;rbrack; Die Berechnung endet nie, nachdem ein Material dupliziert wurde
* &amp;lbrack;Projekt&amp;rbrack; Projektelement wird nach dem ersten Speichern des Projekts dupliziert
* &amp;lbrack;Projekt&amp;rbrack; Unnötige Berechnungen beim Wechseln des Assets
* &amp;lbrack;Rendering&amp;rbrack; Einige Ebenenstapel werden nach dem Löschen einer Ebene nicht richtig gerendert
* &amp;lbrack;Sicherheit&amp;rbrack; Problembehebung CVE-2015-20107
* &amp;lbrack;UI&amp;rbrack; 2D-Ausgaben können je nach Fenstergröße verschwommen sein
* &amp;lbrack;UI&amp;rbrack; Die Elementvorschau kann oben geöffnet bleiben, wenn die Anwendung den Fokus verliert
* &amp;lbrack;UI&amp;rbrack; Abgerundete Ecken des Begrüßungsbildschirms haben einen quadratischen, deckenden Hintergrund

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.2 Zucchini

*(Freigegeben: 28. Juni 2022)*

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Beheben eines potenziellen Absturzes beim Öffnen eines Projekts
* &amp;lbrack;Export&amp;rbrack; Neustarten von Sampler unterbricht die Liste der importierten benutzerdefinierten Exportvorgaben
* &amp;lbrack;Interoperabilität&amp;rbrack; Absturz beheben, wenn ein von Designer gesendetes Material gelöscht und dann von Designer erneut gesendet wird
* &amp;lbrack;Projekt&amp;rbrack; Das letzte Material- oder Umgebungslicht kann nicht gelöscht werden, wenn es das letzte Asset im Projekt ist
* &amp;lbrack;Projekt&amp;rbrack; Durch Rechtsklick auf eine Umgebungsbeleuchtung werden die Sternchen &quot;nicht gespeicherte Änderungen&quot; angezeigt.

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.1 Zucchini

*(Freigegeben: 7. Juni 2022)*

**Hinzugefügt:**

* &amp;lbrack;Anwendung&amp;rbrack; Native Unterstützung für Apple silicon (M1)
* &amp;lbrack;UI&amp;rbrack; Neue Taste &quot;C&quot; zum Wechseln zwischen Kanälen in der 2D-Ansicht
* &amp;lbrack;Extras&amp;rbrack; Numerisches Feld zum Bearbeiten des Graustufenfarbwerts in der Pinselsymbolleiste

**Fest:**

* &amp;lbrack;Extras&amp;rbrack; Wenn Sie das Pinsel-Werkzeug unter Windows mit einer fraktionierten UI-Skala (150 %) verwenden, werden die Striche versetzt
* &amp;lbrack;Performance&amp;rbrack; Verbessern der Speicherauslastung
* &amp;lbrack;Physische Größe&amp;rbrack; Informationen zur Physische Größe können fehlen, wenn die Funktion aktiviert wird
* &amp;lbrack;UI&amp;rbrack; Das Scrollen mit der Maus funktioniert manchmal nicht wie erwartet, wenn Sie die Alt-Taste drücken
* &amp;lbrack;Anwendung&amp;rbrack; Die Anwendung kann beim Öffnen eines gespeicherten Projekts abstürzen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Ziehen und Ablegen mehrerer Bilder und bei Verwendung des Texturimports im Fenster &quot;Materialerstellungsvorlage&quot;
* &amp;lbrack;Anwendung&amp;rbrack; Potenzieller Absturz beim Speichern eines Projekts, das einen benutzerdefinierten Filter enthält
* &amp;lbrack;Anwendung&amp;rbrack; Manchmal geht der Status der Strg-Taste beim Wechseln der Anwendung verloren
* &amp;lbrack;Assets&amp;rbrack; Absturz beim Umbenennen eines lokalen Ordners

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.3.0 Zucchini

*(Freigegeben: 17. Mai 2022)*

**Hinzugefügt:**

* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot; (Windows und Mac)
* &amp;lbrack;Inhalt&amp;rbrack; Die inhaltsbasierte Füllung bearbeitet Bilder, PBR-Materialien und Umgebungslichter
* &amp;lbrack;Inhalt&amp;rbrack; Hinzufügen des Parameters &quot;Kachelung beibehalten&quot; zu &quot;Bild zu Material&quot; (KI-gestützt)
* &amp;lbrack;Inhalt&amp;rbrack; Der Filter &quot;Perspektivisches Transformieren&quot; kann ein Raster zwischen seinen vier Punkten anzeigen
* &amp;lbrack;Interoperabilität&amp;rbrack; Materialien an Adobe Substance 3D Stager senden.
* &amp;lbrack;Extras&amp;rbrack; Transformation beim Skalieren des Transformieren- oder Freistellungswerkzeugs durch Drücken der Strg-Taste zentrieren
* &amp;lbrack;Extras&amp;rbrack; Sperren des Verhältnisses zum Quadrat durch Drücken der Umschalttaste bei Größenänderung des Transformieren- oder Freistellungswerkzeugs
* &amp;lbrack;Extras&amp;rbrack; Cursor für Kopierstempel bietet eine Vorschau dessen, was gestempelt wird
* &amp;lbrack;Extras&amp;rbrack; Vorschau des Originalinhalts im Radiergummi, wenn Kopierstempel verwendet werden
* &amp;lbrack;Extras&amp;rbrack; Strg+Klick erstellt einen neuen Stempel in der Kopierstempel-Ebene
* &amp;lbrack;Extras&amp;rbrack; Aufeinander folgende Kopierstempel sind jetzt auf einer Ebene gruppiert
* &amp;lbrack;Extras&amp;rbrack; Pinsel-Symbolleiste - UI überarbeiten
* &amp;lbrack;Extras&amp;rbrack; Die Position der Pinsel-Symbolleiste bleibt während einer Sitzung erhalten.
* &amp;lbrack;Extras&amp;rbrack; Neue Optionen für die Pinselneigung nach Achse
* &amp;lbrack;Extras&amp;rbrack; Überlagerung beim Malen über der 2D-Ansicht ausblenden/anzeigen
* &amp;lbrack;Extras&amp;rbrack; Neuer Tastaturbefehl &quot;X&quot; zum Umschalten zwischen Pinsel und Radiergummi
* &amp;lbrack;Extras&amp;rbrack; Neue Tastenkombination &quot;&amp;lbrack;&quot; &quot;&amp;rbrack;&quot; zum Ändern der Pinselgröße
* &amp;lbrack;Extras&amp;rbrack; Neue Taste &quot;E&quot; zum Umschalten des Radiergummis
* &amp;lbrack;2D Ansicht&amp;rbrack; Neuer Sphärische Projektion-Modus beim Erstellen der Umgebungsbeleuchtung
* &amp;lbrack;2D Ansicht&amp;rbrack; Das Pinselwerkzeug wird vom sphärische Projektion-Modus unterstützt.
* &amp;lbrack;2D Ansicht&amp;rbrack; Positionierungswerkzeug wird im sphärische Projektion-Modus unterstützt
* &amp;lbrack;2D Ansicht&amp;rbrack; Das Rückgängigmachen/Wiederholen wird mit dem sphärische Projektion-Modus unterstützt.
* &amp;lbrack;2D Ansicht&amp;rbrack; Legen Sie in Sphärische Projektion die Standardposition fest, sodass der Blick auf den Mittelpunkt der Umgebung gerichtet ist.
* &amp;lbrack;2D Ansicht&amp;rbrack; Neue Belichtungssteuerung
* &amp;lbrack;UI&amp;rbrack; Im Bedienfeld &quot;Eigenschaften&quot; zeigt die Bildkorrektur die Quelle des Inhalts an (Bild oder aus einer Ebene)
* &amp;lbrack;UI&amp;rbrack; Verbesserte Ebenen-/Materialausgabe-Dropdown-Hintergrundebene
* &amp;lbrack;UI&amp;rbrack; Neue Position der Auflösungsinformationen in der 2D-Ansicht
* &amp;lbrack;UI&amp;rbrack; Neue QuickInfo mit Tastaturbefehlen für die 3D-Ansichtsnavigation
* &amp;lbrack;UI&amp;rbrack; Neue QuickInfo mit Pinselsteuerungen
* &amp;lbrack;UI&amp;rbrack; Neue QuickInfo mit Tastaturbefehlen für die Projektionsnavigation
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Verbundfilter verarbeiten Varianten für Bilder, PBR-Materialien und Umgebungslichter
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Tweak-Reihenfolge entspricht der Knoten-Listenreihenfolge im zusammengesetzten Filter
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Zwei verschiedene Knoten mit derselben Gruppe werden in einer Gruppe im Bedienfeld &quot;Eigenschaften&quot; zusammengeführt.
* &amp;lbrack;Anwendung&amp;rbrack; Dedizierte Anzeigeeinstellungen für jeden Elementtyp

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Anwendung kann abstürzen, wenn zur 2D-Ansicht gewechselt wird
* &amp;lbrack;Anwendung&amp;rbrack; Beheben einer möglichen Deadlock oder eines Absturzes beim mehrmaligen Exportieren
* &amp;lbrack;Anwendung&amp;rbrack; Festlegen von Standardwerten für Kanäle für die Konsistenz mit Substance 3D Designer
* &amp;lbrack;Anwendung&amp;rbrack; Das Laden eines Projekts löst keine Neuberechnung des Materials aus
* &amp;lbrack;Anwendung&amp;rbrack; Die URL zur Dokumentation zum Texturimport wurde aktualisiert
* &amp;lbrack;Inhalt&amp;rbrack; Bei Verwendung eines zusammengesetzten Filters muss er beim erneuten Laden aktualisiert werden, wenn dies nicht der Fall sein sollte
* &amp;lbrack;Inhalt&amp;rbrack; Details in der Height-Map verschwinden bei Verwendung der Deckkraftüberblendung
* &amp;lbrack;UI&amp;rbrack; Im Farbdialogfeld können Sie mit den Textfeldern des Schiebereglers den Bereich verlassen
* &amp;lbrack;UI&amp;rbrack; Verwendungsliste enthält eine nutzlose vertikale Bildlaufleiste

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* &amp;lbrack;Inhalt&amp;rbrack; Das Shape-Licht-Widget funktioniert nicht im sphärische Projektion-Modus
* &amp;lbrack;Interoperabilität&amp;rbrack; Für Material, dessen Versatz an Stager gesendet wurde, verlieren die Versatz-Steuerelemente

### 3.2.1 Jakitori

*(Freigegeben: 08. März 2022)*

**Hinzugefügt:**

* &amp;lbrack;Export&amp;rbrack; Exportieren von dpi-Metadaten in Bilddateien
* &amp;lbrack;Physische Größe&amp;rbrack; Beim Bearbeiten physikalischer Abmessungen das Verhältnis mit nicht quadratischen Texturen beibehalten
* &amp;lbrack;Physische Größe&amp;rbrack; Physische Größe-Metadaten werden sofort angewendet, wenn sich die Physische Größe ändert
* &amp;lbrack;UI&amp;rbrack; Passen Sie den Regler &quot;Max. Skalierung des Heights&quot; an, damit er bei aktivierter Physische Größe jede Art von Material beeinflussen kann.
* &amp;lbrack;UI&amp;rbrack; Neue QuickInfos zu Suchfiltern im Bedienfeld &quot;Elemente&quot;
* &amp;lbrack;UI&amp;rbrack; QuickInfos, um zu erläutern, wann Schaltflächen im Bedienfeld &quot;Elemente&quot; deaktiviert sind
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierung des Helligkeitskontrastfilters

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Die Schaltfläche &quot;Drehung um 90 Grad&quot; in den Werkzeugen &quot;Zuschneiden und transformieren&quot; funktioniert nicht wie erwartet
* &amp;lbrack;2D Ansicht&amp;rbrack; Das Zuschneide-Widget fehlt manchmal
* &amp;lbrack;Anwendung&amp;rbrack; Durch das Löschen eines Bildparameters wird die zugrunde liegende Ebene nicht erneut verbunden.
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden nach dem Speichern eines Projekts
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Ziehen und Ablegen des aktuellen Materials in eine Sammlung des Bedienfelds &quot;Elemente&quot;
* &amp;lbrack;Anwendung&amp;rbrack; Das Ziehen und Ablegen eines Assets im Viewport kann abstürzen
* &amp;lbrack;Inhalt&amp;rbrack; Die normale Füllmethode hat einen zufälligen Startpunkt.
* &amp;lbrack;Inhalt&amp;rbrack; Schneefilter hat eine falsche Normalausgabe, abhängig von den Snow- und Schneeparameterwerten
* &amp;lbrack;Inhalt&amp;rbrack; Parkettfilter: feste unerwartete Nähte
* &amp;lbrack;Inhalt&amp;rbrack; Stickfilter: Gewinde in metallischer Karte entfernen
* &amp;lbrack;Inhalt&amp;rbrack; Bodenfliesen-Filter: x- und y-Kachelanzahl korrigieren
* &amp;lbrack;Inhalt&amp;rbrack; Ziegelwandfilter: Normal-Ausgang und Height auf 16 bit
* &amp;lbrack;Export&amp;rbrack; Der Standarddateiname im Export-Popup ist nicht der aktuelle Materialname
* &amp;lbrack;Export&amp;rbrack; Beim Exportieren mit physischem Verhältnis mit einer Exportvorgabe werden falsche Abmessungen angezeigt
* &amp;lbrack;Export&amp;rbrack; Metallic fehlt in der CLO-Exportvorgabe
* &amp;lbrack;Export&amp;rbrack; Beim Ersetzen einer benutzerdefinierten Exportvorgabe wird der Anzeigename nicht aktualisiert
* &amp;lbrack;Layers&amp;rbrack; Benutzerdefinierte Kanäle der ersten eingefügten Ebene werden nicht erkannt.
* &amp;lbrack;Layers&amp;rbrack; Material wird neu bewertet, wenn Änderungen einer ausgeblendeten Ebene geändert werden
* &amp;lbrack;Lokalisierung&amp;rbrack; QuickInfos sind im Exportbedienfeld nicht lokalisiert
* &amp;lbrack;Physische Größe&amp;rbrack; Durch Deaktivieren der Physische Größe eines Assets wird die physische Skalierung nicht entfernt.
* &amp;lbrack;Physische Größe&amp;rbrack; Der Skalierungswert des Heights kann beim ersten Mal nicht außerhalb der Reglergrenzen festgelegt werden
* &amp;lbrack;Physische Größe&amp;rbrack; Das Importieren eines Bildes ohne Physische Größe verhindert das Öffnen des Projekts
* &amp;lbrack;Physische Größe&amp;rbrack; Physische Größe ist fälschlicherweise auf Null gesetzt, wenn sie fehlt
* &amp;lbrack;Physische Größe&amp;rbrack; Der Status des Kontrollkästchens &quot;Physische Skalierung der Physische Größe&quot; wird bei der ersten Anzeige nicht aktualisiert
* &amp;lbrack;UI&amp;rbrack; Basismaterial &amp; Normal zu Height haben keine Kategorie
* &amp;lbrack;UI&amp;rbrack; Der Cursor ist beim Malen eines Bildes manchmal unsichtbar
* &amp;lbrack;UI&amp;rbrack; Deaktivieren der Optionen &quot;Alle kopieren&quot; und &quot;Alle ausschneiden&quot; im Bearbeitungsmenü eines Textfelds, wenn es leer ist
* &amp;lbrack;UI&amp;rbrack; Filternamen haben falsche Zeichen
* &amp;lbrack;UI&amp;rbrack; Schaltfläche zum Sperren der Physische Größe hat nicht den richtigen Stil
* &amp;lbrack;UI&amp;rbrack; Die Schaltfläche &quot;Schließen&quot; in der Suchleiste im Bedienfeld &quot;Elemente&quot; löscht die Suchzeichenfolge nicht

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.2.0 Jakitori

*(Freigegeben: 25. Januar 2022)*

**Hinzugefügt:**

* &amp;lbrack;Physische Größe&amp;rbrack; Neues Bedienfeld &quot;Physische Größe&quot;
* &amp;lbrack;Physische Größe&amp;rbrack; Optionen für die Physische Größe im Fenster &quot;Materialerstellungsvorlage&quot; hinzufügen
* &amp;lbrack;Physische Größe&amp;rbrack; Werkzeug zum Messen von Physische Größen hinzufügen
* &amp;lbrack;Physische Größe&amp;rbrack; Automatisch messende Physische Größe hinzufügen
* &amp;lbrack;Physische Größe&amp;rbrack; Physische Größe hinzufügen
* &amp;lbrack;Physische Größe&amp;rbrack; Festlegen des z-Werts der Physische Größe zulassen
* &amp;lbrack;Physische Größe&amp;rbrack; Dropdown-Widget zum Festlegen der Zoomstufe in der 2D-Ansicht
* &amp;lbrack;Physische Größe&amp;rbrack; Neue Option &quot;Anzeige mit physischem Verhältnis&quot; auf der Ebene der Zoom-Dropdown-Liste
* &amp;lbrack;Physische Größe&amp;rbrack; Neue Option &quot;An Physische Größe anpassen&quot; auf der Ebene der Zoom-Dropdown-Liste
* &amp;lbrack;Physische Größe&amp;rbrack; Anzeigen der Physische Größe in der 2D-Ansicht
* &amp;lbrack;Physische Größe&amp;rbrack; Anzeigen der Physische Größe im 3D-Viewport
* &amp;lbrack;Physische Größe&amp;rbrack; Im Dialogfeld &quot;Bildimport&quot; Tiefe der Physische Größe anzeigen, wenn eine importierte Height-Map vorhanden ist
* &amp;lbrack;Physische Größe&amp;rbrack; Physische Größe im Kontextmenü des Elements anzeigen
* &amp;lbrack;Physische Größe&amp;rbrack; Legen Sie die Längeneinheit in den Voreinstellungen fest.
* &amp;lbrack;Physische Größe&amp;rbrack; Exportieren von Texturen, die das physische Verhältnis berücksichtigen
* &amp;lbrack;Metadaten&amp;rbrack; Möglichkeit, einem von Benutzern erstellten Asset benutzerdefinierte Metadaten hinzuzufügen
* &amp;lbrack;Export&amp;rbrack; Exportieren benutzerdefinierter Metadaten in .sbs(ar)-Dateien
* &amp;lbrack;Export&amp;rbrack; Exportieren von Beschreibungen, Kategorien, Autoren und Tagmetadaten in .sbs(ar)-Dateien
* &amp;lbrack;Export&amp;rbrack; Exportieren der Physische Größe in .sbs(ar)-Dateien
* &amp;lbrack;Export&amp;rbrack; Komprimierungseinstellung für .sbsar-Dateien festlegen
* &amp;lbrack;Export&amp;rbrack; Exportieren der Miniaturansicht des Elements in .sbs(ar)-Dateien
* &amp;lbrack;Export&amp;rbrack; Festlegen des Diagrammtyps beim Exportieren einer .sbs(ar)-Datei
* &amp;lbrack;Anwendung&amp;rbrack; Realtime Engine 2021 ist nicht mehr verfügbar
* &amp;lbrack;Anwendung&amp;rbrack; &quot;Rückgängig/Wiederholen&quot; unterstützt jetzt Änderungen an den Teilungseinstellungen (U,V) und am Height-Skalierungsregler
* &amp;lbrack;Rendering&amp;rbrack; Generieren des Disk-Cache beim Speichern des erstellten Assets
* &amp;lbrack;Assets&amp;rbrack; Mehrere Elementtypfilter im Bedienfeld &quot;Ressourcen&quot; durch Klicken bei gedrückter Strg-Taste aktivieren
* &amp;lbrack;UI&amp;rbrack; Funktion zum Sperren der Kachelregler (U,V)
* &amp;lbrack;UI&amp;rbrack; Kontextmenü mit &quot;Kopieren&quot;, &quot;Ausschneiden&quot;, &quot;Einfügen&quot;, &quot;Alle kopieren&quot; und &quot;Alle ausschneiden&quot; in Textfeldern hinzufügen
* &amp;lbrack;UI&amp;rbrack; Längeneinheit (Meter, Zoll, Parsec, ...) Unterstützung für Beschriftungen und Textfelder
* &amp;lbrack;UI&amp;rbrack; Der Benutzer kann die Dezimalpräzision festlegen, die zum Anzeigen von Zahlen verwendet wird.
* &amp;lbrack;UI&amp;rbrack; Maßeinheiten in Popups verwenden, wo immer es relevant ist
* &amp;lbrack;Lokalisierung&amp;rbrack; Der Name des neuen Standardstockmediums ist jetzt lokalisiert
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Gewebewebgenerator
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Kanalschalter-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Alle relevanten Filter kennen jetzt die Physische Größe
* &amp;lbrack;Inhalt&amp;rbrack; Neue Icons für Wood Finish
* &amp;lbrack;Inhalt&amp;rbrack; Alle Filter sind jetzt mit Adobe Standard Materials (ASM) Kanälen kompatibel.
* &amp;lbrack;Inhalt&amp;rbrack; Filter können jetzt eine &quot;Umgebungs&quot;-Variation haben

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Kanal bleibt in der Liste, wenn er entfernt wird
* &amp;lbrack;Anwendung&amp;rbrack; Ein aus dem Dateiexplorer des Betriebssystems geladenes Asset kann nicht dupliziert werden.
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Absturz manchmal beim Klicken auf &quot;Starter-Elemente&quot; im Bedienfeld &quot;Elemente&quot;
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Löschen eines Materials
* &amp;lbrack;Anwendung&amp;rbrack; Die Umgebungsvariable &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; ist noch aktiv, wenn sie auf &quot;0&quot; oder &quot;&quot; gesetzt ist.
* &amp;lbrack;Anwendung&amp;rbrack; Einfrieren beim Speichern eines Projekts mit mehreren Materialien
* &amp;lbrack;Anwendung&amp;rbrack; Das Importieren eines Bildes kann zu einem Absturz führen
* &amp;lbrack;Anwendung&amp;rbrack; Beim ersten Start fehlen einige Starter-Assets
* &amp;lbrack;Export&amp;rbrack; Das Exportieren eines Assets kann zu einem Absturz führen
* &amp;lbrack;Layers&amp;rbrack; Bilder können nicht importiert werden, wenn das Ebenenfenster geschlossen oder nicht sichtbar ist
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie die Sprache ändern, wird das aktuelle Asset neu berechnet.
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie die Verwendung eines importierten Bildes ändern, wird nicht aktualisiert, welche Filtervariante verwendet werden soll
* &amp;lbrack;Layers&amp;rbrack; &quot;Bild zu Material&quot; (AI) wird manchmal nicht berechnet, wenn Ebenen darunter angepasst werden
* &amp;lbrack;Layers&amp;rbrack; &quot;Bild zu Material&quot; (AI) wird manchmal neu berechnet, wenn es nicht benötigt wird
* &amp;lbrack;Layers&amp;rbrack; Wenn ein benutzerdefinierter Filter auf der Festplatte aktualisiert wird, wird kein Update vorgeschlagen.
* &amp;lbrack;Layers&amp;rbrack; Der normale Kanal hat manchmal das falsche Pixelformat
* &amp;lbrack;Layers&amp;rbrack; Einige Ebenen werden immer noch berechnet, auch wenn sie nicht sichtbar sind
* &amp;lbrack;Layers&amp;rbrack; Beim Umschalten der Ebenensichtbarkeit können die Werkzeuge der 2D-Ansicht beschädigt werden
* &amp;lbrack;Layers&amp;rbrack; Die Benutzeroberfläche friert ein, wenn Bild zu Material (AI) verwendet wird
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie die Sichtbarkeit der Transformieren-Filterebene umschalten, wird das 2D-Ansichtswerkzeug beschädigt und kann zu einem Absturz führen
* &amp;lbrack;Layers&amp;rbrack; Zu viele Neuberechnungen beim Entfernen einer Ebene aus dem Ebenenstapel
* &amp;lbrack;Layers&amp;rbrack; Wenn ein zusammengesetzter Filter eine ungewöhnliche oder benutzerdefinierte Eingabe/Ausgabe enthält, wird diese von Sampler nicht berechnet
* &amp;lbrack;Performance&amp;rbrack; Bedienfeld &quot;Elemente&quot; lässt sich nur langsam öffnen
* &amp;lbrack;Performance&amp;rbrack; Vermeiden Sie unnötige Neuberechnungen des Ebenenstapels
* &amp;lbrack;Performance&amp;rbrack; Das Laden von Projekt-Assets dauert zu lange
* &amp;lbrack;Performance&amp;rbrack; Der Render-Cache auf dem Datenträger darf nicht verwendet werden.
* &amp;lbrack;Performance&amp;rbrack; Der Wechsel zwischen Ebenen ist langsam
* &amp;lbrack;Performance&amp;rbrack; Das Anpassen eines Materials oder Filters ist langsam
* &amp;lbrack;Projekt&amp;rbrack; Das Speichern eines Projekts beim Beenden kann zu einem Absturz führen
* &amp;lbrack;Rendering&amp;rbrack; Durch Entfernen eines Bildes werden möglicherweise alle Ausgaben entfernt
* &amp;lbrack;Rendering&amp;rbrack; Die im Viewport angezeigte Renderzeit ist beim Anpassen falsch
* &amp;lbrack;UI&amp;rbrack; Bei Bedarf kann im Popup &quot;Export&quot; nicht vertikal gescrollt werden
* &amp;lbrack;UI&amp;rbrack; Es ist möglich, das Popup &quot;Exportieren&quot; zu öffnen, wenn es nichts zu exportieren gibt
* &amp;lbrack;UI&amp;rbrack; Einige Popups scrollen nicht, wenn ihr Inhalt überläuft
* &amp;lbrack;UI&amp;rbrack; Textfelder sind nicht ausgewählt, wenn Sie darauf klicken oder ein Menü öffnen
* &amp;lbrack;UI&amp;rbrack; Der Name der Füllmethode im Eigenschaftenfenster ist manchmal nicht korrekt
* &amp;lbrack;UI&amp;rbrack; Die Option &quot;Speichern&quot; im Menü &quot;Datei&quot; ist manchmal ausgegraut.
* &amp;lbrack;UI&amp;rbrack; Das Textfeld verschwindet nach dem Umbenennen von zwei Materialien nicht
* &amp;lbrack;UI&amp;rbrack; Tippfehler im Voreinstellungs-Popup

**Bekannte Probleme:**

* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.2 Xocoatl

*(Freigegeben: 14. Dezember 2021)*

**Fest:**

* &amp;lbrack;Interoperabilität&amp;rbrack; Das Öffnen von .sbsar-Dateien mit Substance 3D Sampler aus Bridge kann unter Windows fehlschlagen
* &amp;lbrack;Layers&amp;rbrack; Das Verschieben der einzigen Ebene unter sich führt zum Absturz
* &amp;lbrack;UI&amp;rbrack; Schaltfläche &quot;Kanaleinstellungen&quot; verschwindet beim Ändern der Sprache
* &amp;lbrack;UI&amp;rbrack; Der Materialname im Eigenschaftenfenster verschwindet nach dem Speichern des Projekts
* &amp;lbrack;Assets&amp;rbrack; Das Klicken auf &quot;Alle Bibliotheken&quot; kann zu einem Absturz führen

**Bekannte Probleme:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.1 Xocoatl

*(Freigegeben: 24. November 2021)*

**Hinzugefügt:**

* &amp;lbrack;Interoperabilität&amp;rbrack; Elemente (SBS oder SBSAR) an Substance 3D Designer senden
* &amp;lbrack;Interoperabilität&amp;rbrack; Festlegen des Standardformats für die Interoperabilität mit Substance 3D Designer in den Voreinstellungen
* &amp;lbrack;Interoperabilität&amp;rbrack; Mehrere Elemente aus Adobe Bridge erhalten
* &amp;lbrack;UI&amp;rbrack; Neues Widget für Zufallsverteilung
* &amp;lbrack;UI&amp;rbrack; Aktualisierung des Kontextmenüs
* &amp;lbrack;Assets&amp;rbrack; Bilder vom Bedienfeld &quot;Elemente&quot; in das Bedienfeld &quot;Eigenschaften&quot; ziehen
* &amp;lbrack;Projekt&amp;rbrack; Elementnamen werden bereinigt, um bestimmte Zeichen zu vermeiden
* &amp;lbrack;Branding&amp;rbrack; Dateisymbol für SBSAR-Dateien aktualisieren
* &amp;lbrack;Motor&amp;rbrack; Substance Engine 8.3.0 aktualisieren

**Fest:**

* &amp;lbrack;Inhalt&amp;rbrack; Freistellen - Beibehalten des Verhältnisses beim Freistellen nicht quadratischer Bilder
* &amp;lbrack;Inhalt&amp;rbrack; Transformieren : Die horizontale Transformation wird bei Verwendung des Widgets nicht invertiert
* &amp;lbrack;Inhalt&amp;rbrack; Kies - benutzerdefinierte Maskenmalerei auf allen Kanälen beheben
* &amp;lbrack;Inhalt&amp;rbrack; Bodenfliesen - Beheben Sie Probleme mit Musterkacheln und Wiederholung
* &amp;lbrack;Assets&amp;rbrack; Option &quot;Adobe Bridge grau hinterlegen&quot;, wenn diese nicht installiert ist
* &amp;Klammer;Farbwähler&amp;Klammer; Esc-Taste schließt Farbwähler
* &amp;lbrack;Rendering&amp;rbrack; Streuungsdistanzskalierung bei Verwendung von Graustufeneingaben korrigieren
* &amp;lbrack;Share&amp;rbrack; Optionen für &quot;Senden an&quot; sind nur mit Adobe-Lizenzen verfügbar
* &amp;lbrack;Projekt&amp;rbrack; Beheben eines Problems mit der Speicherleistung

**Bekannte Probleme:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.1.0 Xocoatl

*(Freigegeben: 28. September 2021)*

**Hinzugefügt:**

* &amp;Klammer;Farbwähler&amp;Klammer; Neue Benutzeroberfläche für den Farbwähler
* &amp;Klammer;Farbwähler&amp;Klammer; Vorschau der aktuellen und vorherigen Farben nebeneinander
* &amp;Klammer;Farbwähler&amp;Klammer; Eingabe der Farbe in Hexadezimal
* &amp;Klammer;Farbwähler&amp;Klammer; Neue Pipette mit Farbvorschau
* &amp;Klammer;Farbwähler&amp;Klammer; Die Pipette kann eine Farbe außerhalb von Sampler auswählen
* &amp;Klammer;Farbwähler&amp;Klammer; Anpassen der Farbe im RGB- oder HSV-Farbraum
* &amp;Klammer;Farbwähler&amp;Klammer; Farbfelder speichern und verwalten
* &amp;lbrack;Interoperabilität&amp;rbrack; Bilder in Illustrator aus der Bildimportebene oder den Bildparametern bearbeiten
* &amp;lbrack;Interoperabilität&amp;rbrack; Bilder in Photoshop aus der Bildimportebene oder den Bildparametern bearbeiten
* &amp;lbrack;Widget&amp;rbrack; Neues Freistellungs-Widget
* &amp;lbrack;Widget&amp;rbrack; Bestätigen des Freistellungsvorgangs mit der Eingabetaste
* &amp;lbrack;Widget&amp;rbrack; Das Widget &quot;Zuschneiden&quot; liest die Bildgröße, um sie an das Widget anzupassen, und behält das Verhältnis bei der Größenänderung bei
* &amp;lbrack;UI&amp;rbrack; Neue Benutzeroberfläche für Regler im Graustufenmodus
* &amp;lbrack;Anwendung&amp;rbrack; Hinzufügen einer normalen Formatauswahl in den Voreinstellungen
* &amp;lbrack;Anwendung&amp;rbrack; Das Standardformat für Bildimportebenen entspricht dem in den Voreinstellungen festgelegten Standardformat
* &amp;lbrack;Anwendung&amp;rbrack; In der 2D-Ansicht wird die Normale entsprechend dem in den Voreinstellungen festgelegten Normalformat angezeigt
* &amp;lbrack;Anwendung&amp;rbrack; Die Normale wird in das in den Voreinstellungen festgelegte normale Format exportiert
* &amp;lbrack;Export&amp;rbrack; Hinzufügen eines normalen Formatparameters zu SBS- und SBSAR-Dateiexporten
* &amp;lbrack;Export&amp;rbrack; Shader-Einstellungen zu SBS- und SBSAR-Dateiexporten hinzufügen
* &amp;lbrack;Export&amp;rbrack; Standardauflösung für exportierte SBS-Diagramme festlegen
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; SSA-Filter mit 7z verpacken
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Kategoriemetadaten in zusammengesetzten Filtern hinzufügen
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Verknüpfte Filter können eine eingebettete Miniaturansicht haben
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Dem Dateidialogfeld &quot;Inhalt abrufen&quot; wurde die Erweiterung &quot;Zusammengesetzte Filter&quot; (.ssafilter) hinzugefügt.
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Importieren von zusammengesetzten Filtern (.ssafilter) im Bedienfeld &quot;Elemente&quot;
* &amp;lbrack;Motor&amp;rbrack; Substance-Engine auf Version 8.2.0 aktualisieren

**Fest:**

* &amp;lbrack;Anwendung&amp;rbrack; Verbundene lokale Ordner können hängen bleiben
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Starten von zwei Instanzen von Sampler
* &amp;lbrack;Inhalt&amp;rbrack; Der Freistellungsfilter verfügt über eine zufällige Anpassung des Startwerts.
* &amp;lbrack;Inhalt&amp;rbrack; Einige Substance-Materialien werden manchmal nicht aktualisiert
* &amp;lbrack;Export&amp;rbrack; Absturz beim Exportieren mit einer neu hinzugefügten benutzerdefinierten Vorgabe
* &amp;lbrack;Export&amp;rbrack; Geschätzte Größe des Pakets fehlt im Export-Popup
* &amp;lbrack;Export&amp;rbrack; Beheben von Speicherlecks beim Exportieren von SBS- und SBSAR-Dateien
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Zusammengesetzte Filter können duplizierte Eingaben aufweisen
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Absturz, wenn ein Filter nicht erfüllt ist
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Absturz beim Neuanordnen eines Ebenenstapels mit einem zusammengesetzten Filter darin
* &amp;lbrack;Zusammengesetzte Filter&amp;rbrack; Das Rendering hängt manchmal
* &amp;lbrack;Bildimport&amp;rbrack; Beim Importieren eines Bildes werden mehrere Renderings ausgelöst
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Rückgängigmachen/Wiederholen
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Hinzufügen eines Basismaterials
* &amp;lbrack;Layers&amp;rbrack; Absturz bei Verwendung eines ungültigen Bildes als Umgebungslicht
* &amp;lbrack;Layers&amp;rbrack; Doppelten Import beheben, wenn ein Filter mit mehreren Graphen eingefügt wird
* &amp;lbrack;Layers&amp;rbrack; Das Neuanordnen von Ebenen funktioniert nicht immer
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Laden einer unvollständigen Projektdatei
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Öffnen eines beschädigten Projekts
* &amp;lbrack;Projekt&amp;rbrack; Einige Elemente können aus einem Projekt verschwinden
* &amp;lbrack;Eigenschaften&amp;rbrack; Vorgaben für fehlende Filter korrigieren
* &amp;lbrack;UI&amp;rbrack; Winkelparameter können nicht festgelegt werden.
* &amp;lbrack;UI&amp;rbrack; Filtermetadaten werden im Bedienfeld &quot;Elemente&quot; angezeigt
* &amp;lbrack;UI&amp;rbrack; Beim Gruppieren nach Kategorie werden Filter ausgeblendet.
* &amp;lbrack;UI&amp;rbrack; Bildlaufproblem im Bedienfeld &quot;Elemente&quot;
* &amp;lbrack;UI&amp;rbrack; Das Exportbedienfeld verfügt jetzt über eine Bildlaufleiste
* &amp;lbrack;UI&amp;rbrack; Die Miniaturansicht wird für einige Bildformate in der Bildauswahl nicht angezeigt

**Bekannte Probleme:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Starke Berechnungen können die Anwendung abstürzen lassen
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer ab, auf dem sowohl AMD-CPU als auch Nvidia-GPU installiert sind.
* &amp;Klammer;Farbwähler&amp;Klammer; Das Auswählen einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht

### 3.0.1 Waffel

*(Freigegeben: 27. Juli 2021)*

**Hinzugefügt:**

* &amp;Klammer;Pinsel&amp;Klammer; Aktivieren von Farben im Pinselwerkzeug, wenn die Bildeingabe dies unterstützt
* &amp;Klammer;Pinsel&amp;Klammer; Durch Drücken der Umschalttaste im Pinselwerkzeug werden gerade Linien gezeichnet
* &amp;Klammer;Pinsel&amp;Klammer; Zeilenvorschau anzeigen, wenn Sie die Umschalttaste im Pinselwerkzeug gedrückt halten
* &amp;Klammer;Pinsel&amp;Klammer; Pinsel-Werkzeug unterstützt jetzt Rückgängig und Wiederholen
* &amp;lbrack;2D Ansicht&amp;rbrack; Beim Malen wird die Standardfarbe für die Bildeingabe verwendet
* &amp;lbrack;Layers&amp;rbrack; Lesen des Substance-Eingabestandardwerts in SBSAR-Dateien
* &amp;lbrack;Rendering&amp;rbrack; Height mit normalen Elementen kombinieren
* &amp;lbrack;Rendering&amp;rbrack; Unterstützung für Volumenstreuung (nicht verfügbar in MacOS)
* &amp;lbrack;Assets&amp;rbrack; SBSAR-Diagrammtyp zum Bestimmen des Elementtyps verwenden
* &amp;lbrack;Assets&amp;rbrack; Bessere Leistung für die Suche und die Auffindbarkeit von Elementen im Bedienfeld &quot;Elemente&quot;
* &amp;lbrack;Assets&amp;rbrack; Im Bedienfeld &quot;Elemente&quot; wurde der Eintrag &quot;Alle Bibliotheken&quot; hinzugefügt, in dem alle Elemente aus allen Ihren Bibliotheken angezeigt werden.
* &amp;lbrack;Assets&amp;rbrack; Der Benutzer kann jetzt Elemente nach Kategorie oder Typ gruppieren.
* &amp;lbrack;Import&amp;rbrack; Texturen in Anisotropie, Coat, Glanz und Specular edge color beim Import automatisch erkennen
* &amp;lbrack;UI&amp;rbrack; Titel des verbundenen Bedienfelds durch ein Symbol ersetzen
* &amp;lbrack;UI&amp;rbrack; Textfeldstil aktualisieren
* &amp;lbrack;UI&amp;rbrack; Neuer Beschreibungstext im Fenster &quot;Environment Light Template Creation&quot; (Erstellung der Umgebungslichtvorlage)
* &amp;lbrack;Anwendung&amp;rbrack; Elemente mit der aktuellen Auflösung exportieren, wenn sie an eine externe Anwendung gesendet werden
* &amp;lbrack;Anwendung&amp;rbrack; Die Materialstandardauflösung ist jetzt 2048\*2048 (1024\*1024 unter macOS).
* &amp;lbrack;Inhalt&amp;rbrack; Neue Muster im Bodenfliesen-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Dual-Farbmodus im Farbaustauschfilter

**Fest:**

* &amp;lbrack;2D Ansicht&amp;rbrack; Der erste Strich im Pinselwerkzeug ist manchmal beschädigt
* &amp;lbrack;2D Ansicht&amp;rbrack; Kostenlose Ressourcen, wenn das Pinselwerkzeug nicht sichtbar ist
* &amp;lbrack;2D Ansicht&amp;rbrack; Verwenden des Cursors zur Größenänderung rechts im Transformieren-Widget
* &amp;lbrack;2D Ansicht&amp;rbrack; Widgets werden nicht angezeigt, wenn der Benutzer zuvor in der 2D-Ansicht geschwenkt hat
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Öffnen eines Projekts mit beschädigtem Arbeitsablauf
* &amp;lbrack;Anwendung&amp;rbrack; Beheben des Herunterfahrens der Anwendung, um eine Überflutung des Protokolls mit nutzlosen Fehlern zu verhindern
* &amp;lbrack;Anwendung&amp;rbrack; Auf einigen Betriebssystemen funktionieren die Tastaturbefehle zum Wiederherstellen, Löschen und Speichern nicht
* &amp;lbrack;Anwendung&amp;rbrack; Das Rückgängigmachen/Wiederholen von Änderungen der Bildnutzung in der Importebene ist fehlgeschlagen
* &amp;lbrack;Export&amp;rbrack; Die exportierten Bilder der Emissionsfarbe haben einen falschen Namen
* &amp;lbrack;Export&amp;rbrack; Umgebung ist 8 Bit, wenn SBSAR-Export verwendet wird
* &amp;lbrack;Export&amp;rbrack; Entfernen zusätzlicher Leerzeichen in exportierten Bilddateinamen
* &amp;lbrack;Export&amp;rbrack; Das Ersetzen oder Löschen einer benutzerdefinierten Exportvorgabe stürzt ab
* &amp;lbrack;Layers&amp;rbrack; Absturz bei nicht übereinstimmender Eingangsanzahl vermeiden
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Einfügen einer Basismaterial-Ebene
* &amp;lbrack;Layers&amp;rbrack; Die Anzahl der Filtereingaben ist auf den Standardwert begrenzt
* &amp;lbrack;Layers&amp;rbrack; Durch &quot;Wiederholen&quot; wird die Füllmethode fälschlicherweise in &quot;Height-Überblendung&quot; geändert
* &amp;lbrack;Layers&amp;rbrack; Ablagebereich über Eingabekopfzeilen entfernen
* &amp;lbrack;Layers&amp;rbrack; Ebenen werden an der falschen Stelle um die Kopfzeilen eingefügt.
* &amp;lbrack;Layers&amp;rbrack; Schaltfläche &quot;Alle Einstellungen zurücksetzen&quot; setzt die Werte der Dropdown-Widgets nicht zurück
* &amp;lbrack;Layers&amp;rbrack; Durch Rückgängigmachen/Wiederholen beim Ändern eines Bildes auf der Bildimportebene wird das Projekt als geändert markiert und somit gespeichert
* &amp;lbrack;Layers&amp;rbrack; Verwenden von Mischebenen kann gestoppt werden
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Laden eines älteren Projekts mit fehlenden Abhängigkeitsordnern
* &amp;lbrack;Projekt&amp;rbrack; Absturz bei Verwendung von Rückgängig/Wiederholen nach dem Speichern
* &amp;lbrack;Projekt&amp;rbrack; Durch Öffnen einer SBSAR-Datei mit einer Umgebungsbeleuchtung wird ein Materialelement erstellt.
* &amp;lbrack;Projekt&amp;rbrack; Das Umbenennen eines Materials kann eine Miniaturgenerierung auslösen
* &amp;lbrack;Projekt&amp;rbrack; Durch Speichern nach dem Umbenennen eines Materials wird das Projekt als nicht geändert markiert
* &amp;lbrack;Projekt&amp;rbrack; Einige Änderungen nach dem Umbenennen eines Materials werden nicht gespeichert
* &amp;lbrack;Rendering&amp;rbrack; Helle Punkte sind in der Umgebung mit der Echtzeit-Engine 2020 sichtbar
* &amp;lbrack;Rendering&amp;rbrack; Absturz beim Skalieren mit Real Time Engine 2021
* &amp;lbrack;Rendering&amp;rbrack; Neuberechnen von Schatten bei Änderungen auf Height-Ebene
* &amp;lbrack;Assets&amp;rbrack; Verbundene Ordner beenden die Indizierung neuer Assets, wenn eine ungültige Datei hinzugefügt wird
* &amp;lbrack;Assets&amp;rbrack; Absturz beim Verbinden eines lokalen Ordners mit vielen Materialien
* &amp;lbrack;UI&amp;rbrack; Schaltflächen in 2D-/3D-Ansicht fehlen QuickInfos
* &amp;lbrack;UI&amp;rbrack; Alle Elemente im Bedienfeld &quot;Elemente&quot; werden beim Start hervorgehoben
* &amp;lbrack;UI&amp;rbrack; Breadcrumbs werden beim Importieren von Materialien manchmal im Bedienfeld &quot;Elemente&quot; ausgeblendet
* &amp;lbrack;UI&amp;rbrack; Das Ändern der Sprache hat keine Auswirkungen auf das Projektfenster
* &amp;lbrack;UI&amp;rbrack; Das Bedienfeld &quot;Kanaleinstellungen&quot; zeigt ältere Workflow-Informationen an.
* &amp;lbrack;UI&amp;rbrack; Richten Sie den Text &quot;Keine Einstellungen für dieses Element&quot; für Filter ohne Änderungen im Eigenschaftenbedienfeld korrekt aus.
* &amp;lbrack;UI&amp;rbrack; Elemente werden auf dem Begrüßungsbildschirm und im Popup &quot;Voreinstellungen&quot; falsch ausgerichtet
* &amp;lbrack;UI&amp;rbrack; Bedienfeldtitel haben eine falsche Breite
* &amp;lbrack;UI&amp;rbrack; Im Bedienfeld &quot;Eigenschaften&quot; kann das Scrollen unterbrochen werden
* &amp;lbrack;UI&amp;rbrack; Der Begrüßungsbildschirm hat ein falsches Verhältnis und ist verschwommen.
* &amp;lbrack;UI&amp;rbrack; Der Vollbildmodus ist nicht Vollbildmodus.
* &amp;lbrack;UI&amp;rbrack; Nicht angedockte Bedienfelder sind immer oben, auch wenn die Anwendung in MacOS nicht aktiv ist
* &amp;lbrack;UI&amp;rbrack; Bannerbild für Begrüßungsbildschirm aktualisieren
* &amp;lbrack;Inhalt&amp;rbrack; Der Kachelfilter verarbeitet den Umgebungskanal für die Verdeckung nicht
* &amp;lbrack;Inhalt&amp;rbrack; Steppstich Problem mit der Kante Zusammenbau Nahtauswahl und Diamantmuster
* &amp;lbrack;Inhalt&amp;rbrack; Relief-Filter funktioniert in 256 px x 256 px
* &amp;lbrack;Inhalt&amp;rbrack; Problem mit Unterkacheln bei Bodenfliesen beheben, wenn der Versatz größer als 0 ist

**Bekannte Probleme:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Starke Berechnung, Absturz der Anwendung
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 stürzt auf einem Windows-Computer mit AMD-CPU und Nvidia-GPU ab

### 3.0.0 Waffel

*(Freigegeben: 23. Juni 2021)*

**Hinzugefügt:**

* &amp;lbrack;Branding&amp;rbrack; Substance Alchemist wird zu Adobe Substance 3D Sampler
* &amp;lbrack;Branding&amp;rbrack; Neue Anwendungssymbole
* &amp;lbrack;UI&amp;rbrack; Neues Benutzererlebnis und neue Benutzeroberfläche
* &amp;lbrack;UI&amp;rbrack; Neuer Splashscreen
* &amp;lbrack;UI&amp;rbrack; Bedienfelder können abgedockt und an der Oberfläche angedockt werden.
* &amp;lbrack;UI&amp;rbrack; Andocken von bis zu drei Bedienfeldern in derselben Spalte
* &amp;lbrack;UI&amp;rbrack; Andocken von bis zu drei Bedienfeldern im selben Bedienfeld (Registerkarten)
* &amp;lbrack;UI&amp;rbrack; Abdocken von Bedienfeldern, um ein separates Fenster auf demselben oder einem anderen Bildschirm zu erstellen
* &amp;lbrack;UI&amp;rbrack; Geschlossene Bedienfelder, die beim Klicken auf ihre Symbole eingeblendet werden
* &amp;lbrack;UI&amp;rbrack; Die linke und rechte Leiste durch Verschieben der Bedienfeldsymbole neu anordnen
* &amp;lbrack;UI&amp;rbrack; Neue Symbolleiste für den direkten Zugriff auf bestimmte Filter (Zuschneiden, Transformieren, Perspektivisches Transformieren, Kopierstempel)
* &amp;lbrack;UI&amp;rbrack; Neue Schaltfläche &quot;Inhalt abrufen&quot; in der linken Leiste
* &amp;lbrack;UI&amp;rbrack; Importieren Sie Dateien direkt in Ihre Assets mit der Schaltfläche &quot;Inhalt abrufen&quot;
* &amp;lbrack;UI&amp;rbrack; Importiere Dateien über die Schaltfläche &quot;Inhalt abrufen&quot; direkt in deine Ebenen
* &amp;lbrack;UI&amp;rbrack; Direkter Zugriff auf die Adobe Substance 3D Assets-Website über die Schaltfläche &quot;Inhalt abrufen&quot;
* &amp;lbrack;UI&amp;rbrack; Das Auflösungs-Widget ist jetzt direkt im Viewport verfügbar
* &amp;lbrack;UI&amp;rbrack; Alle UI-Elemente werden jetzt dynamisch geladen
* &amp;lbrack;UI&amp;rbrack; Tastaturbefehl - Verwenden Sie &quot;2&quot;, um die Sichtbarkeit der 2D-Ansicht zu ändern.
* &amp;lbrack;UI&amp;rbrack; Tastaturbefehl - Verwenden Sie &quot;3&quot;, um die Sichtbarkeit der 3D-Ansicht zu ändern.
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Projekt mit der Schaltfläche &quot;Neu&quot; per Mausklick erstellen
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Neues Bildmaterial-Banner
* &amp;lbrack;Projekt&amp;rbrack; Alle Projekte sind jetzt einer eindeutigen Datei zugeordnet
* &amp;lbrack;Projekt&amp;rbrack; Neue Projektdateierweiterung .ssa
* &amp;lbrack;Projekt&amp;rbrack; Bei &quot;Als Projekt speichern&quot; müssen Sie auswählen, wo das Projekt gespeichert werden soll
* &amp;lbrack;Projekt&amp;rbrack; Wenn Sie Sampler schließen, werden Sie aufgefordert, Ihr Projekt zu speichern, falls es nicht gespeichert wurde
* &amp;lbrack;Projekt&amp;rbrack; Wenn Sie Sampler schließen, werden Sie aufgefordert, Ihr Projekt zu speichern, wenn seit dem letzten Speichern Änderungen vorgenommen wurden
* &amp;lbrack;Projekt&amp;rbrack; Der Name Ihres Projekts wird über dem Viewport angezeigt
* &amp;lbrack;Projekt&amp;rbrack; Der Projektname ist kursiv mit einem Stern gekennzeichnet, wenn er nicht gespeichert ist oder wenn er seit dem letzten Speichern Änderungen enthält
* &amp;lbrack;Projekt&amp;rbrack; Öffnen einer .ssa-Projektdatei direkt über den Betriebssystem-Explorer
* &amp;lbrack;Projekt&amp;rbrack; Öffnen Sie eine .sbsar-Datei auf Ihrem Betriebssystem-Explorer startet Sampler mit einem neuen Projekt mit dieser .sbsar-Datei, die Sie sofort verwenden können
* &amp;lbrack;Projekt&amp;rbrack; Öffnen Sie eine .alch-Datei (ältere Substance Alchemist-Datei) in Ihrem Betriebssystem-Explorer
* &amp;lbrack;Projektfenster&amp;rbrack; Neues Bedienfeld, das alle in einem Projekt erstellten Elemente enthält
* &amp;lbrack;Projektfenster&amp;rbrack; Element (Material- oder Umgebungslicht) mit dem Symbol &quot;+&quot; erstellen
* &amp;lbrack;Projektfenster&amp;rbrack; Durch Rechtsklick auf ein Element wird ein Kontextmenü geöffnet
* &amp;lbrack;Projektfenster&amp;rbrack; Im Kontextmenü können Sie ein Element löschen
* &amp;lbrack;Projektfenster&amp;rbrack; Über das Kontextmenü können Sie ein Element duplizieren
* &amp;lbrack;Projektfenster&amp;rbrack; Im Kontextmenü können Sie ein Element umbenennen
* &amp;lbrack;Projektfenster&amp;rbrack; Durch den Wechsel zwischen Elementen gehen Änderungen nicht verloren
* &amp;blbrack;Auflösung&amp;blbrack; Sie können jetzt eine nicht quadratische Auflösung für alle Ihre Assets festlegen
* &amp;blbrack;Auflösung&amp;blbrack; Der Auflösungswert wird von einem Asset innerhalb eines Projekts gespeichert
* &amp;lbrack;Umgebungslicht&amp;rbrack; Umgebungslicht in Substance 3D Sampler erstellen
* &amp;lbrack;Umgebungslicht&amp;rbrack; Beim Erstellen einer Umgebungsbeleuchtung wird durch Ziehen und Ablegen von Bildern das Vorlagenfenster für die Erstellung von Umgebungsbeleuchtungen angezeigt
* &amp;lbrack;Umgebungslicht&amp;rbrack; Wählen Sie in der Vorlage Umgebungslicht erstellen die Option Umgebungsimport aus, um das Bild der Umgebung in der 3D-Ansicht zuzuweisen.
* &amp;lbrack;Umgebungslicht&amp;rbrack; Wählen Sie in der Vorlage zur Erstellung von Umgebungslicht die Option HDR-Zusammenfügung aus, um ein Umgebungslicht aus mehreren 360-Grad-Bildern mit unterschiedlicher Belichtung zu erstellen
* &amp;lbrack;Umgebungslicht&amp;rbrack; Wählen Sie in der Vorlage für die Umgebungsbeleuchtung die Option &quot;Als Bitmap verwenden&quot; aus, um Ihre Bilder vor dem Erstellen einer Umgebungsbeleuchtung zu bearbeiten.
* &amp;lbrack;Umgebungslicht&amp;rbrack; Weisen Sie die Umgebungsnutzung in der Bildimportebene zu, um das Bild direkt der Umgebung in der 3D-Ansicht zuzuweisen.
* &amp;lbrack;Umgebungslicht&amp;rbrack; In der 2D-Ansicht für den Umgebungskanal gibt es eine automatische Farbkorrektur, damit das Rendering genauso wie in der 3D-Ansicht angezeigt wird
* &amp;lbrack;Umgebungslicht&amp;rbrack; Neuer dedizierter Content für die Erstellung von Umgebungslicht
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Die Ressourcen- und Filterfelder werden in einem neuen Bedienfeld &quot;Elemente&quot; zusammengeführt
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Das Bedienfeld &quot;Elemente&quot; unterstützt jetzt die folgenden Elementtypen: Materialien, Filter und Bilder
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Auf alle Starter-Assets kann im Abschnitt Starter-Assets zugegriffen werden.
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Der Abschnitt &quot;Starter-Assets&quot; ist schreibgeschützt
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Neuer Bereich &quot;Ihre Assets&quot;
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Der Bereich &quot;Ihre Assets&quot; ist der Bereich, in den Sie alle Ihre Ressourcen importieren können
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Alle Elemente unter &quot;Ihre Elemente&quot; werden einem bestimmten Ordner in Ihren Dokumenten hinzugefügt
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Lokale Ordner im Bedienfeld &quot;Elemente&quot; verbinden, um neue Abschnitte hinzuzufügen
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Die Suche erfolgt im aktuellen Ordner und seinen Unterordnern.
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Mit Breadcrumbs zwischen Ordnern und Unterordnern navigieren
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Aktuellen Ordner nach Material, Filter oder Bild filtern
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Kombiniere mehrere Filter, um nur Materialien und Bilder zu erhalten.
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Ändern der Anzeige durch Umschalten zwischen einem Raster oder einer Liste
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Filter werden durch ihr Symbol dargestellt
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Bilder werden in der Vorschau angezeigt
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Durch Erhöhen der Breite wird das Layout des Bedienfelds mit einer bestimmten Ansicht geändert, um zwischen Ordnern zu navigieren.
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; In nicht schreibgeschützten Bereichen löschen Sie ein Asset, indem Sie es auf das Ablagesymbol ziehen und dort ablegen
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Durch Rechtsklick auf ein Element wird ein Kontextmenü geöffnet
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Greifen Sie über das Kontextmenü mit der rechten Maustaste auf die Asset-Metadaten (Name, Kategorie, Speicherort) zu
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Löschen Sie das Element aus dem Kontextmenü (nur in nicht schreibgeschützten Bereichen verfügbar).
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Durchsuchen Sie das Element über das Kontextmenü in Adobe Bridge
* &amp;lbrack;Ebenenbedienfeld&amp;rbrack; Neues Symbol, um ein Basismaterial direkt über Ihren Ebenen hinzuzufügen
* &amp;lbrack;Ebenenbedienfeld&amp;rbrack; Tastaturbefehl: Mit Umschalt+B wird ein Basismaterial über den Ebenen hinzugefügt.
* &amp;lbrack;Ebenenbedienfeld&amp;rbrack; Ebenen verfügen jetzt über eine Miniaturvorschau (Material-Miniaturansicht, Filtersymbol oder Bildvorschau)
* &amp;blbrack;Eigenschaftenbedienfeld&amp;rbrack; Neues Design für den Titel des Bedienfelds &quot;Eigenschaften&quot; mit dem Elementnamen und der Miniaturansicht des Elements
* &amp;blbrack;Eigenschaftenbedienfeld&amp;rbrack; Filterebenen unterstützen jetzt Vorgaben
* &amp;blbrack;Eigenschaftenbedienfeld&amp;rbrack; Mache einen Rechtsklick bzw. Ctrl-Klick auf die Vorschau, um das Bild in Photoshop zu bearbeiten.
* &amp;lbrack;Adobe Bridge&amp;rbrack; Durchsuchen Sie Ihr Asset in Adobe Bridge und starten Sie Bridge am Speicherort des Assets.
* &amp;lbrack;Adobe Photoshop&amp;rbrack; &quot;In Adobe Photoshop bearbeiten&quot; öffnet das Bild in Photoshop und kann bearbeitet werden.
* &amp;lbrack;Adobe Photoshop&amp;rbrack; Bei jedem Speichern in Adobe Photoshop wird das bearbeitete Bild in Sampler neu geladen.
* &amp;lbrack;Substance 3D Designer&amp;rbrack; Von Adobe Substance 3D Designer gesendete Elemente werden direkt im Bereich &quot;Ihre Elemente&quot; des Bedienfelds &quot;Elemente&quot; angezeigt
* &amp;lbrack;Export&amp;rbrack; Elemente direkt an Adobe Substance 3D Painter und Adobe Substance 3D Stager senden
* &amp;lbrack;Export&amp;rbrack; Materialien und Umgebungslichter an Adobe Substance 3D Painter senden
* &amp;lbrack;Export&amp;rbrack; Umgebungslichter an Adobe Substance 3D Stager senden
* &amp;lbrack;Rendering&amp;rbrack; Neue Materialeigenschaften werden jetzt unterstützt und in 3D gerendert
* &amp;lbrack;Rendering&amp;rbrack; Hinzufügen von Unterstützung für Glanz (Glanzfarbe, Deckkraft des Glanzes und Raueit des Glanzes)
* &amp;lbrack;Rendering&amp;rbrack; Hinzufügen von Beschichtungsunterstützung (Beschichtungsfarbe, Beschichtungsrauhigkeit, Beschichtungsnormalität, Beschichtungsfarbe und Specular level-IOR)
* &amp;lbrack;Rendering&amp;rbrack; Hinzufügen von Anisotropie-Unterstützung (Anisotropie und Anisotropie)
* &amp;lbrack;Rendering&amp;rbrack; Hinzufügen von Specular edge color-Unterstützung
* &amp;lbrack;Rendering&amp;rbrack; Aktivieren Sie diese neuen Eigenschaften im Bedienfeld &quot;Kanaleinstellungen&quot;
* &amp;lbrack;Rendering&amp;rbrack; Einführung eines neuen Echtzeit-Engine (2021)-Renderers in der Beta-Version
* &amp;lbrack;Rendering&amp;rbrack; Wechseln zwischen den beiden Renderer-Versionen im Bedienfeld &quot;Anzeigeeinstellungen&quot;
* &amp;lbrack;Rendering&amp;rbrack; Der Renderer der Realtime Engine (2021) unterstützt Eigenschaften für Transparenz, Absorption und Streuung von Material.
* &amp;lbrack;Rendering&amp;rbrack; Der Renderer der Realtime Engine (2021) bietet eine neue Möglichkeit, Schatten aus dem Umgebungslicht zu berechnen.
* &amp;lbrack;Rendering&amp;rbrack; Der Renderer der Realtime Engine (2021) berechnet in Echtzeit die Bestrahlung des Umgebungslichts.
* &amp;blbrack;Bedienfeld für Shader-Einstellungen&amp;rbrack; Neues Bedienfeld mit Shader-Einstellungen zum Anpassen bestimmter Parameter für Material-Shader
* &amp;blbrack;Bedienfeld für Shader-Einstellungen&amp;rbrack; Neue Parameter (Normal-Skala, Height-Skala, Height-Level, Emissionsintensität, IOR, Coat-Normal-Intensität und Coat-IOR)
* &amp;blbrack;Bedienfeld für Shader-Einstellungen&amp;rbrack; Spezifische Parameter für die Realtime Engine 2021 (Subsurface Scattering, Scattering Distance, Red Shift und Rayleigh Scattering)
* &amp;blbrack;Bedienfeld für Shader-Einstellungen&amp;rbrack; Die Einstellungswerte werden pro Element gespeichert.
* &amp;blbrack;Einstellungsbedienfeld der Anzeige&amp;rbrack; Eine Vorschau der standardmäßigen Umgebungslichter wurde hinzugefügt.
* &amp;blbrack;Einstellungsbedienfeld der Anzeige&amp;rbrack; Eine Vorschau der Standardgitter wurde hinzugefügt
* &amp;blbrack;Einstellungsbedienfeld der Anzeige&amp;rbrack; Neuer Parameter für die Umgebungsdeckkraft
* &amp;blbrack;Einstellungsbedienfeld der Anzeige&amp;rbrack; Neuer Parameter für die Umgebungsweichzeichnung (spezifisch für den Renderer &quot;Realtime Engine 2021&quot;)
* &amp;lbrack;Lokalisierung&amp;rbrack; Neue Übersetzungen in Deutsch und Französisch
* &amp;lbrack;Inhalt&amp;rbrack; Neue Standard-Startmaterialien
* &amp;lbrack;Inhalt&amp;rbrack; Neue Standard-Umgebungslichter
* &amp;lbrack;Inhalt&amp;rbrack; Alle Filter wurden aktualisiert, bereinigt und optimiert.
* &amp;lbrack;Inhalt&amp;rbrack; Der Korrekturfilter wurde in mehrere Filter aufgeteilt
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Helligkeits-/Kontrastfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Farbton/Sättigung&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Dynamikfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Scharfzeichnungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neue Normal-/Height-Anpassung
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Neue Fenster&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Verwisch-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Webfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Verkrümmungstransformationsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer AO-Filter-Height
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Height zu Normal&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Farbersetzung - Ersetzen in neuen unterstützten Kanälen (Glanz, Beschichtung, Anisotropie,...)
* &amp;lbrack;Inhalt&amp;rbrack; Farbvariation - Manueller Modus, um genau die Farben auszuwählen, die geändert werden sollen
* &amp;lbrack;Inhalt&amp;rbrack; Kachelung - Option zur Visualisierung der Nahtstellen
* &amp;lbrack;Inhalt&amp;rbrack; Kachelung - Option, um die Nähte für eine perfekte Kachelung schneiden
* &amp;lbrack;Inhalt&amp;rbrack; Anpassen - Option, um ein Material hinzuzufügen, das seiner Farbe und seiner Raueit entspricht
* &amp;lbrack;Inhalt&amp;rbrack; Anpassen - funktioniert jetzt für Bilder, die der Farbe eines anderen Bildes entsprechen
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Farbtemperaturfilter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Belichtungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Belichtungsvorschaufilter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Nadir Patch-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Nadir Extract-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neue Lichtfilter (Kugel, Linie, Form, Ebene)
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Panorama-Ausbesserungsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer Filter &quot;Horizont begradigen&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Umgebungslicht - Neuer HDR-Mergefilter

**Bekannte Probleme:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Ändern des Layouts, Absturz der Anwendung
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Starke Berechnung, Absturz der Anwendung
* &amp;blbrack;Panels&amp;blbrack; MacOS - Nicht angedockte Bedienfelder befinden sich vor allen Anwendungen
* &amp;lbrack;Widgets&amp;rbrack; Die Widgets &quot;Transformieren&quot; und &quot;Positionen&quot; können verschwinden. Blende die Ebenen ein- und aus, um sie sichtbar zu machen.
* &amp;lbrack;Export&amp;rbrack; SBSAR-Export einer Umgebungsbeleuchtung verliert die 32-Bittiefen-Genauigkeit
* &amp;blbrack;Bedienfeld &quot;Elemente&quot;&amp;blbrack; Elemente können beim Öffnen eines Ordners hervorgehoben werden.
* &amp;blbrack;Eigenschaftenbedienfeld&amp;rbrack; Durch das Zurücksetzen der Parameter wird die Benutzeroberfläche des Kombinationsfelds nicht zurückgesetzt
* &amp;lbrack;Lokalisierung&amp;rbrack; Das Ändern der Sprache wirkt sich nicht auf das Projektfenster aus, bis es neu erstellt wurde

## Version 2

### 2.3.2 (2020.3.2) Vermicelli

*(Freigegeben: 23. Februar 2021)*

**Hinzugefügt:**

* &amp;lbrack;Lokalisierung&amp;rbrack; Unterstützung für Japanisch

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Beim Verändern eines Materials im Stickfilter geht das Stickbild verloren

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.3.1 (2020.3.1) Vermicelli

*(Freigegeben: 17. Dezember 2020)*

**Hinzugefügt:**

* &amp;lbrack;Motor&amp;rbrack; Substance Engine-Update
* &amp;lbrack;Anwendung&amp;rbrack; Umgebungsvariable zum Deaktivieren bestimmter Funktionen
* &amp;lbrack;Inhalt&amp;rbrack; Farbe ersetzen - Neue erweiterte Segmentierungsoption
* &amp;lbrack;Inhalt&amp;rbrack; Bodenfliesen - neue Muster und Optionen verfügbar
* &amp;lbrack;Inhalt&amp;rbrack; Stickerei - Komplette Revamp des Filters
* &amp;lbrack;Inhalt&amp;rbrack; Anpassung - Neuer metallischer Parameter + opazitätssichere Transformationskorrektur

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Doppelter Import eines benutzerdefinierten Filters nicht möglich
* &amp;lbrack;Layers&amp;rbrack; Bildeingabe mit dem Pinselwerkzeug kann nicht verwendet werden
* &amp;lbrack;Export&amp;rbrack; Exportieren Sie .jpg anstelle von .jpeg
* &amp;lbrack;UI&amp;rbrack; Bildnachweise für den Begrüßungsbildschirm aktualisieren
* &amp;lbrack;UI&amp;rbrack; Unsichtbare Trennlinie in Menüs reparieren
* &amp;lbrack;UI&amp;rbrack; Optionsfelder zeigen eine QuickInfo an, wenn sie abgeschnitten werden
* &amp;lbrack;UI&amp;rbrack; Typo: Starter-Materialien
* &amp;lbrack;Anwendung&amp;rbrack; UTF-8-Zeichen in Elementnamen funktionieren nicht
* &amp;lbrack;Lokalisierung&amp;rbrack; Kursiven Schriftstil für chinesisches Gebietsschema deaktivieren
* &amp;lbrack;Lokalisierung&amp;rbrack; Lokalisierte Zeichenfolge, in zwei Zeilen aufgeteilt
* &amp;lbrack;Lokalisierung&amp;rbrack; Ändern des Ordnernamens und Ersetzen durch Auslassungspunkte, wenn der Ordner zu lang ist
* &amp;lbrack;Lokalisierung&amp;rbrack; Formatieren von Zahlen mit Tausendertrennzeichen
* &amp;lbrack;Lokalisierung&amp;rbrack; Lokalisieren der Datums- und Zeitanzeige
* &amp;lbrack;Lokalisierung&amp;rbrack; Lokalisieren des Farbwählers unter Windows
* &amp;lbrack;Inhalt&amp;rbrack; Transformieren - Bei aktivierter sicherer Transformation dreht sich die Normale alle 45° korrekt.
* &amp;lbrack;Inhalt&amp;rbrack; Surface Relief - Beheben Sie Kachelprobleme mit dem fraktalen Perlin-Rauschen (erweitertes Rauschen)
* &amp;lbrack;Inhalt&amp;rbrack; Brickwall-Muster - Height-Eingabe in 16-Bit
* &amp;lbrack;Inhalt&amp;rbrack; Materialsymbol-Render - Problem mit Specular-Reflexionen
* &amp;lbrack;Inhalt&amp;rbrack; Farbvariation - Keine Farbverschiebung zwischen Farbeingaben und dem Ergebnis
* &amp;lbrack;Inhalt&amp;rbrack; Farbvariation - Leistungsaktualisierung

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.3.0 (2020.3.0) Vermicelli

*(Freigegeben: 26. Oktober 2020)*

**Hinzugefügt:**

* &amp;lbrack;Bild zu Material&amp;rbrack; Unterstützung für die NVIDIA RTX 3000-Serie
* &amp;lbrack;Bild zu Material&amp;rbrack; Neue Parameter zur Steuerung der Geometriedetails
* &amp;lbrack;Bild zu Material&amp;rbrack; Neue Parameter zur Steuerung der Raueit
* &amp;lbrack;Bild zu Material&amp;rbrack; Neue Parameter zur Steuerung der Begeisterungsintensität
* &amp;Klammer;Miniaturen&amp;Klammer; Neuer Miniaturbildgenerator basierend auf dem PBR-Renderer des Substance Designers
* &amp;Klammer;Miniaturen&amp;Klammer; Basismaterialien und Atlanten aktualisieren, um ihre Miniaturansicht einzubetten
* &amp;Klammer;Miniaturen&amp;Klammer; Abrufen der Miniaturansicht aus der .sbsar-Datei, sofern vorhanden
* &amp;Klammer;Miniaturen&amp;Klammer; Ändern der Miniaturansichtsqualität in den Voreinstellungen
* &amp;lbrack;Motor&amp;rbrack; Aktualisiert auf Substance Engine 8
* &amp;lbrack;Lokalisierung&amp;rbrack; Chinesische Lokalisierung
* &amp;lbrack;UI&amp;rbrack; Experimenteller Volltonfarbenwähler
* &amp;lbrack;Inhalt&amp;rbrack; Neue Umgebungskarte - Studio 06
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Atlas-Generator hinzufügen&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Atlas Splitter hinzufügen&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Verworfene Gummen&quot; hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Fingerabdruckfilter hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Scratches hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Surface Relief-Filter hinzufügen (Height-Modulationsfilter ersetzen)
* &amp;lbrack;Inhalt&amp;rbrack; Verkrümmungsfilter hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Umkehren&quot; hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Färben&quot; hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Ersetzen-Farbe&quot; hinzufügen
* &amp;lbrack;Inhalt&amp;rbrack; Transformieren - Fügen Sie die Möglichkeit hinzu, die Transformation für einen bestimmten Kanal zu deaktivieren.
* &amp;lbrack;Inhalt&amp;rbrack; Transformieren - Drehung hinzufügen, wenn die sichere Transformation aktiviert ist
* &amp;lbrack;Inhalt&amp;rbrack; Farbvariation - Fügen Sie eine Segmentierungsoption hinzu, um auszuwählen, wie die Farben verteilt werden sollen

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Richtige Aktualisierung der Benutzeroberfläche bei mehreren Aktionen zum Rückgängigmachen/Wiederholen
* &amp;lbrack;Layers&amp;rbrack; Abstürze bei mehreren Aktionen zum Rückgängigmachen/Wiederholen verhindern
* &amp;lbrack;Layers&amp;rbrack; Absturz bei Verwendung von Bild zu Material (KI-gestützt) mit folgendem Protokoll: ungültige Geräteordinale
* &amp;lbrack;Filter&amp;rbrack; Verbessern der NVIDIA-Grafikkartenerkennung für NVIDIA-spezifische Funktionen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Schließen der Anwendung
* &amp;lbrack;Anwendung&amp;rbrack; Beheben der VRAM-Betragserkennung auf dem MacOS
* &amp;lbrack;Export&amp;rbrack; Einige Exportvorgaben fehlen manchmal
* &amp;lbrack;Inhalt&amp;rbrack; Ölfarbeneffekt - Korrigieren des Height-Bereichs mit hoher Versatz-Amplitude
* &amp;lbrack;Inhalt&amp;rbrack; Make It Tile Advanced - Keine ausgewaschene Grundfarbe beim Export
* &amp;lbrack;Inhalt&amp;rbrack; Make It Tile Advanced - Weiße Maske auf der Grundfarbe, wenn der AO zu stark ist
* &amp;lbrack;Inhalt&amp;rbrack; Anpassung - Es funktioniert jetzt auf Bildern (scan1, ...)

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.2.1 (2020.2.1) Udon

*(Freigegeben: 21. Juli 2020)*

**Hinzugefügt:**

* &amp;lbrack;Layers&amp;rbrack; In App-Fehlermeldung, wenn Bild zu Material (KI-gestützt) nicht genügend Arbeitsspeicher hat

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; &quot;Bild zu Material&quot; (KI-gestützt) funktioniert nicht mit Specular-/Glossiness-Workflows
* &amp;lbrack;Layers&amp;rbrack; Abstürze, wenn kein Videospeicher mehr vorhanden ist, während Bild zu Material verwendet wird (KI-gestützt)
* &amp;lbrack;Layers&amp;rbrack; Disk-Cache wird nicht für die Anzeige beim Öffnen eines Stapels verwendet
* &amp;lbrack;Layers&amp;rbrack; Erkennung von NVIDIA RTX 8000
* &amp;lbrack;Layers&amp;rbrack; Manchmal ist es unmöglich, eine Ebene außerhalb einer Splatter-Eingabe zu verschieben
* &amp;lbrack;Layers&amp;rbrack; Beim Einfügen eines Stapels in einen Stapel wird der Disk-Cache nicht verwendet
* &amp;lbrack;Layers&amp;rbrack; Einige Kanalnutzung werden berechnet, obwohl sie nicht verwendet werden.
* &amp;lbrack;Layers&amp;rbrack; Beim Importieren von Bildern werden manchmal leere Ausgaben erstellt
* &amp;lbrack;2D Ansicht&amp;rbrack; Wechseln zu einer anderen Ebene mit aktiviertem Zeichnungsmodus blockiert Schwenken und Zoomen
* &amp;lbrack;Inhalt&amp;rbrack; Snow - 8-Bit-Problem auf der Normalkarte
* &amp;lbrack;Inhalt&amp;rbrack; Pflasterbild - 8-Bit-Problem auf der normalen Karte
* &amp;lbrack;Inhalt&amp;rbrack; Equalizer - 8-Bit-Problem auf der normalen Karte
* &amp;lbrack;Inhalt&amp;rbrack; Kiesgenerator - 8-Bit-Problem auf der normalen Karte
* &amp;lbrack;Inhalt&amp;rbrack; Bodenfliesen - Handle-Deckkraft und Specular level
* &amp;lbrack;Inhalt&amp;rbrack; Mischzyklen je Exportvorgabe - Normalmap umkehren
* &amp;lbrack;Inhalt&amp;rbrack; Korrigieren von Problemen mit riesigen Bildern von Bild zu Material (KI-gestützt)
* &amp;lbrack;Anwendung&amp;rbrack; Absturz bei Auswahl von &quot;Sichern und neu starten&quot; bei Datenbankfehler
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim schnellen Klicken auf dasselbe Asset
* &amp;lbrack;Anwendung&amp;rbrack; Seltene Abstürze beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Ablegen von Dateien auf dem Startbildschirm
* &amp;lbrack;Anwendung&amp;rbrack; Absturz, wenn eine beschädigte Umgebungsdatei geladen wird
* &amp;lbrack;Anwendung&amp;rbrack; Seltener Absturz beim schnellen Wechseln des gerenderten Assets
* &amp;lbrack;Anwendung&amp;rbrack; Einfrieren beim Beenden während der Datenverarbeitung eines Assets
* &amp;lbrack;Anwendung&amp;rbrack; Seltener Absturz beim Start auf macOS
* &amp;lbrack;Anwendung&amp;rbrack; Deadlock beim Schließen der Anwendung kurz nach dem Start
* &amp;lbrack;Rendering&amp;rbrack; 3D-Ansicht flackert manchmal
* &amp;lbrack;UI&amp;rbrack; Farbwähler und Widgets für Zufallsverteilung werden nicht an den restlichen Anpassungen ausgerichtet
* &amp;lbrack;Rendering&amp;rbrack; Falsche Berechnungszeit angezeigt
* &amp;lbrack;Export&amp;rbrack; Einige Exportvorgaben fehlen manchmal

**Bekannte Probleme:**

* Die Verwendung von Bild-zu-Material (KI-gestützt) bei Bildern mit hoher Auflösung kann langsam sein
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Doppelte Speicherung des gleichen Materialschichtstapels nicht möglich

### 2.2.0 (2020.2.0) Udon

*(Freigegeben: 15. Juni 2020)*

**Hinzugefügt:**

* &amp;lbrack;Erstellen&amp;rbrack; Neuer Filter &quot;Bild zu Material&quot; (KI-gestützt) für Windows und Linux verfügbar
* &amp;lbrack;Erstellen&amp;rbrack; Bitmap zu Material in Bild zu Material umbenennen (B2M)
* &amp;lbrack;Bildimport&amp;rbrack; Popupmenü &quot;Neue Materialerstellungsvorlage&quot;
* &amp;lbrack;Bildimport&amp;rbrack; Neue Option &quot;Basismaterial hinzufügen&quot;
* &amp;lbrack;Bildimport&amp;rbrack; Möglichkeit, zusätzliche Bilder per Drag &amp; Drop in die Vorlage zur Materialerstellung zu ziehen
* &amp;lbrack;Bildimport&amp;rbrack; Bilder in der Materialerstellungsvorlage entfernen können
* &amp;lbrack;Bildimport&amp;rbrack; Zuweisen von Kanälen zu importierten Bitmaps automatisch anhand ihres Dateinamens
* &amp;lbrack;Bildimport&amp;rbrack; In der Lage sein, Normalmaps umzukehren
* &amp;lbrack;2D Ansicht&amp;rbrack; Einführung des Malmodus
* &amp;lbrack;2D Ansicht&amp;rbrack; Die Malkacheln
* &amp;lbrack;2D Ansicht&amp;rbrack; Festlegen eines Graustufenwerts für die Pinselfarbe
* &amp;lbrack;2D Ansicht&amp;rbrack; Schwenken und Zoomen beim Malen
* &amp;lbrack;2D Ansicht&amp;rbrack; X-Verknüpfung zum Umkehren des Graustufenwerts des Pinsels
* &amp;lbrack;2D Ansicht&amp;rbrack; &amp;lbrack; und &amp;rbrack; Tastaturbefehle zum Ändern der Pinselgröße
* &amp;lbrack;2D Ansicht&amp;rbrack; Strg (bzw. Befehl) + Mausrad zum Ändern der Pinselgröße
* &amp;lbrack;2D Ansicht&amp;rbrack; Es ist jetzt möglich, die Quellposition bei Verwendung des Kopierpatches zu ändern
* &amp;lbrack;Layers&amp;rbrack; Umschalttaste + Ziehen und Ablegen, um Atlanten mit automatischer Streuung zu erstellen
* &amp;lbrack;Layers&amp;rbrack; Alt + Drag &amp; Drop fügt ein Material als Aufkleber ein
* &amp;lbrack;Layers&amp;rbrack; Transformationsmatrizen aus dem Substance Designer leicht zugänglich machen
* &amp;lbrack;Layers&amp;rbrack; Beim Ablegen von Texturen in einem nicht leeren Stapel werden die richtigen Kanäle automatisch zugewiesen.
* &amp;lbrack;Layers&amp;rbrack; Neuer Ebenentyp: Zusammengesetzte Filter
* &amp;lbrack;Parameter&amp;rbrack; Unterstützung von Substance-Zeichenfolgeneingaben
* &amp;lbrack;UI&amp;rbrack; Hinzufügen von Schlagschatten für Popups und Menüs
* &amp;lbrack;UI&amp;rbrack; Neues Farb-Widget mit Rechtsklick-Optionen (Löschen, Kopieren, Einfügen)
* &amp;lbrack;UI&amp;rbrack; Neue Bild-Widget mit Malwerkzeug-Option
* &amp;lbrack;UI&amp;rbrack; In einem Bild-Widget über ein importiertes Bild malen können
* &amp;lbrack;Rendering&amp;rbrack; Neue Standardkameraposition
* &amp;lbrack;Export&amp;rbrack; Substance-Dateien werden für Substance Designer 2020.1.2 (10.1.2) exportiert
* &amp;lbrack;Performance&amp;rbrack; Verbesserte Startzeit der Anwendung
* &amp;lbrack;Performance&amp;rbrack; Verbessern der Handhabung asynchroner Aufgaben
* &amp;lbrack;Performance&amp;rbrack; Verbessern der Leistung von Ebenenstapeln beim Hinzufügen, Entfernen oder Verschieben von Ebenen
* &amp;lbrack;Performance&amp;rbrack; &quot;Bild zu Material&quot; (KI-gestützt) läuft auf RTX-GPUs schneller
* &amp;lbrack;Inhalt&amp;rbrack; Neue Gitter: Weibliches T-Shirt, Männliches T-Shirt, Schuh
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Mischmodus - Pro Kanal mischen
* &amp;lbrack;Inhalt&amp;rbrack; Korrektur des Heights der Deckkraftüberblendung mit zwei neuen Parametern (Height-Position und Height-Skala)
* &amp;lbrack;Inhalt&amp;rbrack; Heights im Mischmodus &quot;Heights&quot; anpassen.
* &amp;lbrack;Inhalt&amp;rbrack; Option &quot;Height-Informationen&quot; in der benutzerdefinierten Maskenüberblendung verwenden
* &amp;lbrack;Inhalt&amp;rbrack; Neues Perspektivkorrektur-Werkzeug
* &amp;lbrack;Inhalt&amp;rbrack; Mustergenerator - Fügen Sie einen Parameter hinzu, um das Muster umzukehren
* &amp;lbrack;Inhalt&amp;rbrack; Mustergenerator - Neuen Parameter hinzufügen Materialdetails überschreiben
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Aufkleberfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Moosfilter
* &amp;lbrack;Inhalt&amp;rbrack; Filter &quot;Neue Risse&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer PBR-Validierung-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Bodenfliesen&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Quilt Stich-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Atlas Scatter - Benutzerdefinierte Maskeneingabe hinzufügen, um Maloption zu aktivieren
* &amp;lbrack;Inhalt&amp;rbrack; Dirt - Benutzerdefinierte Maskeneingabe hinzufügen, um Maloption zu aktivieren
* &amp;lbrack;Inhalt&amp;rbrack; CLO-Exportvorgabe
* &amp;lbrack;Inhalt&amp;rbrack; VSpitcher-Exportvorgabe
* &amp;lbrack;Inhalt&amp;rbrack; Unity HDRP-Vorgaben exportieren ein detailMap

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Importierte Bilder werden zu oft geladen
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Erstellen eines Klonpatches am unteren Rand des Stapels
* &amp;lbrack;Layers&amp;rbrack; Durch Hinzufügen eines Materials am unteren Rand des Stapels wird es instabil
* &amp;lbrack;Layers&amp;rbrack; Filter nach Bildimport funktioniert nicht ordnungsgemäß
* &amp;lbrack;Layers&amp;rbrack; Der Wert workflow_type wird nicht aktualisiert, wenn der Workflow zwischen Projekten mit einem benutzerdefinierten Filter gewechselt wird.
* &amp;lbrack;Layers&amp;rbrack; Schaltfläche &quot;Ebene entfernen&quot; deaktivieren, wenn keine Ebene ausgewählt ist
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Laden eines Assets, das einen Klonpatch enthält
* &amp;lbrack;Layers&amp;rbrack; Abstürze des Filters &quot;Normal zu Height&quot; auf MacOS
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Laden von Umgebungskarten
* &amp;lbrack;Anwendung&amp;rbrack; Leistungsprobleme, wenn ein Grafiktabletttreiber installiert ist
* &amp;lbrack;Anwendung&amp;rbrack; Import von EXR 32-Bit-Dateien ist schwarz
* &amp;lbrack;Anwendung&amp;rbrack; Abstürze beim Laden und Entladen von Elementen
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Wechsel von &quot;Durchsuchen&quot; zum Erstellen
* &amp;lbrack;Anwendung&amp;rbrack; Zielsammlung beim Speichern eines Materials, das nicht aus dem aktuellen Projekt stammt
* &amp;lbrack;Anwendung&amp;rbrack; Backup und Neustart beheben
* &amp;lbrack;Bildimport&amp;rbrack; Graustufenbilder richtig importieren
* &amp;lbrack;Inhalt&amp;rbrack; Neue Filter für die Handhabung neuer Matrizen
* &amp;lbrack;Inhalt&amp;rbrack; Importierte benutzerdefinierte Filter werden in der Schnellzugriffsleiste angezeigt
* &amp;lbrack;Inhalt&amp;rbrack; Farbverschiebung mit dem erweiterten Filter &quot;Make it tile&quot; korrigieren
* &amp;lbrack;Performance&amp;rbrack; Das Öffnen eines Farbdialogs ist langsam und berechnet die aktuelle Ebene neu
* &amp;lbrack;UI&amp;rbrack; Tastaturbefehle funktionieren manchmal nicht
* &amp;lbrack;2D Ansicht&amp;rbrack; Inhaltsbasierte Füllung erfordert einen nutzlosen ersten Klick
* &amp;lbrack;Resources&amp;rbrack; Ordner auf lokalen Datenträgern werden nach dem Entfernen immer noch auf Updates überwacht
* &amp;lbrack;Resources&amp;rbrack; Wenn Sie einen verknüpften Ordner aus dem Dateisystem löschen, wird er nicht entfernt
* &amp;lbrack;Export&amp;rbrack; Benutzerdefinierte Verwendungen in benutzerdefinierten Exportvorgaben werden nicht exportiert
* &amp;lbrack;Export&amp;rbrack; Fehler beim Exportieren der .sbsar-Datei mit Sonderzeichen im Pfad

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

* &amp;lbrack;Projekt&amp;rbrack; Metadaten exportieren und importieren
* &amp;lbrack;Anwendung&amp;rbrack; Strg+S speichert jetzt eine Vorgabe in Entdecken
* &amp;lbrack;Performance&amp;rbrack; Verwenden Sie Render-Cache, anstatt gespeicherte Materialien für Auflösungen von bis zu 2k neu zu berechnen

**Fest:**

* &amp;lbrack;UI&amp;rbrack; Anzeige für feste Datenverarbeitung im Darstellungsfenster
* &amp;lbrack;UI&amp;rbrack; Die Eingabe negativer Werte in Regler ist fest
* &amp;lbrack;UI&amp;rbrack; Kombinationsfelder: Die Tastaturpfeile und die Bildlaufleiste funktionieren jetzt
* &amp;lbrack;UI&amp;rbrack; Beibehalten des ausgewählten Kanals beim Wechsel zwischen &quot;Materialausgabe&quot; und &quot;Ebeneneingabe&quot; in der 2D-Ansicht
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Hinzufügen benutzerdefinierter Kanäle im Basismaterial behoben
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Bearbeiten von Ebenen
* &amp;lbrack;Layers&amp;rbrack; Benutzerdefinierte Kanäle werden nicht mit einem gespeicherten Material angezeigt
* &amp;lbrack;Anwendung&amp;rbrack; Seltene Abstürze beim Importieren eines Assets behoben
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Beenden
* &amp;lbrack;Anwendung&amp;rbrack; Kombinationsfelder zeigen jetzt beim Wechseln von Vorgaben richtige Werte an
* &amp;lbrack;Export&amp;rbrack; Enscape-Voreinstellung in Enscape Revit umbenannt
* &amp;lbrack;Export&amp;rbrack; Importieren einer Exportvorgabe nach dem Entfernen funktioniert
* &amp;lbrack;Export&amp;rbrack; Absturz beim Export
* &amp;lbrack;Rendering&amp;rbrack; Rendering behoben, wenn die Grundfarbe im 16-Bit-Halbschwebformat ist
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Importieren eines beschädigten Pakets nicht
* &amp;lbrack;Projekt&amp;rbrack; Handle-Migration von 2019.1.4 zu 2.x.x, wenn Create noch nie geöffnet wurde
* &amp;lbrack;Projekt&amp;rbrack; Beheben eines Absturzes beim zweimaligen Importieren desselben Projekts
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim Importieren von Projekten beheben
* &amp;lbrack;Resources&amp;rbrack; In früheren Versionen importierte benutzerdefinierte Filter funktionieren
* &amp;lbrack;Resources&amp;rbrack; Materialien mit demselben Namen löschen sich nicht mehr gegenseitig
* &amp;lbrack;Resources&amp;rbrack; Absturz beim Verknüpfen eines lokalen Ordners
* &amp;lbrack;Resources&amp;rbrack; Vom Benutzer erstellte Ordner für Starter-Materialien werden nach einem Neustart nicht mehr entfernt
* &amp;lbrack;Inspire&amp;rbrack; Korrektur des Material-/Sammlungs-Ablagebereichs und Hinzufügen einer Warnmeldung, wenn ein nicht gespeichertes Material verwendet wird

**Bekannte Probleme:**

* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

### 2.1.0 (2020.1.0) Tiramisu

*(Freigegeben: 12. März 2020)*

**Hinzugefügt:**

* &amp;lbrack;Export&amp;rbrack; Exportiere eine vordefinierte Auswahl an Vorlagen, um deine Strukturen für Renderer und Game-Engines zu verpacken
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Unreal Engine 4 exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Unity Standard exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Unity HDRP exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Mischzyklen/Gleichmäßig exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe nach Arnold 5 exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Corona Renderer exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Enscape exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Keyshot 9 exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Redshift exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in &quot;Nächste variieren&quot; exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgabe in Lens Studio exportieren
* &amp;lbrack;Export&amp;rbrack; Vorgaben in Spark AR Studio exportieren
* &amp;lbrack;Export&amp;rbrack; Exportieren einer Vorgabe in PBR Specular Glossiness von PBR Metallic Roughness
* &amp;lbrack;Export&amp;rbrack; Neue Export-Benutzeroberfläche
* &amp;lbrack;Export&amp;rbrack; Exporteinstellungen speichern
* &amp;lbrack;Export&amp;rbrack; Benutzerdefinierte Exportvorgaben importieren und verwalten
* &amp;lbrack;Export&amp;rbrack; Löschen und Ersetzen Ihrer benutzerdefinierten Exportvorgaben
* &amp;lbrack;Export&amp;rbrack; Benutzerdefinierte Exportvorgaben umbenennen
* &amp;lbrack;Export&amp;rbrack; Legen Sie die Standardexportauflösung auf die aktuelle Auflösung fest.
* &amp;lbrack;Export&amp;rbrack; Fügen Sie die Option zum Erstellen eines Unterordners zum Exportspeicherort hinzu
* &amp;lbrack;Export&amp;rbrack; Warnmeldung vor dem Ersetzen vorhandener Dateien
* &amp;lbrack;Anwendung&amp;rbrack; Neues Versionsnummerierungsschema
* &amp;lbrack;Anwendung&amp;rbrack; Öffnen Sie &quot;Beim Start erstellen&quot; und ändern Sie die Laborreihenfolge
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Neues Willkommensbanner
* &amp;lbrack;Projekt&amp;rbrack; Letztes Projekt beim Start öffnen
* &amp;lbrack;UI&amp;rbrack; Neuer Kombinationsfeldstil
* &amp;lbrack;2D-Ansicht&amp;rbrack; F-Verknüpfung zum Fokus in der 2D-Ansicht
* &amp;lbrack;Filter&amp;rbrack; Neue Unterstützung für das alchemist::parameterVisibility-Tag in Substance-Diagrammen
* &amp;lbrack;Filter&amp;rbrack; Globale Anpassung der Parametersichtbarkeit auf Basis Ihres Workflows
* &amp;lbrack;Resources&amp;rbrack; Neue Befehlszeilenoption zum Einrichten von Ressourcen und verknüpften Ordnern mit einer Konfigurationsdatei
* &amp;lbrack;Versionsprüfung&amp;rbrack; Konfiguration der Versionsprüfung
* &amp;lbrack;Inhalt&amp;rbrack; Neue Startmaterialien
* &amp;lbrack;Inhalt&amp;rbrack; Bitmap zu Material : Fügen Sie die Möglichkeit hinzu, den metallischen Kanal zu definieren (einheitlich, benutzerdefinierter Bildimport, Farbauswahl).
* &amp;lbrack;Inhalt&amp;rbrack; Anpassung: Fügen Sie die Unterstützung des PBR-Workflows für Specular/Glanz hinzu.
* &amp;lbrack;Inhalt&amp;rbrack; Atlas Scatter - Neue Parameter

**Fest:**

* &amp;lbrack;Projekt&amp;rbrack; Absturz beim zweimaligen Importieren desselben Projekts
* &amp;lbrack;Projekt&amp;rbrack; Absturz beim mehrmaligen Importieren und Öffnen von Projekten behoben
* &amp;lbrack;Anwendung&amp;rbrack; Absturz beim Laden eines unbenannten Materials
* &amp;lbrack;Anwendung&amp;rbrack; Erkennen fehlender Dateien beim erneuten Import
* &amp;lbrack;Anwendung&amp;rbrack; Beheben eines zufälligen Absturzes beim Herunterfahren
* &amp;lbrack;Anwendung&amp;rbrack; Seltene Abstürze beim Entladen eines Materials in Create wurden behoben
* &amp;lbrack;Anwendung&amp;rbrack; Zufälliger Absturz bei Verwendung von UI-Steuerelementen behoben
* &amp;lbrack;Anwendung&amp;rbrack; Der Export von Protokolldateien auf den Desktop unter Windows 10 wurde behoben.
* &amp;lbrack;UI&amp;rbrack; Das Exportierenbedienfeld hat die falsche Größe, wenn Sie es in Erstellen öffnen
* &amp;lbrack;UI&amp;rbrack; Projekt mit einem Klick öffnen
* &amp;lbrack;UI&amp;rbrack; Richtiges Festlegen von minimalen und maximalen Schiebereglerwerten
* &amp;lbrack;UI&amp;rbrack; Beschriftung der Kanalnutzung anstelle von IDs anzeigen
* &amp;lbrack;UI&amp;rbrack; Durch Klicken auf ein Material wird das Bedienfeld &quot;Anpassen&quot; immer geöffnet/geschlossen.
* &amp;lbrack;UI&amp;rbrack; Farben von ausgeblendeten Ebenen korrigieren
* &amp;lbrack;UI&amp;rbrack; Verbesserungen an den Begrüßungsbildschirmschaltflächen
* &amp;lbrack;Layers&amp;rbrack; Weniger unnötige Neuberechnungen
* &amp;lbrack;Layers&amp;rbrack; Absturz bei Verwendung des Klonpatches
* &amp;lbrack;Layers&amp;rbrack; Wenn Sie eine Bildimportebene auswählen, wird kein Computer mehr ausgelöst.
* &amp;lbrack;Layers&amp;rbrack; Ebenen &quot;Klonen&quot; und &quot;Inhaltsbasierte Füllung&quot; werden bei Auswahl nicht mehr neu berechnet
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Das Aktivieren oder Deaktivieren von Verwendungen löst jetzt ein Rendering aus
* &amp;lbrack;Resources&amp;rbrack; Einfrieren verhindern, wenn Sie auf einen Stapel in der Bibliothek massenhaft klicken
* &amp;lbrack;Resources&amp;rbrack; Leistungseinbußen beim erneuten Hinzufügen eines zuvor hinzugefügten verknüpften Ordners
* &amp;lbrack;Resources&amp;rbrack; Absturz beim Versuch, eine gelöschte .sbsar-Datei zu öffnen, behoben
* &amp;lbrack;Performance&amp;rbrack; Vermeiden Sie das Laden von Materialien, um auf deren Parameter zuzugreifen
* &amp;lbrack;Performance&amp;rbrack; Sichern von Assets nur bei Verwendung in einem Projekt oder in einem erstellten Material
* &amp;lbrack;Export&amp;rbrack; Fixierte Materialien in der Exportwarteschlange werden manchmal übersprungen oder mit falschen Parametern exportiert
* &amp;lbrack;2D Ansicht&amp;rbrack; Schwenken und Zoomen wiederhergestellt
* &amp;lbrack;Inhalt&amp;rbrack; Das Parkettmuster berücksichtigt den Umgebungskanal für die Verdeckung.
* &amp;lbrack;Inhalt&amp;rbrack; Malen - Maskeneingabe anzeigen, wenn benutzerdefinierte Maske aktiviert wird
* &amp;lbrack;Inhalt&amp;rbrack; Stonewall-Muster - Entfernen Sie mögliche Streifeneffekte in der normalen Karte
* &amp;lbrack;Inhalt&amp;rbrack; Height Modulation - Korrigieren Sie doppelte Grundfarbeinträge in der 2D-Ansicht

**Bekannte Probleme:**

* Inhaltsbasierte Füllfilter sind bei hoher Auflösung langsam
* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben

## Version 1

### 1.1.4 (2019.1.4) Sesam

*(Freigegeben: 30. Januar 2020)*

**Hinzugefügt:**

* &amp;lbrack;Resources&amp;rbrack; Bestätigungsaufforderung beim Löschen eines Ressourcenordners

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Ebenen unter oder über zwei oder mehr Ebenen verschieben
* &amp;lbrack;Erstellen&amp;rbrack; Zuweisung eines ausreichenden VRAM-Budgets für eine gute Leistung

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

* &amp;lbrack;Workflow&amp;rbrack; Unterstützung mehrerer Arbeitsabläufe
* &amp;lbrack;Workflow&amp;rbrack; Unterstützung des PBR Specular Glossiness-Workflows
* &amp;lbrack;Workflow&amp;rbrack; Neues Bedienfeld &quot;Kanaleinstellungen&quot;
* &amp;lbrack;Workflow&amp;rbrack; Arbeitsablaufauswahl bei der Projekterstellung
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Bestimmte Kanalberechnung aktivieren/deaktivieren
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Liste der im aktuellen Material verfügbaren benutzerdefinierten Kanäle anzeigen
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Automatische Berechnung benutzerdefinierter Kanäle, falls erforderlich
* &amp;lbrack;Kanaleinstellungen&amp;rbrack; Berechnung benutzerdefinierter Kanäle erzwingen/blockieren
* &amp;lbrack;Layers&amp;rbrack; Neue Benutzeroberfläche für Platzhalter für Materialeingabe in den Atlas Scatter- und Farbspritzer-Filtern
* &amp;lbrack;Layers&amp;rbrack; Der Bildeingabeparameter eines Filters kann durch Unterschichten zugeführt werden.
* &amp;lbrack;Layers&amp;rbrack; Eine Benachrichtigung anzeigen, wenn einige Ebenen veraltet sind
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit, über die Benachrichtigung auf die neueste Version veralteter Ebenen zu aktualisieren
* &amp;lbrack;Projekt&amp;rbrack; Neue Metadatenfelder bei der Projekterstellung
* &amp;lbrack;Inspire&amp;rbrack; Generierte Varianten sind projektspezifisch
* &amp;lbrack;2D Ansicht&amp;rbrack; Zwischen den Ebeneneingängen, Ebenenausgängen und den Materialausgängen wechseln
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Option &quot;Importprojekt (.alch) hinzufügen&quot;
* &amp;lbrack;Voreinstellungen&amp;rbrack; Neues Fenster &quot;Voreinstellungen&quot; zum Festlegen des Cachespeicherorts und der Datenschutzeinstellungen für die Analyse
* &amp;lbrack;UI&amp;rbrack; Neue UI-Schaltflächen
* &amp;lbrack;Performance&amp;rbrack; Gesamtverbesserung des Parallelisierungssystems
* &amp;lbrack;Performance&amp;rbrack; Optimierung der Anzahl der Materialrechner
* &amp;lbrack;Motor&amp;rbrack; Substance Engine-Update
* &amp;Klammer;Rahmen&amp;Klammer; Upgrade auf Qt 5.13
* &amp;lbrack;MacOS&amp;rbrack; Globale Verbesserungen der Unterstützung für macOS Catalina
* &amp;lbrack;Inhalt&amp;rbrack; Anpassungsfilter - Normale Intensität und Umkehrparameter

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Parameter &quot;Bildeingabe&quot; beim Löschen der Ebene aufheben
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Hinzufügen einer Klonpatchebene beheben
* &amp;lbrack;Layers&amp;rbrack; Abstürze beim Mischen von Ebenen, die Materialien in anderen Ebenen stapeln, beheben
* &amp;lbrack;Export&amp;rbrack; Die Kanalauswahl für den Export wird jetzt berücksichtigt
* &amp;lbrack;Resources&amp;rbrack; Absturz beim Navigieren im Bedienfeld &quot;Ressourcen&quot; nicht
* &amp;lbrack;Resources&amp;rbrack; Absturz beim Importieren beschädigter Substance-Dateien beheben
* &amp;lbrack;Resources&amp;rbrack; Verringern der Anzahl von Abstürzen beim Laden großer Ordner
* &amp;Klammer;Miniatur&amp;Klammer; Bei der Berechnung der Miniaturansichten wird die Benutzeroberfläche nicht eingefroren
* &amp;lbrack;Bildimport&amp;rbrack; Einheitlichkeit des in der Anwendung unterstützten Bildtyps
* &amp;lbrack;Vorgabe&amp;rbrack; Speichern Sie die Beschreibung beim Erstellen einer Vorgabe aus einem SBSAR
* &amp;lbrack;Inspire&amp;rbrack; Bild per Drag-and-Drop korrigieren
* &amp;lbrack;Anwendung&amp;rbrack; Abstürze beim Beenden beheben
* &amp;lbrack;Anwendung&amp;rbrack; Abstürze am Ausgang beim Exportieren von Materialien beheben
* &amp;lbrack;UI&amp;rbrack; Korrekturen und Verbesserungen
* &amp;lbrack;UI&amp;rbrack; Temporäres Element in &quot;nicht gespeichertes Material&quot; umbenennen
* &amp;lbrack;Inhalt&amp;rbrack; Globale Aktualisierung und Bereinigung aller Filter

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

* &amp;lbrack;Layers&amp;rbrack; Optionen zum Speichern und Speichern unter sind über die Benutzeroberfläche in der Symbolleiste &quot;Ebenenstapel&quot; verfügbar.
* &amp;lbrack;Resources&amp;rbrack; Klarere Breadcrumbs im Ressourcenfenster zum Navigieren durch Ordner
* &amp;lbrack;Resources&amp;rbrack; Schaltfläche &quot;Zurück halten&quot; gedrückt, um auf alle oberen Ordner zuzugreifen
* &amp;lbrack;Resources&amp;rbrack; Option &quot;Importierten Materialien neu laden&quot; hinzufügen, um sie auf die neueste Version zu aktualisieren
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit, das Bild in der Bildimportebene zu ändern
* &amp;lbrack;Layers&amp;rbrack; Möglichkeit, ein Bild als Kanal zu definieren (Grundfarbe, Normal, Height,...) in der Bildimportebene
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Atlas Scatter-Filter zur Streuung neuer Atlaselemente aus Substance Source
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Ölfarben-Effektfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Kanalgenerierungsfilter zum Generieren von Height, Verdeckung und Raueit aus Grundfarben- und Normalmaps

**Fest:**

* &amp;lbrack;UI&amp;rbrack; QuickInfos in der Symbolleiste &quot;Ebenenstapel&quot; erneut aktivieren
* &amp;lbrack;UI&amp;rbrack; Problem bei der Eingabe von zwei Dezimalstellen in einem Schiebereglerwert beheben
* &amp;lbrack;Performance&amp;rbrack; Absturz beim schnellen Wechsel zwischen Materialien beheben
* &amp;lbrack;Export&amp;rbrack; Das Wechseln zu einem anderen Material vor dem Ende eines Exports stürzt nicht mehr ab
* &amp;lbrack;Resources&amp;rbrack; Kontextmenü wird über dem Material angezeigt, wenn Sie mit der rechten Maustaste darauf klicken
* &amp;lbrack;Layers&amp;rbrack; Der Link &quot;Klicken Sie hier&quot; funktioniert, wenn der Ebenenstapel leer ist
* &amp;blbrack;Vorgaben&amp;blbrack; Schaltfläche &quot;Speichern entfernen&quot; im Bedienfeld &quot;Anpassen&quot;, wenn es sich um ein auf einem Alchemist erstelltes Material handelt
* &amp;lbrack;Tweak&amp;rbrack; Informationsmeldung, die angezeigt wird, wenn es sich um ein in Alchemist erstelltes Material handelt
* &amp;lbrack;Viewport&amp;rbrack; Der Standardwert der Specular level-Textur wurde auf 0,04 korrigiert.
* &amp;lbrack;Dateimenü&amp;rbrack; Korrigieren und Umbenennen Speichern und Speichern unter
* &amp;lbrack;Motor&amp;rbrack; Aktualisieren Sie die Substance-Engine-Version, um einen Absturz einiger SBSAR-Dateien während des Imports zu vermeiden.
* &amp;lbrack;Inhalt&amp;rbrack; Kachelfilter funktioniert auf dem Umgebungskanal der Verdeckung
* &amp;lbrack;Inhalt&amp;rbrack; Der Freistellungsfilter arbeitet auf dem Kanal für die umgebende Verdeckung
* &amp;lbrack;Inhalt&amp;rbrack; Wasserfilter modifiziert die Verstärkung des Heights map
* &amp;lbrack;Inhalt&amp;rbrack; Korrigieren der Kachelung des oberen Materials im Deckkraft-Mischmodus
* &amp;lbrack;Inhalt&amp;rbrack; Height des oberen Materials wird im Deckkraftmischmodus beibehalten
* &amp;lbrack;Inhalt&amp;rbrack; Es ist möglich, eine benutzerdefinierte Maske, ein benutzerdefiniertes Muster oder eine Skalierungsmaske im Perforationsfilter hinzuzufügen.
* &amp;lbrack;Inhalt&amp;rbrack; Height Modulation-Filter erzwingt Height- und Normalmaps in 16 bit
* &amp;lbrack;Inhalt&amp;rbrack; Korrekturfilter erzwingt Height- und Normalmaps in 16 Bit

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

* &amp;lbrack;Angleichen&amp;rbrack; Neue Füllmethode für Deckkraft
* &amp;lbrack;Motor&amp;rbrack; Neue Substance Engine-Version

**Fest:**

* &amp;lbrack;Layers&amp;rbrack; Beheben von Abstürzen beim Löschen einer Ebene, die noch berechnet wird
* &amp;lbrack;Layers&amp;rbrack; Absturz beim Entfernen der unteren Ebene beheben
* &amp;lbrack;Layers&amp;rbrack; Absturz beheben, während der Materialname Sonderzeichen enthält
* &amp;lbrack;Layers&amp;rbrack; Berechnung aller Filter, die ein Widget verwenden, beenden
* &amp;lbrack;Layers&amp;rbrack; Vermeiden Sie Abstürze bei der Verwendung von Kopierpatch- und inhaltsbasierten Füllfiltern
* &amp;lbrack;Layers&amp;rbrack; Beheben von Abstürzen beim Ziehen und Ablegen eines Filters in einem Splätter-Eingabebereich
* &amp;lbrack;Resources&amp;rbrack; Absturz beim Verknüpfen lokaler Ordner oder Importieren von Ressourcen auf dem Substance Alchemist beheben
* &amp;lbrack;Sammlung&amp;rbrack; Beheben von Abstürzen beim schnellen Wechsel zwischen Materialien
* &amp;lbrack;UI&amp;rbrack; Absturz beheben, während der Wert null ist oder nicht gültig in Untertiteln, Versatz-Schieberegler im Viewport
* &amp;lbrack;Inspire&amp;rbrack; Absturz beim Zugriff auf die Registerkarte &quot;Inspiration&quot; beheben
* &amp;lbrack;Inspire&amp;rbrack; Beheben Sie einen Absturz, während Sie an gerade gespeicherten Ebenen inspirieren.
* &amp;lbrack;Performance&amp;rbrack; Schneller berechnen schwere Substance-Materialien und -Filter (Kacheln)
* &amp;lbrack;Hilfe&amp;rbrack; Exportprotokolldatei korrigieren
* &amp;lbrack;Inhalt&amp;rbrack; Randomizer-Filter funktioniert auf allen Kanälen
* &amp;lbrack;Inhalt&amp;rbrack; Multiangle-Arbeitsablauf berücksichtigt alle Scans
* &amp;lbrack;Inhalt&amp;rbrack; AO Korrekte Füllmethode
* &amp;lbrack;Inhalt&amp;rbrack; Kurvenüberblendung korrigieren.
* &amp;lbrack;Inhalt&amp;rbrack; Farb-ID Füllmethode
* &amp;lbrack;Inhalt&amp;rbrack; Benutzerdefinierte Maskenüberblendung - korrekte Überblendung
* &amp;lbrack;Inhalt&amp;rbrack; Korrekturanpassungsfilter für die Raueitsänderung
* &amp;lbrack;Inhalt&amp;rbrack; Basismaterial-Filter für benutzerdefinierten Upload über normale Kanäle beheben
* &amp;lbrack;Inhalt&amp;rbrack; Benutzerdefiniertes Importmuster des Prägefilters korrigieren

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen

### 1.1.0 (2019.1.0) Sesam

*(Freigegeben: 04. November 2019)*

**Hinzugefügt:**

* &amp;lbrack;Projekt&amp;rbrack; Projekterstellung
* &amp;lbrack;Projekt&amp;rbrack; Einführung des .alch-Dateiformats, das Projektdaten enthält
* &amp;lbrack;Projekt&amp;rbrack; Exportieren eines .alch-Projekts mit den Sammlungen und ihren Materialien
* &amp;lbrack;Projekt&amp;rbrack; Importieren eines .alch-Projekts
* &amp;lbrack;Projekt&amp;rbrack; Öffnen aktueller Projekte
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Ein Begrüßungsbildschirm wird beim Start angezeigt
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Erstellen eines Projekts über den Begrüßungsbildschirm
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Zugriff auf die Liste all Ihrer Projekte auf dem Begrüßungsbildschirm
* &amp;lbrack;Begrüßungsbildschirm&amp;rbrack; Quick-Links zum Zugriff auf die Dokumentation, das Info-Popup und die Lizenzverwaltung
* &amp;lbrack;Dateimenü&amp;rbrack; Integration eines Dateimenüs
* &amp;lbrack;Dateimenü&amp;rbrack; Auf die Projektbefehle über die Registerkarte &quot;Datei&quot; und das Speichern des Ebenenstapels zugreifen
* &amp;lbrack;Dateimenü&amp;rbrack; Auf die Befehle &quot;Rückgängig&quot; und &quot;Wiederholen&quot; auf der Registerkarte &quot;Bearbeiten&quot; zugreifen
* &amp;lbrack;Dateimenü&amp;rbrack; Das vorherige Hilfemenü wurde in das Dateimenü auf der Registerkarte Hilfe verschoben.
* &amp;lbrack;Layers&amp;rbrack; Neue Architektur des Ebenenstapels
* &amp;lbrack;Layers&amp;rbrack; Neue Benutzeroberfläche des Ebenenstapels
* &amp;lbrack;Layers&amp;rbrack; Wählen Sie den Mischmodus direkt in der Symbolleiste aus
* &amp;lbrack;Layers&amp;rbrack; Separater Zugriff auf die Überblendungsparameter und die Materialparameter
* &amp;lbrack;Layers&amp;rbrack; Fügen Sie Materialien direkt in die dedizierten Eingaben des Splatter-Filters im Ebenenstapel hinzu
* &amp;lbrack;Layers&amp;rbrack; Ändern der Scanreihenfolge direkt in der Bildimportebene
* &amp;lbrack;Viewport&amp;rbrack; Steuerung des Kamerafelds
* &amp;lbrack;Viewport&amp;rbrack; Möglichkeit, zwischen orthogonaler oder perspektivischer Kamera zu wechseln
* &amp;lbrack;Viewport&amp;rbrack; Informationen zur Auflösung und Bittiefe für jeden Kanal anzeigen
* &amp;lbrack;Resources&amp;rbrack; Basismaterialien werden standardmäßig geöffnet
* &amp;lbrack;Zwischenspeichern&amp;rbrack; Ordner mit Miniaturansichten im Cache
* &amp;lbrack;Zwischenspeichern&amp;rbrack; Finden Sie Ihren Render-Cache-Ordner
* &amp;blbrack;Panels&amp;blbrack; Das Bedienfeld &quot;Materialeinstellungen&quot; ist vorübergehend ausgeblendet
* &amp;lbrack;Workflow&amp;rbrack; Specular/Glanzgrad vorübergehend deaktiviert
* &amp;lbrack;MacOS&amp;rbrack; Beglaubigung der Catalina OS-Version
* &amp;lbrack;Inhalt&amp;rbrack; Neue Version des Delighter-Filters
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Inhaltsbasierte Füllung&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Der Transformationsfilter verfügt über eine sichere Transformationsoption

**Fest:**

* Alle vorherigen Fehler im Zusammenhang mit Create sind heute mit der neuen Benutzeroberfläche und dem neuen Architekturrelease ungültig.
* QuickInfos blenden die Symbole in der oberen Leiste nicht aus (3D, 2D, 2D/3D)
* &amp;lbrack;Inhalt&amp;rbrack; Splatter-Filter akzeptiert Atlas mit vollständiger Height-Map
* &amp;lbrack;Inhalt&amp;rbrack; Der Transformieren-Filter funktioniert für Bilder (scan1, scan2,...)

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

* &amp;lbrack;Erstellen&amp;rbrack; Einige Filter wurden im Schnellzugriff, aber nicht im Filterbereich aufgeführt
* &amp;lbrack;MacOS&amp;rbrack; Einige Abstürze beim Beenden behoben

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

* &amp;lbrack;Resources&amp;rbrack; Verbinden und Spiegeln Ihrer Materialordner auf Ihren lokalen Festplatten
* &amp;lbrack;Resources&amp;rbrack; Durchsuchen Sie Ihre Materialordner und deren Unterordner
* &amp;lbrack;Resources&amp;rbrack; Lösen Sie das Bedienfeld &quot;Materialressourcen&quot; in einem separaten Fenster, um Ihre Ressourcen im Vollbildmodus anzuzeigen.
* &amp;lbrack;Resources&amp;rbrack; Neues Layout des Bedienfelds &quot;Ressourcen&quot; zur Unterstützung der Navigation von Ordnern und Unterordnern
* &amp;lbrack;Resources&amp;rbrack; Verwenden Sie das Breadcrumb, um durch Ihre Ordner zu navigieren
* &amp;lbrack;Resources&amp;rbrack; Erzwingen der Synchronisierung Ihres lokalen Ordners mit der Option Synchronisieren , die per Rechtsklick aufgerufen werden kann
* &amp;lbrack;Resources&amp;rbrack; Trennen Sie den lokalen Ordner mit der Option &quot;Trennen&quot;, die per Rechtsklick zugänglich ist
* &amp;lbrack;Verwalten&amp;rbrack; Anzeigen eingebetteter Tags von Substance-Dateien
* &amp;lbrack;Verwalten&amp;rbrack; Hinzufügen, Bearbeiten und Löschen von Tags Ihrer Materialien
* &amp;lbrack;Verwalten&amp;rbrack; Material bewerten.
* &amp;lbrack;Layers&amp;rbrack; Panorama-Ausgabe unterstützen
* &amp;lbrack;Layers&amp;rbrack; Sie können Bildeingaben in der Bildimportebene löschen
* &amp;lbrack;Layers&amp;rbrack; Automatische Auswahl der neuen hinzugefügten Ebene
* &amp;lbrack;Layers&amp;rbrack; Automatische Auswahl der Ebene darunter nach dem Löschen einer Ebene
* &amp;lbrack;UX&amp;rbrack; Sichtbarkeit des linken Bereichs beim Wechsel zu einem anderen Labor beibehalten
* &amp;lbrack;UX&amp;rbrack; Erstellen Sie keine Basisebene oder öffnen Sie das Popup &quot;Material-Arbeitsablauf&quot; nicht, wenn Sie Bilder in einen nicht leeren Ebenenstapel importieren.
* &amp;lbrack;UI&amp;rbrack; Neuer Textfeldstil
* &amp;lbrack;UI&amp;rbrack; Neue Suchfeld-Formatvorlage
* &amp;lbrack;UI&amp;rbrack; Neuer Kopfzeilenstil für Bedienfelder
* &amp;lbrack;UI&amp;rbrack; Neuer Anzeigestil &quot;Gebucht&quot;
* &amp;lbrack;UI&amp;rbrack; Neues Hintergrundformat für Ebenenstapel
* &amp;lbrack;UI&amp;rbrack; Adobe Clean-Schrift verwenden
* &amp;lbrack;UI&amp;rbrack; Entfernen des Platzhalters für das Pipettensymbol des Farbeingabeparameters
* &amp;lbrack;Performance&amp;rbrack; Optimierung der Belegungsanzeige
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Mustergenerator-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Weichzeichnungsfilter

**Fest:**

* &amp;lbrack;Inspire&amp;rbrack; Absturz bei Verwendung von mehr als 10 Farben beheben
* &amp;lbrack;2D Ansicht&amp;rbrack; Fixieren der Bildlaufleiste in der Kanalliste der 2D-Ansicht
* &amp;blbrack;Viewer&amp;rbrack; Absturz beim Importieren einer Umgebungskarte ohne Stromversorgung von 2 beheben
* &amp;lbrack;Inhalt&amp;rbrack; PNG-Import für benutzerdefiniertes Muster von Präge- und Perforationsfiltern korrigieren
* &amp;lbrack;Export&amp;rbrack; Normal- und Height-Export mit 16 Bit pro Kanal
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

* &amp;lbrack;Filter&amp;rbrack; Per Leertaste schnell auf Filter zugreifen
* &amp;lbrack;Filter&amp;rbrack; Neues spezielles Bedienfeld zum Verwalten, Durchsuchen und Importieren Ihrer Filter
* &amp;lbrack;Metadaten&amp;rbrack; Rechtsklick auf ein Material, um seine Metadaten anzuzeigen
* &amp;lbrack;Metadaten&amp;rbrack; Klicken Sie mit der rechten Maustaste auf ein Material, um seinen Speicherort auf der Festplatte anzuzeigen.
* &amp;blase;Regler&amp;blase; Animieren Sie die Schieberegler, wenn Sie mit der Maus darauf zeigen, indem Sie Strg drücken
* &amp;blase;Regler&amp;blase; Die Animation der Regler anhalten und neu starten, indem Sie P drücken.
* &amp;lbrack;Export&amp;rbrack; SBSAR-Export folgt den Richtlinien für die Substance Source
* &amp;lbrack;Lizenz&amp;rbrack; Substance Alchemist mit einer Umgebungsvariablen aktivieren
* &amp;lbrack;UX&amp;rbrack; Dateidialogfeld merkt sich den zuletzt ausgewählten Dateipfad
* &amp;lbrack;UX&amp;rbrack; Ordnerdialog merkt sich den zuletzt ausgewählten Ordnerpfad
* &amp;lbrack;UI&amp;rbrack; Benutzeroberfläche des Bedienfelds &quot;Ressourcen aktualisieren&quot;
* &amp;lbrack;UI&amp;rbrack; Benutzeroberfläche der Suchleiste aktualisieren
* &amp;lbrack;UI&amp;rbrack; Symbol &quot;Neues Material erstellen&quot; wurde aktualisiert
* &amp;lbrack;Hilfe&amp;rbrack; URLs werden auf substance3d.com Domäne aktualisiert
* &amp;lbrack;Mesh&amp;rbrack; Ein Tuchgeflecht ist jetzt verfügbar
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Korrosionsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Oxydationsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Moosfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Dust-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Brickwall-Musterfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Steinmauer-Musterfilter
* &amp;lbrack;Inhalt&amp;rbrack; New Wood Finish Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Metal-Finish-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Snow-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Randomizer-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Sie können Ihre Texturen jetzt direkt in den Basismaterial-Filter importieren

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

* &amp;lbrack;Motor&amp;rbrack; Substance Engine-Update, um mit der neuesten Substance Designer-Version kompatibel zu sein
* &amp;lbrack;Lizenz&amp;rbrack; Aktualisieren des Lizenzordners für die erste Installation
* &amp;lbrack;Layers&amp;rbrack; Sie können den Ebenenstapel jederzeit neu laden, um Ihre benutzerdefinierten Filter zu aktualisieren

**Fest:**

* &amp;lbrack;Datenkompatibilität&amp;rbrack; Präventive Korrektur zur Begrenzung der Datenbeschädigung zum Zeitpunkt des Upgrades

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

* &amp;lbrack;Metadaten&amp;rbrack; Metadaten in einem speziellen Register anzeigen und ausfüllen
* &amp;lbrack;Sammlung&amp;rbrack; Erstellen einer Sammlung direkt aus den Suchergebnissen
* &amp;lbrack;Media Publishing&amp;rbrack; Exportieren eines Dashboards einer Sammlung
* &amp;lbrack;UX&amp;rbrack; Vorgenommene Änderungen oder Bildimport durch Drücken von Strg+Z rückgängig machen
* &amp;lbrack;UX&amp;rbrack; Änderungen oder Bildimport mit Strg+Umschalt+Z wiederherstellen
* &amp;lbrack;UI&amp;rbrack; Neue Icons mit neuem Stil
* &amp;lbrack;Performance&amp;rbrack; Neuer Sitzungs-Manager, der das Wechseln der Registerkarten verbessert
* &amp;lbrack;Performance&amp;rbrack; Schnelleres Öffnen der Bildimportebene
* &amp;lbrack;Inhalt&amp;rbrack; Neues Metal-Generikum
* &amp;lbrack;Inhalt&amp;rbrack; Neues Material für Rost
* &amp;lbrack;Inhalt&amp;rbrack; Neues Stone-Generikum
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierung des Prägefilters
* &amp;lbrack;Inhalt&amp;rbrack; Stickerei Filter Update
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierung des Malfilters
* &amp;lbrack;Inhalt&amp;rbrack; Delighter-Filteraktualisierung

**Fest:**

* &amp;lbrack;Inhalt&amp;rbrack; Wasserfilter funktioniert im Specular-/Glossiness-Workflow
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

* &amp;lbrack;Stapel&amp;rbrack; Absturz beim Entfernen einer Spritzschicht
* &amp;lbrack;Daten&amp;rbrack; Asset-Datenbank wird beschädigt, wenn die Anwendung abstürzt
* &amp;lbrack;Daten&amp;rbrack; Substance Alchemist kann nicht gestartet werden, wenn die Elementdatenbank beschädigt ist
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
* &amp;lbrack;UI&amp;rbrack; Kopierwerkzeug: neue Benutzeroberfläche mit Visualisierung der Pinselgröße
* &amp;lbrack;UI&amp;rbrack; Ausgeblendete Phasen auswählen und löschen
* &amp;lbrack;UI&amp;rbrack; Neue Textfeld-Benutzeroberfläche
* &amp;lbrack;Hilfe&amp;rbrack; Zugriff auf Websites von Substance Source, Substance share und Substance Academy
* &amp;lbrack;Inhalt&amp;rbrack; Neue Standardmaterialien mit Generatoren und Atlas
* &amp;lbrack;Inhalt&amp;rbrack; Bitmap zu Materialaktualisierung
* &amp;lbrack;Inhalt&amp;rbrack; Dirt-Update
* &amp;lbrack;Inhalt&amp;rbrack; Rost-Update
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Prägefilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Stickereifilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Erosionsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Kiesgenerator
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Malfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Parkettmuster&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Filter &quot;Pflastermuster&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Perforationsfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Farbspritzer-Filter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Textilverschleißfilter
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Transformierenfilter

**Fest:**

* &amp;lbrack;Viewport&amp;rbrack; Sphäre-Gitter mit X2-Kacheln auf X
* &amp;lbrack;Viewport&amp;rbrack; Absturz beim Laden der eigenen Umgebung
* &amp;lbrack;Viewport&amp;rbrack; Die Umgebungskarte verwendet jetzt auch den Belichtungswert.
* &amp;lbrack;Viewport&amp;rbrack; F-Verknüpfung setzt Kamerawinkel nicht zurück
* &amp;lbrack;Export&amp;rbrack; SBS-Export funktioniert mit dem neuesten Substance Designer 2018.3.3
* &amp;lbrack;Export&amp;rbrack; SBSAR-Export entspricht den gleichen Richtlinien wie Substance Source
* &amp;lbrack;UI&amp;rbrack; Bildlaufleisten können gezogen werden
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

* &amp;lbrack;Ebenenstapel&amp;rbrack; Neuanordnung von Ebenen
* &amp;lbrack;Ebenenstapel&amp;rbrack; Ausgeblendete Ebenen löschen
* &amp;lbrack;Ebenenstapel&amp;rbrack; Importieren Sie ein Material direkt an einer Position Ihrer Wahl
* &amp;lbrack;Ebenenstapel&amp;rbrack; Materialeingabe als neuer Filterparametertyp
* &amp;lbrack;Performance&amp;rbrack; Leistungssteigerung durch dynamisches Substance Engine-Budget
* &amp;lbrack;Performance&amp;rbrack; Bessere OpenGL-Leistung, insbesondere auf MacOS
* &amp;lbrack;Daten&amp;rbrack; Schnelleres Daten-Upgrade nach Veröffentlichung einer neuen Version
* &amp;lbrack;Inhalt&amp;rbrack; AI Delighter für Windows 7 und Windows 8
* &amp;lbrack;Inhalt&amp;rbrack; AI Delighter auf RTX-GPU verfügbar

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

* &amp;lbrack;Export&amp;rbrack; Substance-Archiv (sbsar) exportieren Ihrer Sammlung
* &amp;lbrack;Export&amp;rbrack; Substance-Dateiexport (sbs) Ihrer Sammlung
* &amp;lbrack;Export&amp;rbrack; Exportwarteschlange im Exportbedienfeld sichtbar
* &amp;lbrack;Export&amp;rbrack; Benennen Sie Ihre Sammlung oder Ihr Material vor dem Export
* &amp;lbrack;Daten&amp;rbrack; Als Material speichern durch Drücken von Strg+Umschalt+S
* &amp;lbrack;Daten&amp;rbrack; Material durch Drücken von Strg+S speichern.
* &amp;lbrack;Daten&amp;rbrack; Sammlungen und Materialien sind versionsübergreifend kompatibel.
* &amp;lbrack;Daten&amp;rbrack; Aktualisiere deinen Materialebenen-Stapel mit aktuellen Filtern.
* &amp;lbrack;Daten&amp;rbrack; Hot Reload importierter benutzerdefinierter Filter
* &amp;lbrack;UI&amp;rbrack; Visuelles Feedback im Viewport während der Datenverarbeitung
* &amp;lbrack;UI&amp;rbrack; Neuer Schaltflächenstil
* &amp;lbrack;UI&amp;rbrack; Popup &quot;Speichern&quot; zeigt den Namen der aktiven Sammlung an
* &amp;lbrack;UI&amp;rbrack; Quellbilder einer Bildimportebene ändern
* &amp;lbrack;Inhalt&amp;rbrack; Benutzerdefinierte Verwendungen werden jetzt unterstützt
* &amp;lbrack;Inhalt&amp;rbrack; In den Bildeingabeparametern werden mehr Bildformate unterstützt
* &amp;lbrack;Inhalt&amp;rbrack; Neuer Kachelfilter mit dem Namen &quot;Make It Tile Advanced&quot;
* &amp;lbrack;Inhalt&amp;rbrack; Aktualisierung des Wasserfilters

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

* &amp;lbrack;Export&amp;rbrack; Neues Popup-Fenster &quot;Export&quot;
* &amp;lbrack;Export&amp;rbrack; Gesamte Sammlung exportieren
* &amp;lbrack;Export&amp;rbrack; Exportieren von Bitmaps im gewünschten Format
* &amp;lbrack;Export&amp;rbrack; Bitmaps mit der gewählten Auflösung exportieren
* &amp;lbrack;Export&amp;rbrack; Nur die Kanäle Ihrer Wahl exportieren
* &amp;lbrack;Export&amp;rbrack; Vorschau der Schätzgröße Ihres Exports
* &amp;lbrack;Export&amp;rbrack; Verfügbare Größe auf der Festplatte vor dem Export in der Vorschau anzeigen
* &amp;lbrack;UX&amp;rbrack; Aktionen für Sammlung, auf die per Rechtsklick zugegriffen werden kann
* &amp;lbrack;UX&amp;rbrack; Löschen eines Bildes oder eines Elements in &quot;Inspiration&quot; zulassen
* &amp;lbrack;UX&amp;rbrack; Substance Alchemist wird maximiert gestartet
* &amp;lbrack;Assets&amp;rbrack; Neue Möglichkeit zum Speichern von Materialien, um sie in nächsten Versionen dauerhaft zu halten
* &amp;lbrack;Hilfe&amp;rbrack; Zugriff auf die Online-Dokumentation über das Hilfemenü
* &amp;lbrack;Performance&amp;rbrack; Schnellere Farbvariationen auf komplexen Materialien, die mit Substance Alchemist erstellt wurden
* &amp;lbrack;Performance&amp;rbrack; Verringern von Speicherlecks beim Wechseln von Labs
* &amp;lbrack;Inhalt&amp;rbrack; Skalierungsprüfer zur Diagnose der Physische Größe Ihres Materials
* &amp;lbrack;Inhalt&amp;rbrack; Update Italien Venice Mosaik Fliesenmaterial
* &amp;lbrack;Inhalt&amp;rbrack; Moosspritzer aktualisieren

**Fest:**

* Kein Standardname mehr beim Speichern eines Materials
* Filterparameter gehen nach dem Speichern eines Materials und dem erneuten Öffnen von Substance Alchemist verloren
* &amp;lbrack;Inhalt&amp;rbrack; Korrektur von unten und von oben für AO- und Krümmungs-Überblendung

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
* &amp;lbrack;Log&amp;rbrack; Protokolldatei über das Hilfemenü exportieren
* &amp;blbrack;UI&amp;rbrack;Neuer Reglerstil
* &amp;blbrack;UI&amp;rbrack;Vorgaben- und Tweak-Bedienfelder werden zusammengeführt
* &amp;lbrack;UI&amp;rbrack;Neues Miniaturenformat
* Einstellungen für Versatz, Kacheln und Schatten, auf die direkt im Viewport zugegriffen werden kann
* &amp;lbrack;Inhalt&amp;rbrack; Neue Standardmaterialien
* &amp;lbrack;Inhalt&amp;rbrack; Update für Moos-Farbspritzer
* &amp;Klammer;Rahmen&amp;Klammer; Update Substance Engine Framework

**Fest:**

* Das Löschen Ihres Ebenenstapels durch Wechseln der Labs ist fest
* Die im Viewport angezeigten Zeitwerte werden korrekt geladen.
* Standardkanäle des Material-Workflows sind korrekt initialisiert
* Benutzerdefinierten Gitterimport deaktivieren
* Bitmapexport
* &amp;lbrack;MacOS&amp;rbrack; Das Schließen des Substance Alchemist kann ein &quot;Beenden erzwingen&quot; erfordern

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
* &amp;lbrack;MacOS&amp;rbrack; Substance Alchemist kann im Vollbildmodus eingestellt werden
* &amp;lbrack;Filter&amp;rbrack; Benutzerdefinierte Maske importieren , um die Überblendung zwischen zwei Materialien zu verwalten
* &amp;lbrack;Filter&amp;rbrack; Moos-Skala steuern
* &amp;lbrack;Filter&amp;rbrack; Kopierpatchaktualisierung

**Fest:**

* Bild in einer Bildeingabe in der Parameterliste hinzufügen aktualisiert Ausgaben
* Beim Import eines benutzerdefinierten Filters werden keine schwarze Umgebungsfilter und keine schwarze Deckkraft hinzugefügt.

**Bekannte Probleme:**

* Mit einer früheren Version erstellte Materialien sind in der neuen Version nicht verfügbar.
* &amp;lbrack;MacOS&amp;rbrack; Das Schließen des Substance Alchemist kann ein &quot;Beenden erzwingen&quot; erfordern
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
