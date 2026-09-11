---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/clone-stamp.html"
breadcrumb-title: ''
description: Mit dem Klon-Stempel-Werkzeug in Substance 3D Sampler können Sie Texturen klonen und Malen, um Materials nahtlos zu bearbeiten und zu reparieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Clone Stamp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Klon
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

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

Mit dem **Klon-Stempelwerkzeug** können Sie Teile Ihres Materials manuell duplizieren oder ausbessern. Dies ist nützlich, um Nähte zu beheben oder Fehler von Ihrem Material zu entfernen. Der **Klon-Stempelfilter** ist eines der Tools, die in der linken Seitenleiste verfügbar sind.

Die folgenden Bilder zeigen den **Schneestempel**, der verwendet wird, um Schutt aus einem Klon-Material zu entfernen.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

In der obigen Abbildung enthält das Schnee-Material eine Reihe von Zweigen und anderen Trümmern, die um sich verstreut sind.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

Der **Schneestempel** wird verwendet, um einige Zweige zu entfernen und durch Klon zu ersetzen.

</td>
</tr>
</table>

## Tutorial zu Klon-Stempel

## Parameter

<b>Basisparameter</b>

* <b>Maske erweitern</b>: 0-1\
  Passen Sie an, wie weit um den gemalten Bereich herum der Filter versucht, das darunter liegende Material abzugleichen.
* <b>Verblassen-Überblendung</b>: 0-1\
  Reduziere die Kante des geklonten Bereichs, um einen Übergang zum darunter liegenden Material zu schaffen.
* <b>Weichzeichnungsmaske</b>: 0-1\
  Passen Sie die Detailgenauigkeit der Kante des Kopierstempels an. Wenn Sie diesen Wert erhöhen, werden die Ränder des geklonten Bereichs blubenartiger.
* <b>Verhältnis beibehalten</b>: Knebel\
  Wenn diese Option deaktiviert ist, können Sie die Proportionen des gestempelten Bereichs anpassen.
  * <b>Horizontal</b>: 0-2
  * <b>Vertikal</b>: 0-2
* <b>Drehung</b>: -180 bis 180\
  Drehen Sie den gestempelten Bereich.
* <b>Horizontal spiegeln</b>: Knebel\
  Spiegeln Sie den gestempelten Bereich entlang einer horizontalen Achse.
* <b>Vertikal spiegeln</b>: Knebel\
  Spiegeln Sie den gestempelten Bereich entlang einer senkrechten Achse.

<b>Verblassen-Überblendung</b>

Verwenden Sie die Steuerelemente für die Verblassen-Füllmethode, um die Verblassen-Füllmethode für jeden Kanal in Ihrem Material individuell anzupassen.

<b>Erweitert</b>

* <b>Normale Intensität</b>: 0-2\
  Passen Sie die Stärke der Normalen im gestempelten Bereich an.
* <b>Quellposition</b>: \
  0-1: Passen Sie die horizontale Quellposition an.\
  0-1: Passen Sie die vertikale Quellposition an.
* <b>Zielposition</b>:\
  0-1: Passen Sie die horizontale Zielposition an.\
  0-1: Passen Sie die vertikale Zielposition an.
* <b>Kachelung-Modus</b>: Dropdown\
  Aktivieren oder Deaktivieren der Kachelung.

## Benutzerhandbuch

Klicken Sie auf das **Klon-Stempelwerkzeug**, um eine neue Klon-Stempelfilterebene oben in Ihrem Ebenenstapel zu erstellen. Sie können auch einen Klon-Stempelfilter hinzufügen, indem Sie die **Schaltfläche &quot;Ebene hinzufügen&quot;** im **Ebenenbedienfeld** verwenden.

Beim Erstellen einer Kopierstempel-Filterebene wird automatisch die **2D-Ansicht** im **Viewport** geöffnet. Eine **Symbolleiste** wird oben in der **2D-Ansicht** angezeigt, wenn die Klon-Stempelebene ausgewählt ist.

![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

Um mit der Verwendung des Klon-Stempels zu beginnen, klicken Sie auf den problematischen Bereich in der **2D-Ansicht** und ziehen Sie ihn über diesen. Das Material wird automatisch basierend auf der Quelle aktualisiert. Bereiche, in denen Sie das **Klon-Stempelwerkzeug** verwenden, sind hervorgehoben.

## Symbolleiste

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Während die Klon-Stempel-Ebene ausgewählt ist, wird in der 2D-Ansicht eine Werkzeugleiste mit zusätzlichen Steuerelementen angezeigt.

* Wählen Sie entweder das <b>Pinselwerkzeug </b> aus, das der Maske hinzugefügt werden soll, oder das <b>Radiergummi-Werkzeug </b>, das aus der Maske entfernt werden soll.
* Legen Sie die Größe des aktuell ausgewählten Werkzeugs fest.
* Zugriff auf zusätzliche Steuerelemente:
  * <b>Pinsel-Kachelung</b>: \
    X- und Y-Kachelung umschalten.
  * <b>Überlagerung:</b>\
    Stellt ein, ob die Überlagerung angezeigt wird, während der Mauszeiger über die 2D-Ansicht bewegt wird.
* 2D-Ansichten anzeigen.

</td>
</tr>
</table>

>[!NOTE]
>
> Wie bei anderen Ansichtsport-Symbolleisten können Sie den oberen Griff der Symbolleiste ziehen, um die Symbolleiste im Ansichtsport neu zu positionieren, auf den Griff doppelklicken, um zwischen dem vertikalen und dem horizontalen Modus zu wechseln, oder die Symbolleiste mit dem Doppelpfeil ein- bzw. ausblenden.

## Quellauswahl

Verwenden Sie Strg + Klicken in die 2D-Ansichten, um eine neue Quelle hinzuzufügen. Durch das Hinzufügen einer neuen Quelle wird ein zusätzlicher Klon unter der Stempelebene im <b>Ebenenbedienfeld</b> erstellt. Sie können jeden Stempel einzeln steuern.

>[!NOTE]
>
> Es empfiehlt sich in der Regel, den Quellpunkt nicht in der Nähe des Bereichs zu haben, über den Sie klonen. Wenn sich der Quellpunkt in der Nähe des problematischen Bereichs befindet, können Sie den problematischen Bereich klonen.

## Tastaturkürzel

| Aktion | Windows + Linux | MacOS |
| --- | --- | --- |
| Pinselgröße vergrößern | &rbrack; oder Strg + Mausrad | &rbrack; oder Befehl + Mausrad |
| Pinselgröße verkleinern | &lbrack; oder Strg + Mausrad | &lbrack; oder Befehl + Mausrad |
| Quelle festlegen. | Strg + Linksklick | Cmd + Linksklick |
