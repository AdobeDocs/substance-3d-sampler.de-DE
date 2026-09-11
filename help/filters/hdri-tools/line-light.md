---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/hdri-tools/line-light.html"
breadcrumb-title: ''
description: Mit dem Linienlichtwerkzeug in Substance 3D Sampler können Sie HDRI-Umgebungen lineare Lichtquellen hinzufügen, um eine präzise Lichtsteuerung zu ermöglichen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Line Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Linienbeleuchtung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---


# Linienbeleuchtung

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-linelight-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Fügen Sie Ihrem Umgebungslicht ein **Linienlicht** hinzu.

Die folgenden Bilder zeigen, wie Sie ein **Linienlicht** verwenden können, um die Beleuchtung Ihrer Umgebung anzupassen.![](../../assets/3d-2d-filters-cropped-0017-line-light-in.jpg)

Die Abbildung oben zeigt eine Kugel ohne Änderungen am Umgebungslicht.

![](../../assets/3d-2d-filters-cropped-0016-line-light-out.jpg)

Nach dem Hinzufügen eines **Linienlichts** hat sich das Erscheinungsbild der Kugel merklich geändert.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Exposition (EV)**: 0-10\
  Passen Sie die Belichtung oder Helligkeit des Lichts an.
* **Formfarbmodus**:\
  Legen Sie fest, mit welcher Methode die Farbe des Lichts bestimmt werden soll. Die verfügbaren Parameter ändern sich entsprechend dieser Auswahl.
  * **Temperatur (Kelvin)**
    * **Temperatur**: 1000 - 27000\
      Passe die Lichttemperatur an.
  * **RGB**
    * **Farbe**: Farbauswahl\
      Wähle die Farbe des Lichts aus.
  * **Image-Eingabe**
    * **Shape Image Input**: Bild/Pinsel\
      Importieren Sie ein Bild, das als Farbe verwendet werden soll. Sie können das Pinselwerkzeug verwenden, um direkt in der **2D-Ansicht** zu Malen. Dies kann jedoch zu unvorhersehbaren Ergebnissen mit diesem Filter führen.
  * **Beispielhintergrund**
    * Der Beispielhintergrund stellt keine neuen Parameter zur Verfügung - stattdessen basiert die Lichtfarbe auf den Hintergrundwerten.
* **Positionsmodus**:\
  Ändern Sie die Methode, mit der die Lichtposition bestimmt wird. Die Parameter im Abschnitt **Positionskoordinaten** ändern sich basierend auf der Auswahl. Wenn **Weltposition** ausgewählt ist, verschwinden die Handles aus der **2D-Ansicht**. Verwenden Sie stattdessen die Parameter in **Positionskoordinaten**, um die Lichtposition zu ändern.

**Form**

* **Zeilendrehung**: 0-1\
  Drehen der Lichtquelle
* **Thickness der Zeile**: 0-1\
  Passe die Thickness der Linie an, die die Lichtquelle bildet.
* **Muster**:\
  Die Form der Linie ändern.
* **Pattern-Härte**: 0-1\
  Glätten der Kanten des Lichts
* **Muster-UV-Modus**:\
  Passe das Muster an, auf dem das Licht basiert. **Dehn** dehne die gesamte Form, sodass sie mit den Linienendpunkten übereinstimmt. **Nur Mitte Gedehnt** dehne die Mitte der Form bei, wobei die Enden der Linie unverzerrt bleiben. **Wiederholen + Abstand** erstellt Stempel der Form entlang der Zeilenlänge und fügt einen zusätzlichen Parameter hinzu, um Abstand zu verwalten:
  * **Abstand zur Musterwiederholung**: 0-1\
    Die Breite des Abstands zwischen Forminstanzen anpassen.

**Positionskoordinaten**

Verfügbare Parameter hängen von der Auswahl ab, die für **Basisparameter > Positionsmodus** vorgenommen wurde. Wenn **Boden/Decke** oder **Abstand zum Ursprung** ausgewählt ist, sind die folgenden Parameter verfügbar:

* **Absolutes Height der Zeile**: 0-1\
  Ändere die Entfernung des Lichts zur Kamera.
* **Position der Kamera**: 0-1\
  Passen Sie die relative Position der Kamera zur Lichtquelle in der X-, Y- und Z-Achse an.

Wenn **Weltposition** in **Basisparameter > Positionsmodus** ausgewählt wird, sind die folgenden Parameter verfügbar:

* **Vektor nach oben**:\
  Ändere die Richtung nach oben.
* **Weltrangliste für Punkt 1**: -2 bis 2\
  Passen Sie die Position des ersten Punkts der Linie in der X-, Y- und Z-Achse an.
* **Weltrangliste für Punkt 2**: -2 bis 2\
  Passen Sie die Position des zweiten Linienpunkts in der X-, Y- und Z-Achse an.
* **Position der Kamera**: 0-1\
  Passen Sie die relative Position der Kamera zur Lichtquelle in der X-, Y- und Z-Achse an.

**Hintergrund**

* **Boden-Raster anzeigen**: Knebel\
  Blenden Sie den Boden-Raster ein oder aus.
* **Bodenbeschneidung aktivieren**: Knebel\
  Legen Sie fest, ob die Lichtquelle durch den Boden hindurch geschnitten werden kann. Wenn diese Option aktiviert ist, wird das folgende Steuerelement angezeigt:
  * **Boden-Height**: -2 bis 2\
    Passe das Height des Bodens an, um das Licht abzuschneiden.
* **Gamma im Hintergrund**:\
  Wählen Sie das Farbsystem aus, mit dem das Gamma-Hintergrundbild bestimmt wird.
