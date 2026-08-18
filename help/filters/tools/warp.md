---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Mit dem Verformen-Werkzeug in Substance 3D Sampler können Sie Texturen und Materialebenen mit Effekten für gerichtete Verkrümmung und Verzerrung versehen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Warp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Verformen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---


# Verformen

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-warp-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Verkrümmungsfilter** können Sie Ihr Material auf der Grundlage einer Reihe generierter Geräusche verkrümmen.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Rauschauswahl**:\
  Wähle das Rauschen aus, auf dem die Verkrümmung basieren soll. Unterschiedliche Geräusche können unterschiedliche Effekte erzeugen.
* **Rauschskalierung**: 0-10\
  Passen Sie die Skalierung des Ausgangsrauschens an. Das Geräusch wird immer kacheln.
* **Typ**:\
  Wählen Sie aus, mit welcher Methode das Material verkrümmt werden soll. Wenn **Richtungsverkrümmung** oder **Mehrrichtungsverkrümmung** ausgewählt sind, wird ein zusätzlicher Parameter angezeigt:
  * **Verkrümmungswinkel**: 0-1\
    Richtung der Verformung anpassen.
* **Intensität**: 0-1\
  Passe die Stärke der Verformung an.
* **Benutzerdefiniertes Rauschen**: Knebel\
  Aktivieren Sie diese Option, um anstelle der Auswahl unter **Rauschauswahl** ein benutzerdefiniertes Rauschen zu verwenden. Die verfügbaren Parameter ändern sich je nachdem, ob **Benutzerdefiniertes Rauschen** aktiviert oder deaktiviert ist. Wenn diese Option aktiviert ist, werden die folgenden Parameter angezeigt:
  * **Benutzerdefiniertes Rauschen weichzeichnen**: 0-1\
    Weichzeichnen des benutzerdefinierten Rauschens
  * **Benutzerdefiniertes Rauschen**: Bild/Pinsel\
    Importieren Sie eine benutzerdefinierte Geräuschkarte, die als Verkrümmungsquelle verwendet werden soll.
* **Verkrümmung pro Kanal**: Knebel\
  Wenn diese Option aktiviert ist, werden zusätzliche Abschnitte angezeigt, um die Verkrümmung jedes Kanals unabhängig zu steuern. Für jeden Kanal stehen die folgenden Parameter zur Verfügung:
  * ***Kanalname***: Knebel\
    Stellt ein, ob dieser Kanal durch den **Verkrümmungsfilter** beeinflusst wird.
  * **Füllmethode**:\
    Wählen Sie aus, wie die Ergebnisse der Verformung für diesen Kanal mit der darunter liegenden Ebene vermischt werden sollen.
  * **Deckkraft**: 0-1\
    Ändern Sie die Deckkraft der Filterergebnisse für diesen Kanal.
