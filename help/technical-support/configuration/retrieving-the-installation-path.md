---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie den Installationspfad für Substance 3D Sampler auf verschiedenen Plattformen für Skript- und Konfigurationszwecke abrufen.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ermitteln des Installationspfads
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 6%

---


# Ermitteln des Installationspfads

Auf dieser Seite werden Informationen darüber neu gruppiert, wie der Installationspfad der Anwendung je nach Version und Plattform abgerufen werden kann.

## Windows

### Creative Cloud Desktop

1. Öffnen Sie den Windows-Registrierungseditor (**regedit**).
1. Navigieren Sie zum Registrierungsschlüssel: **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Pfade\**
1. Öffnen Sie den Unterschlüssel &quot;**Adobe Substance 3D Sampler.exe**&quot;.
1. Der Wert des Schlüssels enthält den Pfad zur ausführbaren Anwendungsdatei, in der er installiert ist

>[!NOTE]
>
> Dieser Registrierungsschlüssel ist nur seit Version 3 verfügbar.\
> Bei älteren Versionen kann der Installationspfad aus den Dateizuordnungen in **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts** abgerufen werden.

### Substance 3D Standalone

1. Öffnen Sie den Windows-Registrierungseditor (**regedit**).
1. Navigieren Sie zum Registrierungsschlüssel: **HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. Suchen Sie den Unterschlüssel, der mit der AppID Ihrer Anwendungsversion übereinstimmt (siehe Tabelle unten).
1. Der Wert des Schlüssels enthält den Pfad zum Speicherort der Anwendungsinstallation

| Version | AppId |
| --- | --- |
| **1.x (2019.x) bis 2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x (oder neuer)** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### dämpfen

Die Anwendung wird im Unterordner **steamapps/common/** des Steam-Installationsordners installiert.

## Mac

Unter Mac wird die Anwendung wie folgt installiert:

| Version | Pfad |
| --- | --- |
| **3.x oder neuer** | **/Applications/Adobe Substance 3D Sampler.app** |
| **Veraltet** | **/Applications/Substance Alchemist.app** |

## Linux

Unter Linux wird das rpm-Paket unter folgendem Pfad installiert:

| Version | Pfad |
| --- | --- |
| **3.x oder neuer** | **/opt/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **Veraltet** | **/opt/Allegorithmic/Substance\_Alchemist** |
