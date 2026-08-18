---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/generators/perforate.html"
breadcrumb-title: ''
description: Verwenden Sie den Perforate-Generator in Substance 3D Sampler, um perforierte Muster und Locharrays in Materialien und Texturen zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Perforate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: durchbohren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---


# durchbohren

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-perforation-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den Perforate-Filter, um Ihrem Material Löcher hinzuzufügen.

*Vor und nach Anwendung des **Perforate-Filters**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0007-perforate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0006-perforate-out.jpg){width="200px"}

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
* **Musterauswahl**:\
  Wählen Sie die Form der Bohrungen aus, oder wählen Sie ein eigenes Muster.
* **Perforationsposition**:\
  Lege fest, ob die Normalen und das Height in dein Material eingelassen werden oder sich vom Material abheben.
* **Größe der Perforationsschräge**: 0-1\
  Ändern der Größe der Fase an den Rändern von Bohrungen
* **Bohrungsgröße**: 0-1\
  Ändern der Größe der Bohrungen
* **Maske verwenden**: Knebel\
  Aktiviert den **Maskenabschnitt**, mit dem Sie die Perforation mit einem Pinsel oder Bild maskieren können.
* **Skalierungszuordnung verwenden**: Knebel\
  Aktiviert die Verwendung einer Skalierungskarte. Wenn diese Option aktiviert ist, werden die folgenden Parameter angezeigt:
  * **Zuordnungsmultiplikator skalieren**: 0-1\
    Passen Sie den Einfluss der Skalierungskarte auf die Größe der Perforation an.
  * **Skalierungszuordnung umkehren**: Knebel\
    Umkehren der Werte der Skalierungszuordnung
  * **Benutzerdefinierte Skalierungszuordnung**: Bild/Pinsel\
    Importieren Sie ein Bild, das als Maßstabszuordnung verwendet werden soll, oder verwenden Sie den Pinsel, um eine Maßstabszuordnung direkt in der **2D** **Ansicht** zu malen.

**Maske**

Dieser Abschnitt ist nur sichtbar, wenn **Grundlegende Parameter > Maske verwenden** aktiviert ist.

* **Maske umkehren**:
* **Maske weichzeichnen**: 0-1\
  Weichzeichner auf die Maske anwenden.
* **Maskenschwellenwert**: 0-1\
  Ändern Sie den Schwellenwert der Maske. Verwenden Sie die Werte **Maskenunschärfe** und **Maskenschwellenwert** zusammen, um die Kanten Ihrer Maske zu optimieren.
* **Benutzerdefinierte Maske**: Bild/Pinsel\
  Importieren Sie ein Bild, das als Maske verwendet werden soll, oder malen Sie Ihre eigene Maske direkt in der **2D-Ansicht**.

**Perforation**

* **Perforationsgröße**: 0-1\
  Ändern Sie die Größe jeder Perforation - dies schließt das Loch und die Fase ein.
* **Anzahl der Perforation Y**: 1-64\
  Anzahl der Perforationen auf der Y-Achse anpassen
* **Perforation x Betrag**: 1-64\
  Anzahl der Perforationen auf der X-Achse anpassen
* **Perforationsdichte**: 0-1\
  Perforationen zufällig maskieren
* **Perforationsversatz**: 0-1\
  Anpassen des Versatzes jeder zweiten Perforationsreihe
* **Perforationsfarbdeckkraft**: 0-1\
  Transparenz der Farbe des abgeschrägten Bereichs der Perforationen anpassen
* **Perforationsfarbe**: Farbauswahl\
  Wählen Sie die Farbe des abgeschrägten Bereichs jeder Perforation aus.
* **Raueit der Perforation**: 0-1\
  Ändern des Raueitswerts von Perforationen
* **Perforation Metallic**: 0-1\
  Ändern des metallischen Werts von Perforationen

**Erweiterte Parameter**

* **Luminanz**: 0-1
* **Kontrast**: -1 bis 1
* **Farbtonverschiebung**: 0-1
* **Sättigung**: 0-1
* **Normalintensität**: -1 bis 1\
  Stärke jeder Perforationsnorm anpassen
* **Height-Intensität**: 0-1\
  Stärke der einzelnen Perforationsdiagramme anpassen (Height Map)
