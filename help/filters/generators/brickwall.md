---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/brickwall.html"
breadcrumb-title: ''
description: Verwenden Sie den Brickwall-Generator in Substance 3D Sampler, um realistische Ziegel-Wandmuster und Mauerwerk-Texturen für Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Brickwall
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Brickwall
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '558'
ht-degree: 0%

---


# Brickwall

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-brickwall-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

BeschreibungDer Brickwall-Filter erzeugt ein Ziegel-Muster auf Basis der darunterliegenden Ebenen. Dies ist nützlich für die Erstellung von Ziegel Wänden (wie der Name schon sagt), aber auch Böden, oder irgendwo anders Ziegel verwendet werden.

In den folgenden Abbildungen wird ein Material aus Ton mit dem **Brickwall-Ziegel in eine Steinmauer konvertiert.**

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0053-brickwall-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0052-brickwall-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Vorgaben**

Wählen Sie aus einer Reihe von Vorgaben aus, um schnell einen bestimmten Stil zu emulieren.

**Basisparameter**

* **Zufallsparameter**: Zufallszahl\
  Der Zufallswert, der zum Bestimmen anderer Zufallswerte in diesem Filter verwendet wird.\
  Klicken Sie auf die Zahl, um einen neuen zufälligen Wert zu erhalten. Wenn ein zufälliger Wert ausgewählt wurde, klicken Sie auf den Parameternamen, um den Wert auf 0 zurückzusetzen.
* **Ziegel-Bindung**:\
  Ziegel anhand des ausgewählten Stils zusammenführen
* **Ziegel Typ**:\
  Auswählen des Stils für Ziegel
* **Kachel**: 1-25\
  Ändern Sie die Kachelung auf der X- und Y-Achse.
* **Offset**: 0-1\
  Ändern Sie den Versatz für jede Zeile mit Ziegeln in der vorherigen Zeile.
* **Benutzerdefinierte Farbe verwenden**: Knebel\
  Ziegel anhand des ausgewählten Stils zusammenführen

**Mix**

* **Mischmodus**:\
  Ändert die Organisation von Ziegeln. Mit einem **Mischmodus** wird eine zweite Gruppe von Ziegeln erstellt, die unabhängig von der Grundmenge gesteuert werden können.\
  Wenn **Mischmodus** auf **Ohne** festgelegt ist, werden in diesem Abschnitt keine weiteren Parameter angezeigt.
* **Ziegel Typ 2**:\
  Wählen Sie den Stil der zweiten Gruppe von Ziegeln aus.
* **Height-Offset**: 0-1\
  Versatz des Heights der zweiten Gruppe von Ziegeln

**Zement**

* **Zementfarbe**: Farbwähler\
  Ändern Sie die Zementfarbe zwischen Ziegeln.
* **Cement-Rauheit**: 0-1\
  Ändern Sie die Rauheit des Zements zwischen Ziegeln.
* **Zement-Schnittstelle**: 0-1\
  Ändern Sie die Breite des Zements zwischen den Ziegeln. Ändert die Größe des Ziegels.
* **Zementebene**: 0-1\
  Ändern des Heights des Zements
* **Zement-Störung**: 0-1\
  Passen Sie die Ebenheit des Zements an. Bei hohen Werten kann Zement über die Ziegel steigen.

**Alter**

* **Ziegel-Störung**: 0-1\
  Passen Sie die Drehung jedes Ziegels nach dem Zufallsprinzip in 3 Dimensionen an.
* **Ziegel zertrümmern**: 0-1\
  Risse zu Ziegeln hinzufügen
* **Ziegel Edge**: 0-1\
  Beschädigen Sie die Kanten von Ziegeln und brechen Sie sie.
* **Ziegel wurde entfernt**: 0-1\
  Ziegel zufällig entfernen
* **Farbvariation des Ziegels**: 0-1\
  Variieren Sie die Farbgebung der Ziegel, um die Einheitlichkeit der Mauer zu verringern.
* **Ziegel: Schmutzig**: 0-1\
  Dirt zu Ziegeln hinzufügen

**Erweiterte Parameter**

* **Intensität der Height-Überblendung**: 0-1\
  Passen Sie die Überblendung des Heights aus dem Basismaterial an. Ein Wert von 0 ignoriert das Height des Basismaterials und verwendet nur die Brickwall-Filterparameter, um Height-Informationen zu generieren. Bei einem Wert von 1 wird das Basismaterial zum Generieren von Height-Informationen verwendet.
* **Normalintensität**: 0-1\
  Passen Sie die Stärke der vom Brickwall-Filter generierten Normalen an. Ein Wert von 0 bedeutet praktisch keine Normalen.
* **Ambient occlusion-Intensität**: 0-1\
  Passen Sie die Stärke der AO an. Ein Wert von 0 bedeutet praktisch kein Ambient occlusion.

Benutzerhandbuch

Der Brickwall-Filter teilt das darunter liegende Material in einzelne Ziegel auf, die es dann neu anordnet. Deshalb arbeitet der Brickwall-Filter am besten mit harten Oberflächen wie Steinen oder Metallen - also den Materialien, die sich am besten als Ziegel in der realen Welt eignen.

Der Brickwall-Filter ist nützlich, um ein Basismaterial zu erstellen, auf das du dann andere Effekte wie Moos, Schnee oder Dirt überlagern kannst.
