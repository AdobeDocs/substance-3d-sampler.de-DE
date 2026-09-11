---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/color-replace.html"
breadcrumb-title: ''
description: Verwenden Sie den Filter "Farbe ersetzen" in Substance 3D Sampler, um bestimmte Farben in Texturen durch neue Farbwerte zu ersetzen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Replace
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Farbe ersetzen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '570'
ht-degree: 0%

---


# Farbe ersetzen

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-replacecolor-18-n-d.png)

**In:** Korrekturen

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Ausgewählte Farbe oder Wert in einem Kanal ersetzen.

Die folgenden Bilder zeigen **Color Replace** in Aktion. Beachten Sie, dass die Bereiche zwischen den Kacheln dieselbe Farbe aufweisen - nur die Kacheln selbst werden geändert.

![](../../assets/3d-2d-filters-cropped-0051-color-replace-in.jpg)![](../../assets/3d-2d-filters-cropped-0050-color-replace-out.jpg)

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Erweiterte Segmentierung**: Knebel\
  Wenn diese Option aktiviert ist, kann der Filter einen separaten Kanal verwenden, um Maskeninformationen aus dem Kanal zu generieren, der vom Farbaustausch betroffen ist.
  * **Maske** **Von**:\
    Wählen Sie einen Kanal aus, der als Quelle für die Maskengenerierung dient. Beispiel: Maske aus dem metallic Wert ersetzt die Grundfarbe der metallic Bereiche des Materials
* **Ersetzen in**:\
  Wählen Sie den Kanal aus, auf den sich die Farbersetzung auswirkt.
* **Zielfarbe**: Farbauswahl\
  Wählen Sie die Farbe aus, die die aktuellen Kanalfarben ersetzen soll.
* **Luminanzvariation**: 0-1\
  Passen Sie an, wie stark die ursprüngliche Luminanz durch die Luminanz der neuen Farbe beeinflusst wird.
* **Maskenbereich**\
  Die Maske wird basierend auf der Kombination der folgenden Werte erstellt
  * ****** Von Luminanz **: 0-1\
    Der Luminanzbereich, der zum Erstellen der Maske verwendet wird ****
  * **Von Farbe**: 0-1\
    Der zum Erstellen der Maske verwendete Farbbereich
* **Smoothness maskieren**: 0-1\
  Anpassen der Granularität der Maske
* **Maske weichzeichnen**: 0-1\
  Weichzeichnen der Maske

**Maske**

Diese Maske unterscheidet sich von der unter **Basisparameter** erstellten Maske. Sie können zum Malen eine benutzerdefinierte Maske verwenden oder ein Bild verwenden, um die Bereiche anzugeben, die vom **Farbaustausch**-Filter als Ganzes betroffen sein sollen.

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um eine benutzerdefinierte Maske direkt in die 2D-Ansicht Malen
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Weichzeichnen der Maske
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Maske umkehren.

## Benutzerhandbuch

Der **Farbersetzungsfilter** ist eine leistungsstarke Möglichkeit, das Erscheinungsbild Ihrer Materialien zu ändern - z. B. um Eisen-Rost in oxidiertes Kupfer umzuwandeln

Der Filter erstellt zunächst eine Maske basierend auf den Luminanz- und Farbwerten eines ausgewählten Punkts und ersetzt dann die Farbe des Bereichs, der durch diese Maske definiert ist. So verwenden Sie den Filter:

1. Fügen Sie dem Ebenenstapel den **Farbersetzungsfilter** hinzu.
1. Legen Sie fest, welchen Kanal Sie zum Erstellen der Maske verwenden möchten und welchen Kanal Sie ersetzen möchten.
   1. Wenn Sie die Maske auf einem Kanal basieren, aber die Farbe eines anderen Kanals ersetzen möchten, aktivieren Sie **Erweiterte Segmentierung** und wählen Sie die entsprechenden Kanäle aus.
   1. Wenn Sie die Maske auf einem Kanal basieren und die Farbe desselben Kanals ersetzen möchten, lassen Sie **Erweiterte Segmentierung** deaktiviert.
1. Bewegen Sie das Steuerelement in der **2D-Ansicht** über die Farbe, die Sie ersetzen möchten.
1. Passen Sie mithilfe der Steuerelemente **Maskenbereich**, **Maskenmaske** und **Maskenunschärfe** an, welche Bereiche die Smoothness verdeckt.
1. Wählen Sie eine **Zielfarbe** aus und passen Sie die **Luminanzvariation** an, bis Sie mit dem Effekt zufrieden sind.
1. Optional können Sie eine benutzerdefinierte Maske hinzufügen, um die Effekte des Filters nur auf die ausgewählten Bereiche anzuwenden. Die benutzerdefinierte Maske wirkt sich nicht auf die in Schritt 1 erstellte Maske aus, sondern ist eine zusätzliche Maske, mit der Sie die Anwendungsbereiche des Effekts weiter anpassen können.

Manchmal kann es nützlich sein, mehrere **Farbersetzungsfilter** übereinander zu verwenden, um komplexere Effekte zu erstellen.
