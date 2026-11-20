---
description: Lesen Sie die Versionshinweise für Substance 3D Sampler 6.1, um mehr über die neuen Funktionen, Verbesserungen und Arbeitsablaufverbesserungen zu erfahren.
title: Version 6.1
hold: true
source-git-commit: 038e30bc03e8fc8f3165cb5c84680495d8af718f
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 1%
---

# Leistungsmodus

Im Leistungsmodus werden alle Einstellungen zusammengefasst, die Ihren Arbeitsablauf verlangsamen können: Auflösungsgrenzen, Schatten, Versatz-Qualität und Pfadverfolgung. Deaktiviere alle Funktionen, die du nicht brauchst, und sichere dir die gewünschte Reaktionsgeschwindigkeit, insbesondere bei kleinerer Hardware.

>[!NOTE]
>
> Wenn Ihre Hardware die [Mindestanforderungen](../getting-started/system-requirements.md) von Sampler nicht erfüllt, wird Sampler automatisch im [Spezifikationsmodus mit niedriger Auflösung](low-spec-mode.md) gestartet, der sich wie der Leistungsmodus verhält, ohne dass Sie die Einstellungen ändern können.

## Leistungsmodus umschalten

Der Leistungsmodus kann mit der Schaltfläche **Leistungsmodus** oben rechts im **Sampler-Fenster** umgeschaltet werden.

![](../assets/performance-mode-button.png)

## Ändern der Einstellungen für den Leistungsmodus

Verwenden Sie das Dropdown-Menü neben der Schaltfläche für den **Leistungsmodus**, um die durch den Leistungsmodus aktivierten Grenzwerte zu steuern.

![](../assets/performance-mode-settings.png)

| Einstellung | Beschreibung |
| --- | --- |
| **Maximale Vorschauauflösung** | Der Leistungsmodus senkt die Vorschauauflösung, um ein schnelleres Rendering zu ermöglichen. Die Auflösung importierter Elemente oder des Dokuments wird dadurch nicht geändert. Dadurch wird die Qualität des Viewport-Renderers geändert. |
| **Qualität des Versatzes deaktivieren** | Wenn diese Einstellung aktiviert ist, sperrt **Leistungsmodus** den **Versatz-Qualitätswert** auf 0 und deaktiviert den Versatz-Effekt im Viewport. Bei glatten Materialien wie Fliesen oder feinen Geweben hat dies nur minimale optische Auswirkungen, kann aber die Leistungsfähigkeit wesentlich verbessern. |
| **Schatten deaktivieren** | Mesh und verschobene Materialien können Schatten Geworfen, sodass ein realistischeres Bild entsteht, und das auf Kosten der Performance. Wenn **Schatten deaktivieren** aktiviert ist, deaktiviert der Leistungsmodus die gesamte Schattenverarbeitung und verbessert so die Leistung. |
| **Pfadverfolgung deaktivieren** | Die Pfadverfolgung ist eine leistungsstarke Rendermethode, die Lichtpfaden folgt, während sie durch die Szene reflektiert werden, sodass fotorealistische Renderings entstehen. Das Nachzeichnen von Pfaden ist jedoch sehr kostspielig. Wenn **Pfadverfolgung deaktivieren** aktiviert ist, deaktiviert der Leistungsmodus die Option zum Aktivieren der Pfadverfolgung im **3D-Viewport**. |

>[!NOTE]
>
> Auf die Pfadverfolgung kann über die **3D-Viewport-Symbolleiste** zugegriffen werden.
>
> ![](../assets/enable-path-tracing.png)
>
> Wenn die Pfadverfolgung nicht aktiviert ist, hat das Aktivieren des Leistungsmodus, bei dem nur **Pfadverfolgung deaktivieren** aktiviert ist, keine Auswirkungen.