---
title: Empfohlene Verfahren beim Scannen
description: Erfahren Sie, wie Sie Ihre physischen Proben vor dem Scannen mit HP Z Captis vorbereiten und platzieren, um Zeit bei der Nachbearbeitung in Substance 3D Sampler zu sparen.
source-git-commit: a0034da3bee13d0d7423828a902da62cf2219474
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 0%

---


# Best Practices zum Scannen

Die Qualität eines digitalisierten Materials wird lange vor dem Drücken der Scan-Taste bestimmt. Mit einer sauberen, ebenen, gut platzierten Probe werden gebrauchsfertige saubere Karten erstellt, während bei einer übereilten Aufnahme jede Falte, jeder Dust-Fleck und jede Streufaser direkt in Ihre PBR-Kanäle geleitet werden.

Die Faustregel ist einfach: **Eine zusätzliche Minute für die Vorbereitung Ihres Materials vor dem Scan spart Ihnen ca. 10 Minuten für die spätere Bereinigung**. Die Zeit, die Sie mit dem Bügeln eines Stoffs, dem Wegstreichen von Dust oder dem Ausrichten Ihrer Probe verbringen, ist die Zeit, die Sie nicht damit verbringen werden, später das Material zu entformen, Partikeln auszubessern oder lose Fasern zu entfernen.

Diese Seite behandelt zwei Bereiche, die den größten Unterschied machen: **das physische Beispiel vorbereiten** und **es richtig platzieren** auf dem Gerät.

## Physische Probe vorbereiten.

Alles, was beim Aufnehmen auf der Probe sichtbar ist, wird in die Karten Baking geführt. Einige Minuten Vorbereitung entfernen Probleme an der Quelle, bevor sie zur Bearbeitung werden.

**Beispiel bereinigen**

Geben Sie der Probe eine schnelle Reinigung, bevor Sie sie platzieren. Jede Markierung auf der Oberfläche wird als Material-Detail interpretiert und auf jedem Kanal wiedergegeben.

**Dust und ausländische Partikeln entfernen**

Dust, Haare, Fäden und andere lose Partikeln gehören zu den häufigsten Nachbearbeitungsquellen. Bürsten oder verwenden Sie Druckluft, um die Oberfläche zu reinigen, da jede zurückgelassene Partikel später von Hand ausgemalt werden muss.

![](../../assets/scanning/clean-textile.png)

**Eisengewebe zum Entfernen von Falten**

Bei Geweben und anderen biegsamen Materialien muss die Probe vor dem Scannen immer flach gebügelt werden. Falten erzeugen falsche Height- und Schatteninformationen, die sich später nur schwer entfernen lassen und die Kachelbarkeit des Materials beeinträchtigen.

![](../../assets/scanning/flatten-textile.png)

**Flecken von glatten Oberflächen entfernen**

Wischen Sie auf glatten, nicht porösen Materialien Flecken, Fingerabdrücke oder Verschmutzungen ab. Diese werden in den Grundfarbe- und Rauheit-Kanälen deutlich sichtbar.

**Kennen Sie die Beispiel-Thickness**

Achten Sie darauf, wie dick Ihre Probe ist. Wenn du die Thickness kennst, kannst du sie leichter richtig platzieren und die Aufnahme so einrichten, dass die Oberfläche über den gesamten Scanbereich im Fokus bleibt.

## Das Muster richtig platzieren.

Eine gute Platzierung sorgt dafür, dass das Material flach, scharf und zentriert bleibt. Dadurch verringert sich der Grad der Zuschneidung, Entformung und Ausrichtung, den Sie später vornehmen müssen.

![](../../assets/scanning/center-textile.png)

**Material im Scanbereich zentrieren**

Positionieren Sie die Probe in der Mitte des Scanbereichs. An dieser Stelle sind Fokus und Beleuchtung am gleichmäßigsten und du erhältst die brauchbarste Oberfläche, sobald das Material zugeschnitten ist. Deshalb ist es immer ideal, jeweils ein Muster zu scannen, sodass es in der Mitte des Scanbereichs platziert werden kann und Ihnen die bestmöglichen Ergebnisse liefert.

**Richten Sie sie so gerade wie möglich aus**

Richten Sie die Probe nicht in einem Winkel, sondern exakt mit dem Scanbereich aus. Ein gerades Muster lässt sich wesentlich einfacher kacheln und benötigt weniger Drehung und Zuschnitt in Sampler.

**Beispiel flach halten**

Stellen Sie sicher, dass die Probe vollständig flach auf der Scanfläche liegt. Verwenden Sie bei Bedarf die Magnete, die mit dem HP Z Captis-Gerät mitgeliefert werden, um biegsame oder rollende Material an Ort und Stelle zu halten. Ein flaches Muster vermeidet Verformungen und ungleichmäßige Fokussierungen, die sonst zeitaufwendig zu korrigieren sind.

**Beispiele nicht überlappen**

Wenn Sie mehrere Samples auf einmal platzieren, lassen Sie sie sich nicht berühren oder überlappen. Überlappende Kanten erzeugen mehrdeutige Begrenzungen, die sich nur schwer trennen lassen und später sauber zuschneiden.

## Der Lohn in Sampler

Wenn die Farben in Sampler sauber, eben und zentriert sind, sind die Karten bereits fast produktionsbereit. Sie verbringen Ihre Zeit damit, das Material zu verfeinern, anstatt es zu reparieren: weniger Zeit zum Entformen, weniger Zeit zum Reinigen von Dust und Fasern und weniger Zeit zum Entfernen von Flecken und Falten aus deinen Kanälen.

Sobald dein Material importiert wurde, verwende Sampler-Filter (Ausgleichen, Automatische Kachelung, Perspektive zuschneiden, Kachelung, ...) für die letzten Feinanpassungen und exportiere, wenn du mit dem Ergebnis zufrieden bist.
