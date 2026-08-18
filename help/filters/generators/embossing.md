---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embossing.html"
breadcrumb-title: ''
description: Verwenden Sie den Prägegenerator in Substance 3D Sampler, um geprägte Relief und erhöhte Oberflächeneffekte in Materialien zu erzeugen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embossing
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Prägen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---


# Prägen

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embossing-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Text oder Muster in Materialien integrieren.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Prägegröße**: 0-1\
  Die Größe jeder Instanz ändern.
* **Relief-Abstand**: 0-1\
  Ändern der Thickness von Relieflinien
* **Musterauswahl**:\
  Wählen Sie das Muster aus, das geprägt werden soll. Von hier aus kannst du Text oder ein benutzerdefiniertes Muster prägen.
* **Mustertitel X**: 1-64\
  Anzahl der Instanzen auf der X-Achse ändern
* **Mustertitel Y**: 1-64\
  Anzahl der Instanzen auf der Y-Achse ändern

**Relief**

* **Rahmenrelief verwenden**: Knebel\
  Legt fest, ob der Rand des ausgewählten Musters geprägt werden soll.
* **Umkehrung des Rahmenrelief**: Knebel\
  Height der Randprägung umkehren
* **Intensität der Randprägung**: 0-1\
  Stärke des Relief-Effekts ändern.
* **Füllrelief verwenden**: Knebel\
  Legt fest, ob die Fläche des ausgewählten Musters geprägt werden soll.
* **Umkehrung des Flächenrelief**: Knebel\
  Height des Effekts &quot;Flächenprägung&quot; umkehren
* **Intensität der Prägung der Fläche**: 0-1\
  Stärke des Relief-Effekts ändern.

**Muster**

* **Farbe verwenden**: Knebel\
  Umschalten, ob der geprägte Bereich farbig gestaltet werden soll\
  Wenn **Farbe verwenden** aktiviert ist, wird ein zusätzlicher **Farbe**-Parameter angezeigt, um die Farbe anzupassen.
* **Mustermaske** **Abstand**: 0-1\
  Größe der Maske ändern, die zum Anwenden von Farbe auf den geprägten Bereich verwendet wird
* **Mustermaskenkontrast**: 0-1\
  Passen Sie den Kontrast der Maske an. Durch Verringern des Kontrasts werden die Kanten der Maske unscharfer.
* **Mustertitel verwenden**: Knebel\
  Aktivieren Sie die Option, um das Muster nebeneinander anzuordnen, und deaktivieren Sie die Option, um nur eine einzelne Instanz anzuzeigen. Wenn das Muster nicht unterteilt ist, werden die Optionen **Mustertitel** nicht im Abschnitt **Basisparameter** angezeigt.
* **Musterrotation**: 0-1\
  Muster drehen.
* **Musterversatz**: 0-1\
  Versatz jede Zeile des Musters zur vorherigen Zeile.
* **Musterschärfe verwenden**: Knebel\
  Aktivieren Sie diese Option, um die zugrunde liegende Materialrauhigkeit mit einem benutzerdefinierten Raueitswert zu überschreiben, wenn der Prägeeffekt auftritt.\
  Wenn diese Option aktiviert ist, wird ein Steuerelement **Musterschärfe** angezeigt, das die Schärfe festlegt.
* **Metallisches Muster verwenden**: Knebel\
  Aktivieren Sie diese Option, um die zugrunde liegenden metallischen Materialwerte überall dort, wo der Prägeeffekt auftritt, mit einem benutzerdefinierten metallischen Wert zu überschreiben.\
  Wenn diese Option aktiviert ist, wird ein **Pattern Metallic**-Steuerelement angezeigt, das die Raueit festlegt.

**Text** - Dieser Abschnitt wird nur angezeigt, wenn **Musterauswahl** unter **Basisparameter** auf **Text** festgelegt ist.

* **Schriftauswahl**:\
  Schrift auswählen.
* **Text**: Textfeld\
  Text eingeben, der geprägt werden soll
* **Textgröße**: 0-1\
  Schriftgröße anpassen

**Radiergummi**

* **Radiergummi Normal**: 0-1
* **Umgebungsradiergummi-Verdeckung**: 0-1
* **Radiergummi-Deckkraft**: 0-1

**Erweiterte Parameter**

Mit diesen Parametern können Sie Werte für das gesamte Material anpassen.

* **Luminanz**: 0-1
* **Kontrast**: -1 bis 1
* **Farbtonverschiebung**; 0-1
* **Sättigung**: 0-1
* **Normalintensität**; 0-1

## Benutzerhandbuch

Setze den Prägefilter an oberster Stelle in der Ebenenliste. Passe die Parameter an.

Die wichtigsten Parameter sind im Allgemeinen **Grundlegende Parameter > Musterauswahl**, um zu ändern, welches Muster der Filter verwenden soll, und **Muster > Mustertitel verwenden**, um die Musterunterteilung ein- und auszuschalten.
