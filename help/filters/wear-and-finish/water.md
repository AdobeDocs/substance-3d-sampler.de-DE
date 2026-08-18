---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/water.html"
breadcrumb-title: ''
description: Verwende den Wasserfilter in Substance 3D Sampler, um deinen Materialien und Strukturen Wassereffekte, Feuchtigkeit und Feuchtigkeit hinzuzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Water
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Wasser
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Wasser

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-water-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Erosionsfilter**, um an hohen Stellen Ihres Materials abzutragen.

![](../../assets/water-compare.png)

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Wasserstand**: 0-1\
  Passen Sie das Height des Wassers an.
* **Wasserdunkel**: 0-1\
  Mache das Wasser heller oder dunkler.
* **Kantennässe**: 0-1\
  Passe an, wie weit über der Wasserlinie das Material nass erscheint.
* **Dirt auf Wasser aktivieren**: Knebel\
  Fügen Sie dem oberen Teil des Wassers Dirt hinzu, indem Sie die Raueitskarte leicht ändern. Der **Parameterabschnitt** wird nur angezeigt, wenn dieser Dirt aktiviert ist.
* **Benutzerdefinierte Maske**: Knebel\
  Wenn diese Option aktiviert ist, wird das folgende zusätzliche Steuerelement angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als benutzerdefinierte Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine Maske direkt in der **2D-Ansicht**.

**Dirt**

Dieser Abschnitt wird nur angezeigt, wenn **Grundlegende Parameter > Dirt auf Wasser aktivieren** aktiviert ist.

* **Anzahl Dirt**: 0-1\
  Passen Sie die Menge des auf der Wasseroberfläche schwebenden Dirts an.
* **Intensität der Verzerrung**: 0-1\
  Steuern Sie die Verzerrung des Dirts der Oberfläche auf der Grundlage des Schnittpunkts zwischen dem Wasser und dem restlichen Material.
* **Rahmenintensität des Dirts**: 0-1\
  Stärke des Dirts in der Nähe der Ränder der Dirt-Maske verwalten.
* **Dirt-Randabstand**: 0-1\
  Lege fest, wie weit der Dirt vom Schnittpunkt zwischen der Nass- und der Trockenpartie des Materials entfernt ist.
* **Rahmengenauigkeit**: 0-1\
  Passen Sie die Präzision des Dirts an.
* **Randverkrümmung**: 0-1\
  Verformen Sie die Begrenzungslinie, um die Gleichmäßigkeit der Dirt-Oberfläche aufzubrechen.

**Erweiterte Parameter**

* **Kantenfeuchtigkeitsentfernung**: 0-1\
  Kontrollieren Sie, wie weit in trockene Bereiche die Kantenfeuchtigkeit reicht.
* **Tiefen-Weichzeichnungsbetrag**: 0-1\
  Passen Sie an, wie stark die Grundfarbe für Bereiche unter Wasser weichgezeichnet wird.
* **Tiefe-Weichzeichnungsdeckkraft**: 0-1\
  Passe die Transparenz des Wassers an.
* **Schlammfarbe**: Farbauswahl\
  Ändere die Farbe des Dirts, der auf der Wasseroberfläche liegt.
* **Schlammdeckkraft**: 0-1\
  Stellen Sie die Transparenz des Schlamms ein.
