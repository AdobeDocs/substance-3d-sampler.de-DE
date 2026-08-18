---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/brickwall.html"
breadcrumb-title: ''
description: Verwenden Sie den Brickwall-Generator in Substance 3D Sampler, um realistische Muster von Backsteinwänden und Mauerwerkstexturen für Materialien zu erstellen.
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

BeschreibungDer Brickwall-Filter erzeugt ein Backsteinmuster basierend auf den Ebenen darunter. Dies ist nützlich für die Schaffung von Ziegelmauern (wie der Name schon sagt), aber auch Böden, oder irgendwo anders Ziegelsteine verwendet werden.

In den folgenden Bildern wird ein Tonmaterial mit dem **Brickwall-Filter in eine Ziegelwand umgewandelt.**

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
* **Brick Bond**:\
  Zusammenfügen von Steinen basierend auf dem ausgewählten Stil
* **Ziegeltyp**:\
  Wählen Sie den Stil des Ziegels aus
* **Kachel**: 1-25\
  Ändern Sie den Umfang der Unterteilung auf der X- und Y-Achse.
* **Offset**: 0-1\
  Ändern Sie den Versatz jeder Ziegelreihe in der vorhergehenden Zeile.
* **Benutzerdefinierte Farbe verwenden**: Knebel\
  Zusammenfügen von Steinen basierend auf dem ausgewählten Stil

**Mix**

* **Mischmodus**:\
  Ändert die Organisation von Bausteinen. Mit einem **Mischmodus** wird ein zweiter Satz von Steinen erstellt, der unabhängig vom Basissatz gesteuert werden kann.\
  Wenn **Mischmodus** auf **Ohne** festgelegt ist, werden in diesem Abschnitt keine weiteren Parameter angezeigt.
* **Ziegeltyp 2**:\
  Wählen Sie den Stil des zweiten Satzes Ziegel.
* **Height-Offset**: 0-1\
  Versatz des Heights der zweiten Gruppe von Ziegeln

**Zement**

* **Zementfarbe**: Farbwähler\
  Ändern Sie die Farbe des Zements zwischen den Steinen.
* **Zement-Raueit**: 0-1\
  Ändern Sie die Rauhigkeit des Zements zwischen den Steinen.
* **Zement-Schnittstelle**: 0-1\
  Ändern Sie die Breite des Zements zwischen den Steinen. Ändert die Größe des Steins.
* **Zementebene**: 0-1\
  Ändern des Heights des Zements
* **Zement-Störung**: 0-1\
  Passen Sie die Ebenheit des Zements an. Bei hohen Werten kann Zement über die Ziegel steigen.

**Alter**

* **Ziegel-Störung**: 0-1\
  Passen Sie die Rotation jedes Steins nach dem Zufallsprinzip in 3 Dimensionen an.
* **Ziegelzertrümmerung**: 0-1\
  Risse in Steinen einfügen
* **Brick Edge**: 0-1\
  Beschädigen und Brechen der Kanten von Ziegeln
* **Verborgener Ziegel**: 0-1\
  Ziegelsteine zufällig entfernen
* **Brick-Farbvariation**: 0-1\
  Variieren Sie die Farbe der Steine, um die Wand weniger einheitlich aussehen zu lassen
* **Schmutziges Ziegelstein**: 0-1\
  Dirt zu Steinen hinzufügen

**Erweiterte Parameter**

* **Height-Mischintensität**: 0-1\
  Passen Sie die Überblendung des Heights aus dem Basismaterial an. Ein Wert von 0 ignoriert das Height des Basismaterials und verwendet nur die Brickwall-Filterparameter, um Height-Informationen zu generieren. Bei einem Wert von 1 wird das Basismaterial zum Generieren von Height-Informationen verwendet.
* **Normalintensität**: 0-1\
  Passen Sie die Stärke der vom Brickwall-Filter generierten Normalen an. Ein Wert von 0 bedeutet praktisch keine Normalen.
* **Umgebungsintensität der Verdeckung**: 0-1\
  Passen Sie die Stärke der AO an. Ein Wert von 0 bedeutet praktisch keine Ambient-Verdeckung.

Benutzerhandbuch

Der Brickwall-Filter zerlegt das darunter liegende Material in einzelne Steine, die er dann neu anordnet. Deshalb arbeitet der Brickwall-Filter am besten mit harten Oberflächen wie Steinen oder Metallen - also den Materialien, die am besten dazu geeignet sind, in der realen Welt Steine zu sein.

Der Brickwall-Filter ist nützlich, um ein Basismaterial zu erstellen, auf das du dann andere Effekte wie Moos, Schnee oder Dirt überlagern kannst.
