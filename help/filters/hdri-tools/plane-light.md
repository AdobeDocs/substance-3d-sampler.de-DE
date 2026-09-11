---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/hdri-tools/plane-light.html"
breadcrumb-title: ''
description: Verwende das Flächenlicht-Werkzeug in Substance 3D Sampler, um planare Lichtquellen zu HDR-Umgebungen hinzuzufügen, um Flächenbeleuchtungseffekte zu erzeugen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Plane Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Flächenlicht
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '502'
ht-degree: 0%

---


# Flächenlicht

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-planelight-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Fügen Sie Ihrer Umgebung ein Licht in Form einer flachen Ebene hinzu.

![](../../assets/3d-2d-filters-cropped-0002-plane-light-out.jpg)

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

* **Ebenenskala**; 0-1\
  Passe die Skalierung des Lichts an.
* **Ebenengröße**: 0-1\
  Passe die Abmessungen des Lichts in der X- und Y-Achse an.
* **Ebenendrehung**: 0-1\
  Passen Sie die Drehung des Lichts entlang der X-, Y- und Z-Achse an.
* **Muster**:\
  Wähle die Form des Lichts aus.
* **Pattern-Härte**: 0-1\
  Ränder des Lichts weichzeichnen oder weichzeichnen.
* **Muster-UV-Modus**:\
  Legen Sie fest, ob die gesamte Form oder nur die Mitte der Form gedehnt werden soll, damit Kanten- und Eckdetails beibehalten werden.

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
* **Boden-Clipping aktivieren**: Knebel\
  Legen Sie fest, ob die Lichtquelle durch den Boden hindurch geschnitten werden kann. Wenn diese Option aktiviert ist, wird das folgende Steuerelement angezeigt:
  * **Boden-Height**: -2 bis 2\
    Passe das Height des Bodens an, um das Licht abzuschneiden.
* **Gamma im Hintergrund**:\
  Wählen Sie das Farbsystem aus, mit dem das Gamma-Hintergrundbild bestimmt wird.
