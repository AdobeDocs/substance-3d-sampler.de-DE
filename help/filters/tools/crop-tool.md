---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/crop-tool.html"
breadcrumb-title: ''
description: Mit dem Freistellungswerkzeug in Substance 3D Sampler kannst du Texturen und Materialebenen zuschneiden und ihre Größe ändern, ohne die Abmessungen zu ändern.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Crop tool
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Freistellungswerkzeug
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '707'
ht-degree: 0%

---


# Freistellungswerkzeug

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-crop-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie das **Freistellungswerkzeug**, um die Freistellung Ihres Bildes oder Materials anzupassen. Das **Freistellungswerkzeug** funktioniert sehr ähnlich wie das **Transformieren-Werkzeug**. Mit dem **Transformieren-Tool** verhalten sich Änderungen am transformieren-Feld eins zu eins mit dem zugrunde liegenden Bild, sodass das Erhöhen der Skalierung des Transformieren-Felds die Größe des zugrunde liegenden Bildes erhöht. Mit dem **Freistellungswerkzeug** wird diese Beziehung umgekehrt, da durch Erhöhen der Skalierung des Freistellungsfeldes die Größe des zugrunde liegenden Bildes verringert wird. Aus diesem Grund kann es bei Verwendung des **Freistellungswerkzeugs** hilfreich sein, die **2D-Ansicht** so festzulegen, dass Ebeneneingänge anstelle der Standardmaterialausgänge angezeigt werden.

Das **Freistellungswerkzeug** ist nützlich, um Anpassungen an Bildern vorzunehmen, die nicht standardmäßige Seitenverhältnisse aufweisen. Beispielsweise können Sie das Freistellungswerkzeug verwenden, um die Skalierung eines importierten Bildes über die Parameter für die Eingabegröße im **Eigenschaftenbedienfeld** anzupassen.

>[!NOTE]
>
> Beachten Sie, dass das **Freistellungswerkzeug** entweder für Bilder oder Materialien verwendet werden kann. Wenn im Ebenenstapel unter der **Zuschneideebene** ein Bild- oder Scankanal vorhanden ist, wird der **Zuschneidefilter** auf den Scankanal angewendet. Wenn kein Bild- oder Scankanal vorhanden ist, ändert der **Zuschneidefilter** stattdessen das Material.

In den folgenden Bildern sehen Sie das **Freistellungswerkzeug** in Aktion.

![](../../assets/3d-2d-filters-cropped-0047-crop-in.jpg)

Beachten Sie, dass die 2D-Ansicht so eingestellt ist, dass Ebeneneingaben angezeigt werden, sodass die Handles in **2D-Ansicht** zeigen, welcher Bereich der Eingabe zur Ausgabe wird.

![](../../assets/3d-2d-filters-cropped-0046-crop-out.jpg)

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Eingabegröße**: 0-8192\
  Passen Sie die Größe der Eingabe in Pixel auf der X- und Y-Achse an.

**Erweiterte Parameter**

* **Filterung**:\
  Wählen Sie die Filterung-Methode aus, die auf die skalierten Pixel angewendet wird. Bilineare Filterung verwischt Pixel ineinander, während &quot;Nächste Filterung&quot; die Kanten beibehält.
* **Transformieren Zuschneiden**: 0-1\
  Ändern Sie die Matrixwerte des transformieren. Durch Bearbeiten dieser Werte erhalten Sie eine präzisere Kontrolle über die Drehung und Skalierung sowie die Möglichkeit, die Zuschneideziehpunkte zu neigen.
* **Offset für Zuschneiden**: 0-1\
  Versatz die Freistellung von der Ausgangsposition.

## Benutzerhandbuch

>[!NOTE]
>
> Der Zuschneidefilter hat eine eigene Auflösung. Er schneidet und gibt die entsprechende Auflösung aus, abhängig vom zugeschnittenen Material oder Bild. Um optimale Ergebnisse zu erzielen, setzen Sie die oben genannten Ebenen in &quot;Max. Eingabe&quot; und verwenden Sie einen &quot;Hochskalieren&quot;-Modus, um die Endergebnisse zu vergrößern.

Klicken Sie auf das **Freistellungswerkzeug**, um eine neue Freistellungsfilterebene oben im Ebenenstapel hinzuzufügen.

Beim Erstellen oder Auswählen einer Ebene des Zuschneidefilters wird die **2D-Ansicht** automatisch geöffnet. Bei ausgewählter Ebene &quot;Zuschneiden&quot; wird oben in der **2D-Ansicht** eine Symbolleiste angezeigt.

## Funktionalität

>[!NOTE]
>
> Der Filter &quot;Zuschneiden&quot; führt die gewünschte Umkehrung der Verschiebung, Skalierung oder Drehung durch. Wenn du feststellst, dass sich der Freistellungsfilter nicht richtig anfühlt, findest du den Transformieren Filter möglicherweise besser.

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
