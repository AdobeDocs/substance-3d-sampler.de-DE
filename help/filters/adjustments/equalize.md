---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/adjustments/equalize.html"
breadcrumb-title: ''
description: Mit dem Filter "Tonwertangleichung" in Substance 3D Sampler lassen sich Helligkeitswerte automatisch verteilen und der Bildkontrast erhöhen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Equalize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tonwertangleichung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---


# Tonwertangleichung

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-equalize-18-n-d.png)

**In:** Korrekturen

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Der Equalize-Filter passt den lokalen Kontrast basierend auf einem Abstandsbereich an. Ziel des Equalize-Filters ist es, große Unterschiede in jedem Kanal zu reduzieren. Daher ist es in der Regel als Teil des Arbeitsablaufs &quot;Bild zu Material&quot; (B2M) nützlich - der Filter &quot;Bild zu Material&quot; (KI-basiert) enthält einen Entzerrungsdurchgang innerhalb des Filters, um die Ergebnisse zu verbessern.

Die folgenden Bilder zeigen den **Filter zum Ausgleichen** in Aktion.

![](../../assets/3d-2d-filters-cropped-0033-equalizer-in.jpg)

Bevor der **Equalize-Filter** hinzugefügt wurde, gibt es erhebliche Unterschiede zwischen der Materialzuordnung und der Grundfarbe dieses Heights.

![](../../assets/3d-2d-filters-cropped-0032-equalizer-out.jpg)

Nachdem der **Filter zum Entzerren** hinzugefügt wurde, sind sowohl die Height-Map als auch die Grundfarbkanäle einheitlicher, ohne dass Details verloren gehen.

</td>
</tr>
</table>

## Filterausgleichsübung

## Parameter

<b>Basisparameter</b>

* <b>Eingabetabelle</b>: Knebel\
  Wenn diese Option aktiviert ist, behandeln Sie das Material so, als ob es wiederholt gekachelt ist. Daher werden geänderte Nahbereiche durch Farbwerte auf der gegenüberliegenden Seite beeinflusst.
* <b>Radius</b>: 0-1\
  Verteile den Effekt &quot;Tonwertangleichung&quot; über einen größeren Bereich.
* <b>Farbausblutung</b>: 0-1\
  Lege fest, welche Farben in die Umgebung verlaufen.
* <b>Lokale Details</b>: 0-1\
  Passen Sie an, wie der Filter &quot;Tonwertangleichung&quot; versucht, lokale Details beizubehalten.

<b>*Kanal*</b>

Die Steuerelemente für die einzelnen Kanäle funktionieren auf die gleiche Weise.

* <b>Allgemeine Parameter überschreiben</b>: Knebel\
  Aktivieren Sie diese Option, um den Effekt &quot;Tonwertangleichung&quot; für diesen Kanal anzupassen. Wenn diese Option aktiviert ist, werden zusätzliche Steuerelemente angezeigt:
  * <b>Eingabetabelle</b>: Knebel\
    Wenn diese Option aktiviert ist, behandeln Sie das Material so, als ob es wiederholt gekachelt ist. Daher werden geänderte Nahbereiche durch Farbwerte auf der gegenüberliegenden Seite beeinflusst.
  * <b>Radius</b>: 0-1\
    Verteile den Entzerrungseffekt über einen größeren Bereich.
  * <b>Lokale Unterschiede beibehalten</b>: Knebel\
    Aktivieren Sie diese Option, damit der Entzerrungseffekt mit einer höheren Auflösung funktioniert, um Details beizubehalten.
* <b>Zielmodus</b>:\
  Legen Sie fest, wie der Effekt &quot;Tonwertangleichung&quot; beeinflusst werden soll. Standardmäßig versucht die Entzerrung, Farben zur Durchschnittsfarbe des Kanals zu verschieben. Verwenden Sie den Parameter, um einen Verzerrungseffekt zu einer ausgewählten Farbe oder einem ausgewählten Wert zu erzeugen. Wenn Parameter ausgewählt ist, wird ein zusätzliches Steuerelement angezeigt:
  * <b>Ziel</b>: Farbauswahl\
    Wählen Sie eine Farbe oder einen Wert, die bzw. der als Ziel für den Algorithmus &quot;Tonwertangleichung&quot; dienen soll.
* <b>Benutzerdefinierte Farbvariation</b>: HSL-Schieberegler\
  Passen Sie Farbton, Chrominanz (Sättigung) und Helligkeit (Luminanz) des Ergebnisses an, nachdem der Algorithmus zum Entzerren für den angegebenen Kanal ausgeführt wurde.

<b>Maske</b>

* <b>Benutzerdefinierte Maske</b>: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske für diesen Filter
* <b>Benutzerdefinierte Maske</b>: Bild/Pinsel\
  Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
* <b>Benutzerdefinierte Maskenumkehrung</b>: Knebel
