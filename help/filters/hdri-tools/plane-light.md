---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/plane-light.html"
breadcrumb-title: ''
description: Mit dem Flächenlicht-Werkzeug in Substance 3D Sampler können Sie HDRI-Umgebungen planare Lichtquellen für Flächenbeleuchtungseffekte hinzufügen.
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
      Importieren Sie ein Bild, das als Farbe verwendet werden soll. Sie können das Pinselwerkzeug verwenden, um direkt in der **2D-Ansicht** zu malen, dies kann jedoch zu unvorhersehbaren Ergebnissen mit diesem Filter führen.
  * **Beispielhintergrund**
    * Der Beispielhintergrund stellt keine neuen Parameter zur Verfügung - stattdessen basiert die Lichtfarbe auf den Hintergrundwerten.
* **Positionsmodus**:\
  Ändern Sie die Methode, mit der die Lichtposition bestimmt wird. Die Parameter im Abschnitt **Positionskoordinaten** ändern sich basierend auf der Auswahl. Wenn **Weltposition** ausgewählt ist, verschwinden die Handles aus der **2D-Ansicht**. Verwenden Sie stattdessen die Parameter in **Positionskoordinaten**, um die Position des Lichts zu ändern.

**Form**

* **Ebenenskala**; 0-1\
  Passe die Skalierung des Lichts an.
* **Ebenengröße**: 0-1\
  Passen Sie die Abmessungen des Lichts in der X- und Y-Achse an.
* **Ebenendrehung**: 0-1\
  Passen Sie die Drehung des Lichts entlang der X-, Y- und Z-Achse an.
* **Muster**:\
  Wähle die Form des Lichts aus.
* **Musterhärte**: 0-1\
  Ränder des Lichts weichzeichnen oder weichzeichnen.
* **Muster-UV-Modus**:\
  Wählen Sie aus, ob Transformationen die gesamte Form oder nur die Mitte der Form dehnen sollen, um Rand- und Eckdetails beizubehalten.

**Positionskoordinaten**

Verfügbare Parameter hängen von der Auswahl ab, die für **Basisparameter > Positionsmodus** vorgenommen wurde. Wenn **Boden/Decke** oder **Abstand zum Ursprung** ausgewählt ist, sind die folgenden Parameter verfügbar:

* **Absolutes Height der Zeile**: 0-1\
  Ändere die Entfernung des Lichts zur Kamera.
* **Kameraposition**: 0-1\
  Passen Sie die relative Position der Kamera zum Licht in der X-, Y- und Z-Achse an.

Wenn **Weltposition** in **Basisparameter > Positionsmodus** ausgewählt wird, sind die folgenden Parameter verfügbar:

* **Vektor nach oben**:\
  Ändere die Richtung nach oben.
* **Weltrangliste für Punkt 1**: -2 bis 2\
  Passen Sie die Position des ersten Punkts der Linie in der X-, Y- und Z-Achse an.
* **Weltrangliste für Punkt 2**: -2 bis 2\
  Passen Sie die Position des zweiten Punkts der Linie in der X-, Y- und Z-Achse an.
* **Kameraposition**: 0-1\
  Passen Sie die relative Position der Kamera zum Licht in der X-, Y- und Z-Achse an.

**Hintergrund**

* **Grundraster anzeigen**: Knebel\
  Blendet das Grundraster ein oder aus.
* **Bodenbeschneidung aktivieren**: Knebel\
  Lege fest, ob das Licht durch den Boden hindurch geclippt werden kann. Wenn diese Option aktiviert ist, wird das folgende Steuerelement angezeigt:
  * **Ground-Height**: -2 bis 2\
    Passe das Height des Bodens an, um das Licht abzuschneiden.
* **Gamma im Hintergrund**:\
  Wählen Sie das Farbsystem aus, mit dem das Gamma-Hintergrundbild bestimmt wird.
