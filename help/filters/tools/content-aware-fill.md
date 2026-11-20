---
title: Inhaltsbasierte Füllung
description: Erfahren Sie, wie Sie den Filter "Inhaltsbasierte Füllung" in Substance 3D Sampler verwenden, um Probleme mit sich wiederholenden Mustern zu beheben oder unerwünschten Dirt oder Schmutz zu entfernen.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 1%
---

# Inhaltsbasierte Füllung

<table>
  <tr>
    <td><img src="../../assets/Filters/S_ContentAwareFill_18_N_D.png" alt=""/><br><strong>In:</strong> Tools</td>
    <td>Beschreibung<br>Die inhaltsbasierte Füllung ermöglicht das nahtlose Entfernen von Elementen wie Dirt, Text oder anderen unerwünschten Objekten aus Ihren Materials.<br>Im Beispiel für den Waldboden unten hebt sich der Stock durch das sich wiederholende Muster hervor. Mit der Funktion "Inhaltsbasierte Füllung" lässt sich der Zweig entfernen, sodass sich die Wiederholung etwas weniger bemerkbar macht. <br><br><img src="../../assets/content-aware-fill-before.png" alt=""/><br><em>Vor dem Entfernen</em><br><br><img src="../../assets/content-aware-fill-after.png" alt=""/><br><em>Nach dem Entfernen</em></td>
  </tr>
</table>

## Parameter

* **Kanalauswahl:** Wählen Sie aus, auf welchen Kanälen der Filter ausgeführt werden soll. Standardmäßig ist dies auf alle Kanäle festgelegt. Sie können jedoch auch festlegen, dass die Anwendung nur auf dem Height oder in den Grundfarbe-Kanälen ausgeführt wird.
* **Spiegeln:** Bei symmetrischen Materialien oder Mustern wird die inhaltsbasierte Füllung durch diese Einstellung so geleitet, dass sie gespiegelten Inhalt im gesamten Material einbezieht.
* **Skalierung:** Bei geometrischen Mustern wie Kacheln oder Ziegeln kann diese Einstellung dazu beitragen, die Strukturierung des Musters beizubehalten.

### Technische Parameter

* **Benutzerdefinierte Maske:** Wenden Sie eine Maske mithilfe einer Textur an oder verwenden Sie den Pinsel, um Ihre eigene Maske im **2D-Viewport** Malen.
* **Crop-Faktor suchen:** Schneiden Sie den vom Filter verwendeten Beispielbereich zu. Standardmäßig deckt der Beispielbereich die gesamte Textur ab, mit Ausnahme des maskierten Bereichs. Wenn Sie den **Freistellungsfaktor für die Suche** erhöhen, verringert sich der Beispielbereich, wodurch die Samples auf Pixel beschränkt werden können, die näher am maskierten Bereich liegen.

### Fülleinstellungen

* **Farbanpassung:** Passen Sie an, wie sehr sich die Füllung an die umgebenden Farben anpasst. Diese Einstellung kann bei Materialien nützlich sein, die
* **Drehungsanpassung:** Bei Mustern, bei denen die Drehung von Elementen wichtig ist, z. B. bei den Blütenblättern einer Blume oder den Speichen eines Rades, kann diese Einstellung dazu beitragen, einheitlichere Ergebnisse zu erzielen.