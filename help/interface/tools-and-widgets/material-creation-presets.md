---
breadcrumb-title: ''
description: Lerne, wie du in Substance 3D Sampler auf Basis von Material-Vorlagen schnell komplexe, realistische Materials erstellst, indem du die physikalischen Effekte in einfachen, sofort einsatzbereiten Templates anwendest.
user-guide-description: ''
user-guide-title: ''
title: Vorgaben zum Erstellen von Materialien
source-git-commit: 8777fdda4545110ed765f1d275c35bd11e71903b
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 2%

---


# Vorgaben zum Erstellen von Materialien

Vorlagen zur Erstellung von Materialien bieten vordefinierte Ausgangspunkte für die Erstellung von Materialien mit erweitertem physischen Verhalten. Mit jeder Vorlage werden das Materialmodell, die aktivierten Kanäle und die Standardparameter konfiguriert, die für einen bestimmten Oberflächentyp erforderlich sind. So können Sie schnell komplexe Materialien erstellen und gleichzeitig die vollständige Kontrolle über das Ergebnis behalten. Vorlagen sind beim Erstellen eines neuen Materials verfügbar und können sowohl mit OpenPBR- als auch mit ASM-Materialmodellen verwendet werden.

![Das Fenster &quot;Neues Material erstellen&quot;](../../assets/6.0_materialPresets.png)

>[!TIP]
> Hier erfahren Sie mehr über das Erstellen erweiterter Materialien, die Fuzz-, Untergrund- und Beschichtungskanäle [&#x200B; nutzen.](../../features-and-workflows/create-advanced-materials/advanced-materials.md)

## Material aus Vorlage erstellen

Erstellen eines Materials mithilfe einer Vorlage:

Öffnen Sie das Dialogfeld Neues Material erstellen . Wählen Sie eine Vorlage auf den Registerkarten Vordefiniert oder Benutzerdefiniert aus. Passen Sie die Material-Einstellungen (Name, Auflösung, Materialmodell, Kanäle) an. Klicken Sie auf Erstellen , um mit dem konfigurierten Material zu arbeiten.

Die ausgewählte Vorlage definiert die Anfangsstruktur des Materials, einschließlich der aktivierten Kanäle und ihrer Einrichtung im Ebenenstapel.

## Vorgabenkategorien

### Vordefinierte Vorlagen

Bei den vordefinierten Vorlagen handelt es sich um gebrauchsfertige Material-Setups, die für gängige physische Verhaltensweisen von Materialien entwickelt wurden. Sie kodieren Best Practices und empfohlene Kanalkonfigurationen für jeden Anwendungsfall. Zu den verfügbaren vordefinierten Vorlagen gehören:

- Basismaterial Ein physikalisch basiertes Standardkanal-Material, bei dem häufig verwendete Kanäle aktiviert sind. Verwenden Sie diese Vorlage für einfache oder generische Material, für die kein spezielles Verhalten erforderlich ist.

- Anisotropie Konfiguriert das Material für richtungsabhängige Reflexionen, geeignet für gebürstete Metalle oder Oberflächen mit orientierten Mikrodetails.

- Beschichtung Fügt eine sekundäre reflektierende Schicht auf dem Basismaterial hinzu, die Klarlack- oder Lackeffekte ermöglicht.

- Fuzz Ermöglicht weiche, lichtstreuende Oberflächeneffekte, die für Stoffe, Fasern oder Materialien mit samtigem Aussehen verwendet werden.

- Untergrund Aktiviert den Untergrund-Lichttransport für Materialien wie Wachs, Kunststoffe oder organische Oberflächen, bei denen das Licht unter die Oberfläche eindringt.

- Transparent Konfiguriert das Material für die Lichtübertragung, geeignet für glasartige oder dünne transparente Materialien.

Jede vordefinierte Vorgabe legt die erforderlichen Kanäle und Standardwerte automatisch fest, wodurch die manuelle Einrichtung und der technische Aufwand reduziert werden.

### Benutzerdefinierte Vorgaben

Mit benutzerdefinierten Vorgaben können Sie Ihre eigenen Materialkonfigurationen wiederverwenden. Jede von Ihnen erstellte Materialvorgabe kann als benutzerdefinierte Vorlage gespeichert werden und wird auf der Registerkarte Benutzerdefiniert angezeigt. Dies ermöglicht die konsistente Material-Erstellung über Projekte oder Teams hinweg mithilfe von gemeinsam genutzten Standards und Kanalkonfigurationen.

## Vorgabedetails

Im Bedienfeld &quot;Vorgabendetails&quot; werden die Einstellungen angezeigt und gesteuert, die zum Erstellen des neuen Materials verwendet werden.

### Elementname

Definiert den Namen des Material-Assets, das erstellt wird.

### Auflösung

Steuert die Standardauflösung der Material-Maps (Breite und Height). Diese Auflösung gilt für alle aktivierten Kanäle, wenn das Material erstellt wird.

### Materialmodell

Gibt das vom Material verwendete Materialmodell an:

OpenPBR für moderne, standardisierte physikbasierte Workflows ASM für Kompatibilität mit bestehenden Pipelines

Die ausgewählte Vorlage wird an das ausgewählte Materialmodell angepasst.

### Basismaterial hinzufügen

Wenn diese Option aktiviert ist, erstellt Sampler eine Grundfüllungsebene aus einem Basismaterial, das mit der ausgewählten Vorlage kompatibel ist. Dies bietet ein sofortiges visuelles Ergebnis und einen brauchbaren Ausgangspunkt. Das Basismaterial ist sowohl an OpenPBR- als auch an ASM-Materialmodell angepasst.

### Thumbnail-Vorgabenwerte anwenden

Wenn diese Option aktiviert ist, wird das Material mit den Werten initialisiert, die zum Generieren der Vorschauminiatur der Vorlage verwendet werden, anstatt mit neutralen Standardwerten. Dies hilft, das beabsichtigte Verhalten der Vorlage zu demonstrieren und eine visuelle Basis zu haben, auf der Sie aufbauen können.

### Liste bearbeiten

Klicken Sie auf **Liste bearbeiten**, um den Kanalsatz anzupassen, bevor Sie das Material erstellen. Sie können Kanäle nach Bedarf aktivieren oder deaktivieren oder die Konfiguration als neue benutzerdefinierte Vorlage speichern.