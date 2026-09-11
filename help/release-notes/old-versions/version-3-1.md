---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-1.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 3.1, um mehr über Farbwähler, SVG-Unterstützung und Verbesserungen der Interoperabilität zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 3.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '791'
ht-degree: 0%

---


# Version 3.1

Adobe Substance 3D Sampler 3.1 bietet einen neuen Farbwähler, Unterstützung für SVG-Dateien und verbesserte Interoperabilität mit Stager, Photoshop und Illustrator.

Freigabedatum: *28. September 2021*

## Wichtigste Funktionen

### Farbwähler

Diese Version fügt einen neuen [Farbwähler](../../interface/tools-and-widgets/color-picker.md) hinzu, der eine Pipette und Unterstützung für Farbfelder enthält.

Der Farbwähler wird immer angezeigt, wenn Sie eine Farbe auswählen müssen. Sie kann an eine beliebige Stelle auf Ihrem Bildschirm verschoben werden.

![](../../assets/color-picker-raw.png){width="250px"}

### SVG-Unterstützung

Sampler unterstützt jetzt SVG. Sie können sie in Ihre Assets importieren, direkt in den Ebenenstapel oder als Bildeingabe einer Ebene.

![](../../assets/svg-support.jpg){width="500px"}

### In Illustrator bearbeiten

Eine neue Funktion zum Bearbeiten in bietet große Flexibilität bei der Aktualisierung importierter Bilder. Wenn Sie Ihre SVG-Datei optimieren möchten, können Sie sie einfach direkt in Illustrator bearbeiten. Sampler aktualisiert Ihre Grafik sofort mit der neuen SVG.

### Neues UX/UI-Zuschneiden

Sampler erhält jetzt ein richtiges und überarbeitetes Widget für das Zuschneiden, um den zugeschnittenen Bereich einfach zu definieren. Auch beim Zuschneiden von nicht quadratischen Bildern in quadratische Texturen werden keine gedehnt Ergebnisse erzielt.

![](../../assets/crop-9.jpg){width="500px"}

### Normalen-Format

Bearbeiten Sie Ihre Voreinstellungen, um das [normale Format](../../interface/preferences/normal-format.md) festzulegen, das Sie für Ihren Arbeitsablauf benötigen. Ihre Normalwerte werden in dem Format importiert, angezeigt und exportiert, das Sie in den Voreinstellungen ausgewählt haben.

![](../../assets/7-normal-format-preferences.jpg){width="250px"}

### Exportieren von Material-Eigenschaften in SBSAR

Alle Material-Parameter der Shader-Einstellungen (Normalskala, Height-Skala, Height-Level,...) werden in die Sbsar-Dateien exportiert, die in Substance 3D Stager gelesen werden sollen, damit das Material perfekt übereinstimmt.

![](../../assets/material-consistency-sa-sg.jpg){width="500px"}

## Versionshinweise

### 3.1.0 Xocoalt

*(veröffentlicht am 28. September 2021)*

**Hinzugefügt:**

* [Farbwähler] Neue Farbwähler-Benutzeroberfläche
* [Farbwähler] Aktuelle und vorherige Farben nebeneinander in der Vorschau anzeigen
* [Farbwähler] Geben Sie die Farbe im Hexadezimalformat ein.
* [Farbwähler] Neue Pipette mit Farbvorschau
* [Farbwähler] Die Pipette kann eine Farbe außerhalb von Sampler auswählen
* [Farbwähler] Passen Sie Ihre Farbe in RGB- oder HSV-Farbräumen an
* [Farbwähler] Farbfelder speichern und verwalten
* [Interoperabilität] Bearbeiten von Bildern in Illustrator aus der Bildimportebene oder den Bildparametern
* [Interoperabilität] Bearbeiten von Bildern in Photoshop aus der Bildimportebene oder den Bildparametern
* [Widget] Neues Freistellungs-Widget
* [Widget] Drücken Sie die Eingabetaste, um die Freistellung zu bestätigen.
* [Widget] Das Freistellungs-Widget liest die Bildgröße, um sie an das Widget anzupassen, und behält das Verhältnis bei der Größenänderung bei
* [UI] Neue stufenlose Schieberegler-Benutzeroberfläche
* [Anwendung] Hinzufügen einer normalen Formatauswahl in den Voreinstellungen
* [Anwendung] Das normale Format in Bildimportebenen entspricht dem in den Voreinstellungen festgelegten normalen Standardformat
* [Anwendung] In den 2D-Ansichten wird das Normalformat entsprechend dem in den Voreinstellungen festgelegten Normalformat angezeigt.
* [Anwendung] Die Normale wird in das in den Voreinstellungen festgelegte normale Format exportiert
* [Exportieren] Hinzufügen eines Normalformatparameters zum Exportieren von SBS und Sbsar-Dateien
* [Exportieren] Hinzufügen von Shader-Einstellungen zu SBS- und Sbsar-Datei-Exporten
* [Exportieren] Festlegen der Standardauflösung für exportierte SBS Graf
* [Compound Filters] SSA-Filter mit 7z verpacken
* [Zusammengesetzte Filter] Kategoriemetadaten in zusammengesetzten Filtern hinzufügen
* [Zusammengesetzte Filter] Zusammengesetzte Filter können eine eingebettete Miniaturansicht haben
* [Zusammengesetzte Filter] Dem Dialogfeld &quot;Inhalt abrufen&quot; wurde die Erweiterung &quot;Zusammengesetzte Filter&quot; (.ssafilter) hinzugefügt.
* [Zusammengesetzte Filter] Importieren zusammengesetzter Filter (.ssafilter) im Bedienfeld &quot;Elemente&quot;
* [Engine] Aktualisieren des Substance-Engine auf Version 8.2.0

**Fest:**

* [Anwendung] Verbundene lokale Ordner können hängen bleiben
* [Anwendung] Absturz beim Beenden
* [Anwendung] Absturz beim Starten von zwei Instanzen von Sampler
* [Inhalt] Zuschneidefilter hat eine zufällige Starteinstellung
* [Inhalt] Einige Substance-Material werden manchmal nicht aktualisiert
* [Exportieren] Absturz beim Exportieren mit einer neu hinzugefügten benutzerdefinierten Vorgabe
* [Export] Geschätzte Größe des Pakets fehlt im Export-Popup
* [Exportieren] Beheben von Speicherlecks beim Exportieren von SBS- und SBSAR-Dateien
* [Zusammengesetzte Filter] Zusammengesetzte Filter können doppelte Eingaben aufweisen.
* [Zusammengesetzte Filter] Absturz, wenn ein Filter nicht erfüllte Referenzen enthält
* [Verbundfilter] Absturz beim Neuanordnen eines Ebenenstapels mit einem Verbundfilter
* [Verbundfilter] Das Rendering hängt manchmal
* [Bildimport] Das Importieren eines Bildes löst mehrere Renderings aus
* Absturz [Ebenen] bei Rückgängigmachen/Wiederholen
* Absturz [Ebenen] beim Hinzufügen eines Basismaterials
* Absturz [Ebenen] bei Verwendung eines ungültigen Bildes als Umgebungslicht
* [Ebenen] Fixieren des doppelten Imports beim Einfügen eines Filters mit mehreren Grafen
* [Ebenen] Das Neuanordnen von Ebenen funktioniert nicht immer
* [Project] Absturz beim Laden einer unvollständigen Projektdatei
* Absturz beim Öffnen eines beschädigten Projekts.
* [Projekt] Einige Elemente können aus einem Projekt verschwinden
* [Eigenschaften] Korrektur fehlender Filtervorgaben
* [UI] Winkelparameter können nicht festgelegt werden.
* [UI] Filter Metadaten werden im Bedienfeld &quot;Elemente&quot; angezeigt
* [UI] Gruppierung nach Kategorie blendet Filter aus
* [UI] Bildlaufproblem im Bedienfeld &quot;Elemente&quot;
* [UI] Das Exportbedienfeld verfügt jetzt über eine Bildlaufleiste.
* [UI] Die Miniaturansicht wird für einige Bildformate in der Bildauswahl nicht angezeigt

**Bekannte Probleme:**

* [Echtzeit-Engine 2021] Starke Berechnung kann Absturz in der Anwendung verursachen
* [Echtzeit-Engine 2021] Echtzeit-Engine 2021 wird auf einem Windows-Computer mit installierter AMD-CPU und Nvidia-GPU Absturz
* [Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
