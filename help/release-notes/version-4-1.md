---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-1.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 4.1, um mehr über die Malen-Verkrümmungsfilter, Stickereifilter-Updates und Verbesserungen der 3D-Erfassung zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 4.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 4.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '812'
ht-degree: 0%

---


# Version 4.1

<b>Substance 3D Sampler 4.1.0 </b> führt neue Inhalte mit dem <b>Malen-Warp </b>filter und einer verbesserten Version des <b>Stickerei </b>filters ein. Dieses Update enthält einige Verbesserungen bei der 3D-Erfassung.

*Freigabedatum: 28. März 2023*

## Verformung malen

Mit dem Malen-Verkrümmungsfilter können Sie Materialien verkrümmen, indem Sie Kurven auf der 2D-Ansicht zeichnen.\
Mit der Option &quot;Begradigen&quot; können Sie Materialien neu ausrichten und so einen reibungslosen Arbeitsablauf bei der Kachelung ermöglichen.

## Stickerei

Mit dem neuen Stickereigenerator können Sie Stickereien aus einer einzelnen Bildvektordatei oder einer Zeichnung erstellen.\
Es kann bis zu 6 Farben sticken und kombiniert mehrere Hefttechniken.

## Tutorials

## Versionshinweise

<b>4.1.2 CANNOLI</b>

*(Freigegeben: 20. Juni 2023)*

<b>Fest:</b>

* [Ebenen] Speicherleck beim Anpassen von Substance-Materialien und Filtern, was zu Abstürzen führt

<b>4.1.1 CANNOLI</b>

*(Freigegeben: 6. Juni 2023)*

<b>Hinzugefügt</b>:

* [Engine] Substance Engine auf Version 9.0 aktualisieren
* [Interoperabilität] 3D-Objekte an Stager und Painter senden

<b>Fest:</b>

* [3D-Erfassung] Anwendungs-Absturz, wenn 3D-Erfassung-Renderer fehlschlägt
* [3D-Erfassung] Absturz, wenn ein Bild nicht geladen werden kann
* [3D-Erfassung] Absturz beim Erreichen des Mesh-Rekonstruktionsschritts
* [3D-Erfassung] Absturz beim Ändern der Größe des Begrenzungsrahmens
* [3D-Erfassung] Beim Importieren von Masken gemäß der Konvention wird die Maske nicht ordnungsgemäß zugewiesen.
* [3D-Erfassung] Rendering-Störungen beim Anpassen des Begrenzungsrahmens
* [3D-Erfassung] Der Wechsel zwischen den Versions- und Umschalt-Rendering-Optionen während des 3D-Erfassung-Nachbearbeitungsprozesses ist langsam
* [3D-Erfassung] Das Umschalten zwischen Versionen während des 3D-Erfassung-Nachbearbeitungsschritts ist manchmal unterbrochen
* [Anwendung] Absturz beim Start
* [Anwendung] Absturz beim Duplizieren eines umbenannten Materials
* [Application] Absturz beim Öffnen eines älteren .alch-Projekts ohne seinen Abhängigkeitsordner
* [Anwendung] Absturz beim Anschließen/Abziehen eines Bildschirms, Ruhemodus des Computers oder Fernzugriff
* [Anwendung] Absturz und Speicherlecks im Zusammenhang mit der Verwaltung nicht persistenter Assets
* [Exportieren] Die Auswahl des Material-Formats für 3D-Objekt-Dateitypen, in die Texturen eingebettet oder referenziert werden, sollte deaktiviert sein.
* [Exportieren] Absturz, wenn beim Exportieren von 3D-Objekten ein Fehler auftritt
* [Export] Absturz beim Exportieren einer .sbs/.sbsar-Datei
* [Exportieren] Absturz beim Importieren einer benutzerdefinierten Vorgabe, die dieselbe Bezeichnung, aber nicht denselben Dateinamen aufweist
* [Exportieren] Das Exportieren eines Umgebungslichts in eine .sbs/.sbsar-Datei funktioniert manchmal nicht
* [Exportieren] Gltf/Glb-Export codiert Texturen in base64
* [Export] Das Namenstextfeld funktioniert beim erneuten Fokussieren nicht
* [Exportieren] Kachelung beibehalten funktioniert nicht, wenn eine Image-to-Material-Ebene (AI-gestützt) in eine .sbs/.sbsar-Datei exportiert wird
* [Exportieren] Beim Exportieren von GTF und Ersetzen von Dateien ist die Liste der zu ersetzenden Dateien nicht korrekt
* [Freigelegte Parameter] Zufälliger Seed funktioniert nicht in exportierten .sbs/.sbsar-Dateien
* [Ebenen] Beim zweiten Hinzufügen von Abstürzen kommt es manchmal zu inhaltsbasierten Füllungen
* [Ebenen] Absturz beim Berechnen eines Ebenenstapels
* [Ebenen] Disk-Cache für Image-zu-Material (AI) funktioniert nicht
* [Ebenen] Mögliche Absturz beim Anpassen einer Ebene
* [Leistung] Speicherlecks
* [Projekt] Absturz beim Speichern eines Projekts
* [Projekt] Beim zweimaligen Importieren desselben Projekts in einer Zeile werden die Elemente dupliziert.
* [UI] Abgerundete Schaltflächen mit nur einem Symbol werden nicht korrekt gerendert

### 4.1.0 Cannoli

*(Freigegeben: 28. März 2023)*

<b>Hinzugefügt:</b>

* [Inhalt] Neuer Stickereifilter
* [Inhalt] Neuer Malen-Verkrümmungsfilter
* [UI] Option &quot;Export hinzufügen&quot; im Menü &quot;Datei&quot;
* [3D-Erfassung] Schaltfläche &quot;Zurück&quot; ist jetzt für den Ausrichtungsschritt verfügbar.
* [3D-Erfassung] Bilder behandeln JPEG EXIF-Ausrichtung
* [3D-Erfassung] Skripterstellung - Neues Dataset\_info.Kamera-Eigenschaft
* [3D-Erfassung] Linux-Unterstützung hinzufügen (siehe Dokumentation)
* [3D-Erfassung] Überprüfen Sie den Lesezugriff der importierten Bilder.
* [Onboarding] Training - 2 neue Tutorials (Stickerei und Malen-Verkrümmung)
* [Onboarding] Aktualisierter Inhalt

<b>Fest:</b>

* [3D-Erfassung] Beibehalten der Versionsposition beim Ändern der Kamera
* [3D-Erfassung] Zusammenführen aller Gruppen eines Objekts in einer
* [3D-Erfassung] Generierte Gitter wurden in Original umbenannt.
* [Anwendung] Absturz beim Generieren der Miniaturansicht eines nicht vorhandenen Bildes
* [Elemente] Papierkorbsymbol hat im Bedienfeld &quot;Elemente&quot; keine Wirkung
* [Inhalt] Das Aktualisieren von Filtern mit Material-Steckplätzen funktioniert nicht wie erwartet
* [Exportieren] Möglicher Absturz beim Exportieren eines Assets mit bestimmten Filtern
* [Exportieren] SBS/SBSAR-Export - Bildimportebenen hatten Priorität vor Bildparametern
* [Export] UE4-Exportvoreinstellung funktioniert nicht mit PNG
* [Ebenen] Absturz beim gleichzeitigen Ablegen eines Materials und eines Filters aus dem Explorer des Betriebssystems
* Absturz [Ebenen] beim Ziehen von Sbsar-Dateien mit einer Bilddatei
* [Ebenen] Der Kanal für die Deckkraft der Stickerei kann vollständig weiß sein.
* [Lokalisierung] Chinesisch wird unter Linux möglicherweise standardmäßig angezeigt
* [Leistung] Beim Entfernen einer Ebene aus einem Asset wurde ein Speicherproblem behoben.
* [Project] Möglicher Absturz beim Speichern
* [UI] Fehlenden Abstand auf der Menüschaltfläche &quot;Version&quot; hinzufügen
* [UI] Schaltfläche &quot;Abbrechen&quot; wird nicht richtig angezeigt
* [UI] Deaktivieren der Schieberegleranimation für 3D-Erfassung-Nachbearbeitungsparameter
* [UI] Das Fenster Material Creation Template schließt sich nicht, wenn Sie auf eine Stelle außerhalb des Fensters klicken
* [UI] Der Schnellzugriff auf Filter schließt sich, wenn Sie außerhalb klicken

<b>Bekannte Probleme:</b>

* [Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* [Inhalt] Shape Light-Widget funktioniert nicht im sphärische Projektion-Modus
* [Interoperabilität] Material mit Versatz, der an Stager gesendet wird, verliert die Versatz-Steuerelemente.
