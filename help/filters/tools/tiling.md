---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/tiling.html"
breadcrumb-title: ''
description: Verwenden Sie das Kachelung-Werkzeug in Substance 3D Sampler, um nahtlose Kachelung-Muster aus Texturen für wiederholbare Material-Oberflächen zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Tiling
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Kacheln
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Kacheln

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Kachelung-Filter**, um Ihr Material kachelbar zu machen. Der **Kachelfilter erstellen** macht Ihr Material ebenfalls kachelbar, aber jeder Filter funktioniert auf andere Weise. Wenn Sie feststellen, dass der **Kachelfilter** nicht für Sie funktioniert, versuchen Sie den **Kachelfilter erstellen**.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Naht anzeigen**: Knebel\
  Auswählen, ob die Naht angezeigt werden soll
* **Maske verwenden**: Knebel\
  Wenn diese Option aktiviert ist, können Sie eine benutzerdefinierte Naht erstellen, um den Maskenspeicherort zu steuern.
  * **Maske**: Bild/Pinsel\
    Importieren Sie ein Bild, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um eine Maske direkt in der **2D-Ansicht** Malen.

**Edge**

* **Kanten erkennen**: Knebel\
  Stellt ein, ob Ränder auf Basis der Materialkanäle erkannt werden sollen, um einen organischeren Übergang zwischen den Materialschichten zu erzeugen. Wenn aktiviert, werden die folgenden zusätzlichen Parameter angezeigt:
  * **Schwellenwert pro Kanal verwenden**: Knebel\
    Wenn diese Option aktiviert ist, werden zusätzliche Parameter angezeigt, mit denen Sie den Schwellenwert für jeden Kanal einzeln anpassen können.
    * **Grundfarbe des Schwellenwerts**: 0-1
    * **Schwellenwert Normal**: 0-1
    * **Schwellenwert-Height**: 0-1
  * **Schwellenwert**: 0-1\
    Passen Sie den Schwellenwert an, mit dem die Naht ermittelt wird.
  * **Weichzeichnen**: 0-1\
    Bereich um die Naht weichzeichnen.
  * **Smoothness**: 0-2\
    Passen Sie die Smoothness der Naht an. So können Artefakte vermieden werden.
  * **Raster-Auflösung**: 1-11\
    Passen Sie die Auflösung des Rasters an, auf dem die Naht gezeichnet wird. Niedrigere Auflösung kann die Naht verbessern, aber die Qualität beeinträchtigen.
  * **Grundfarbe verwenden**: Knebel\
    Umschalten, ob Grundfarbinformationen bei der Nahtgenerierung berücksichtigt werden
  * **Normal verwenden**: Knebel\
    Umschalten, ob Normalinformationen bei der Generierung von Nähte berücksichtigt werden
  * **Height verwenden**: Knebel\
    Umschalten, ob Height-Informationen bei der Generierung von Nähte berücksichtigt werden
  * **Offset abschneiden**: 0-0,5\
    Versatz der Naht auf der X- und Y-Achse anpassen

**Erweiterte Parameter**

* **Transformieren**: 0-2\
  Passen Sie die transformieren Werte an. Erhöhe die X- und W-Werte, um die Stärke der Überlagerung zwischen dem darunterliegenden und dem darüberliegenden Material anzupassen.
* **Offset**: 0-1\
  Material um die X- und Y-Achse versetzen
* **Filterung**:\
  Wählen Sie die Filterung-Methode aus, die für skalierte Pixel verwendet werden soll. Bilineare Filterung verwischt Pixel, während die nächstliegende Filterung die scharfe Kante zwischen den Pixeln beibehält.
* **Eingabegröße**: 0-8192\
  Passen Sie die Größe der Eingabe in Pixel auf der X- und Y-Achse an.

## Benutzerhandbuch

Der **Kachelung-Filter** funktioniert in zwei Schritten:

1. Es skaliert und verschiebt Ihr Material, um eine Überlappung zu erzeugen.
1. Anschließend wird die überlappende Kante geändert, um die Naht auszublenden.

Wenn Sie also den **Kachelung-Filter** verwenden möchten, können Sie durch Anpassen dieser beiden Teile des Prozesses die besten Ergebnisse erzielen.

1. Fügen Sie den **Kachelung-Filter** oben im Ebenenstapel hinzu.
1. Verwenden Sie die Ziehpunkte, um das Material so transformieren, dass es genügend Überlappungen gibt, um die Naht auszublenden.
   1. Die Skalierung des Materials kann hilfreich sein, um eine Überlappung zu erstellen, aber auch zu einem Detailverlust führen.
1. Passen Sie die Parameter im Abschnitt **Edge** an, um die Naht anzupassen.

Bei einigen Materialien, die nur den **Kachelung-Filter** verwenden, führt dies dennoch zu Artefakten oder Problemen in der Naht. In diesem Fall empfiehlt es sich, andere Filter wie **Klon Stamp** zu verwenden, um Probleme mit der Naht und Kachelung zu beheben.

Es ist eine gute Angewohnheit, früh im Material-Erstellungsprozess an der Kachelung des Materials zu arbeiten - sobald ein Nicht-Kachelung-Element zum Material hinzugefügt wird, ist es gut, sicherzustellen, dass es kachelt, bevor es weiter bearbeitet wird. Sampler-Filter sind so konzipiert, dass sie Kachelung-Materials nicht stören. Das bedeutet, dass Sie nach den Kacheln des zugrunde liegenden Materials weiterhin mit Filtern und den in Sampler enthaltenen Materialien arbeiten können und Ihr Material weiterhin kacheln wird.
