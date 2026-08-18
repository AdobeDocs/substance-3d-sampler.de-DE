---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-5-0-substance-3d-sampler.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 5.0, um mehr über die neuen Digitalisierungstools, -funktionen und Workflow-Verbesserungen zu erfahren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 5.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '647'
ht-degree: 0%

---


# Version 5.0

![](../assets/welcome_digitization_tool.jpg)

Mit <b>Substance 3D Sampler 5.0</b> werden Möglichkeiten für den Einstieg in materielle digitale Zwillinge mit Scans und Renderings höherer Qualität eingeführt.

Die wichtigsten neuen Funktionen sind:

## Schnellaktionen

Starten Sie alle Haupt-Workflows von Sampler mit einem Klick und machen Sie den Ebenenstapel für Sie bereit!

Weitere Informationen *[hier](../interface/panels/quick-actions-panel.md)*.

![](../assets/quick_actions_1440x810.png)

## Neues Startbildschirm-Layout

Über die Startseite finden Sie alle Projekte und Tutorials, an denen Sie Ihre Arbeit beginnen können.

Weitere Informationen *[hier](../interface/the-home-screen.md)*.

![](../assets/new_home_screen_layout_1440x810.png)

## Neuer Renderer

Optimiert die visuelle Konsistenz eurer Bilder mit Echtzeit- oder Pfad-Tracking und unterstützt neue Materialeigenschaften. Speichern Sie Schnappschüsse Ihrer Arbeit direkt aus der 3D-Ansicht.

Weitere Informationen *[hier](../interface/2d-and-3d-viewport.md)*.

![](../assets/eclair_support_1440x810.png)

## HP Z Captis-Integration

Mit HP Z Captis und Substance 3D Sampler lassen sich realistische Materialien in wenigen Minuten digitalisieren.

Funktion für Unternehmens-, Teams- und Bildungseinrichtungskonten verfügbar.

Weitere Informationen *[hier](../pipeline-and-integrations/hp-z-captis-support/hp-z-captis-support.md)*.

![](../assets/hp_z_captis_1440x810.png)

## Versionshinweise zu Version 5.0

*(Freigegeben: 20. Februar 2025)*

<b>Hinzugefügt</b>:



* [Onboarding] Neue Homepage mit schnellem Zugriff auf Lerninhalte, Beispielprojekte, Schnellaktionen und aktuelle Projekte.
* [Onboarding] Schneller Einstieg mit den neuen Schnellaktionen, die über die Startseite und das spezielle Bedienfeld zugänglich sind
* [Onboarding] [Inhalt] Schnellaktionen sind vordefinierte Workflows, die den Ebenenstapel mit den meisten verwendeten Ebenen füllen
* [Onboarding] Möglichkeit, ein neues Projekt über ein neues Schnellstartmenü, über Schnellaktionen oder über ein benutzerdefiniertes Projekt zu erstellen
* [Onboarding] Möglichkeit, leeres Projekt direkt von der Startseite über eine dedizierte Schaltfläche zu erstellen
* [3D-Ansicht] Neuer erweiterter Raster- und Pathtracer mit neuen Rendering-Funktionen (Eigenschaften wie Überziehen, Schein, Lichtdurchlässigkeit, Volumenstreuung) und visueller Konsistenz im Substance-Ökosystem
* [3D-Ansicht] Anzeigeeinstellungen sind jetzt direkt in der 3D-Ansicht verfügbar.
* [3D-Ansicht] Möglichkeit zum Speichern eines Renderschnappschusses in der Zwischenablage oder in Dateien
* [3D-Ansicht] Zeigt ein Raster an, um den Ursprung der Szene zu visualisieren
* [3D-Ansicht] Aktivieren Sie die Grundebene, um Schatten und Reflexionen zu fangen.
* [3D-Ansicht] Steuern Sie, wie reflektierend und undurchsichtig Ihre Grundebene ist
* [3D-Erfassung] Positionierung der Masche auf dem Boden
* [Anwendung] Überprüfen der Hardwarekompatibilität beim Starten der Anwendung
* [Anwendung] Das Fenster für Absturzberichte wird jetzt direkt nach einem Absturz geöffnet
* [Inhalt] Öffnen Sie ein Beispielprojekt, um einfach zu beginnen.
* [Exportieren] Exportieren von Adobe Standard Material Shader in USD-Dateien
* [Generative AI] Tag &quot;Nicht ableiten&quot; aktivieren, wenn Bild als Eingabe in Workflows von Bild zu Textur verwendet wird
* [Projekt] Miniaturansichten werden in der Projektdatei gespeichert, um Projekte schneller zu öffnen
* [Project] Einstellung in den Voreinstellungen zum Speichern von Cache-Daten innerhalb der Projektdatei mit verschiedenen Modi (kein Cache, heller Cache, voller Cache)
* [Skripterstellung] [Breaking change] Qt-Migration zu Qt6.15 - Auswirkungen auf die Kompatibilität vorhandener Plug-ins
* [Scripting] Standard-Plug-ins und Skriptordner befinden sich jetzt im Ordner Dokumente
* [Scripting] Neue Benutzeroberfläche für Plug-ins für visuelle Konsistenz mit den wichtigsten Sampler-Bedienfeldern
* [Scripting] Zugriff auf 2 Plug-in-Beispiele zum Erkennen der Funktionen von Sampler Plug-ins
* [Scripting] Neue open\_3d\_capture()-Funktion
* [Scripting] Beim Einfügen einer Ebene können Sie steuern, ob sie über oder unter der Zielposition eingefügt wird.

<b>Fest:</b>

* [3D-Erfassung] Absturz, wenn die Objekterfassung auf macOS nicht gestartet werden kann
* [Anwendung] Absturz beim Beenden
* [Anwendung] Hängenbleiben beim Hinzufügen von Elementen zum Projektfenster
* [Anwendung] Das Umbenennen eines Projekt-Assets funktioniert nur, wenn Sie die Eingabetaste drücken
* [Anwendung] Menüeinträge &quot;Rückgängig&quot; und &quot;Wiederholen&quot; sind nicht deaktiviert, wenn sie
* [Assets] Assets können nicht aus dem Bereich Alle Bibliotheken des Bedienfelds &quot;Assets&quot; gelöscht werden
* [Inhalt] Atlasersteller - Vorhandene Deckkraftmap verwenden, sofern vorhanden
* [Inhalt] Farb-ID-Überblendung - Korrigieren der Farbauswahl in der Grundfarbe
* [Ebenen] Vermeiden Sie nutzlose Berechnungen bei der Verwendung von Generatoren
* [Ebenen] Das Verändern eines Generators kann dazu führen, dass zu viele Berechnungen ausgelöst werden.
* [Leistung] Verbessern der GPU-Speicherverwaltung
* [Leistung] Der Render-Cache darf beim Neustart der Anwendung nicht verwendet werden.
* [Ressourcen] Schreibgeschützte Dateien werden im Bedienfeld &quot;Elemente&quot; nicht angezeigt
* [Scripting] Wiederverwendung einer Ebene nach dem Hinzufügen einer anderen Ebene zulassen
* [Skripterstellung] Das mehrmalige Ändern der Ebenenstapelstruktur in einem Skript kann fehlschlagen

<b>Entfernt:</b>

* [Anwendung] Unterstützung für .dng- und .nef-Bilddateien entfernen
