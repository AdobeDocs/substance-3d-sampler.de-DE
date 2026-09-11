---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/auto-tiling.html"
breadcrumb-title: ''
description: Mit dem Tool zur automatischen Kachelung in Substance 3D Sampler lassen sich mithilfe von KI-Technologie aus Texturen automatisch nahtlose Muster für Kachelungen erstellen.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Automatische Kachelung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '575'
ht-degree: 0%

---


# Automatische Kachelung

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Der <b>Filter für die automatische Kachelung</b> sucht nach sich wiederholenden Strukturen in Ihrem Material und verwendet sie zum Erstellen eines Materials für die Kachelung. Im Gegensatz zum Kachelfilter <b>Kachelfilter erstellen</b> oder dem Filter <b>Kachelung filtern</b> konzentriert sich <b>Automatische Kachelung</b> darauf, den kleinsten Bereich des Materials zu isolieren, der als Kachel erstellt werden kann.

<b>Die automatische Kachelung </b> ist besonders für Textilien nützlich.

</td>
</tr>
</table>

>[!NOTE]
>
> Damit der Filter &quot;Automatische Kachelung&quot; funktioniert, sind mindestens 3x3 Wiederholungen im Quellbild oder Material erforderlich.

## Filter mit automatischer Kachelung

## Automatische Kachelung

Wenn Sie ihn Ihrem Ebenenstapel hinzufügen, versucht <b>Automatische Kachelung</b> automatisch, sich wiederholende Muster zu finden und ein Kachelung-Material zu generieren. Wenn dies nicht erfolgreich ist, können Sie die Schaltfläche <b>Erweiterte Einstellungen </b> verwenden, um den Prozess manuell anzupassen.

Wenn Sie ein Kachelung-Material aus einem Image erstellen möchten, sollten Sie zuerst den <b>Filter für die automatische Kachelung</b> verwenden und dann das <b>Image zum Materialfilter</b> verwenden.

<b>Die automatische Kachelung </b> wird vollständig auf Ihrem Gerät ausgeführt. Es wird kein Inhalt an die Cloud gesendet.

## Parameter

Im Gegensatz zu den meisten Filtern verfügt <b>die automatische Kachelung </b> nicht über Parameter. Stattdessen gibt es eine Schaltfläche <b>Erweiterte Einstellungen </b>, mit der Sie den Prozess der Konfiguration des Filters durchlaufen können. Sie müssen nicht für jeden Schritt manuelle Anpassungen vornehmen. Sie können vorwärts oder rückwärts springen, indem Sie einen Schritt oben im Fenster auswählen.

Dieser Vorgang umfasst die folgenden Schritte:

1. <b>Einführung</b>: Erläutert die Funktionsweise des Filters. Verwenden Sie das Kontrollkästchen, um diesen Bildschirm in Zukunft auszublenden.
1. <b>Kartenauswahl</b>: Wählen Sie den Kanal aus, den der Filter verwenden soll. Es wird empfohlen, den Kanal mit dem sichtbarsten Wiederholungsmuster zu verwenden. Dies ist normalerweise der Grundfarbe- oder der Height-Kanal, aber je nach Material können auch andere Kanäle hilfreich sein.
1. <b>Beispieleinstellungen</b>: Nehmen Sie Änderungen am Eingabe-Material vor, um die besten Ergebnisse zu erzielen. Dazu gehören das Auswählen einer Auflösung und das Drehen oder Verformen der Eingabe. Wenn dein Muster sehr klein ist, kann es nützlich sein, eine höhere Auflösung auszuwählen, um sicherzustellen, dass das Muster sichtbar ist. Bei größeren Mustern kann eine niedrigere Auflösung jedoch bessere und schnellere Ergebnisse liefern.
1. <b>Mustergröße</b>: In diesem Schritt sucht der Filter nach dem kleinsten verfügbaren Muster. Sie können zwischen einer größeren und kleineren automatischen Erkennung wählen oder eine benutzerdefinierte Größe auswählen, um Ihre eigene Größe anzugeben. Um optimale Ergebnisse zu erzielen, wählen Sie die kleinste Größe aus, bei der das Muster einmal pro Feld wiederholt wird.\
   Wenn alle Felder unregelmäßig geformt sind und nicht dem Muster zu entsprechen scheinen, verwenden Sie die benutzerdefinierte Größe, um regelmäßigere Ergebnisse zu erhalten.
1. <b>Mustererkennung</b>: Positionieren Sie die Punkte so, dass sich jeder Punkt an derselben Position im Muster befindet. Wenn Sie beispielsweise ein Schwarz-Weiß-Schachbrettmuster verwenden, sollten die Punkte in der Mitte der schwarzen Quadrate liegen.
1. <b>Fokusbereich</b>: Wählen Sie den Bereich des Materials aus, in dem das endgültige Muster erstellt werden soll. Wenn Sie einen größeren Bereich verwenden, wird die sichtbare Wiederholung reduziert. Die Verwendung von Bereichen mit Artefakten oder sichtbaren Beleuchtungsunterschieden kann jedoch die sichtbare Wiederholung verstärken.
1. <b>Entfernen der Naht</b>: Passen Sie die Einstellungen an, um die Sichtbarkeit der Naht zu minimieren. <b>Die Smoothness &quot;</b>&quot; beschneiden steuert, wie glatt die Linie der Naht ist, während die Überblendung &quot;<b>&quot; der Breite &quot;</b>&quot; die Naht zwischen den Kacheln verwischt.

Nachdem Sie alle Schritte ausgeführt haben, bestätigen Sie Ihre Auswahl mit <b>Anwenden</b>. Der Filter <b>Automatische Kachelung</b> verarbeitet das Material, um ein Endergebnis zu generieren.
