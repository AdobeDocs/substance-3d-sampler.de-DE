---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/wear-and-finish/oxidate.html"
breadcrumb-title: ''
description: Verwenden Sie den Oxidationsfilter in Substance 3D Sampler, um Metallmaterialien für gealterte Erscheinungsbilder mit Oxidations- und Anschmutzungseffekten zu versehen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Oxidate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: oxidieren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---


# oxidieren

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-oxidate-18-n-d.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Fügen Sie eine Oxidationsschicht auf der Oberseite Ihres Materials hinzu.*Auf eine zerknitterte Oberfläche wird der **Oxidationsfilter**&#x200B;angewendet.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0019-oxidate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0018-oxidate-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Zielbereiche**: Knebel\
  Aktivieren Sie diese Option, um festzulegen, wie der Oxidationseffekt auf das Material angewendet wird. Wenn diese Option aktiviert ist, wird das folgende Steuerelement angezeigt:
  * **Stärke für Zielbereiche**: 0-1\
    Passen Sie die Verteilung des Effekts &quot;Zielbereiche&quot; an.
  * **Verteilung**: 0-1\
    Passen Sie an, wie weit sich die oxidierende Wirkung ausbreitet.
* **Farbe**: Farbauswahl\
  Wählen Sie die Grundfarbe des Filters aus. Die Grundfarben ändern den Farbton aller Farben, aus denen der oxidierende Effekt besteht.
* **Farbvariationen**: 0-1\
  Passen Sie die Skalierung des Effekts &quot;Farbvariation&quot; an.
* **Dichte**: 0-1\
  Ändern Sie die Deckungsdichte des Effekts.
* **Anschnitt der Kante**: 0-1\
  Ändern Sie, wie die Ränder des Oxidationseffekts in nicht oxidierte Bereiche verlaufen.
* **Patches**: 0-1\
  Dies ist ein separates Steuerelement zum Ändern der Maske zwischen oxidierten und nicht oxidierten Bereichen. Kombinieren Sie sie mit der Dichte und anderen Steuerelementen, um die Kanten der oxidierten Bereiche zu optimieren.
* **Chipping**: 0-1\
  Späne im oxidierten Bereich ab, um das darunter liegende Material zu zeigen.
* **Stains**: 0-1\
  Passen Sie die Stärke der Farbüberlagerung auf dem Material an.
* **Raueit der Korrosion**: 0-1\
  Passen Sie die Raueit der oxidierten Bereiche an.
* **Korrosionsmetall**: 0-1\
  Passen Sie die metallischen Werte der oxidierten Bereiche an.
* **Rauschstärke**: 0-1

**Maske**

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Die Maske weichzeichnen.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.
  * **Benutzerdefinierte Maskendeckkraft**: 0-1\
    Passe die Deckkraft der Maske an.

**Technische Parameter**

Mit den folgenden Parametern können Sie den benannten Wert für das gesamte Material anpassen, ohne eine Einstellungsebene wie **Helligkeit/Kontrast** oder **Farbton/Sättigung** hinzuzufügen.

* **Luminanz**: 0-1
* **Kontrast**: -1 bis 1
* **Farbtonverschiebung**: 0-1
* **Sättigung**: 0-1
* **Normalintensität**: 0-1
* **Height-Bereich**: 0-1
* **Height-Position**: 0-1
* **Umgebungsintensität der Verdeckung**: 0-1
