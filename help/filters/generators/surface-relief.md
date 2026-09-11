---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Verwenden Sie den Generator für Oberflächenmuster in Substance 3D Sampler, um geprägte und Relief-Oberflächenmuster in Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Surface Relief
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Surface Relief
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Surface Relief

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-surfacerelief-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den Filter Surface Relief , um Ihrem Material Rauschen hinzuzufügen. Damit kannst du große Formen zerlegen oder dein Design interessanter gestalten.

</td>
</tr>
</table>

## Parameter

<b>Basisparameter</b>

* <b>Zufallsparameter</b>:\
  Die Zufallsgeschwindigkeit, auf der alle anderen Zufallsparameter in diesem Filter basieren.
* <b>Intensität</b>: 0-1\
  Ändern der Amplitude des Rauschen
* <b>Weichzeichnungsintensität</b>: 0-1\
  Die Stärke des Weichzeichners, der auf den Rauschen angewendet wird
* <b>Oberflächenstörung </b>: Image/Brush/Textur Generator\
  Verwenden Sie ein Bild oder einen Textur-Generator, um die Oberflächenunvollkommenheit zu erzeugen.

<b>Rauschen-Parameter</b>

* <b>Beschränk</b>: 0-1\
  Rauschen in einen bestimmten Bereich beschränken
* <b>Kontrast</b>: 0-1\
  Kontrast der Rauschen ändern.
* <b>Umkehren</b>: Knebel\
  Rauschen-Höhen-Map umkehren

<b>Transformieren</b>

* <b>Kachelung</b>: 1-16\
  Im Gegensatz zu <b>Basisparameter > scale</b> verwaltet <b>Kachelung</b> die Anzahl der Instanzen der Rauschen.
* <b>Spiegelung</b>:\
  Spiegeln der Rauschen über eine oder beide Achsen
* <b>Offset</b>:\
  Das Geräusch in der X- und Y-Achse neu positionieren
* <b>Drehung</b>:\
  Drehe das Rauschen. Der Drehwinkel rastet ein, um sicherzustellen, dass eine Kachelung noch möglich ist.

<b>Maske</b>

* <b>Benutzerdefinierte Maske verwenden</b>: Knebel\
  Aktivieren, um Steuerelemente für benutzerdefinierte Masken anzuzeigen:
  * <b>Maske</b>: image/brush/Textur Generator\
    Importieren Sie ein Bild, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um direkt in der <b>2D-Ansicht</b> Malen.
  * <b>Benutzerdefinierte Maske - Weichzeichnen</b>: 0-1\
    Weichzeichnen der Maske
  * <b>Benutzerdefinierte Maske - Umkehren</b>: Knebel

<b>Erweiterte Parameter</b>

* <b>Height-Intensität</b>: 0-1\
  Steuern Sie die Überblendung der Rauschen-Höhenkarte mit der zugrunde liegenden Materialien-Höhenkarte
* <b>Height - Basis ersetzen</b>: Knebel\
  Stellt ein, ob das Basis-Height ersetzt werden soll
* <b>Normalintensität</b>: 0-1\
  Anpassen der Stärke des Rauschen-Normalen-Map
* <b>Normal - Basis ersetzen</b>: Knebel\
  Stellt ein, ob die normale Grundkarte ersetzt werden soll oder nicht
* <b>Normal - Richtung</b>:\
  Ändern der für die normale Generierung zu verwendenden Achsen
* <b>Normal - Drehrichtung</b>
* <b>Ambient occlusion - Intensität</b>
* <b>Ambient occlusion - Radius</b>
