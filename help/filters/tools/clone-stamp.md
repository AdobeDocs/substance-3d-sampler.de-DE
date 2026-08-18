---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/clone-stamp.html"
breadcrumb-title: ''
description: Mit dem Kopierstempel in Substance 3D Sampler können Sie Strukturbereiche klonen und malen, um Material nahtlos zu bearbeiten und zu reparieren.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Clone Stamp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Kopierstempel
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---


# Kopierstempel

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-clonestamp-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Kopierstempel-Werkzeug** können Sie Teile Ihres Materials manuell duplizieren oder ausbessern. Dies ist nützlich, um Nähte zu reparieren oder Fehler aus Ihrem Material zu entfernen. Der **Kopierstempel-Filter** ist eines der Werkzeuge, die in der linken Seitenleiste verfügbar sind.

Die folgenden Bilder zeigen den **Kopierstempel**, der zum Entfernen von Schutt aus einem Schneematerial verwendet wird.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

In der obigen Abbildung enthält das Schneematerial eine Reihe von Zweigen und anderen Trümmern, die um sich herum verstreut sind.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

Mit dem **Kopierstempel** werden einige Zweige entfernt und durch sauberen Schnee ersetzt.

</td>
</tr>
</table>

## Tutorial zum Kopierstempel

## Parameter

<b>Basisparameter</b>

* <b>Maske erweitern</b>: 0-1\
  Passen Sie an, wie weit der Filter um den gemalten Bereich herum versucht, das darunter liegende Material abzugleichen.
* <b>Überblendung überblenden</b>: 0-1\
  Reduziere die Kante des geklonten Bereichs, um einen fließenden Übergang zum darunter liegenden Material zu ermöglichen.
* <b>Weichzeichnungsmaske</b>: 0-1\
  Passen Sie die Detailgenauigkeit der Kante des Kopierstempels an. Wenn Sie diesen Wert erhöhen, werden die Ränder des geklonten Bereichs blubenartiger.
* <b>Verhältnis beibehalten</b>: Knebel\
  Wenn diese Option deaktiviert ist, können Sie die Proportionen des gestempelten Bereichs anpassen.
  * <b>Horizontal</b>: 0-2
  * <b>Vertikal</b>: 0-2
* <b>Drehung</b>: -180 bis 180\
  Drehen Sie den gestempelten Bereich.
* <b>Horizontal spiegeln</b>: Knebel\
  Spiegeln Sie den gestanzten Bereich entlang einer horizontalen Achse.
* <b>Vertikal spiegeln</b>: Knebel\
  Spiegeln Sie den gestanzten Bereich entlang einer vertikalen Achse.

<b>Überblendung überblenden</b>

Verwenden Sie die Steuerelemente für die Überblendung &quot;Überblenden&quot;, um die Überblendung für jeden Kanal in Ihrem Material einzeln anzupassen.

<b>Erweitert</b>

* <b>Normale Intensität</b>: 0-2\
  Passen Sie die Stärke von Normalen im gestanzten Bereich an.
* <b>Quellposition</b>: \
  0-1: Passen Sie die horizontale Quellposition an.\
  0-1: Passen Sie die vertikale Quellposition an.
* <b>Zielposition</b>:\
  0-1: Passen Sie die horizontale Zielposition an.\
  0-1: Passen Sie die vertikale Zielposition an.
* <b>Kachelmodus</b>: Dropdown\
  Aktivieren oder Deaktivieren der Unterteilung.

## Benutzerhandbuch

Klicken Sie auf das **Kopierstempel-Werkzeug**, um eine neue Kopierstempel-Filterebene oben in Ihrem Ebenenstapel zu erstellen. Sie können auch einen Kopierstempelfilter hinzufügen, indem Sie die **Schaltfläche &quot;Ebene hinzufügen&quot;** im **Ebenenbedienfeld** verwenden.

Beim Erstellen einer Kopierstempel-Filterebene wird automatisch die **2D-Ansicht** im **Viewport** geöffnet. Eine **Symbolleiste** wird oben in der **2D-Ansicht** angezeigt, wenn die Kopierstempel-Ebene ausgewählt ist.

![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

Um das Kopierstempel-Werkzeug zu verwenden, klicken Sie auf den problematischen Bereich in der **2D-Ansicht** und ziehen Sie ihn über diesen. Das Material wird automatisch basierend auf der Quelle aktualisiert. Bereiche, in denen Sie das **Kopierstempel-Werkzeug** verwenden, werden hervorgehoben.

## Symbolleiste

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Während die Kopierstempel-Ebene ausgewählt ist, wird in der 2D-Ansicht eine Werkzeugleiste mit zusätzlichen Steuerelementen angezeigt.

* Wählen Sie entweder das <b>Pinselwerkzeug </b> aus, das der Maske hinzugefügt werden soll, oder das <b>Radiergummi-Werkzeug </b>, das aus der Maske entfernt werden soll.
* Legen Sie die Größe des aktuell ausgewählten Werkzeugs fest.
* Zugriff auf zusätzliche Steuerelemente:
  * <b>Pinselunterteilung</b>: \
    X- und Y-Pinselbearbeitung aktivieren/deaktivieren.
  * <b>Überlagerung:</b>\
    Stellt ein, ob die Überlagerung angezeigt wird, während der Mauszeiger über die 2D-Ansicht bewegt wird.
* Anzeigen der 2D-Ansichtssteuerelemente.

</td>
</tr>
</table>

>[!NOTE]
>
> Wie bei anderen Ansichtsport-Symbolleisten können Sie den oberen Griff der Symbolleiste ziehen, um die Symbolleiste im Ansichtsport neu zu positionieren, auf den Griff doppelklicken, um zwischen dem vertikalen und dem horizontalen Modus zu wechseln, oder die Symbolleiste mit dem Doppelpfeil ein- bzw. ausblenden.

## Quellauswahl

Drücken Sie Strg + Klicken in der 2D-Ansicht, um eine neue Quelle hinzuzufügen. Durch das Hinzufügen einer neuen Quelle wird ein zusätzlicher Stempel unter der Ebene &quot;Kopierstempel&quot; im <b>Ebenenbedienfeld</b> erstellt. Sie können jeden Stempel einzeln steuern.

>[!NOTE]
>
> Es empfiehlt sich in der Regel, den Quellpunkt nicht in der Nähe des Bereichs zu haben, über den Sie klonen. Wenn sich der Quellpunkt in der Nähe des problematischen Bereichs befindet, können Sie den problematischen Bereich klonen.

## Tastaturkürzel

| Aktion | Windows + Linux | MacOS |
| --- | --- | --- |
| Pinselgröße vergrößern | &rbrack; oder Strg + Mausrad | &rbrack; oder Befehl + Mausrad |
| Pinselgröße verkleinern | &lbrack; oder Strg + Mausrad | &lbrack; oder Befehl + Mausrad |
| Quelle festlegen. | Strg + Linksklick | Cmd + Linksklick |
