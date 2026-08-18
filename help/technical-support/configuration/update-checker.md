---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/update-checker.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie die Update-Prüfung in Substance 3D Sampler verwenden, um über neue Versionen und Versionshinweise auf dem Laufenden zu bleiben.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Update Checker
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Update Checker
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---


# Update Checker

Im Aktualisierungsfenster wird angezeigt, ob eine neue Substance Alchemist-Version verfügbar ist, und es werden die neuesten [Versionshinweise](../../release-notes/release-notes.md) angezeigt.

Dieses Fenster wird beim Start von Substance Alchemist automatisch angezeigt, wenn eine neue Version zum Herunterladen verfügbar ist.

Mit den folgenden Methoden können Sie die Anzeige dieses Fensters während des Startvorgangs vermeiden:

* Verwenden Sie die Einstellung &quot;Nicht bis zur nächsten Version erinnern&quot; im Fenster, um die Anzeige des Fensters vorübergehend bis zur nächsten Version zu überspringen.
* Deaktivieren Sie die Einstellung &quot;**Nach Updates suchen**&quot; unter Bearbeiten > Voreinstellungen > Nach Updates suchen.
* Mit der Befehlszeile **—skip-version-check** Es wird nicht überprüft, ob beim Starten des Substance Alchemist eine neue Anwendungsversion verfügbar ist.
* Verwenden einer Umgebungsvariablen **SUBSTANCE\_ALCHEMIST\_SKIP\_CHECK\_FOR\_UPDATES**:Value 0 oder 1 (1 = Updateprüfung deaktivieren)

>[!NOTE]
>
> Unterstützt seit Substance Alchemist 2020.1 (2.1)
