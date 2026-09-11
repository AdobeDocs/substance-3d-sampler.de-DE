---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/moss.html"
breadcrumb-title: ''
description: Verwende den Moosfilter in Substance 3D Sampler, um Materials realitätsgetreues Mooswachstum und organische Oberflächeneffekte zu verleihen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Moss
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Moos
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 0%

---


# Moos

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/moss-filter-icon.png)

**In:** Verschleiß und Ende

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Moosfilter**, um Moos und Flechten zu Ihrem Material hinzuzufügen. **Moss** verwendet die Verdeckung-Map Ihres Materials, um in Rissen und Spalten natürlich zu wachsen.

Die folgenden Bilder zeigen das Moosmaterial, bevor und nachdem der **Dirt-Filter** angewendet wurde.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0021-moss-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0020-moss-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Die Zufallsgeschwindigkeit, auf der alle anderen Zufallsparameter in diesem Filter basieren.
* **Globale MOSS-Verteilung**: 0-1\
  Passen Sie die Abdeckung des Mooses auf Ihrem Material an.
* **Moosfarbe**: Farbauswahl\
  Wählen Sie die Primärfarbe des Mooses aus.
* **Sekundäre Moosfarbe**: Farbauswahl\
  Wählen Sie die Sekundärfarbe des Mooses aus.
* **Moss-Partition**:\
  Wählen Sie die Methode aus, mit der das Moos angewendet wird. Standardmäßig verwendet **Verdeckung** die AO-Map Ihres Materials, um das Moos anzuwenden, aber die anderen Optionen haben unterschiedliche Auswirkungen. Wenn **Benutzerdefiniert** **Maske** ausgewählt ist, wird die **Maske** **Abschnitt** angezeigt.

**Maske**

Dieser Abschnitt wird nur angezeigt, wenn **Benutzerdefinierte Maske** unter **Grundlegende Parameter > Moss-Partition** ausgewählt wurde.

* **Benutzerdefinierte Maske - Weichzeichnen**: 0-1\
  Die Maske weichzeichnen.
* **Benutzerdefinierte Maske - Umkehren**: Knebel\
  Kehre die Maske um.
* **Benutzerdefinierte Maske**: Bild/Pinsel\
  Wählen Sie ein Bild aus, das als Maske verwendet werden soll, oder malen Sie mit dem Pinsel eine benutzerdefinierte Maske direkt in der 2D-Ansicht.

**Moos**

Die verfügbaren Parameter in diesem Abschnitt hängen davon ab, welche Option unter **Basisparameter > Moss-Partition** ausgewählt ist.

* **Verdeckung**
  * **Moss Verdeckung Propagation**: 0-1\
    Steuern Sie die Ausbreitung des Mooses auf der Grundlage der Verdeckung.
  * **Maske der MOSS-Verdeckung**: 0-1\
    Passen Sie die Anzahl der Moose mithilfe der Maskenkarte als Verdeckung an.
* **Insgesamt**
  * **Gesamtausbreitung des MOSS**: 0-1\
    Passen Sie die Menge des Mooses an, das angezeigt werden soll.
* **Oben**
  * **Schwellenwert für oberes Moos**: 0-1\
    Steuern Sie den Schwellenwert, der bestimmt, ob Moos angezeigt wird.
  * **Oberer Mooswinkel** Passen Sie anhand der Normalen-Map an, wie das Moos auf das Material angewendet wird.
* **Alle**
  * **All** enthält alle oben genannten Parameter für **Verdeckung**, **Insgesamt** und **Top**.

Die folgenden Parameter sind unabhängig davon verfügbar, welche Option unter **Basisparameter > Moss-Partition** ausgewählt ist.

* **Größe der Moosblumen**: 0-1\
  Ändern der Granularität des Mooses.
* **Mooskornintensität**: 0-1\
  Passen Sie an, wie sichtbar die Körnung des Mooses ist.
* **Größe der Moosklumpen**: 0-1\
  Kontrolliere die Tendenz des Mooses, sich zu verklumpen.
* **Moos klumpt Schärfe**: 0-1\
  Passen Sie an, wie weich die Kanten der Klumpen erscheinen sollen.
* **Moosklumpintensität**: 0-1\
  Kontrolliere die Intensität der Klumpen des Mooses.
* **Moosfeder**: 0-1\
  Passen Sie an, wie die Kanten der Moosmaske weichgezeichnet werden.
* **Moossprungintensität**: 0-1\
  Ändern Sie die Unebenheiten des Mooses.
* **Schwellenwert für oberes Moos**: 0-1

**Technische Parameter**

* **Normalintensität**: 0-1\
  Passen Sie die Stärke der Moos-Normalwerte an.
* **Ambient occlusion-Intensität** Steuern Sie die Stärke der Moss-ambient occlusion.
