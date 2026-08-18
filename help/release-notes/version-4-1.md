---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-1.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 4.1, um mehr über den Paint Warp-Filter, die Aktualisierung des Stickfilters und die Verbesserung der 3D-Erfassung zu erfahren.
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

<b>Substance 3D Sampler 4.1.0 </b> führt neue Inhalte mit dem <b>Paint Warp </b>-Filter und einer verbesserten Version des <b>Stickerei </b>-Filters ein. Dieses Update enthält einige Verbesserungen bei der 3D-Erfassung.

*Freigabedatum: 28. März 2023*

## Verformung malen

Mit dem Farbverkrümmungsfilter können Sie Materialien verkrümmen, indem Sie Kurven in der 2D-Ansicht zeichnen.\
Mit der Option &quot;Begradigen&quot; können Sie Materialien für einen einfachen, nahtlosen Arbeitsablauf beim Kacheln neu ausrichten.

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

* [Engine] Update-Substance Engine auf Version 9.0
* [Interoperabilität] 3D-Objekte an Stager und Painter senden

<b>Fest:</b>

* [3D-Erfassung] Anwendungen stürzen ab, wenn der 3D-Erfassung-Renderer fehlschlägt
* [3D-Erfassung] Absturz, wenn ein Bild nicht geladen werden kann
* [3D-Erfassung] Absturz beim Erreichen des Schritts &quot;Gitterrekonstruktion&quot;
* [3D-Erfassung] Absturz beim Ändern der Größe des Begrenzungsrahmens
* [3D-Erfassung] Beim Importieren von Masken gemäß der Konvention wird die Maske nicht ordnungsgemäß zugewiesen.
* [3D-Erfassung] Rendering-Störungen beim Anpassen des Begrenzungsrahmens
* [3D-Erfassung] Der Wechsel zwischen den Versions- und Umschalt-Rendering-Optionen während des 3D-Erfassung-Nachbearbeitungsprozesses ist langsam
* [3D-Erfassung] Das Umschalten zwischen Versionen während des 3D-Erfassung-Nachbearbeitungsschritts ist manchmal unterbrochen
* [Anwendung] Absturz beim Start
* [Anwendung] Absturz beim Duplizieren eines umbenannten Materials
* [Anwendung] Absturz beim Öffnen eines älteren .alch-Projekts ohne seinen Abhängigkeitsordner
* [Anwendung] Absturz beim Verbinden/Trennen eines Bildschirms, Computer geht in den Ruhemodus oder wird remote aufgerufen
* [Anwendung] Abstürze und Speicherlecks im Zusammenhang mit der Verwaltung nicht dauerhafter Assets
* [Exportieren] Die Auswahl des Materialformats für 3D-Objekt-Dateitypen, in die Texturen eingebettet oder referenziert werden, sollte deaktiviert sein.
* [Export] Absturz, wenn beim 3D-Objekt-Export etwas schief geht
* [Export] Absturz beim Exportieren einer .sbs/.sbsar-Datei
* [Export] Absturz beim Importieren einer benutzerdefinierten Vorgabe, die dieselbe Bezeichnung, aber nicht denselben Dateinamen aufweist
* [Export] Das Exportieren einer Umgebungsbeleuchtung in eine .sbs/.sbsar-Datei funktioniert manchmal nicht
* [Exportieren] Der GLTF/GLB-Export kodiert Texturen in base64.
* [Export] Das Namenstextfeld funktioniert beim erneuten Fokussieren nicht
* [Export] Kachelung beibehalten funktioniert nicht, wenn eine Bild-zu-Material-Ebene (AI-gestützt) in eine .sbs/.sbsar-Datei exportiert wird
* [Exportieren] Beim Exportieren von GTF und Ersetzen von Dateien ist die Liste der zu ersetzenden Dateien nicht korrekt
* [Verfügbare Parameter] Zufälliger Seed funktioniert nicht in exportierten .sbs/.sbsar-Dateien
* [Ebenen] Inhaltsbasierte Füllung stürzt manchmal ab, wenn sie zum zweiten Mal hinzugefügt wird
* [Ebenen] Absturz beim Berechnen eines Ebenenstapels
* [Ebenen] Disk-Cache für Bild zu Material (AI) funktioniert nicht
* [Ebenen] Möglicher Absturz beim Anpassen einer Ebene
* [Leistung] Speicherlecks
* [Projekt] Absturz beim Speichern eines Projekts
* [Projekt] Beim zweimaligen Importieren desselben Projekts in einer Zeile werden die Elemente dupliziert.
* [UI] Abgerundete Schaltflächen mit nur einem Symbol werden nicht korrekt gerendert

### 4.1.0 Cannoli

*(Freigegeben: 28. März 2023)*

<b>Hinzugefügt:</b>

* [Inhalt] Neuer Stickereifilter
* [Inhalt] Neuer Farbverkrümmungsfilter
* [UI] Option &quot;Export hinzufügen&quot; im Menü &quot;Datei&quot;
* [3D-Erfassung] Schaltfläche &quot;Zurück&quot; ist jetzt für den Ausrichtungsschritt verfügbar.
* [3D-Erfassung] Bilder behandeln JPEG EXIF-Ausrichtung
* [3D-Erfassung] Skripterstellung - Neue Dataset\_info.camera-Eigenschaft
* [3D-Erfassung] Linux-Unterstützung hinzufügen (siehe Dokumentation)
* [3D-Erfassung] Überprüfen Sie den Lesezugriff der importierten Bilder.
* [Onboarding] Training - 2 neue Tutorials (Sticken und Malen verformen)
* [Onboarding] Aktualisierter Inhalt

<b>Fest:</b>

* [3D-Erfassung] Kameraposition beim Ändern der Version beibehalten
* [3D-Erfassung] Zusammenführen aller Gruppen eines Objekts in einer
* [3D-Erfassung] Generierte Gitter wurden in Original umbenannt.
* [Anwendung] Absturz beim Generieren der Miniaturansicht eines nicht vorhandenen Bildes
* [Elemente] Papierkorbsymbol hat im Bedienfeld &quot;Elemente&quot; keine Wirkung
* [Inhalt] Das Aktualisieren von Filtern mit Materialsteckplätzen funktioniert nicht wie erwartet
* [Export] Möglicher Absturz beim Exportieren eines Assets mit bestimmten Filtern
* [Export] SBS/SBSAR-Export - Bildimportebenen hatten Priorität vor Bildparametern
* [Export] UE4-Exportvoreinstellung funktioniert nicht mit PNG
* [Ebenen] Absturz beim gleichzeitigen Ablegen eines Materials und eines Filters aus dem Betriebssystem-Explorer
* [Ebenen] Absturz beim Ziehen einer SBSAR-Datei mit einer Bilddatei
* [Ebenen] Der Kanal für die Deckkraft der Stickerei kann vollständig weiß sein.
* [Lokalisierung] Chinesisch wird unter Linux möglicherweise standardmäßig angezeigt
* [Leistung] Beim Entfernen einer Ebene aus einem Asset wurde ein Speicherproblem behoben.
* [Projekt] Möglicher Absturz beim Speichern
* [UI] Hinzufügen fehlender Abstände auf der Menüschaltfläche &quot;Version&quot;
* [UI] Schaltfläche &quot;Abbrechen&quot; wird nicht richtig angezeigt
* [UI] Deaktivieren der Schieberegleranimation für 3D-Erfassung-Nachbearbeitungsparameter
* [UI] Das Fenster &quot;Materialerstellungsvorlage&quot; schließt sich nicht, wenn Sie auf eine Stelle außerhalb des Fensters klicken
* [UI] Der Schnellzugriff auf Filter schließt sich, wenn Sie außerhalb klicken

<b>Bekannte Probleme:</b>

* [Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht
* [Inhalt] Shape Light-Widget funktioniert nicht im sphärische Projektion-Modus
* [Interoperabilität] Material mit Versatz, der an Stager gesendet wird, verliert die Versatz-Steuerelemente.
