---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/transform.html"
breadcrumb-title: ''
description: Verwenden Sie das Transformieren-Werkzeug in Substance 3D Sampler, um Texturen und Material-Ebenen zu skalieren, zu drehen, Kamera bewegen und zu bearbeiten.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Transform
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Transformieren
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '553'
ht-degree: 1%

---


# Transformieren

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-transformgeneric-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie das **Transformieren-Tool**, um Ihr Bild oder Material zu verschieben, zu skalieren oder zu drehen.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Steuerungsmodus**:\
  Wählen Sie aus, ob zusätzlich zu den Handles **2D-Ansicht** Parameter angezeigt werden sollen, um den transformieren mit Reglern zu steuern.

  Wenn **Widget &amp; Parameters** ausgewählt ist, werden die folgenden zusätzlichen Steuerelemente angezeigt:

  * **Safe Transformieren**: Knebel\
    Aktivieren oder Deaktivieren sicherer Transformationen. Wenn diese Option aktiviert ist, behält der transformieren Knoten die Kachelung bei und vermeidet den Verlust von Pixeldetails aufgrund kleiner Offsets und Drehungen. Dadurch wird die Freiheit eingeschränkt, die Transformation zu steuern, und durch Aktivieren von **Safe Transformieren** werden einige Parameter ausgeblendet.
  * **Verhältnis beibehalten**: Knebel\
    Wenn diese Option aktiviert ist, wird nur ein **Skalierung**-Parameter angezeigt, der die Skalierung auf beiden Achsen gleichzeitig steuert. Wenn diese Option deaktiviert ist, stehen Steuerelemente zur Verfügung, um die Skalierung auf der horizontalen und der vertikalen Achse separat zu ändern.

    * **Skalierung**: 0-1\
      Je nachdem, ob **Verhältnis beibehalten** aktiviert oder deaktiviert ist, stehen 1 oder 2 Schieberegler zur Anpassung der Skalierung zur Verfügung.
  * **Drehung**; 0-360\
    Drehen Sie die Eingabe innerhalb der Handles.
  * **Neigung**: -1 bis 1\
    Neigen Sie die Eingabe innerhalb der Handles an der horizontalen und vertikalen Achse.
* **Positionsversatz**: -1 bis 1\
  Versetzen Sie den transformieren von der Ausgangsposition auf der horizontalen und der vertikalen Achse.
* **Horizontal spiegeln**: Knebel\
  Eingabe horizontal spiegeln
* **Vertikal spiegeln**: Knebel\
  Eingabe vertikal spiegeln

**Erweiterte Parameter**

* **Transformation**:\
  Passen Sie die Transformation der Handles mit Schiebereglern anstelle in der **2D-Ansicht** an.
  * **Skalierung X**: 0-2
  * **Vertikale Neigung**: -7,44 bis 2
  * **Horizontal verzerren**: 0-1
  * **Skalierung Y**: 0-13.15 Uhr
* **Transformation pro Kanal deaktivieren**: Knebel\
  Wenn diese Option aktiviert ist, werden zusätzliche Steuerelemente angezeigt, mit denen Sie diesen transformieren für jeden Kanal deaktivieren können.

## Benutzerhandbuch

Klicken Sie auf das **Transformieren-Tool**, um oben im Ebenenstapel eine neue Transformieren-Filterebene hinzuzufügen.

Beim Erstellen oder Auswählen einer Transformieren Filterebene wird automatisch die **2D-Ansicht** geöffnet. Wenn die Ebene &quot;Transformieren&quot; ausgewählt ist, wird oben in der **2D-Ansicht** eine **Symbolleiste** angezeigt.

## Funktionalität

![](../../assets/alchemist-2020-2-transform-1.gif){width="300px"}

### Verschieben

Verschieben der Ebene:

1. Bewegen Sie die Maus in das Transformationsfeld
1. Der Cursor ändert sich in vier Pfeile.
1. Klicke und ziehe, um das Feld &quot;transformieren&quot; zu verschieben.

### Skalieren

So skalieren Sie die Ebene:

1. Führen Sie den Mauszeiger über einen der Ziehpunkte an der Kante oder Ecke des transformieren Rahmens.
1. Der Cursor ändert sich in vier Pfeile.
1. Klicke und ziehe, um das Feld &quot;transformieren&quot; zu skalieren.

>[!NOTE]
>
> Mit den Griffen an der Ecke des Rahmens &quot;transformieren&quot; kannst du die Skalierung in zwei Dimensionen gleichzeitig durchführen. Die Griffe an der Kante des Rahmens &quot;transformieren&quot; beschränken die Skalierung in einer Dimension.

### Drehen

So drehen Sie die Ebene:

1. Bewegen Sie den Mauszeiger aus dem transformieren Feld heraus, jedoch innerhalb der **2D-Ansicht**.
1. Neben dem Cursor erscheint ein kleiner horizontaler Pfeil.
1. Klicken und ziehen Sie, um das transformieren Feld zu drehen.

>[!NOTE]
>
> Sie können den Drehpunkt ändern, indem Sie den kleinen Kreis in der Mitte des transformieren Rahmens ziehen. Der transformieren-Rahmen dreht sich immer um diesen Kreis.

## Symbolleiste

![](../../assets/transform-toolbar.png){width="200px"}

Die Symbolleiste enthält die folgenden Tastaturbefehle:

* Quadratisch machen: Passen Sie die Skalierung der aktuellen Transformation an, um sie quadratisch zu machen.
* Drehung +90° (rechts): Drehung im Uhrzeigersinn um 90°.
* Drehung -90° (links): Drehung gegen den Uhrzeigersinn um 90°.
* Drehpunkt zurücksetzen: Setzt den Mittelpunkt der Drehung auf den Mittelpunkt des Transformieren Rahmens zurück.
* Transformation zurücksetzen: Setzen Sie das Transformieren-Werkzeug auf die Standardposition zurück.
