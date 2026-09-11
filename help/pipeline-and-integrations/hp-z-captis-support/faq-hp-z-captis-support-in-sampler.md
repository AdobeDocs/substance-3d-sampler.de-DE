---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/faq-hp-z-captis-support-in-sampler.html"
breadcrumb-title: ''
description: Greifen Sie auf häufig gestellte Fragen zur Unterstützung von HP Z Captis in Substance 3D Sampler zu, um Antworten zur Hardwareintegration und -nutzung zu erhalten.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Häufig gestellte Fragen zur Unterstützung von HP Z Captis in Sampler
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1547'
ht-degree: 0%

---


# Häufigste Fragen

## Material-Samples

+++Welche Nutzungsszenarien werden von Captis abgedeckt?
Die Lösung deckt branchenübergreifende Nutzungsszenarien ab (Automobil, Bekleidung, Produktdesign, Medien &amp; Unterhaltung, Architektur...). Der Studiomodus ermöglicht Desktopaufnahmen (wiederholbar, effizient und einfach), während der Explorer-Modus die mobile Aufnahme &quot;flexibel, unterwegs, an jede Situation angepasst&quot; ermöglicht.

+++

+++Welche Material-Typen können gescannt und mit Captis erfasst werden?
Alle Materialtypen können mit Ausnahme mehrerer Klarlackschichten gescannt und erfasst werden (Autolacke sind vom Captis-Programm ausgeschlossen). Für einige bestimmte Material ist möglicherweise eine zusätzliche Verarbeitung in Sampler erforderlich, um die Ergebnisse zu optimieren. Bitte beachten Sie, dass die Verarbeitungsalgorithmen im Laufe der Zeit kontinuierlich optimiert werden.

+++

+++Welche Einschränkungen gelten für die Größe oder Form von Material-Samples? Müssen Samples eben sein?
Captis kann eine Vielzahl von Material-Samples in Größe oder Form scannen. Es wird mit Magneten geliefert, um die Proben auf dem Probenfach zu flachen. Es gibt verschiedene Modi, um ein Material mit Captis aufzunehmen:

* Studio-Modus: mit der Studiobasis auf Ihrem Schreibtisch, im Studio oder in der Fabrik nimmt Captis Proben bis zu 30cm x 30cm - mit Hintergrundbeleuchtung für Deckkraft. Die Tiefe des Probenfachs beträgt 1,8 CM.

* Explorer-Modus: können Sie den Explorer-Ring vor Ort, am Set oder in speziellen Umgebungen verwenden und ermöglichen die flexible Aufnahme von Proben, die größer als 30 cm x 30 cm sind. Aktuelle Einschränkung: Bitte beachten Sie, dass der Explorer-Modus noch eine frühe Version ist und noch nicht optimiert wurde (ab der Version vom 29. Juli 2024).

+++

## Software

+++Benötigt das HP Z Captis-Gerät ein Software-Abonnement oder eine Lizenz für die Verwendung?
Das Captivate-Gerät erfordert eine aktive Substance 3D Sampler Enterprise-, Teams- oder Universitätslizenz, die in der Substance 3D Collection unter den gleichen Bedingungen und Nutzungsbedingungen wie jedes Substance 3D-Abonnement verfügbar ist.

Das Gerät (HP Z Captis) und die Lizenz (Substance 3D Sampler) sind separat erhältlich.

+++

+++Wie weit ist die Integration mit der Substance-Suite von Adobe bereits fortgeschritten?
Das HP Z Captis-Gerät wird vollständig von Adobe Substance 3D Sampler gesteuert und betrieben: Sie können die Aufnahme in Substance 3D Sampler in der Vorschau anzeigen und starten. Nach Abschluss der Aufnahme werden die PBR-Kanäle automatisch als Ebene geladen und ein 3D-Material erstellt. Sie können Ihre Materials mit allen in Sampler verfügbaren Werkzeugen und Filtern weiter verarbeiten.

Sobald sich das aufgenommene Material in Substance 3D Sampler befindet, können Sie es in eine beliebige Anwendung der Substance 3D-Suite (Substance 3D Designer, Painter, Stager) und in jede Anwendung eines Drittanbieters exportieren, die Substance unterstützt, einschließlich 3DS Max, Maya, Blender, Unreal Engine, CLO, Browzwear, VRED, Rhino, Cinema4D und vieles mehr (die vollständige Liste finden Sie hier: <https://www.adobe.com/products/substance3d/plugins.html>).

+++

+++Welche Spezifikationen werden für die Verwendung von Substance 3D Sampler mit Captis empfohlen?
Sampler-Hardwarespezifikationen sind hier [verfügbar](system-requirements-to-use-hp-z-captis.md).

+++

+++Ist der HP Z Captis-Arbeitsablauf sowohl unter Windows als auch unter Mac verfügbar?
Ab der Version vom 20. Februar 2025 ist der Arbeitsablauf für Sampler mit HP Z Capture nur unter Windows verfügbar.

+++

+++Wo finde ich die Version von Substance 3D Sampler mit dem Arbeitsablauf HP Z Captis?
Ab der Version vom 20. Februar 2025 können Sie im Rahmen der regulären Versionen von Substance 3D Sampler, die Sie von der Creative Cloud-Desktop-Applikation herunterladen, mit Captivate auf Adobe Substance 3D Sampler zugreifen. Es ist nicht mehr notwendig, sie von der Adobe Prerelease herunterzuladen.

+++

+++Was ist noch nicht verfügbar?
*Einschränkungen ab August 2025 (Sampler 5.1.0-Build):*

* Der Arbeitsablauf von Sampler mit HP Z Captis ist derzeit nur unter Windows verfügbar.

* Die fünf Karten, die heute exportiert werden, sind Grundfarbe, Raueit, Normal, Height, Deckkraft.

* Explorer Mode ist noch eine frühe Version und wurde noch nicht optimiert.

* Die Kachelung erfolgt in Sampler Ebenenstapel mit den Filtern für die aktuelle Kachelung.

+++

+++Welche PBR-Kanäle sind verfügbar?
Ab der Version vom 7. August 2025 lauten die exportierten fünf Karten &quot;Grundfarbe&quot;, &quot;Raueit&quot;, &quot;Normal&quot;, &quot;Height&quot; und &quot;Deckkraft&quot;. Die aktuelle Verarbeitungspipeline verarbeitet die Metalness-Map noch nicht.

+++

+++Erfolgt die Kachelung automatisch?
Die Kachelung wird im Sampler-Ebenenstapel mit den Filtern für die aktuelle Kachelung ausgeführt.

Der Filter &quot;Automatische Kachelung&quot; kann verwendet werden, um Material mit einer definierten Wiederholungsstruktur oder kleinen Mustern mit mindestens 3 Mustern in jeder Richtung automatisch anzuordnen. Weitere Informationen zu diesem Filter finden Sie im Abschnitt [Dediziert in der Dokumentation](../../filters/tools/auto-tiling.md).

+++

+++In welche Formate können die gescannten Materialien exportiert werden?
HP Z Captis wird nativ von Adobe Substance 3D Sampler betrieben. HP Z Capture erfasst 64 Raw-Bilder (die aus Ihrem lokalen Ordner abgerufen werden können) und PBR-Maps (die aus den aufgenommenen Raw-Bildern verarbeitet und automatisch in Substance 3D Sampler geladen werden). Substance 3D Sampler erstellt ein 3D-Material auf Basis der PBR-Kanäle, die nach der Aufnahme automatisch in den Sampler-Ebenenstapel geladen werden.

Von Adobe Substance 3D Sampler aus können Sie Ihr digitales Material in jedes beliebige in Substance 3D Sampler verfügbare Exportformat exportieren: als Substance-Dateien (.SBS- und .SBSAR-Dateien) oder als Bitmaptexturen, einschließlich .PNG, .JPG, .TIFF.. (weitere Informationen finden Sie auf der Sampler-Dokumentations-Webseite: [https://helpx.adobe.com/substance-3d-sampler/getting-started/export.html](../../getting-started/export/export.md)).

+++

+++Was ist der Unterschied zwischen LDR und HDR während der Aufnahme?
Während der Vorschau haben Sie die Möglichkeit, den Ausgabetyp zwischen LDR (Low Dynamic Range) und HDR (High Dynamic Range) zu wählen.\
Auch wenn LDR ausgewählt ist, werden die HDR erfasst und auf Ihrem Gerät gespeichert.\
Es wird empfohlen, dass Sie die LDR auswählen, da dies die Projektgröße in Sampler und in allen Drittanbieter-Apps, in denen die sbsar-Dateien verwendet werden, besser handhaben kann.

+++

## Verarbeitung läuft

+++Wie kann ich Captis in meiner aktuellen 3D-Pipeline verwenden, wenn ich bestimmte Dateiformate, Standards und Spezifikationen oder Anwendungen von Drittanbietern verwende?
HP Z Captis wird nativ von Adobe Substance 3D Sampler betrieben. Nachdem Sie Ihr Material in Substance 3D Sampler aufgenommen und digitalisiert haben, können Sie Ihre digitalen Materials nahtlos exportieren:

In allen Anwendungen des Substance 3D-Ökosystems (einschließlich Substance 3D Designer oder Substance 3D Painter, die verschiedene Exportformate unterstützen): https://experienceleague.adobe.com/en/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats).

In allen Anwendungen, die Substance-Dateiformate wie 3DS Max, Maya, Blender, C4D, Rhino, Browzwear, CLO... integrieren (die vollständige Liste finden Sie hier: <https://www.adobe.com/products/substance3d/plugins.html>). Wenn Sie eine Anwendung verwenden, die dort nicht aufgeführt ist, können Sie PBR-Texturbilder immer exportieren und sie manuell in alle Anwendungen einstecken, die das Substance-Dateiformat nicht nativ unterstützen.

+++

+++Wie viele Bilder werden aufgenommen, um die Karten zu erstellen?
[8 Lichtpaneele + 1 Hintergrundbeleuchtung] x [8 Polarisationszustände] x [8 Belichtungsreihen für HDR.] x [4 Überzüge zur Reduzierung des Rauschen] = 2048 + 256 (für Hintergrundbeleuchtung)

+++

## Geräteverwaltung

Erfahren Sie mehr über das Gerät und seine Spezifikationen auf der [HP-Website](https://www.hp.com/us-en/workstations/z-captis.html "HP Z Captis").

+++Kann ich die IP-Adresse des Geräts ändern?
Um die IP-Adresse des Geräts zu ändern, können Sie die Windows-Datei C:\Windows\System32\drivers\etc\hosts.txt by ändern und eine zusätzliche Zeile hinzufügen:

Sie können beispielsweise 192.168.55.1 captis-device hinzufügen und dann in <b>Sampler-Einstellungen > Speicher und Cache > Materialerfassung > Captis-Adresse</b> die IP-Adresse durch captis-device ersetzen.

+++

## Verwendungsprobleme

+++Sampler erkennt HP Z Captis nicht.
Stellen Sie sicher, dass der HP Z Captis an einen USB 3.0-Anschluss angeschlossen ist.

Stellen Sie sicher, dass das USB-Kabel an die Basis des HP Z Captis und nicht an den Kegel angeschlossen ist.

+++

+++Meine Vorschau in Sampler ist komplett schwarz.
Stellen Sie sicher, dass der Kameraschutz entfernt wurde.

+++

+++Das Kopieren von Dateien vom HP Z Captis auf meinen Computer ist langsam.
Stellen Sie sicher, dass der HP Z Captis an einen USB 3.0-Anschluss angeschlossen ist.

Wenn Sie aufgefordert werden, sowohl die Material- als auch die Fotometriebilder abzurufen, dauert das Kopieren normalerweise länger.

+++

+++Sampler hat die Bilder nicht auf meinen Computer kopiert. Muss ich den Scan neu starten?
Nein, tun Sie nicht. Sie können den Inhalt des Geräts durchsuchen und die Bilder im Adobe-Explorer mithilfe des Dateiordners Ihres Betriebssystems kopieren.

+++

+++Das Menü zeigt an, dass sich das Gerät im Wiederherstellungsmodus befindet.
Drücken Sie den Betriebsschalter einige Sekunden, um ihn auszuschalten. Schalten Sie sie wieder ein.

+++

+++Ich habe den Kegel von seinem Sockel zum Explorer verschoben und kann nicht mehr scannen.
Es wird empfohlen, den HP Z Captis auszuschalten, bevor Sie ihn vom Sockel oder vom Explorer-Ring abziehen.

+++

+++Mein Material wird nur langsam in SBSAR exportiert.
Vergewissern Sie sich, dass die Bilder nicht im 32-Bit-Gleitkommaformat im Eigenschaftenbedienfeld angezeigt werden.

Sie können auch die Komprimierungsstufe auf &quot;none&quot; festlegen, um den Export zu beschleunigen.

+++

+++Ich möchte den Speicherpfad für die aufgenommenen Materialien und Fotometriebilder ändern.
Es ist jetzt möglich, den Speicherort, an dem die aufgenommenen Materialien und Fotometriebilder gespeichert werden, unter Bearbeiten > Voreinstellungen > Speicher und Cache > Material-Aufnahme zu bearbeiten.

+++

+++Das Fenster ist größer als der Bildschirm, und ich kann die Größe nicht ändern.
Die Größe des Captis-Fensters kann nicht geändert werden. Möglicherweise verwenden Sie eine Bildschirmvergrößerung, die nicht behandelt wird. Captis unterstützt Folgendes:

* Lösung: 1920 x 1080
  * Maximale Vergrößerung: 100 %

* Maximale Vergrößerung: 100 %

* Lösung: 2560 x 1440
  * Maximale Vergrößerung: 125 %

* Maximale Vergrößerung: 125 %

* Lösung: 3840 x 2160
  * Maximale Vergrößerung: 200 %

* Maximale Vergrößerung: 200 %

* Auflösungen unter 1920 x 1080 werden nicht unterstützt.



+++
