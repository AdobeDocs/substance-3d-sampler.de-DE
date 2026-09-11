---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/release-notes/version-3-4.html"
breadcrumb-title: ''
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 3.4 , um mehr über die neuen Funktionen zur Beschleunigung und Qualität von 3D-Workflows zu erfahren.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Version 3.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '838'
ht-degree: 0%

---


# Version 3.4

Mit **Substance 3D Sampler 3.4.0** werden eine Reihe neuer Funktionen eingeführt, mit denen die Geschwindigkeit und Qualität von 3D-Workflows gesteigert werden können.

*Freigabedatum: 6. September 2022*

## Wichtigste Funktionen

## Bereitgestellte Parameter

Sie können parametrische Material in jeder Software ändern, die SBSAR-Dateien unterstützt, unter anderem CLO, UE5, Blender, Photoshop und Illustrator.\
Das ist jetzt möglich, da Sampler die neuen Elementparameter legt, sodass du Iterationen beschleunigen und das Hin und Her zwischen Sampler und anderen Programmen vermeiden kannst.

Leg die Parameter deines Materials, indem du einfach auf eine Nadel klickst.

Mithilfe von Farbpunkten kannst du in deinen freigelegten Parametern und in deinen verschiedenen Bedienfeldern navigieren.

## Python-Authoring

Sie können jetzt Plug-ins und Skripte erstellen. Dadurch haben Sie die Möglichkeit, Ihre Oberfläche anzupassen, sodass Sie Sampler ganz einfach in Ihre Pipeline integrieren und Ihren Arbeitsablauf insgesamt beliebig einrichten können.\
So können Sie beispielsweise ein Skript erstellen, mit dem Sie sich wiederholende Aufgaben automatisieren können, indem Sie mehrere Material mit einem Klick exportieren.

Erfahren Sie hier, wie Sie Ihr erstes Plug-in oder Skript [erstellen](../scripting-and-development/scripting-and-development.md).

## Physikalische CLO-Eigenschaften

Sie können jetzt Textilien erstellen, die sich realistisch verhalten, wenn Sie physikalische Simulationen verwenden. Dies wird durch Eingabe der physikalischen Eigenschaften des Stoffes, wie Biegen, Scheren und Reibung erreicht.\
Mit diesem Update enthält die SBSAR die Physikinformationen in den Metadaten, die von CLO verwendet werden, um sicherzustellen, dass das Material realistisch reagiert.

## Von Bild zu Material (KI-gestützt)

&quot;Bild zu Material&quot; (KI-gestützt) ist jetzt auf MacOS verfügbar und wird nativ auf Apple Silicon-Geräten ausgeführt.

## Versionshinweise

### 3.4.0 Arancini

*(Freigabedatum: 6. September 2022)*

**Hinzugefügt:**

[Freigelegte Parameter] Neue Bedienfeld „Veröffentlichte Parameter“\
[Freigelegte Parameter] Neue Schaltfläche für Parameter, die den Mauszeiger über das Fenster &quot;Eigenschaften&quot; bewegen, um Parameter legen und die Anzeige aufzuheben\
[Verfügbare Parameter] Neues Kontextmenü mit der rechten Maustaste auf Parameter zum Verfügbarmachen und Lösen von Parametern aus dem Eigenschaftenbedienfeld\
[Verfügbare Parameter] Verfügbare Parameter sind auf der Bedienfeld „Veröffentlichte Parameter“ aufgelistet.\
[Freigelegte Parameter] Farbpunkte und Farbscheiben werden an mehreren Stellen hinzugefügt, um freigelegte Parameter leicht zu identifizieren\
[Freigelegte Parameter] Parameterbeschriftungen können in der Bedienfeld „Veröffentlichte Parameter“ bearbeitet werden\
[Freigelegte Parameter] Eine Warnung für nicht exportierbare Parameter anzeigen\
[Freigelegte Parameter] Warnung anzeigen, wenn eine Ebene mit gelegt Überblendungsparametern an eine Stelle verschoben wird, an der sie ausgeblendet werden\
[Freigelegte Parameter] Freigelegte Parameter werden im SBS- und SBSAR-Format exportiert\
[Metadaten] Unterstützung benutzerdefinierter Metadatenvorlagen\
[Metadaten] Neue Vorlage für physikalische CLO-Eigenschaften\
[Metadaten] Hinzufügen von Symbolen beim Hovern zum Hinzufügen/Entfernen benutzerdefinierter Metadaten\
[Python-API] Neue Python-API\
[Python-API] API für Asset-Authoring\
[Python-API] API für die Ebenenverwaltung\
[Python-API] API für die Parameterverwaltung\
[Python-API] API für das Projektmanagement\
[Python-API] Ein Plug-in kann aktiviert und deaktiviert werden\
[Python-API] Python-API-Dokumentation im Menü &quot;Hilfe&quot;\
[Scripting] Abschnitt &quot;Neue Plug-ins und Skripte&quot; im Popup &quot;Voreinstellungen&quot;\
[Scripting] Erstellen und importieren Sie Plug-ins, um die Sampler-Oberfläche mit Ihren eigenen Bedienfeldern anzupassen\
[Scripting] Plug-ins werden Teil der Sampler-Oberfläche und können wie herkömmliche Sampler-Bedienfelder angedockt und verschoben werden\
[Scripting] Dedizierte Schaltflächenleiste für die Plug-ins in der rechten Sampler-Symbolleiste\
[Skripterstellung] Erstellen und Importieren von Skripten zum Ausführen einer Liste der angegebenen Aufgaben\
[Skripterstellung] Starten von Python-Skripten über das Menü &quot;Skripte&quot;\
[Scripting] Plug-ins und Skripte können über das Fenster Voreinstellungen gelöscht, neu angeordnet und neu geladen werden.\
[Scripting] —run-script-Befehlszeilenparameter hinzugefügt\
[Protokolle] Neues Protokollbedienfeld\
[Protokolle] Fenster &quot;Protokolle&quot; im Fenster &quot;Voreinstellungen&quot; aktivieren\
[Protokolle] Neue Aktionsleiste zum Löschen, Kopieren/Einfügen und Exportieren von Protokollen\
[Eigenschaften] Neue Schaltfläche für Parameter, die den Mauszeiger zum Zurücksetzen des Parameterwerts bewegen\
[Eigenschaften] Neues Kontextmenü mit der rechten Maustaste auf Parameter zum Zurücksetzen des Parameterwerts\
[Inhalt] Bild-zu-Material (KI-gestützt) funktioniert jetzt auf MacOS\
[Engine] Substance-Engine auf Version 8.6.0 aktualisieren

**Fest:**

[Anwendung] Die Anwendung konnte beim Beenden einen Absturz verursachen, wenn eine Miniaturansichtserstellung ausgeführt wurde\
[Anwendung] Bei Verwendung von &quot;Speichern unter&quot; beim Beenden kann die Anwendung einen Absturz aufweisen.\
[Anwendung] Anwendung hängt möglicherweise beim Herunterfahren unter MacOS\
[Anwendung] Beim Speichern mit geöffnetem Farbdialogfeld werden die Änderungen nicht gespeichert\
[Export] Die Namenskonvention für die Verwendung ist beim Exportieren nicht korrekt.\
[Ebenen] Das Ablegen eines Materials über einem Filter kann zu Abstürzen führen\
[Ebenen] Beim Aktualisieren eines veralteten Ebenenstapels können nicht zugehörige Ebenenstapel aktualisiert werden.\
[Metadaten] Leere Felder werden exportiert\
[Metadaten] Wenn es nur ein Metadatenelement gibt, können Sie auf der Benutzeroberfläche versuchen, es neu anzuordnen\
[Projekt] Die Berechnung wird nach dem Duplizieren eines Materials nie beendet.\
[Projekt] Projektelement wird nach dem ersten Speichern des Projekts dupliziert\
[Projekt] Unnötige Berechnungen beim Wechseln des Assets\
[Rendering] Einige Ebenenstapel werden nach dem Löschen einer Ebene nicht richtig gerendert\
[Sicherheit] Problembehebung CVE-2015-20107\
[UI] 2D-Ausgaben können je nach Fenstergröße verschwommen sein\
[UI] Asset-Vorschau kann oben geöffnet bleiben, wenn die Anwendung den Fokus verliert\
[UI] Abgerundete Ecken des Splash-Bildschirms haben einen quadratischen, undurchsichtigen Hintergrund

**Bekannte Probleme:**

[Farbwähler] Die Auswahl einer Farbe auf einem zweiten Monitor mit einer anderen Auflösung funktioniert möglicherweise nicht\
[Inhalt] Shape Light-Widget funktioniert nicht im sphärische Projektion-Modus\
[Interoperabilität] Material mit an Stager gesendetem Versatz verliert die Versatz-Steuerelemente.
