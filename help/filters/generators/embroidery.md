---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embroidery.html"
breadcrumb-title: ''
description: Verwenden Sie den Stickereigenerator in Substance 3D Sampler, um gestickte Stoffmuster und Nähtexturen für Materialien zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embroidery
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Stickerei
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---


# Stickerei

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embroidery-18-n-d.png)

**In:** Generatoren

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem Stickereifilter können Sie schnell Bilder in gestickte Pflaster konvertieren. Sie können das Aussehen der Patches anpassen und die Farbmanagement-Werkzeuge verwenden, um als Maske für mehrere Materialien zu fungieren.

Die folgenden Bilder zeigen den **Stickereifilter** in Aktion.

![](../../assets/3d-2d-filters-cropped-0035-embroidery-in.jpg)

In der Abbildung oben wurde das Quellbild importiert. Das Bild ist deckend und hat einen weißen Hintergrund.

![](../../assets/3d-2d-filters-cropped-0034-embroidery-out.jpg)

Im Bild oben wurde der **Stickfilter** zum Ebenenstapel hinzugefügt und das Quellbild in einen bestickten Patch konvertiert. Beachten Sie, dass die Ausgabe des **Stickereifilters** transparent ist, während das Quellbild undurchsichtig war.

</td>
</tr>
</table>

## Plug-in für Tajima-Stickerei

Möchtest du das Plug-in für die Tajima-Stickerei testen? \
Weitere Informationen [finden Sie hier](../../pipeline-and-integrations/tajima-exporter-plugin.md).

## Parameter

<b>Basisparameter</b>

* <b>Zufallsparameter</b>:\
  Die Zufallsgeschwindigkeit, auf der alle anderen Zufallsparameter in diesem Filter basieren.
* <b>Image</b>: Bild/Maske\
  Wähle ein Bild in deinem System aus, oder male eine eigene Maske.
* <b>Farbanzahl</b>: 1-8\
  Der Stickereifilter versucht, importierte Bilder in separate Farben aufzuteilen. Ändern Sie diesen Wert, um die Anzahl der verwendeten Farben zu ändern.
* <b>Dichte</b>: 80-300\
  Legen Sie die Dichte der Fasern fest.
* <b>Design</b>: Füllung, Kontur, Füllung + Kontur, Steppstich\
  Wählen Sie den Stickereimodus: *Füllung* füllt die gesamte Farbzone aus, *Kontur* erstellt eine Kontur der Farbzone, *Füllung + Kontur* erstellt sowohl für jede Farbzone als auch *Kopfstich* erstellt eine Kopfstich-Kontur der Farbzone.
* <b>Ausfüllen/Kontur: </b>0-1\
  Ändern Sie die Verteilung der Fasern in der Farbzone.
* <b>Thread</b>:\
  Passen Sie die Thickness und die Länge der Gewinde an.
* <b>Glatte Bereiche: </b>0-1\
  Gleichen Sie die Farbzonen aus und wirken sich auf das Verhalten von Threads aus.
* <b>Mängel</b>: 0-1\
  Unvollkommenheiten hinzufügen, um das Muster aufzubrechen

<b>Farbe 1</b>

Passen Sie die Farbbereiche mit den Steuerelementen einzeln an.

* <b>Füllung</b>: Knebel\
  Machen Sie die Farbzone sichtbar oder unsichtbar.
* <b>Height</b>: \
  Versatz der Ausrichtung der Fäden

<b>Zusammenfügen abgeschlossen</b>

* <b>Benutzerdefinierte Farbe:</b>\
  Die Farbe der gesamten Stickerei anpassen
* <b>Grobheit: </b>0-1\
  Ändern Sie den Wert für &quot;Raueit&quot;, um die Stickerei rau oder glänzend zu gestalten.
* <b>Metallisch: </b>0-1\
  Ändern Sie den Metallic-Wert, um den Threads ein metallisches Flair zu verleihen.
* <b>Anisotropie: </b>0-1\
  Ändere die Intensität der Anisotropie, um den Effekt &quot;Metallisch&quot; zu betonen.

<b>Erweitert</b>

* <b>Normalintensität</b>: 0-1\
  Passen Sie die Stärke der Normalen an.
* <b>Height-Bereich:</b> 0-1\
  Passen Sie die Height-Position der Stickerei auf dem Basismaterial an.
* <b>Height-Position:</b> 0-1\
  Passen Sie die Height-Position der Stickerei auf dem Basismaterial an.

## Benutzerhandbuch

Der Stickerei-Filter kann zunächst etwas verwirrend sein, aber mit nur wenigen wichtigen Parametern werden Sie in kürzester Zeit Patches zu Ihren Materialien hinzufügen.

>[!NOTE]
>
> Wenn Sie den [Webfilter](weave.md)bereits verwendet haben, funktioniert der Stickereifilter ähnlich.

So verwenden Sie den Stickereifilter:

1. Wende den Filter &quot;Stickerei&quot; auf deine Ebenen an.
1. Verwenden Sie <b>Grundlegende Parameter > Bild</b>, um dem Filter ein Bild hinzuzufügen, oder fügen Sie dem Ebenenstapel unterhalb des Stickfilters ein Bild hinzu (nicht in einem der Eingabefächer). Wenn ein Bild nicht zu <b>Basisparametern > Bild</b> hinzugefügt wird, nimmt der Filter Bilder automatisch aus den Scan-Kanälen auf, sofern verfügbar.
1. Passen Sie <b>Grundlegende Parameter > Farbanzahl </b> an, bis die Farbbalance für Ihr Bild korrekt aussieht. Wenn Sie die Anzahl der Farben auf maximal 8 festlegen möchten, aktivieren oder deaktivieren Sie Farben, um die benötigten Farben zu isolieren.\
   Der Filter &quot;Stickerei&quot; eignet sich am besten für flache Farben und illustrierte Bilder.
1. Passen Sie weitere Parameter an, um das Erscheinungsbild des Patches zu optimieren.

Es ist möglich, transparente Bilder im Stickereifilter zu verwenden, aber standardmäßig wirken sich diese auch auf die Deckkraftkarte Ihres Materials aus - transparente Teile des Bildes machen das Material auch transparent. Um einen Patch mit dem Filter &quot;Stickerei&quot; zu erstellen und ihn über den Ebenen darunter liegen zu lassen, verwenden Sie den Filter &quot;Aufkleber&quot;.

1. Erstellen Sie einen Aufkleberfilter.
1. Fügen Sie den Stickereifilter zum Eingangssteckplatz des Decal-Filters hinzu.
1. Um das Stickmuster anzupassen, führen Sie die normalen Schritte aus.

Die Ebene &quot;Decal&quot; konvertiert die Stickerei-Eingabe in einen Aufkleber. Die Transparenz der Ebene &quot;Embroidery&quot; weist die Ebene &quot;Decal&quot; an, wie das Muster maskiert werden soll. Mit der Decal-Ebene kannst du das Muster auch auf deinem Material verschieben oder Funktionen wie Kacheln aktivieren.
