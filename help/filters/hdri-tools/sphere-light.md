---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/hdri-tools/sphere-light.html"
breadcrumb-title: ''
description: Verwenden Sie das Kugellicht-Werkzeug in Substance 3D Sampler, um HDRI-Umgebungen kugelförmige Lichtquellen für Punktlichteffekte hinzuzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Sphere Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Kugellicht
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# Kugellicht

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-spherelight-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Fügen Sie Ihrer Umgebung ein Kugellicht hinzu.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

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
* **Exposition (EV)**: 0-10\
  Passen Sie die Belichtung oder Helligkeit des Lichts an.
* **Kugelradius**: 0-1\
  Passe die Größe des Lichts an.
* **Positionsmodus**:\
  Ändern Sie die Methode, mit der die Lichtposition bestimmt wird. Die Parameter im Abschnitt **Positionskoordinaten** ändern sich basierend auf der Auswahl.

**Positionskoordinaten**

Verfügbare Parameter hängen von der Auswahl ab, die für **Basisparameter > Positionsmodus** vorgenommen wurde. Wenn **Abstand zum Ursprung** ausgewählt ist, sind die folgenden Parameter verfügbar:

* **Abstand zum Ursprung**: 0-20\
  Passe den Abstand zwischen Licht und Kamera an.
* **Position der Kamera**: 0-1\
  Passen Sie die relative Position der Kamera zur Lichtquelle in der X-, Y- und Z-Achse an.

Wenn **Weltposition** ausgewählt ist, sind die folgenden Parameter verfügbar:

* **Vektor nach oben**:\
  Ändere die Richtung nach oben.
* **Sphere World Position**: -2 bis 2\
  Passen Sie die Position des Kugellichts in der X-, Y- und Z-Achse an.
* **Abstand zum Ursprung**: 0-20\
  Passe den Abstand zwischen Licht und Kamera an.
* **Position der Kamera**: 0-1\
  Passen Sie die relative Position der Kamera zur Lichtquelle in der X-, Y- und Z-Achse an.

**Form**

* **Kugelhärte**: 0-1\
  Ränder des Kugellichts weichzeichnen oder verfestigen.
* **Schattierung**:\
  Ändere den Belichtungsverlauf des Lichts basierend auf verschiedenen Arten von realem Licht. Wenn **Schattierung Light** ausgewählt ist, werden zusätzliche Parameter angezeigt:
  * **Schattierung Lichtweltposition**: -1 bis 1\
    Position des schattierten Bereichs im Licht ändern.
  * **Penumbra-Transparenz**: 0-1\
    Passen Sie die Deckkraft des schattierten Bereichs des Lichts an.

**Hintergrund**

* **Gamma im Hintergrund**:\
  Wählen Sie das Farbsystem aus, mit dem das Gamma-Hintergrundbild bestimmt wird.
