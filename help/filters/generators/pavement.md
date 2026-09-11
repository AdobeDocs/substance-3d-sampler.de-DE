---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Verwenden Sie den Straßenbelaggenerator in Substance 3D Sampler, um realistische Texturen für den Straßenbelag und die Straßenoberfläche von Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pavement
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Fußweg
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 1%

---


# Fußweg

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pavement-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Wandeln Sie Ihr Material in ein Pflasterbild um. Der Pavement-Filter enthält eine Reihe von Optionen, um den Stil des Musters schnell und einfach zu ändern.

*Ein Beispiel für den **Pavement-Filter**.*

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Basismaterial-Skalierung**: 0-1\
  Steuern der Skalierung des in den einzelnen Ziegeln verwendeten Materials
* **Ziegel Abstand**: 0-1\
  Ändern des Abstands zwischen Ziegeln
* **Eckenrundung**: 0-1\
  Die Ecken von Ziegeln mehr oder weniger abrunden.
* **Kantenrundung**: 0-1\
  Glätten Sie die Kanten von Ziegeln, damit sie abgenutzt aussehen
* **Neigungsintensität**: 0-1\
  Ändern der Stärke der zufälligen Neigung, die auf jeden Ziegel angewendet wird
* **Intensität zufälliger Erhöhungen**: 0-1\
  Ändert die Height-Varianten von Ziegeln relativ zueinander.

**Muster**

Für jedes Muster ist ein anderer Parametersatz verfügbar, der angezeigt wird, wenn das Muster in **Mustertyp** ausgewählt wird. Experimentiere mit den Parametern, um den Effekt zu sehen.

* **Mustertyp**:\
  Wähle das Muster aus, auf das die Ziegel aufgetragen werden sollen.

**Joint**

* **Joint** **Height**: 0-1\
  Ändern des Heights des Materials zwischen Ziegeln
* **Gemeinsame Breite**: 0-1\
  Passen Sie an, wie weit das Material zwischen Ziegeln die Kanten von Ziegeln überlappt.
* **Variation der gemeinsamen Breite**: 0-1\
  Zufälligkeit der **gemeinsamen Breite** anpassen
* **Gemeinsame Luminanz**: 0-1\
  Ändern Sie das Aussehen des Materials zwischen den Steinen. Dies kann für Maskierungszwecke nützlich sein.

**Erweiterte Parameter**

* **Oberflächenstärke**: 0-1\
  Steuern Sie die Stärke der Normalen für Oberflächendeformationen wie Risse oder Dellen.
* **Oberflächengröße (cm)**: 0-1000\
  Passen Sie die Physische Größe des Materials an.
* **Skalierung des Surface Height (cm)**: 0-1000\
  Ändern des physischen Raums, der durch die Höhen-Map dargestellt wird
* **Surface-Smoothness**: 0-1\
  Steuern des Ausmaßes der Variation und des Details in der Oberfläche
* **Surface Poke**: 0-1\
  Fügen Sie der Fläche Schaden zu, indem Sie zufällig das Height und die Normalen ändern
* **Schwellenwert für Oberflächenspitzenmaske**: 0-1\
  Ändern Sie den Schwellenwert der Maske, die zum Steuern von **Surface Poke** verwendet wird.
* **Scalemap aktivieren**: Knebel\
  Verwenden Sie eine Skalierungszuordnung, um die Größe der Ziegel auf der Grundlage ihrer Position anzupassen.
* **Skalierungszuordnungsintensität**: 0-1\
  Passen Sie an, wie stark die Skalierungszuordnung die Skalierung von Ziegeln beeinflusst.
