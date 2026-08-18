---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/auto-tiling.html"
breadcrumb-title: ''
description: Nutze das Kachelwerkzeug in Substance 3D Sampler, um mithilfe von KI-Technologie automatisch nahtlose Kachelmuster aus Texturen zu erstellen.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Automatisches Kacheln
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

Der <b>Filter zum automatischen Kacheln</b> sucht nach sich wiederholenden Strukturen in Ihrem Material und verwendet sie zum Erstellen eines Kachelmaterials. Im Gegensatz zum Kachelfilter &quot;<b>Make it tile filter</b>&quot; oder dem Kachelfilter &quot;<b>Tiling filter</b>&quot; konzentriert sich <b>Auto Tiling</b> darauf, den kleinsten Bereich des Materials zu isolieren, der als Kachel angefertigt werden kann.

<b>Die automatische Kachelung </b> ist besonders für Textilien nützlich.

</td>
</tr>
</table>

>[!NOTE]
>
> Damit der automatische Kachelfilter funktioniert, sind mindestens 3x3 Wiederholungen im Quellbild oder -material erforderlich.

## Tutorial zum automatischen Anordnen von Filtern

## Allgemeines zu automatischer Kachelung

Wenn Sie ihn Ihrem Ebenenstapel hinzufügen, versucht <b>Auto Tiling</b> automatisch, sich wiederholende Muster zu finden und ein Kachelmaterial zu generieren. Wenn dies nicht erfolgreich ist, können Sie die Schaltfläche <b>Erweiterte Einstellungen </b> verwenden, um den Prozess manuell anzupassen.

Wenn Sie ein Kachelmaterial aus einem Bild erstellen möchten, ist es besser, zuerst den <b>Filter für automatische Kachelung</b> zu verwenden und dann den <b>Filter &quot;Bild zu Material&quot;</b> zu verwenden.

<b>Die automatische Kachelung</b> wird vollständig auf Ihrem Gerät ausgeführt. Es wird kein Inhalt an die Cloud gesendet.

## Parameter

Im Gegensatz zu den meisten Filtern verfügt &quot;<b>Auto Tiling</b>&quot; nicht über Parameter. Stattdessen gibt es eine Schaltfläche <b>Erweiterte Einstellungen </b>, mit der Sie den Prozess der Konfiguration des Filters durchlaufen können. Sie müssen nicht für jeden Schritt manuelle Anpassungen vornehmen. Sie können vorwärts oder rückwärts springen, indem Sie einen Schritt oben im Fenster auswählen.

Dieser Vorgang umfasst die folgenden Schritte:

1. <b>Einführung</b>: Erläutert die Funktionsweise des Filters. Verwenden Sie das Kontrollkästchen, um diesen Bildschirm in Zukunft auszublenden.
1. <b>Kartenauswahl</b>: Wählen Sie den Kanal aus, den der Filter verwenden soll. Es wird empfohlen, den Kanal mit dem sichtbarsten Wiederholungsmuster zu verwenden. Das ist normalerweise der Grundfarben- oder der Height-Kanal, aber je nach Material können auch andere Kanäle hilfreich sein.
1. <b>Beispieleinstellungen</b>: Nehmen Sie Änderungen am Eingabematerial vor, um die besten Ergebnisse zu erzielen. Dazu gehören das Auswählen einer Auflösung und das Drehen oder Verformen der Eingabe. Wenn dein Muster sehr klein ist, kann es nützlich sein, eine höhere Auflösung auszuwählen, um sicherzustellen, dass das Muster sichtbar ist. Bei größeren Mustern kann eine niedrigere Auflösung jedoch bessere und schnellere Ergebnisse liefern.
1. <b>Mustergröße</b>: In diesem Schritt sucht der Filter nach dem kleinsten verfügbaren Muster. Sie können zwischen einer größeren und kleineren automatischen Erkennung wählen oder eine benutzerdefinierte Größe auswählen, um Ihre eigene Größe anzugeben. Um optimale Ergebnisse zu erzielen, wählen Sie die kleinste Größe aus, bei der das Muster einmal pro Feld wiederholt wird.\
   Wenn alle Felder unregelmäßig geformt sind und nicht dem Muster zu entsprechen scheinen, verwenden Sie die benutzerdefinierte Größe, um regelmäßigere Ergebnisse zu erhalten.
1. <b>Mustererkennung</b>: Positionieren Sie die Punkte so, dass sich jeder Punkt an derselben Position im Muster befindet. Wenn Sie beispielsweise ein Schwarz-Weiß-Schachbrettmuster verwenden, sollten die Punkte in der Mitte der schwarzen Quadrate liegen.
1. <b>Fokusbereich</b>: Wählen Sie den Bereich des Materials aus, der zum Erstellen des endgültigen Musters verwendet werden soll. Wenn Sie einen größeren Bereich verwenden, wird die sichtbare Wiederholung reduziert. Die Verwendung von Bereichen mit Artefakten oder sichtbaren Beleuchtungsunterschieden kann jedoch die sichtbare Wiederholung verstärken.
1. <b>Nahtentfernung</b>: Passen Sie die Einstellungen an, um die Nahtsichtbarkeit zu minimieren. <b>Die Schnittbreite </b> steuert, wie glatt die Smoothness der Naht ist, während <b>Die Schnittbreite </b> die Naht zwischen den Kacheln verwischt.

Nachdem Sie alle Schritte ausgeführt haben, bestätigen Sie Ihre Auswahl mit <b>Anwenden</b>. Der Filter <b>Automatische Kachelung</b> verarbeitet das Material, um ein Endergebnis zu generieren.
