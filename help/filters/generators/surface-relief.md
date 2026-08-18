---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Erstellen Sie in Substance 3D Sampler mit dem Oberflächenmaterialgenerator geprägte und Relief-Oberflächenmuster in Reliefs.
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

Verwenden Sie den Oberflächenmaterialfilter, um Ihrem Relief Rauschen hinzuzufügen. Damit kannst du große Formen zerlegen oder dein Design interessanter gestalten.

</td>
</tr>
</table>

## Parameter

<b>Basisparameter</b>

* <b>Zufallsparameter</b>:\
  Die Zufallsgeschwindigkeit, auf der alle anderen Zufallsparameter in diesem Filter basieren.
* <b>Intensität</b>: 0-1\
  Ändern der Amplitude des Rauschens
* <b>Weichzeichnungsintensität</b>: 0-1\
  Stärke des Weichzeichners, der auf das Rauschen angewendet wird
* <b>Oberflächenstörung </b>: Bild-/Pinsel-/Texturgenerator\
  Verwende ein Bild oder einen Texturgenerator, um die Oberflächenstörung zu beheben.

<b>Rauschparameter</b>

* <b>Klemme</b>: 0-1\
  Das Rauschen auf einen bestimmten Bereich begrenzen
* <b>Kontrast</b>: 0-1\
  Den Kontrast des Rauschens ändern.
* <b>Umkehren</b>: Knebel\
  Umkehren des Heights des Rauschens

<b>Transformieren</b>

* <b>Anordnen</b>: 1-16\
  Im Gegensatz zu <b>Basisparameter > scale</b> verwaltet <b>Tiling</b> die Anzahl der Instanzen des Rauschens.
* <b>Spiegelung</b>:\
  Spiegeln des Rauschens über eine oder beide Achsen
* <b>Offset</b>:\
  Das Geräusch in der X- und Y-Achse neu positionieren
* <b>Drehung</b>:\
  Drehe das Rauschen. Der Drehwinkel rastet ein, um sicherzustellen, dass eine Kachelung noch möglich ist.

<b>Maske</b>

* <b>Benutzerdefinierte Maske verwenden</b>: Knebel\
  Aktivieren, um Steuerelemente für benutzerdefinierte Masken anzuzeigen:
  * <b>Maske</b>: image/brush/Texture Generator\
    Importieren Sie ein Bild, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um direkt in der <b>2D-Ansicht zu malen</b>
  * <b>Benutzerdefinierte Maske - Weichzeichnen</b>: 0-1\
    Weichzeichnen der Maske
  * <b>Benutzerdefinierte Maske - Umkehren</b>: Knebel

<b>Erweiterte Parameter</b>

* <b>Height-Intensität</b>: 0-1\
  Steuern Sie die Überblendung der Rauschhöhenkarte mit der zugrunde liegenden Materialkarte
* <b>Height - Basis ersetzen</b>: Knebel\
  Stellt ein, ob das Basis-Height ersetzt werden soll
* <b>Normalintensität</b>: 0-1\
  Passen Sie die Stärke der normalen Geräuschkarte an.
* <b>Normal - Basis ersetzen</b>: Knebel\
  Stellt ein, ob die normale Grundkarte ersetzt werden soll oder nicht
* <b>Normal - Richtung</b>:\
  Ändern der Achsen, die für die normale Erzeugung verwendet werden sollen
* <b>Normal - Drehrichtung</b>
* <b>Umgebungsintensität - Verdeckung</b>
* <b>Umgebungsradius - Verdeckung</b>
