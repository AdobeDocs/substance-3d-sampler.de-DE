---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Mit dem Verkrümmen-Werkzeug in Substance 3D Sampler können Sie Texturen und Material-Ebenen mit Richtungsverkrümmungs- und Verzerrung-Effekten versehen.
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

Mit dem **Verkrümmungsfilter** können Sie Ihr Material auf der Grundlage einer Reihe generierter Rauschen verkrümmen.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Rauschen Selection**:\
  Wähle die Rauschen aus, auf der die Verkrümmung basieren soll. Verschiedene Rauschen können unterschiedliche Effekte erzeugen.
* **Rauschen-Skalierung**: 0-10\
  Passen Sie die Skalierung der Quell-Rauschen an. Die Rauschen wird immer kacheln.
* **Typ**:\
  Wählen Sie aus, mit welcher Methode das Material verkrümmt werden soll. Wenn **Richtungsverzerrung** oder **Mehrere Richtungsverzerrungen** ausgewählt sind, wird ein zusätzlicher Parameter angezeigt:
  * **Verkrümmungswinkel**: 0-1\
    Richtung der Verformung anpassen.
* **Intensität**: 0-1\
  Passe die Stärke der Verformung an.
* **Benutzerdefinierte Rauschen**: Knebel\
  Aktivieren Sie diese Option, um eine benutzerdefinierte Rauschen anstelle der Auswahl unter **Rauschen Selection** zu verwenden. Die verfügbaren Parameter ändern sich je nachdem, ob **Benutzerdefinierte Rauschen** aktiviert oder deaktiviert ist. Wenn diese Option aktiviert ist, werden die folgenden Parameter angezeigt:
  * **Benutzerdefiniertes Rauschen weichzeichnen**: 0-1\
    Rauschen weichzeichnen
  * **Benutzerdefinierte Rauschen**: Bild/Pinsel\
    Importieren Sie eine benutzerdefinierte Rauschen-Map, die als Verkrümmungsquelle verwendet werden soll.
* **Verkrümmung pro Kanal**: Knebel\
  Wenn diese Option aktiviert ist, werden zusätzliche Abschnitte angezeigt, um die Verkrümmung jedes Kanals unabhängig zu steuern. Für jeden Kanal stehen die folgenden Parameter zur Verfügung:
  * ***Kanalname***: Knebel\
    Stellt ein, ob dieser Kanal durch den **Verkrümmungsfilter** beeinflusst wird.
  * **Füllmethode**:\
    Wählen Sie aus, wie die Ergebnisse der Verformung für diesen Kanal mit der darunter liegenden Ebene vermischt werden sollen.
  * **Deckkraft**: 0-1\
    Ändern Sie die Deckkraft der Filterergebnisse für diesen Kanal.
