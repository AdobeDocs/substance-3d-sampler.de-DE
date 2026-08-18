---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Verwenden Sie den Korrosionsfilter in Substance 3D Sampler, um Korrosion und chemische Abbaueffekte zu Metallmaterialien hinzuzufügen.
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

Der Korrosionsfilter ahmt den Effekt von Säure nach, die sich an Ihrem Material absetzt und Löcher hinterlässt und die Oberfläche beschädigt.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Betroffene Bereiche**:\
  Wählen Sie aus, wie sich die Krümmung der Oberfläche auf den Effekt des Filters auswirkt.
* **Leistungsstufe**: 0-1\
  Passen Sie die Anzahl der erstellten Bohrungen an.
* **Krümmungsposition**: 0-1\
  Ändern Sie den zu ändernden Krümmungsbereich.
* **Kurvenglättung**: 0-1\
  Glätten der Krümmungskarte.
* **Schadensentfernung**: 0-1\
  Steuern Sie den Schadensradius in den korrodierten Bereichen.
* **Schadensintensität**: 0-1\
  Passen Sie die Schadenshöhe in den betroffenen Bereichen an.
* **Height-Intensität**: 0-1\
  Kontrollieren Sie die Auswirkungen der Beschädigung auf die Karte des Heights.
* **Position** extrudieren: Knebel\
  Ändern Sie die Schadensrichtung auf der Karte des Heights. Bei deaktivierter Funktion frisst sich der Schaden in die Oberfläche. Wenn diese Option aktiviert ist, baut sich der Schaden von der Oberfläche nach außen auf.

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

Einige der erweiterten Parameter wirken sich auf das gesamte Material aus, nicht nur auf die von diesem Filter geänderten Bereiche.

* **Luminanz**: 0-1\
  Passe Luminanz oder Helligkeit an, um das gesamte Material zu erhalten.
* **Kontrast**: -1 bis 1\
  Passe den Kontrast der Albedo für das gesamte Material an.
* **Farbtonverschiebung**: 0-1\
  Versatz des Farbtonwerts der Farben im gesamten Material.
* **Sättigung**: 0-1\
  Passe die Sättigung für das gesamte Material an.
* **Normalintensität**: 0-1\
  Passen Sie die Intensität der normalen Karte an, auf die sie durch den **Korrosionsfilter** eingewirkt wurde.
* **Height-Bereich**: 0-1\
  Erhöhen Sie den Wertebereich in der Materialkarte für das gesamte Height.
* **Height-Position**: 0-1\
  Versatz das Height des gesamten Materials.
* **Umgebungsintensität der Verdeckung**: 0-1\
  Passen Sie die Stärke des AO-Effekts aufgrund des **Korrosionsfilters** an.
