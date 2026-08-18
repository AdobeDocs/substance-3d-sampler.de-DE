---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/hdri-tools/shape-light.html"
breadcrumb-title: ''
description: Nutze das Formenlicht-Werkzeug von Substance 3D Sampler, um in HDRI-Umgebungen benutzerdefinierte Lichtquellen für eine kreative Beleuchtung hinzuzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Shape Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Shape Light
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---


# Shape Light

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-shapelight-18-n-d.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Erstellen Sie eine Beleuchtung in Form eines Rechtecks oder einer Disc.

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
      Importieren Sie ein Bild, das als Farbe verwendet werden soll. Sie können das Pinselwerkzeug verwenden, um direkt in der **2D-Ansicht** zu malen, dies kann jedoch zu unvorhersehbaren Ergebnissen mit diesem Filter führen.
* **Hotspot-Exposition (EV)**: 0-10\
  Passen Sie die Belichtung des Hotspots an. Der Hotspot kann manchmal schwer oder gar nicht sichtbar sein - stellen Sie in einem neuen **Formlichtfilter** die **Formtemperatur** auf 1000 und die **Hotspot-Belichtung** **(EV)** auf 10 ein, um den Hotspot in der Mitte der Form zu sehen.
* **Form**:\
  Lege die Form des Lichts fest.

**Position**

* **Hotspot-Position**: 0-1\
  Hotspot-Position versetzen
* **Matrixversatz**: -2 bis 2\
  Ändern Sie die Position des Formenlichts. Sie können das Licht auch in der **2D-Ansicht** ziehen, um es neu zu positionieren.

**Form**

* **Formexposition (EV)**: 0-10\
  Anpassen der Belichtung des Lichts
* **Formhärte**: 0-1\
  Glätten der Kanten des Lichts
* **Hotspot-Größe**: 0-1
* **Hotspot-Falloff**: 0-1\
  Passen Sie die Weichheit der Kanten des Hotspots an.

**Hintergrund**

* **Gamma im Hintergrund**:\
  Wählen Sie das Farbsystem aus, mit dem das Gamma-Hintergrundbild bestimmt wird.
