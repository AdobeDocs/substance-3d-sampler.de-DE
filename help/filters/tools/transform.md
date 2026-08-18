---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/transform.html"
breadcrumb-title: ''
description: Verwenden Sie das Transformieren-Werkzeug in Substance 3D Sampler, um Texturen und Materialebenen zu skalieren, zu drehen, zu verschieben und zu bearbeiten.
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

Verwenden Sie das **Transformieren-Werkzeug**, um Ihr Bild oder Material zu verschieben, zu skalieren oder zu drehen.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Steuerungsmodus**:\
  Wählen Sie aus, ob Parameter angezeigt werden sollen, um die Transformation zusätzlich zu den Handles **2D view** mit Reglern zu steuern.

  Wenn **Widget &amp; Parameters** ausgewählt ist, werden die folgenden zusätzlichen Steuerelemente angezeigt:

  * **Sichere Transformation**: Knebel\
    Aktivieren oder Deaktivieren sicherer Transformationen. Wenn diese Option aktiviert ist, behält der Transformationsknoten die Unterteilung bei und vermeidet den Verlust von Pixeldetails aufgrund kleiner Offsets und Drehungen. Dadurch wird die Freiheit eingeschränkt, die Transformation zu steuern, und beim Aktivieren von **Abgesicherte Transformation** werden einige Parameter ausgeblendet.
  * **Verhältnis beibehalten**: Knebel\
    Wenn diese Option aktiviert ist, ist nur ein **Skalierung**-Parameter sichtbar, der die Skalierung auf beiden Achsen gleichzeitig steuert. Wenn diese Option deaktiviert ist, stehen Steuerelemente zur Verfügung, um die Skalierung auf der horizontalen und der vertikalen Achse separat zu ändern.

    * **Skalierung**: 0-1\
      Je nachdem, ob **Verhältnis beibehalten** aktiviert oder deaktiviert ist, stehen 1 oder 2 Schieberegler zur Anpassung der Skalierung zur Verfügung.
  * **Drehung**; 0-360\
    Drehen Sie die Eingabe innerhalb der Handles.
  * **Neigung**: -1 bis 1\
    Neigen Sie die Eingabe innerhalb der Handles an der horizontalen und vertikalen Achse.
* **Positionsversatz**: -1 bis 1\
  Versatz der Transformation von der Ausgangsposition auf der horizontalen und vertikalen Achse.
* **Horizontal spiegeln**: Knebel\
  Eingabe horizontal spiegeln
* **Vertikal spiegeln**: Knebel\
  Eingabe vertikal spiegeln

**Erweiterte Parameter**

* **Transformation**:\
  Passen Sie die Transformation der Handles mit Schiebereglern anstelle in der **2D-Ansicht an**.
  * **Skalierung X**: 0-2
  * **Vertikale Neigung**: -7,44 bis 2
  * **Horizontal verzerren**: 0-1
  * **Skalierung Y**: 0-13.15 Uhr
* **Transformation pro Kanal deaktivieren**: Knebel\
  Wenn diese Option aktiviert ist, werden zusätzliche Steuerelemente angezeigt, mit denen Sie diese Transformation für jeden Kanal deaktivieren können.

## Benutzerhandbuch

Klicken Sie auf das **Transformieren-Werkzeug**, um eine neue Transformieren-Filterebene oben im Ebenenstapel hinzuzufügen.

Beim Erstellen oder Auswählen einer Transformieren-Filterebene wird automatisch die **2D-Ansicht** geöffnet. Wenn die Ebene &quot;Transformieren&quot; ausgewählt ist, wird oben in der **2D-Ansicht** eine **Symbolleiste** angezeigt.

## Funktionalität

![](../../assets/alchemist-2020-2-transform-1.gif){width="300px"}

### Verschieben

Verschieben der Ebene:

1. Bewegen Sie die Maus in das Transformationsfeld
1. Der Cursor ändert sich in vier Pfeile.
1. Klicke und ziehe, um das Transformationsfeld zu verschieben.

### Skalieren

So skalieren Sie die Ebene:

1. Führen Sie den Mauszeiger über einen der Ziehpunkte an der Kante oder Ecke des Transformationsfeldes.
1. Der Cursor ändert sich in vier Pfeile.
1. Klicke und ziehe, um das Transformationsfeld zu skalieren.

>[!NOTE]
>
> Mit den Griffen an der Ecke des Transformationsrahmens können Sie die Skalierung in zwei Dimensionen gleichzeitig durchführen, während die Griffe an der Kante des Transformationsrahmens die Skalierung in einer Dimension einschränken.

### Drehen

So drehen Sie die Ebene:

1. Bewegen Sie die Maus außerhalb des Transformationsfeldes, jedoch innerhalb der **2D-Ansicht**.
1. Neben dem Cursor erscheint ein kleiner horizontaler Pfeil.
1. Klicken und ziehen Sie, um das Transformationsfeld zu drehen.

>[!NOTE]
>
> Sie können den Drehpunkt ändern, indem Sie den kleinen Kreis in der Mitte des Transformationsfeldes ziehen. Der Transformationsrahmen dreht sich immer um diesen Kreis.

## Symbolleiste

![](../../assets/transform-toolbar.png){width="200px"}

Die Symbolleiste enthält die folgenden Tastaturbefehle:

* Quadratisch machen: Passen Sie die Skalierung der aktuellen Transformation an, um sie quadratisch zu machen.
* Drehung +90° (rechts): Drehung im Uhrzeigersinn um 90°.
* Drehung -90° (links): Drehung gegen den Uhrzeigersinn um 90°.
* Drehpunkt zurücksetzen: Setzen Sie den Drehpunkt auf den Mittelpunkt des Transformationsfeldes zurück.
* Transformation zurücksetzen: Setzen Sie das Transformieren-Werkzeug auf die Standardposition zurück.
