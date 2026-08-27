---
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 6.0, um mehr über die neuen Funktionen, Verbesserungen und Arbeitsablaufverbesserungen zu erfahren.
title: Version 6.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 56f4ac8b2b5ec271edb8338d51f8ac51e6746c6c
workflow-type: tm+mt
source-wordcount: '1627'
ht-degree: 1%

---


# Version 6.0

Jalapeño

![Alternativtext](../../help/assets/Sampler_splash_large.jpg)

Dieses Update bietet branchenübliche Unterstützung für OpenPBR, Materialvorgaben zur schnelleren Erstellung erweiterter Materialien und einen neu gestalteten Eigenschaftenbereich für flexibleres Authoring.

Die wichtigsten neuen Funktionen sind:

## OpenPBR im Zentrum des Substance-Ökosystems

Sampler 6.0 übernimmt [OpenPBR](../features-and-workflows/openpbr.md), das einheitliche Materialmodell der Branche. Erstelle Materialien, die nativ im weiteren 3D-Ökosystem verstanden werden: Standardmäßige, unbegrenzte Kompatibilität.Einmal erstellen, sparen Sie Zeit und beschleunigen Sie Ihren Workflow mit einem Modell, das für nahtlose Interoperabilität zwischen Tools entwickelt wurde.

![OpenPBR-Materialstandard in Substance 3D Sampler](../../help/assets/OpenPBR_1820x1024.jpg)

## Komplexe Materialien mit nur einem Klick

Erstelle im Handumdrehen komplexere Materialien. Mithilfe von neuen Vorlagen wie Fuzz, Lichtdurchlässigkeit und Clear Coat kannst du erweiterte physische Effekte hinzufügen, ohne dass die Komplexität darunter leidet. Wähle einfach eine Vorlage aus, und los geht’s!

Weitere Informationen *[hier](../interface/tools-and-widgets/material-creation-presets.md)*

![Alternativtext](../../help/assets/Sampler_Complex_Materials.jpg)

## Entwickelt für die Materialerstellung

Sampler 6.0 verfeinert die gesamte Erfahrung in Bezug auf das, was am wichtigsten ist: hochwertiges digitales Twin-Material. Jedes Update und jede neue Funktion wurde entwickelt, um Reibungsverluste zu vermeiden, Zeit zu sparen und Sie sich auf die Teile Ihres Workflows konzentrieren zu können, die einen echten Mehrwert bieten.

![Alternativtext](../../help/assets/Sampler_built_for_material_creation.jpg)

## Ein neuer Ebenenstapel zur Kontrolle

Übernimm die Verantwortung für deine Materialien. Mit dem neu gestalteten Bedienfeld &quot;Eigenschaften&quot; können Sie Zielfilter für jeden Kanal festlegen, sodass Sie ohne zusätzliche Schritte präzise Bearbeitungen vornehmen können.

Weitere Informationen *[hier](../interface/panels/properties-panel.md)*

![Alternativtext](../../help/assets/Sampler_Infographic_1920x1080.png)

## Schnellere Materialerfassung

Mit Sampler können Sie jetzt eine HP Z Captis -Aufnahme mit einem einzigen Klick starten, wobei der Fokusbereich automatisch erkannt wird, bei Bedarf drehbar ist und Sie eine intelligente Automatisierung für Fokus und Lichtintensität nutzen, sodass Sie gestochen scharfe und konsistente Karten mit weniger Setup erhalten.

Weitere Informationen *[hier](../pipeline-and-integrations/hp-z-captis-support/your-first-capture-step-by-step.md)*

![Alternativtext](../../help/assets/Captis_capture_optimization.JPG)

## V6.0 - Versionshinweise

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

*(Freigegeben: 16. April 2026)*

**Hinzugefügt:**

* [3D-Ansicht] Stellen Standardgitter im USD-Format bereit.
* [Anwendung] Erkennen von Verwendungen in einem Material, das im aktuellen Materialmodell nicht verfügbar ist
* [Anwendung] Materialmodell-Tag aus SBSAR-Dateien lesen
* [Captis] Drehung des Fokusbereichs und neue 4K-Auflösung zulassen
* [Captis] Überprüfen Sie die Captis OS-Version und warnen Sie den Benutzer, sie zu aktualisieren, falls relevant.
* [Captis] Speichern von Scanparametern zwischen aufeinander folgenden Scans
* [Captis] Neues Autofokussystem
* [Captis] Scan mit einem Klick
* [Captis] Eine Benachrichtigung anzeigen, wenn die Aufnahme endet
* [Captis] Verschiedene Verbesserungen der Benutzeroberfläche/UX
* [Kanaleinstellungen] Umgestaltetes Bedienfeld für Kanaleinstellungen für OpenPBR
* [Kanaleinstellungen] Unterstützung für den Wechsel zwischen OpenPBR- und ASM-Materialmodellen
* [Export] Aktivieren Sie den Export von Materialien als USD, USDA oder USDZ.
* [Exportieren] Unterstützt OpenPBR-Kanäle bei der Exportkanalauswahl
* [Export] Verwenden Sie den Projektpfad als Standardexportpfad.
* [Filter] Erlaubt das Aktualisieren von statischen zu dynamischen zusammengesetzten Filtern.
* [Filter] Aktualisieren von statischen zu dynamischen Filtern zulassen
* [Filter] Dynamic versions of Auto Tiling, Content Aware Fill, Height Blend, Normal Blend
* [Filter] Ausblenden der statischen Version eines Filters, wenn eine dynamische Version vorhanden ist
* [Filter] Neues Füllerlebnis
* [Filter] Neues OpenPBR- und ASM-kompatibles Basismaterial
* [Bildimport] Beim Importieren von Bildern wird jetzt vorgeschlagen, dem Arbeitsablauf Verwendungen hinzuzufügen.
* [Bildimport] Verbesserte Verwendungsauswahl
* [Ebenen] Die Standard-Asset-Größe ist jetzt 2K.
* [Ebenen] Aktivieren Sie eine Auswahl für die Ausgabe pro Ebene.
* [Voreinstellungen] Hinzufügen einer standardmäßigen Materialmodell-Voreinstellung
* [Vorgabe] Die Standardvorgabe verwendet jetzt OpenPBR Materialmodell
* [Rendern] Aktivieren des 8K-Renderings
* [Rendern] Handle OpenPBR Shader in USD-Szene
* [Rendern] Rendern von Bildern in Dokumentgröße, wenn sie nicht exportiert werden
* [Skripterstellung] Handle-Materialmodell für Asset-Erstellung in der Python-API
* [Skripterstellung] Neue MaterialModel-Eigenschaft für Element
* [UI] Fügen Sie den Schnellaktionen eine Kategorie hinzu und blenden Sie die Umgebungs-/Gitterfilter aus.
* [UI] Zeigt das Vorlagenfenster an, wenn der Stapel nur ein Basismaterial enthält
* [UI] Implementieren der Fuzzy-Suche im Schnellzugriff
* [UI] Integrierte Vorlagenauswahl im Dialogfeld zur Materialerstellung
* [Benutzeroberfläche] Materialerstellung von Schnellstart
* [Benutzeroberfläche] Arbeitsablauf zum Erstellen von Material mit Vorlagen
* [UI] Neues Format für überlagerte Aktionsleisten
* [UI] Benutzer benachrichtigen, wenn ein Material zusätzliche Verwendungen benötigt
* [UI] Vorschläge für neuen Materialnamen mit erhöhter Anzahl
* [UI] Benennen Sie &quot;Leeres Projekt erstellen&quot; in &quot;Schnellstart&quot; um.
* [UI] hat den Bereich &quot;Inhalt abrufen&quot; überarbeitet
* [UI] Suchimplementierung in der Ausgabe der Kanalliste
* [UI] Beim Speichern eines Snapshots in einer Datei eine Benachrichtigung anzeigen

**Fest:**

* [2D-Ansicht] Ordnen Sie die 2D-Ansicht gemäß dem Ergebnisverwendungsindex in der Spezifikation an
* [Anwendung] Beheben eines Absturzes beim Start
* [Anwendung] Fehlerhafte Logik für die Workflownutzungsfilterung mit OpenPBR beheben
* Die Liste der bekannten Versionen von [Application] wird jetzt bei der Suche nach einem Update gelesen.
* [Anwendung] Verhindern eines Absturzes beim gleichzeitigen Zugriff
* [Anwendung] Verhindern einer doppelten Berechnung beim Importieren von Bildern mit Basismaterial
* [Anwendung] Verhindern eines potenziellen Absturzes beim Beenden
* [Anwendung] Absturz verhindern, wenn eine Maske zweimal gelöscht wird
* [Anwendung] Verhindern Sie eine Verwendungskonvertierung, die den ursprünglichen Fall verliert.
* [Anwendung] Verhindern nutzloser Berechnungen unsichtbarer Ausgaben
* [Anwendung] Ersetzen von Leerzeichen durch Unterstriche beim Erstellen der Verwendungs-ID aus dem Namen
* [Anwendung] Verschiedene Aktualisierungskorrekturen
* [Captis] Gerät nach Aktualisierung der Sicherheitsrichtlinien nicht erkannt
* [Captis] FTP-Protokollfehler beheben
* [Captis] Zuschnitt korrigieren
* [Captis] Konzentrieren Sie sich vor der Farbkalibrierung auf einen technischen Bereich
* [Captis] Beibehalten des Zuschneideverhältnisses, wenn die Auflösung gesperrt ist
* [Captis] Sperren verhindern, wenn mehrmals auf &quot;Ergebnisse an Sampler senden&quot; geklickt wird
* [Captis] löst das Fenster &quot;Captis&quot; aus, wenn auf das Captis-Menü geklickt wird, und es wird minimiert
* [Captis] Tauschen Sie zwei Abschnitte in der Vorschau-Benutzeroberfläche aus
* [Captis] Die Metadaten des endgültigen Assets sind nicht festgelegt.
* [Captis] Verschiedene Fehlerbehebungen
* [Captis] Falsche Freistellungsgröße
* [Kanaleinstellungen] Maskenkanäle im Bedienfeld, wenn sie nicht sichtbar sind
* [Exportieren] Das Öffnen eines Ordners mit Sonderzeichen funktioniert ordnungsgemäß.
* [Export] Absturz beim Export verhindern, wenn die Struktur entladen wurde
* [Export] Ausgewählte Ausgaben sind im Exportdialogfeld nicht dauerhaft.
* [Filter] Das Exportieren eines Baums mit Bildern unterbricht die dynamische Bildauflösung
* [Filter] C++-Filterverfügbarkeit beheben
* [Filter] Erkennung des dynamischen Klonstempels beheben
* [Filter] Beheben Sie die UID-Zählerinitialisierung beim Ausfüllen dynamischer Verwendungen
* [Filter] Korrigieren des Farbraums im Assistenten für automatische Kachelung
* [Filter] Freistellungsausgabegrößen korrigieren
* [Filter] Aktualisieren des Filters mit angehefteten Parametern
* [Filter] Verhindern eines Absturzes auf macOS im Assistenten für automatische Kachelung
* [Filter] Verhindern Sie einen Absturz beim Hochskalieren, wenn eine Eingabe fehlt
* [Filter] Verhindern Sie einen Absturz beim Laden eines zusammengesetzten Filters ohne Dateinamen
* [Filter] Die Zielmaskenoptimierung wurde in PatchMatch dupliziert.
* [Bildimport] Automatische manuelle Messung für Physische Größe korrigieren
* [Bildimport] Die richtige SVG-Rastergröße, wenn sie als Tweak verwendet wird
* [Ebenen] Das Zuweisen einer Verwendung zu einem Bild durch Eingabe funktioniert nicht
* [Ebenen] Vermeiden Sie Abstürze beim Hinzufügen von Ebenen zum Stapel
* [Ebenen] Verfügbare Parameter, die nicht aktualisiert werden müssen, wurden entfernt.
* [Ebenen] Korrektur des Hinzufügens eines Texturgenerators als Map
* [Ebenen] Flachstellen korrigieren
* [Ebenen] Unterstapel in Eingabegröße reduzieren, nicht Dokumentgröße
* [Ebenen] Absturz beim Reduzieren eines Stapels mit reduzierten Ebenen verhindern
* [Ebenen] Verhindern, dass eine Rendering-Optimierungsmeldung mit Basismaterial angezeigt wird
* [Ebenen] Beim Aktualisieren eines Filters auf einen Unique-Output-Filter wurde die Benutzeroberfläche nicht ordnungsgemäß aktualisiert.
* [Voreinstellungen] Korrektur der Änderung der Voreinstellungen
* [Projekt] Import von .alch-Projekten korrigieren
* Das Speichern von [Projekt] schlägt nicht mehr ohne Meldung fehl.
* [Rendern] Vermeiden Sie einen Absturz bei macOS, indem Sie den Planungsmodus auf &quot;Automatisch&quot; setzen
* [Rendern] Das Ändern der V-Komponente der Texturkachelung hatte keine Auswirkungen
* [Rendern] Fehlendes Rendern und Miniaturansichten beheben
* [Rendern] Verhindern gleichzeitiger Zugriffe auf Ausgabewerte
* [Rendern] Verarbeiten Sie die Ausgabewerte einer Struktur im Renderer ordnungsgemäß.
* [Rendern] Beenden Sie die Neuerstellung der Baumstruktur bei jedem Rendern.
* [Skripterstellung] Beheben eines Absturzes in get_project_assets
* [Skripterstellung] Verhindern Sie Abstürze beim Reduzieren von der Python-API
* [UI] Alle Unterteilungen im Eigenschaftenfenster verfügen jetzt über die Fensterbreite.
* [UI] Vermeiden Sie es, interne Benutzer mit automatischer Kachelung als benutzerdefinierte anzuzeigen
* [UI] Fehlerhaftes Kontextmenü reparieren
* [UI] Kontextmenü für Generatoranpassungen reparieren
* [UI] Laden von Schriften korrigieren
* [UI] Schaltfläche &quot;Materialvorgabe&quot; mit langen Namen reparieren
* [UI] Mehrere Regler-Tweak-Bindungen reparieren
* [UI] Seltene Schaltflächen mit kleiner Größe im Dialogfeld reparieren
* [Benutzeroberfläche] Korrektur der Änderung des Tweak-Werts bei der Komponentenerstellung
* [UI] Fehlerbehebung für die Anzeige der Variableneingabe und Entfernen des falschen Phantombefehls
* [UI] Aktualisierung des Bedienfelds &quot;Anzeigeeinstellungen reparieren&quot;, wenn sich der Elementkontext ändert
* [UI] Korrektur des Wortumbruchmodus der einheitlichen Auswahl
* [UI] Das Hinzufügen von Sonderzeichen im Namensfeld von Metadaten ist verboten
* Die Anzeige des [UI]-Physische Größe-Measure-Tools ist fehlerhaft.
* [UI] Absturz beim Öffnen des Bedienfelds &quot;Kanaleinstellungen&quot; verhindern
* [UI] Absturz bei Verwendung von &quot;Auf Standardlayout zurücksetzen&quot; verhindern
* [UI] Verhindern, dass die Aktualisierungsbenachrichtigung im Strukturbereich nicht mehr angezeigt wird
* [UI] Priorisieren des dynamischen Filters bei der Suche nach Namen
* [UI] Scrollen Sie im Eigenschaftenfenster, um Änderungen zu verwenden
* [UI] Kanaleinstellungen beim Anpassen der Verwendung eines Bildes aktualisieren
* [UI] Aktualisieren der Formulierung im Popup-Fenster zur Materialmodell-Konvertierung

## Entfernt

* [UI] Menüelement &quot;3D-Erfassung entfernen&quot;
* [UI] Generatives AI-Bedienfeld entfernen
* [UI] Shader-Einstellungen entfernen
