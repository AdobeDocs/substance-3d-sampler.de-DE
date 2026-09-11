---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/release-notes/old-versions/version-0-8-0.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler Version 0.8.0, um mehr über neue Funktionen, Updates und Verbesserungen zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.8.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 0.8.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---


# Version 0.8.0

**Hinzugefügt:**

* [Ressourcen] Verknüpfen und spiegeln Sie die Material-Ordner auf Ihren lokale Festplatten
* [Ressourcen] Durchsuchen Sie die Materialien-Ordner und deren Unterordner
* [Ressourcen] Lösen Sie das Bedienfeld &quot;Materialressourcen&quot; in einem separaten Fenster, um Ihre Ressourcen im Vollbildmodus anzuzeigen.
* [Ressourcen] Neues Layout des Bedienfelds &quot;Ressourcen&quot; zur Unterstützung der Navigation von Ordnern und Unterordnern
* [Ressourcen] Verwenden Sie das Breadcrum, um durch Ihre Ordner zu navigieren
* [Ressourcen] Erzwingen der Synchronisierung Ihres lokalen Ordners mit der Option Synchronisieren, die per Rechtsklick zugänglich ist
* [Ressourcen] Trennen Sie den lokalen Ordner mit der Option &quot;Trennen&quot;, die per Rechtsklick zugänglich ist
* [Verwalten] Eingebettete Tags von Substance-Dateien anzeigen
* [Verwalten] Hinzufügen, Bearbeiten und Löschen von Tags Ihrer Material
* [Verwalten] Materials bewerten
* [Ebenen] Unterstützung der Panorama-Ausgabe
* [Ebenen] Sie können Bildeingaben in der Bildimportebene löschen
* [Ebenen] Automatische Auswahl der neuen hinzugefügten Ebene
* [Ebenen] Automatische Auswahl der Ebene darunter nach dem Löschen einer Ebene
* [UX] Sichtbarkeit linker Fenster beim Wechsel zu einem anderen Labor beibehalten
* [UX] Erstellen Sie keine Basisebene, oder öffnen Sie das Popup Bildarbeitsablauf, wenn Sie Materialien in einen Stapel mit nicht leeren Ebenen importieren.
* [UI] Neues Textfeldformat
* [UI] Neues Suchfeld-Format
* [UI] Neuer Kopfzeilenstil für Bedienfelder
* [UI] Neuer Anzeigestil &quot;Gebucht&quot;
* [UI] Neues Hintergrundformat für Ebenen-Stapel
* [UI] Adobe Clean-Schriftart verwenden
* [UI] Pipetten-Symbol-Platzhalter für Farb-Eingabeparameter entfernen
* [Leistung] Optimierung der Belegungsanzeige
* [Inhalt] Neuer Mustergenerator-Filter
* [Inhalt] Neuer Weichzeichnungsfilter

**Fest:**

* [Inspiration] Beheben Sie den Absturz, wenn mehr als 10 Farben verwendet werden
* [2D-Ansicht] Fixieren der Bildlaufleiste in der Kanalliste der 2D-Ansicht
* [Viewer] Beheben Sie den Absturz beim Importieren einer Nicht-Power-Umgebungs-Map von 2
* [Inhalt] PNG-Import für benutzerdefiniertes Muster von Präge- und Perforationsfiltern korrigieren
* [Exportieren] Normal- und Height-Export mit 16 Bit pro Kanal.
* Reparieren einer Endlosschleife beim Importieren eines Materials mit zwei Vorgaben mit demselben Namen
* Korrektur der langen Dateipfadanzeige in der Basismaterial-Ebene

**Bekannte Probleme:**

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen.
* Delighter-Absturz mit älteren NVIDIA-Treibern (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann Absturz auf MacOS enthalten
* Kann beim Beenden von MacOS zufällig Absturz verursachen
