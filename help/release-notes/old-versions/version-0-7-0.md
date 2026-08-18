---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-0-7-0.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 0.7.0, um mehr über Updates, Verbesserungen und Fehlerbehebungen zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.7.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 0.7.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Version 0.7.0

Freigabedatum: **2019/06/13**

Hinzugefügt:

* [Filter] Durch Drücken der Leertaste können Sie schnell auf Ihre Filter zugreifen
* [Filter] Neues spezielles Bedienfeld zum Verwalten, Durchsuchen und Importieren Ihrer Filter
* [Metadaten] Klicken Sie mit der rechten Maustaste auf ein Material, um die Metadaten anzuzeigen.
* [Metadaten] Klicken Sie mit der rechten Maustaste auf ein Material, um seinen Speicherort auf Ihrer Festplatte anzuzeigen.
* [Regler] Animieren Sie die Regler, wenn Sie mit der Maus darauf zeigen, indem Sie Strg drücken
* [Schieberegler] Halten Sie die Animation der Schieberegler an und starten Sie sie neu, indem Sie P drücken.
* [Exportieren] SBSAR-Export folgt den Richtlinien für die Substance Source
* [Lizenz] Aktivieren von Substance Alchemist mit einer Umgebungsvariablen
* [UX] Dateidialog merkt sich den zuletzt gewählten Dateipfad
* [UX] Dialogfeld &quot;Ordner&quot; speichert den zuletzt ausgewählten Ordnerpfad
* [UI] Benutzeroberfläche des Bedienfelds &quot;Ressourcen aktualisieren&quot;
* [UI] Benutzeroberfläche für die Suchleiste aktualisieren
* [UI] Symbol &quot;Neues Material erstellen&quot; wurde aktualisiert
* [Help] URLs werden auf die Domäne [substance3d.com](http://substance3d.com) aktualisiert.
* [Mesh] Ein Tuchgeflecht ist jetzt verfügbar.
* [Inhalt] Neuer Korrosionsfilter
* [Inhalt] Neuer Oxydationsfilter
* [Inhalt] Neuer Moosfilter
* [Inhalt] Neuer Dust-Filter
* [Inhalt] Neuer Brickwall-Musterfilter
* [Inhalt] Neuer Steinmauer-Musterfilter
* [Inhalt] New Wood Finish Filter
* [Inhalt] Neuer Metall-Finish-Filter
* [Inhalt] Neuer Snow-Filter
* [Inhalt] Neuer Randomizer-Filter
* [Inhalt] Sie können Ihre Texturen jetzt direkt in den Basismaterial-Filter importieren

Fest:

* Absturz beim Speichern des Ebenenstapels beheben
* Es ist möglich, einen Wert über 1 im Umgebungsdrehungsregler hinzuzufügen.
* Verlieren Sie die Überblendungsparameter nicht, wenn eine Überblendungsebene von der Überblendungsebene in die Materialebene hin- und hertransformiert wird
* Duplikate beheben, wenn Variationen desselben Ebenenstapels mehrmals generiert werden
* Beim erneuten Öffnen eines Materials merkt sich Alchemist die geänderten Bereiche (min und max) Ihrer Schieberegler

Bekannte Probleme:

* Die Verwendung mehrerer Delighter in einem Material wird nicht empfohlen
* Delighter stürzt mit älteren NVIDIA-Treibern ab (weniger als 400.x)
* Schnelle Sichtbarkeit einer Delighter-Phase wird nicht empfohlen.
* Import von benutzerdefinierten Umgebungen kann schwarz werden
* TIF-Bilder werden im Bedienfeld &quot;Eigenschaften&quot; der Bildimportebene nicht angezeigt
* Koma oder Punkt können ignoriert werden, wenn Sie einen bestimmten Wert in einen Schieberegler eingeben
* Filter &quot;Normal zu Height&quot; kann auf MacOS abstürzen
