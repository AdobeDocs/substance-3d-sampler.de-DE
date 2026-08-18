---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: Prüfen Sie die Systemanforderungen für Substance 3D Sampler , um sicherzustellen, dass Ihre Hard- und Software den Kompatibilitätsstandards entspricht.
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Systemanforderungen
user-guide-description: ''
user-guide-title: ''
source-git-commit: cd61972eaf1567863dc8c3549a1c90c84ffee825
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 1%

---


# Unterstützte Systeme

Im Folgenden finden Sie eine Liste der von der Anwendung unterstützten Hardware und Systeme:

>[!WARNING]
>
> Die folgenden NVIDIA-Treiber verursachen bekanntermaßen Instabilität, wenn Sampler ausgeführt wird:
>
> * 610.47
>
> Wir empfehlen, die Verwendung dieser Versionen zu vermeiden. Verwenden Sie idealerweise eine neuere Version oder, wenn keine neuere Version verfügbar ist, die vorherige Version.

## Windows

|  | Minimum | Empfohlen | Optimal |
| --- | --- | --- | --- |
| **Betriebssystem** | Windows 11 64-Bit Version 23H2 | Windows 11 64-Bit Version 24H1 | Windows 11 64-Bit Version 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 ADA Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Speicher** | SSD mit 30 GB verfügbarem Speicherplatz | SSD mit 50 GB verfügbarem Speicherplatz | SSD mit 70 GB verfügbarem Speicherplatz |

### macOS

|  | Minimum | Empfohlen | Optimal |
| --- | --- | --- | --- |
| **Betriebssystem** | macOS 13 Ventura | macOS 14 Sonoma | macOS 26 Tahoe |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 24 GB | 32 GB | 64 GB |
| **Speicher** | SSD mit 30 GB verfügbarem Speicherplatz | SSD mit 50 GB verfügbarem Speicherplatz | SSD mit 70 GB verfügbarem Speicherplatz |

### Linux

| Unternehmen | dämpfen |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22,04 |

>[!NOTE]
>
> Wenn Ihr System die oben genannten Systemanforderungen erfüllt, die Leistung aber immer noch langsam ist, verwendet Sampler möglicherweise die falsche GPU.
>
> Wenn Sie eine NVIDIA-GPU verwenden, [ändern Sie, welche GPU Sampler verwendet, indem Sie die Anweisungen auf dieser Seite befolgen](../technical-support/configuration/nvidia-driver-settings.md).

## Allgemeine Empfehlungen

* Für die Arbeit unter angenehmen Bedingungen empfehlen wir einen Monitor mit einer Auflösung von mehr als 1 MegaPixel und mehr als 1280 Pixel.
* Viele Substance-Apps sind für RHEL8/9-Kompatibilität auf OpenSSL 1.1.1 angewiesen. Bei Systemen mit neueren OpenSSL-Versionen müssen Sie diese manuell bereitstellen.

## Nicht unterstützte Konfigurationen

**Windows**

* Virtuelle Computer werden nicht unterstützt.
* Windows Server wird nicht unterstützt.

**Mac**

* Es werden nur offizielle Apple-Konfigurationen unterstützt.
* eGPUs werden derzeit nicht unterstützt und haben möglicherweise Stabilitätsprobleme.

**Linux**

* Mesa-Treiber unter Linux werden nicht unterstützt.

**Beliebige Plattform**

* Integrierte GPUs werden auf x86-64-CPUs (Intel, AMD) nicht unterstützt.
* Die Verwendung von Sampler in Kombination mit Software von Drittanbietern, die Sampler-Aufrufe an die Grafiktreiber abfängt, wird nicht unterstützt. Diese Software umfasst:
  * Nachbearbeitungs-Injectors wie Schattierer, die Farbkorrektur anwenden, Kameraeffekte, ...
  * On-Screen-Overlays, z. B. benutzerdefinierte Fadenkreuze, GPU-Leistungsmetriken, Skins für Video-Streaming ...

## Mindestversionen von GPU-Treibern

Im Folgenden finden Sie eine Liste der erforderlichen Mindestversionen von GPU-Treibern, damit die Anwendung problemlos ausgeführt werden kann. Diese Liste kann sich mit der Veröffentlichung neuer Versionen ändern.

Informationen zum Herunterladen neuer Treiber finden Sie unter: [GPU hat veraltete Treiber](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers).

| Betriebssystem | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro/FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04 oder höher *oder* 535.54.03 oder höher | Radeon 23.20 Pro 23.Q3 | Nicht unterstützt |

>[!NOTE]
>
> Unter **Mac OS** wird der GPU-Treiber vom Betriebssystem selbst bereitgestellt. Aktualisieren Sie auf die neueste Version Ihres Betriebssystems, um auf den neuesten Treiber zuzugreifen.

## Sprachen

Die Software-Benutzeroberfläche ist in den folgenden Sprachen verfügbar:

* English
* Deutsch
* Français
* 日本語
* Koreanisch
* 中文
* Italienisch
* Portugiesisch
* Spanisch
