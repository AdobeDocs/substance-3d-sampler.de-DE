---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Erstelle mit dem Straßenbelag-Generator in Substance 3D Sampler realistische Oberflächen- und Straßenbeläge für Materialien.
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

Wandle dein Material in ein Straßenmuster um. Der Pavement-Filter enthält eine Reihe von Optionen, um den Stil des Musters schnell und einfach zu ändern.

*Ein Beispiel für den **Pavement-Filter**.*

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Zufallsparameter**:\
  Der Zufallswert bestimmt die Zufallswerte anderer Parameter, die den Zufallswert in diesem Filter verwenden.
* **Basismaterial-Skalierung**: 0-1\
  Steuern Sie den Maßstab des verwendeten Materials in jedem Stein
* **Ziegel**: 0-1\
  Ändern des Abstands zwischen Steinen
* **Eckenrundung**: 0-1\
  Die Ecken der Steine sollten mehr oder weniger rund sein.
* **Kantenrundung**: 0-1\
  Glätten Sie die Kanten von Ziegeln, um sie abgenutzt aussehen zu lassen
* **Neigungsintensität**: 0-1\
  Ändern der Stärke der zufälligen Neigung, die auf jeden Stein angewendet wird
* **Intensität zufälliger Erhöhungen**: 0-1\
  Ändert die Height-Varianten von Steinen relativ zueinander.

**Muster**

Für jedes Muster ist ein anderer Parametersatz verfügbar, der angezeigt wird, wenn das Muster in **Mustertyp** ausgewählt wird. Experimentiere mit den Parametern, um den Effekt zu sehen.

* **Mustertyp**:\
  Wählen Sie das Muster aus, auf das die Steine platziert werden sollen.

**Joint**

* **Joint** **Height**: 0-1\
  Das Height des Materials zwischen Steinen ändern.
* **Gemeinsame Breite**: 0-1\
  Passen Sie an, wie weit das Material zwischen den Steinen die Ränder der Steine überlappt.
* **Variation der gemeinsamen Breite**: 0-1\
  Zufälligkeit der **gemeinsamen Breite** anpassen
* **Gemeinsame Luminanz**: 0-1\
  Ändern Sie das Aussehen des Materials zwischen den Steinen. Dies kann für Maskierungszwecke nützlich sein.

**Erweiterte Parameter**

* **Oberflächenstärke**: 0-1\
  Lege die Stärke der Normalen für Verformungen der Oberfläche fest, z. B. Risse oder Dellen.
* **Oberflächengröße (cm)**: 0-1000\
  Passen Sie die Physische Größe des Materials an.
* **Skalierung des Surface Height (cm)**: 0-1000\
  Ändern des physischen Raums, der durch die Height-Map dargestellt wird
* **Surface-Smoothness**: 0-1\
  Steuern des Ausmaßes der Variation und des Details in der Oberfläche
* **Surface Poke**: 0-1\
  Fügen Sie der Fläche Schaden zu, indem Sie zufällig das Height und die Normalen ändern
* **Schwellenwert für Oberflächenspitzenmaske**: 0-1\
  Ändern Sie den Schwellenwert der Maske, die zum Steuern von **Surface Poke** verwendet wird.
* **Scalemap aktivieren**: Knebel\
  Verwenden Sie eine Skalierungszuordnung, um die Größe der Steine basierend auf ihrer Position anzupassen.
* **Skalierungszuordnungsintensität**: 0-1\
  Passen Sie an, wie stark die Skalierungszuordnung die Skalierung von Bausteinen beeinflusst.
