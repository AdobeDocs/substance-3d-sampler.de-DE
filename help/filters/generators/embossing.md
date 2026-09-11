---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/embossing.html"
breadcrumb-title: ''
description: Verwenden Sie den Prägegenerator in Substance 3D Sampler, um geprägte Relief und erhöhte Oberflächeneffekte in Materials zu erzeugen.
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

Reliefs von Text oder Mustern auf Ihren Materialien

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Relief-Größe**: 0-1\
  Die Größe jeder Instanz ändern.
* **Relief-Entfernung**: 0-1\
  Ändern der Thickness von Relieflinien
* **Musterauswahl**:\
  Wählen Sie das zu Reliefs Muster aus. Von hier aus können Sie Relief-Text oder ein benutzerdefiniertes Muster auswählen.
* **Mustertitel X**: 1-64\
  Anzahl der Instanzen auf der X-Achse ändern
* **Mustertitel Y**: 1-64\
  Anzahl der Instanzen auf der Y-Achse ändern

**Relief**

* **Relief für Rahmen verwenden**: Knebel\
  Stellt ein, ob die Umrandung des ausgewählten Musters Relief werden soll
* **Umkehren des Relief-Rahmens**: Knebel\
  Umkehren des Heights des Rahmen-Reliefs
* **Border Relief Intensity**: 0-1\
  Die Stärke des Effekts &quot;Relief&quot; ändern.
* **Relief füllen** verwenden: Knebel\
  Stellt ein, ob die Füllung des ausgewählten Reliefs geändert werden soll
* **Relief füllen umkehren**: Knebel\
  Height des Effekts &quot;Relief füllen&quot; umkehren
* **Relief-Füllintensität**: 0-1\
  Die Stärke des Effekts &quot;Relief&quot; ändern.

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
* **Muster-Rauheit verwenden**: Knebel\
  Aktivieren Sie diese Option, um die Rauheit des zugrunde liegenden Materials bei jedem Auftreten des Relief-Effekts mit einer benutzerdefinierten Rauheit zu überschreiben.\
  Wenn diese Option aktiviert ist, wird ein **Pattern Rauheit**-Steuerelement angezeigt, mit dem die Rauheit festgelegt wird.
* **Metallic Muster verwenden**: Knebel\
  Aktivieren Sie diese Option, um die metallic Werte des zugrunde liegenden Materials überall dort, wo der Relief-Effekt auftritt, mit einem benutzerdefinierten metallic Wert zu überschreiben.\
  Wenn diese Option aktiviert ist, wird ein **Pattern Metallic**-Steuerelement angezeigt, das die Rauheit festlegt.

**Text** - Dieser Abschnitt wird nur angezeigt, wenn **Musterauswahl** unter **Basisparameter** auf **Text** festgelegt ist.

* **Schriftauswahl**:\
  Schrift auswählen.
* **Text**: Textfeld\
  Text eingeben, der geprägt werden soll
* **Textgröße**: 0-1\
  Schriftgröße anpassen

**Radiergummi**

* **Radiergummi Normal**: 0-1
* **Radiergummi Ambient occlusion**: 0-1
* **Deckkraft des Radiergummis**: 0-1

**Erweiterte Parameter**

Mit diesen Parametern können Sie Werte für das gesamte Material anpassen.

* **Luminanz**: 0-1
* **Kontrast**: -1 bis 1
* **Farbtonverschiebung**; 0-1
* **Sättigung**: 0-1
* **Normalintensität**; 0-1

## Benutzerhandbuch

Setze den Prägefilter auf den oberen Rand des Ebenenstapels, und passe die Parameter an.

Die wichtigsten Parameter sind im Allgemeinen **Grundlegende Parameter > Musterauswahl**, um zu ändern, welches Muster der Filter verwenden soll, und **Muster > Mustertitel verwenden**, um die Kachelung ein- und auszuschalten.
