---
description: Mit dem Klon-Stempel-Werkzeug in Substance 3D Sampler können Sie Texturen klonen und Malen, um Materials nahtlos zu bearbeiten und zu reparieren.
title: Klon
source-git-commit: 09278e59a21757710d15d1bb447002a4aecb25a7
workflow-type: tm+mt
source-wordcount: '872'
ht-degree: 1%
---

# Klon

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-clonestamp-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Klon Stamp**-Tool können Sie Teile Ihres Materials manuell duplizieren oder ausbessern. Es wird hauptsächlich verwendet, um Nähte zu beheben und Fehler aus gescannten Materialien zu entfernen, z. B. Verschmutzungen, Schatten oder Artefakte. Sie können mehrere Stempelstriche aus verschiedenen Quellbereichen innerhalb einer Stempelebene Malen. Sie können jeden Klon einzeln im **Ebenenbedienfeld** verwalten.

Die folgenden Bilder zeigen den **Schneestempel**, der verwendet wird, um Schutt aus einem Klon-Material zu entfernen.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

Das Snow-Material besteht aus einer Reihe von Zweigen und anderen Trümmern, die um sich verstreut sind.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

Nach Verwendung des **Schneestempels** werden die Zweige durch Klon ersetzt.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Maske erweitern**: 0-1

  Passen Sie an, wie weit um den gemalten Bereich herum der Filter versucht, das darunter liegende Material abzugleichen.

* **Verblassen-Überblendung**: 0-1

  Richte einen weichen Rand des geklonten Bereichs ein, um einen natürlicheren Übergang zum umgebenden Material zu schaffen.

* **Weichzeichnungsmaske**: 0-1

  Passen Sie die Detailgenauigkeit der Ränder auf dem Kopierstempel an. Höhere Werte führen zu glatteren, fleckenartigeren Kanten.

* **Verhältnis beibehalten**: Knebel

  Wenn diese Option deaktiviert ist, können Sie die horizontalen und vertikalen Proportionen des gestempelten Bereichs unabhängig anpassen.

  * **Horizontal**: 0-2
  * **Vertikal**: 0-2
* **Drehung**: -180 bis 180

  Drehen Sie den gestempelten Bereich, um ihn an die Richtung oder Körnung des umliegenden Materials anzupassen.

* **Horizontal spiegeln**: Knebel

  Spiegeln Sie den gestempelten Bereich entlang einer horizontalen Achse.

* **Vertikal spiegeln**: Knebel

  Spiegeln Sie den gestempelten Bereich entlang einer senkrechten Achse.

**Verblassen-Überblendung**

Verwenden Sie die Steuerelemente für die Verblassen-Füllmethode pro Kanal, um die Stärke der Füllmethode für jeden Material-Kanal unabhängig voneinander anzupassen.

**Erweitert**

* **Normale Intensität**: 0-2

  Passen Sie die Stärke des Normalen-Map im gestempelten Bereich an, um zu steuern, wie die geklonte Fläche auf die Beleuchtung reagiert.

* **Quellposition**:
  * Horizontal: 0-1 — Passen Sie die horizontale Position der Klonquelle an.
  * Vertikal: 0-1 — Passen Sie die vertikale Position der Klonquelle an.
* **Zielposition**:
  * Horizontal: 0-1 — Passen Sie die horizontale Position des Malen-Ziels an.
  * Vertikal: 0-1 — Passen Sie die vertikale Position des Malen-Ziels an.
* **Kachelung-Modus**: Dropdown

  Aktivieren oder deaktivieren Sie die Kachelung beim Klonen in der Nähe von Materialien.

## Klon-Stempel verwenden

1. Klicken Sie auf der linken Seitenleiste auf **Klon Stamp**, oder fügen Sie ihn über die Schaltfläche **Ebene hinzufügen** im **Ebenenbedienfeld** hinzu. Oben im Ebenenstapel wird eine neue Klon-Stempelebene angezeigt, und die **2D-Ansicht** wird automatisch geöffnet.

1. **Quellpunkt festlegen**: Halten Sie `Ctrl` (`Cmd` in macOS) gedrückt und klicken Sie in der **2D-Ansicht** auf einen sauberen Bereich des Materials. Dadurch wird der zu kopierende Bereich definiert.

   > 📸 SCREENSHOT [ID: clone-stamp-001]
   > Anzeigen: 2D-Viewport mit einem Quellenpunkt-Fadenkreuz auf einem sauberen Bereich eines Schnee-Materials
   > Status: Klon-Stempel-Ebene ausgewählt; Strg gedrückt halten; Quellindikator sichtbar
   > Anmerkung: Quell-Fadenkreuz kennzeichnen

1. **Malen über den Problembereich**: Klicken und ziehen Sie über den Bereich, der korrigiert werden soll. Das Material vom Quellpunkt ersetzt den gemalten Bereich in Echtzeit.

   ![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

1. Passen Sie die **Verblassen-Überblendung** und **Maske erweitern** im **Eigenschaftenfenster** an, um die Überblendung des geklonten Bereichs mit seiner Umgebung zu optimieren.

>[!NOTE]
>
> Vermeiden Sie es, den Quellpunkt in der Nähe des Bereichs zu platzieren, den Sie klonen. Wenn die Quelle den Problembereich überlappt, kann das Artefakt zusammen mit dem sauberen Inhalt geklont werden.

## Arbeiten mit mehreren Quellen

Sie können mehrere Quellpunkte innerhalb einer einzelnen Klon-Stempelebene hinzufügen, von denen jeder eine eigene Position, Drehung und Füllmethode besitzt. So kannst du mehrere verschiedene Bereiche reparieren oder aus verschiedenen sauberen Bereichen zeichnen, ohne mehrere Ebenen stapeln zu müssen.

Um eine neue Quelle hinzuzufügen, halten Sie `Ctrl` (`Cmd` in macOS) gedrückt und klicken Sie in der **2D-Ansicht** auf einen neuen Bereich. Unter der Klon-Stempelebene im **Ebenenbedienfeld** wird ein neuer Stempeleintrag angezeigt.

> 📸 SCREENSHOT [ID: clone-stamp-002]
> Anzeigen: Bedienfeld &quot;Ebenen&quot; mit eingeblendeter Klon-Stempel-Ebene. Darunter sind drei verschiedene Stempeleinträge
> Status: Klon-Stempelebene erweitert; drei sichtbare Stempel mit unterschiedlichen Quellpositionen
> Anmerkung: Pfeil, der auf die verschachtelten Stempeleinträge im Ebenenbedienfeld zeigt

Wählen Sie einen beliebigen einzelnen Stempeleintrag im **Ebenenbedienfeld** aus, um seine Parameter unabhängig im **Eigenschaftenbedienfeld** anzupassen, einschließlich der Quellposition, der Drehung und der Füllmethoden-Einstellungen.

>[!TIP]
>
> Verwenden Sie die **Pinselvorschau** in der **2D-Ansicht**, um das Stempelergebnis anzuzeigen, bevor Sie einen Strich bestätigen. Auf diese Weise können Sie vor dem Malen überprüfen, ob der Quellbereich mit dem Umgebungsbereich übereinstimmt.

## Symbolleiste

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Während eine Klon-Stempelebene ausgewählt ist, wird eine Symbolleiste in der **2D-Ansicht** angezeigt.

* Wählen Sie **Pinselwerkzeug** aus, um es der Maske hinzuzufügen.
* Wählen Sie **Radiergummi-Werkzeug** aus, das aus der Maske entfernt werden soll.
* Legen Sie die Größe des aktuell ausgewählten Werkzeugs fest.
* Zugriff auf zusätzliche Steuerelemente:
  * **Pinsel-Kachelung**: X- und Y-Kachelung umschalten.
  * **Überlagerung**: Wechsle zwischen Überlagerungssichtbarkeit und 2D-Ansicht.
* **2D-Ansicht-Steuerelemente anzeigen**.

</td>
</tr>
</table>

>[!NOTE]
>
> Wie bei anderen Viewport-Symbolleisten können Sie den Griff oben in der Symbolleiste ziehen, um ihn neu zu positionieren, doppelklicken Sie auf den Griff, um zwischen dem vertikalen und dem horizontalen Layout zu wechseln, oder den Doppelpfeil verwenden, um ihn auszublenden oder zu erweitern.

## Tastaturkürzel

| Aktion | Windows + Linux | macOS |
| --- | --- | --- |
| Pinselgröße vergrößern | `]` oder `Ctrl` + Mausrad | `]` oder `Cmd` + Mausrad |
| Pinselgröße verringern | `[` oder `Ctrl` + Mausrad | `[` oder `Cmd` + Mausrad |
| Quelle festlegen. | `Ctrl` + Linksklick | `Cmd` + Linksklick |

## Verwandte

* [Verformen](./warp.md)
* [Anordnen.](./make-it-tile.md)
* [Bild zu Material](./image-to-material.md)
