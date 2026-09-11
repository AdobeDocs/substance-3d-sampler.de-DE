---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Verwenden Sie den Korrosionsfilter in Substance 3D Sampler, um metallische Materialien mit Korrosions- und chemischen Abbaueffekten zu versehen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Corrode
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: korrodieren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---


# korrodieren

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/corrode-filter-icon.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Der Korrosionsfilter ahmt die Wirkung von Säure nach, die sich an Ihrem Material absetzt und Löcher hinterlässt und die Oberfläche beschädigt.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Betroffene Bereiche**:\
  Wählen Sie aus, wie sich die Krümmung der Fläche auf die Wirkung des Filters auswirkt.
* **Leistungsstufe**: 0-1\
  Passen Sie die Anzahl der erstellten Bohrungen an.
* **Position der Krümmung**: 0-1\
  Ändern Sie den zu ändernden Krümmung-Bereich.
* **Krümmung glatt**: 0-1\
  Krümmungs-Map glätten.
* **Schadensentfernung**: 0-1\
  Steuern Sie den Schadensradius in den korrodierten Bereichen.
* **Schadensintensität**: 0-1\
  Passen Sie die Schadenshöhe in den betroffenen Bereichen an.
* **Height-Intensität**: 0-1\
  Steuern Sie die Auswirkungen der Beschädigung der Höhen-Map.
* **Position** extrudieren: Knebel\
  Ändern Sie die Schadensrichtung auf dem Höhen-Map. Bei deaktivierter Funktion frisst sich der Schaden in die Oberfläche. Wenn diese Option aktiviert ist, baut sich der Schaden von der Oberfläche nach außen auf.

**Maske**

* **Benutzerdefinierte Maske verwenden**: Knebel\
  Aktivieren oder Deaktivieren der Verwendung einer benutzerdefinierten Maske. Wenn aktiviert, werden die folgenden Parameter angezeigt:
  * **Maske**: Bild/Pinsel\
    Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.
  * **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
    Die Maske weichzeichnen.
  * **Benutzerdefinierte Maske - Umkehren**: Knebel\
    Kehre die Maske um.

**Erweiterte Parameter**

Einige der erweiterten Parameter wirken sich auf das gesamte Material aus, nicht nur auf die Bereiche, die mit diesem Filter verändert wurden.

* **Luminanz**: 0-1\
  Passe Luminanz oder Helligkeit an, um das gesamte Material zu erfassen.
* **Kontrast**: -1 bis 1\
  Passe den Albedo-Kontrast für das gesamte Material an.
* **Farbtonverschiebung**: 0-1\
  Versatz des Farbtonwerts der Farben im gesamten Material.
* **Sättigung**: 0-1\
  Passe die Sättigung für das gesamte Material an.
* **Normalintensität**: 0-1\
  Passen Sie die Intensität der Normalen-Map an, wenn sie durch den **Korrosionsfilter** beeinträchtigt wurde.
* **Height-Bereich**: 0-1\
  Erhöhen Sie den Wertebereich auf der Höhen-Map für das gesamte Material.
* **Height-Position**: 0-1\
  Versatz das Height des gesamten Materials.
* **Ambient occlusion-Intensität**: 0-1\
  Passen Sie die Stärke der AO-Auswirkung aufgrund des **Korrosionsfilters** an.
