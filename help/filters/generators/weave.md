---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/weave.html"
breadcrumb-title: ''
description: Verwenden Sie den Webgenerator in Substance 3D Sampler, um Webmuster und textile Texturen für die Erstellung von Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Weave
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Weben
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '756'
ht-degree: 0%

---


# Weben

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem Filter &quot;Weben&quot; können Sie Bilder in Webmuster konvertieren.

</td>
</tr>
</table>

## Parameter

**Vorgaben**

Vorgaben verwenden, um schnell Parameter zu ändern und verschiedene Webstile anzuzeigen

**Basisparameter**

* **Zufallsparameter**:\
  Die Zufallsgeschwindigkeit, auf der alle anderen Zufallsparameter in diesem Filter basieren.
* **Image**: Bild/Pinsel\
  Wählen Sie ein Bild oder eine Malen direkt in der **2D-Ansicht** aus. Der **Webfilter** funktioniert am besten, wenn ein Bild ausgewählt ist.
* **Farbanzahl**: 1-10\
  Der **Webfilter** unterteilt die Bildeingabe automatisch in eine Anzahl von Farben, basierend auf diesem Parameter. Die Parameter jeder Farbe können unabhängig voneinander gesteuert werden.
* **Bereichsgröße (cm)**: 2-50\
  Ändern Sie die Physische Größe, die durch den 2D-Raum dargestellt wird. Dadurch wird die Anzahl der Maschen geändert, die verwendet werden, um das Eingabebild neu zu erstellen.
* **Dichte (Nähte pro cm)**: 1-105\
  Arbeitet mit dem Steuerelement **Bereichsgröße (cm)**, um die Anzahl der Maschen im 2D-Raum anzupassen.
* **Globale Rauheit**: 0-1,0\
  Rauheit des Materials anpassen
* **Schussfarbmodus**:\
  Wählen Sie aus, ob der Schussfaden anhand der Bildeingabe oder anhand benutzerdefinierter Farbauswahlen gefärbt wird. Wenn **Überschreiben pro Farbe** ausgewählt ist, wird ein zusätzlicher **Farbe**-Parameter in jeder Farbe angezeigt.

**Farbe X**

Die Anzahl der zu ändernden Farben hängt von **Grundlegende Parameter > Farbanzahl** ab.

* **Farbe**: Farbauswahl\
  Nur verfügbar, wenn **Basisparameter > Schussfarbenmodus** auf **Überschreiben pro Farbe** festgelegt ist. Wählen Sie die Farbe des Materials für diesen Abschnitt.
* **Rahmengröße**: 0-1\
  Fügt einen Rahmen an den Rändern der ausgewählten Farbe hinzu. Die Umrandung erhöht die Länge des Schussfadens zwischen den Kettfäden nahe der Farbkante, sodass Kettstiche nicht in der Nähe der Farbensätze erscheinen.
* **Rauheiten-Offset**: 0-1\
  Rauheit für diesen Farbsatz ändern
* **Metallic**: 0-1\
  Den metallic Wert für diesen Farbsatz ändern
* **Height-Position**: 0-1\
  Passen Sie das Height dieses Farbsatzes an. So verleihst du der Webversion deines Fotos mehr Tiefe.

**Erweitert**

* **Verkrümmungsfarbe**: Farbauswahl\
  Ändern Sie die Farbe der Kettfäden (Standardmäßig verlaufen die Kettfäden senkrecht zu den Fäden, die am meisten sichtbar sind.)
* **Verkrümmen - Schusswechsel**:\
  Tauschen Sie die Kettfäden und die Schussfäden aus. Dadurch werden die Maschen um 90 Grad gedreht,
* **Verkrümmungswellen**: 1-16\
  Passen Sie die relative Häufigkeit von Kettfäden auf Schussfäden an. Kann verwendet werden, um verschiedene Jacquardmuster zu erstellen.
* **Verkrümmungsgröße**: 0-1\
  Die Kettfäden dicker oder dünner machen
* **Intensität der Height-Differenz-Weichzeichnung**: 0-1\
  Steuern Sie die Steigung oder Unschärfe, die durch **Unterschiede bei der Height-Position** verursacht wird. Dies hat keine Auswirkungen, es sei denn, Sie ändern den Regler **Height-Position** für mindestens einen Farbsatz.

## Benutzerhandbuch

Der Weave-Filter kann zunächst etwas verwirrend sein, aber mit ein paar wichtigen Parametern werden Sie schon bald komplexe Webarten erstellen, die Sie zu Ihren Materials hinzufügen können.

>[!NOTE]
>
> Wenn Sie den [Stickerei](embroidery.md)filter zuvor verwendet haben, funktioniert der Webfilter ähnlich. Sie erzeugen verschiedene Effekte, aber du kannst Bilder auf die gleiche Weise verwenden.
> 
> Webbilder sollten quadratische Proportionen, eine hohe Auflösung (mindestens 2K) und höchstens 10 verschiedene Farben aufweisen. Mit dem Alpha- oder Transparenzkanal können Formen ausgeschnitten werden. Idealerweise sind sie vektorbasiert, werden aber als PNG-Bitmap exportiert.

So verwenden Sie den Webfilter:

1. Ziehen und Ablegen eines Bildes in
1. Wende den Webfilter auf deinen Ebenenstapel an.
1. Passen Sie **Grundlegende Parameter > Farbanzahl** an, bis die Farbbalance für Ihr Bild korrekt aussieht. Bei einer Begrenzung auf 10 Farben funktioniert der Weave-Filter am besten mit Flächenfarben und illustrierten Bildern.
1. Passen Sie weitere Parameter an, um das Erscheinungsbild des Patches zu optimieren.

Dies sind die Grundlagen zur Verwendung des Weave-Filters.

Es ist möglich, transparente Bilder im Webfilter zu verwenden, aber standardmäßig wirken sich diese auch auf die Deckkraftmap Ihres Materials aus - transparente Bildbereiche machen das Material auch transparent. Um mit dem Filter &quot;Weben&quot; ein Ausbessern zu erstellen und es über den Ebenen darunter liegen zu lassen, verwenden Sie den Filter &quot;Aufkleber&quot;.

1. Erstellen Sie einen Aufkleberfilter.
1. Fügen Sie den Weave-Filter zum Eingangssteckplatz des Decal-Filters hinzu.
1. Führen Sie die normalen Schritte aus, um das Muster anzupassen.

Die Ebene &quot;Decal&quot; konvertiert die Webeingabe in einen Decal. Die Transparenz der Ebene &quot;Weave&quot; weist die Ebene &quot;Decal&quot; an, wie das Muster maskiert werden soll. Mit der Decal-Ebene kannst du das Muster auch auf deinem Material verschieben oder Funktionen wie Kachelung aktivieren.
