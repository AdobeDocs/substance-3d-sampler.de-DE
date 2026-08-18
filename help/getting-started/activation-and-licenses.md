---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: Hier erfahren Sie, wie Sie Lizenzen für Substance 3D Sampler aktivieren und verwalten, damit Sie die Anwendung verwenden und auf alle Funktionen zugreifen können.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Aktivierung und Lizenzen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 1%

---


# Aktivierung und Lizenzen

Auf dieser Seite wird erläutert, wie Sie Ihre Lizenzen aktivieren und verwalten, damit Sie Sampler verwenden können.

## Aktivierungsprozess nach Anwendungstyp

Der Aktivierungsprozess hängt davon ab, wo Sie Sampler erworben haben oder Zugriff darauf haben:

| Anwendungstyp | Aktivierungsprozess |
| --- | --- |
| Creative Cloud Desktop | Weitere Informationen finden Sie auf der entsprechenden Seite in der [HilfeX-Dokumentation](https://helpx.adobe.com/de/support/substance-3d-sampler.html).Falls Probleme auftreten, kann die [Creative Cloud-Dokumentation](https://helpx.adobe.com/de/creative-cloud/user-guide.html) zusätzliche Antworten liefern. |
| dämpfen | Starten Sie das Produkt direkt aus der Steam-Bibliothek. |
| Substance 3D als eigenständiges Produkt | Weitere Informationen finden Sie im unten beschriebenen Aktivierungsprozess. |

## Aktivierungsschritte

### Der Aktivierungsassistent

![](../assets/activation-wizard.png){width="350px"}

Es stehen drei Optionen zur Auswahl:

* **Dieses Produkt auswerten**: Ältere Testversionen sind nicht mehr verfügbar. Sie können stattdessen eine 30-tägige Testversion für jede Substance 3D-Anwendung [hier](https://www.adobe.com/creativecloud/3d-augmented-reality.html) oder mit Creative Cloud Desktop starten. Jede Testversion ist unabhängig von den anderen Substance 3D-Programmen. Sie können also einzeln oder alle Applikationen gleichzeitig testen.
* **Mit einer Lizenzdatei aktivieren**: Aktivieren Sie das Produkt mit einer Lizenzdatei (**\*.key**), die Sie vor dem 30. September 2022 von Ihrer Kontoseite auf der [Substance 3D-Website](https://store.substance3d.com/user) heruntergeladen haben.
* **Aktivieren mit Ihrem Konto**: Ältere Substanzkonten können nicht mehr für die Aktivierung verwendet werden. [Weitere Informationen zu Substance-Konten finden Sie hier](https://helpx.adobe.com/de/substance-3d/unlisted/faq-end-of-life-accounts.html).

>[!WARNING]
>
> Um die Lizenzdatei mit dem Aktivierungsassistenten zu installieren, müssen Sie Sampler als Administrator ausführen und das Antivirenprogramm vorübergehend deaktivieren.

### Manuelle Aktivierung

Sie können Sampler manuell aktivieren, indem Sie die Datei **license.key** in den folgenden Ordner kopieren:

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Plattform</th><th>Version</th><th colspan="2">Pfad</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>3.0</strong> oder höher</td><td colspan="1">App-Daten (lokal)</td><td colspan="1">C:\Users\[Benutzername]\AppData\Local\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">App-Daten (Roaming)</td><td colspan="1">C:\Users\[Benutzername]\AppData\Roaming\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td rowspan="2">Alte Version</td><td colspan="1">App-Daten (lokal)</td><td colspan="1">C:\Users\[Benutzername]\AppData\Local\Allegorithmic\Substance Alchemist</td></tr><tr><td colspan="1">App-Daten (Roaming)</td><td colspan="1">C:\Users\[Benutzername]\AppData\Roaming\Allegorithmic\Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>3.0</strong> oder höher</td><td colspan="2">/Users/[Benutzername]/Library/Application Support/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">Alte Version</td><td colspan="2">/Users/[Benutzername]/Library/Application Support/Allegorithmic/Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>3.0</strong> oder höher</td><td colspan="2">/home/[Benutzername]/.local/share/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td>Alte Version</td><td colspan="2">/home/[Benutzername]/.local/share/Allegorithmic/Substance Alchemist</td></tr></tbody></table>

>[!NOTE]
>
> Einige der Verzeichnisse in den oben genannten Pfaden sind möglicherweise standardmäßig ausgeblendet. Geben Sie den Pfad manuell im Datei-Explorer ein oder zeigen Sie ausgeblendete Dateien an, um sie anzuzeigen.

>[!NOTE]
>
> Stellen Sie sicher, dass die Datei &quot;**license.key**&quot; heißt, andernfalls kann sie von der Anwendung nicht gefunden werden.

### Umgebungsvariable

Sie können den Speicherort, an dem Sampler die Datei **license.key** sucht, mit einer [Umgebungsvariablen](../pipeline-and-integrations/environment-variables.md) überschreiben.
