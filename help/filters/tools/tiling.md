---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/tiling.html"
breadcrumb-title: ''
description: Verwenden Sie das Kachelwerkzeug in Substance 3D Sampler, um nahtlose Kachelmuster aus Texturen für wiederholbare Materialoberflächen zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Tiling
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Kacheln
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Kacheln

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Kachelfilter**, um Ihr Material kachelbar zu machen. Mit dem **Filter &quot;Kacheln erstellen&quot;** können Sie Ihr Material auch kachelbar machen, aber jeder Filter funktioniert auf andere Weise. Wenn Sie feststellen, dass der **Kachelfilter** nicht für Sie funktioniert, versuchen Sie den **Kachelfilter erstellen**.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Naht anzeigen**: Knebel\
  Auswählen, ob die Naht angezeigt werden soll
* **Maske verwenden**: Knebel\
  Wenn diese Option aktiviert ist, können Sie eine benutzerdefinierte Maske erstellen, um die Nahtposition zu steuern.
  * **Maske**: Bild/Pinsel\
    Importieren Sie ein Bild, das als Maske verwendet werden soll, oder verwenden Sie den Pinsel, um eine Maske direkt in der **2D-Ansicht zu malen**

**Edge**

* **Kanten erkennen**: Knebel\
  Stellt ein, ob Ränder auf Basis der Materialkanäle erkannt werden sollen, um einen organischeren Übergang zwischen den Materialschichten zu erzeugen. Wenn aktiviert, werden die folgenden zusätzlichen Parameter angezeigt:
  * **Schwellenwert pro Kanal verwenden**: Knebel\
    Wenn diese Option aktiviert ist, werden zusätzliche Parameter angezeigt, mit denen Sie den Schwellenwert für jeden Kanal einzeln anpassen können.
    * **Schwellenwert-Basisfarbe**: 0-1
    * **Schwellenwert Normal**: 0-1
    * **Schwellenwert-Height**: 0-1
  * **Schwellenwert**: 0-1\
    Passen Sie den Schwellenwert an, mit dem die Naht ermittelt wird.
  * **Weichzeichnen**: 0-1\
    Bereich um die Nahtstelle weichzeichnen.
  * **Smoothness**: 0-2\
    Passen Sie die Smoothness der Naht an. So können Artefakte vermieden werden.
  * **Rasterauflösung**: 1-11\
    Passen Sie die Auflösung des Rasters an, auf dem die Naht gezeichnet wird. Niedrigere Auflösung kann die Leistung verbessern, aber die Nahtqualität beeinträchtigen.
  * **Grundfarbe verwenden**: Knebel\
    Umschalten, ob Grundfarbinformationen bei der Nahtgenerierung berücksichtigt werden
  * **Normal verwenden**: Knebel\
    Umschalten, ob normale Informationen bei der Nahtgenerierung berücksichtigt werden
  * **Height verwenden**: Knebel\
    Umschalten, ob Height-Informationen bei der Nahtgenerierung berücksichtigt werden
  * **Offset abschneiden**: 0-0,5\
    Versatz der Naht auf der X- und Y-Achse anpassen

**Erweiterte Parameter**

* **Transformieren**: 0-2\
  Passen Sie die Matrixtransformationswerte an. Erhöhe die X- und W-Werte, um die Stärke der Überlagerung zwischen dem darunterliegenden und dem darüberliegenden Material anzupassen.
* **Offset**: 0-1\
  Material um die X- und Y-Achse versetzen
* **Filtern**:\
  Wählen Sie die Filtermethode aus, die für skalierte Pixel verwendet werden soll. Bei der bilinearen Filterung werden Pixel unscharf dargestellt, während bei der nächstgelegenen Filterung die scharfe Kante zwischen den Pixeln beibehalten wird.
* **Eingabegröße**: 0-8192\
  Passen Sie die Größe der Eingabe in Pixel auf der X- und Y-Achse an.

## Benutzerhandbuch

Der **Kachelfilter** funktioniert in zwei Schritten:

1. Es skaliert und verschiebt Ihr Material, um eine Überlappung zu erzeugen.
1. Anschließend wird die Überlappungskante angepasst, um die Naht zu verbergen.

Wenn Sie also den **Kachelfilter** verwenden möchten, können Sie durch das Anpassen dieser beiden Teile des Prozesses die besten Ergebnisse erzielen.

1. Fügen Sie den **Kachelfilter** oben im Ebenenstapel hinzu.
1. Verwenden Sie die Griffe, um das Material so zu transformieren, dass es genügend Überlappung gibt, um die Naht zu verbergen.
   1. Die Skalierung des Materials kann hilfreich sein, um eine Überlappung zu erstellen, kann aber auch zu einem Detailverlust führen.
1. Passen Sie die Parameter im Abschnitt **Kante** an, um die Naht anzupassen.

Bei einigen Materialien, die nur den **Kachelfilter** verwenden, treten entlang der Naht immer noch Artefakte oder Probleme auf. In diesem Fall empfiehlt es sich, andere Filter wie **Kopierstempel** zu verwenden, um Naht- und Kachelprobleme zu beheben.

Es ist eine gute Praxis, an der Kachelung des Materials zu arbeiten, und zwar früh im Prozess der Materialerstellung. Sobald ein nicht gekacheltes Element dem Material hinzugefügt wird, ist es eine gute Idee, sicherzustellen, dass es gekachelt ist, bevor weiter gearbeitet wird. Die Filter von Sampler sind so konzipiert, dass sie Kachelmaterialien nicht beschädigen. Das bedeutet, dass Sie nach dem Anordnen der zugrunde liegenden Materialkacheln weiterhin mit Filtern und den in Sampler enthaltenen Materialien arbeiten können und Ihr Material weiterhin kachelt.
