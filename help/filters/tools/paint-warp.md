---
title: Malen-Verkrümmung
description: Erfahren Sie, wie Sie den Malen-Verkrümmungsfilter in Substance 3D Sampler verwenden, um die Verkrümmung Ihres Materials genau zu steuern.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 2%
---

# Verformung malen

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_WarpPaint_18_N_D.png" alt=""/><br><strong>In:</strong> Tools</td>
    <td style="border: 0;" valign="top"><strong>Beschreibung</strong><br>Der <strong>Malen-Verkrümmungsfilter</strong> ist ein leistungsstarkes Werkzeug zum Korrigieren geometrischer Verzerrungen in bildbasierten Scans. Sie ist besonders für Material mit Linienmustern - wie Kordgewebe, Holzbretter oder Mauerwerk - geeignet, bei denen die natürlichen Linien nicht perfekt gerade sind oder mit den Achsen ausgerichtet sind. Durch die manuelle Definition des Musterflusses können Sie das Material "begradigen", um eine nahtlose Kachelung und professionelle Texturen sicherzustellen.<br></td>
  </tr>
</table>

## Ausrichten von Materialien

Sie können den Malen-Verkrümmungsfilter manuell zu Ihrem Ebenenstapel hinzufügen, aber der effizienteste Arbeitsablauf für Scans ist die Verwendung der dedizierten Schnellaktion.

### Verwenden der Schnellaktion

1. Öffnen Sie die Registerkarte **Schnellaktion**.
1. Wählen Sie **Material-Muster durch Malen ausrichten**.

* Sampler fügt automatisch drei Ebenen zu deinem Stapel hinzu: **Ausgleichen**, **Horizontaler Malen-Warp** und **Vertikaler Malen-Warp**.

1. Geben Sie im **Ebenenstapel** an, in welche Richtung Ihr Muster folgt.

* *Beispiel:* Bei Corduroy mit vertikalen Rippen behalten Sie die **Vertikale Malen-Verkrümmung** bei und deaktivieren oder löschen Sie die Horizontale Version.

### Zeichnen der Verkrümmungsführungen

Nachdem der Filter ausgewählt wurde, müssen Sie den aktuellen &quot;schiefen&quot; Pfad des Musters definieren, damit Sampler ihn begradigen kann.

1. Wechseln Sie zum Bereich **Eigenschaften** des Malen-Verkrümmungsfilters.

1. Suchen Sie die Eigenschaft **Image Input**, und klicken Sie auf das daneben angezeigte Symbol **Brush**, um in den Malmodus zu wechseln.

1. Passen Sie die **Pinselgröße** mithilfe der UI-Widgets oder Tastaturbefehle an.

1. Malen entlang des Materials:

   >[!TIP]
   >
   > Halten Sie **Umschalt** gedrückt, während Sie klicken, um perfekt gerade Segmente zwischen den Punkten zu erstellen.

1. Zeichnen Sie mehrere Zeilen entlang der Breite oder des Heights der Textur nach, um dem Algorithmus genügend Daten zur Verfügung zu stellen.

1. Schalten Sie im Bereich **Eigenschaften** den Parameter **Begradigen** auf **Ein** um. Sampler verzerrt das Bild, sodass die gemalten Linien vollständig parallel zur ausgewählten Achse verlaufen.

## Parameterreferenz

| Name | Beschreibung | Bereich/Optionen | Standard |
| --- | --- | --- | --- |
| **Richtung** | Legt die Achse fest, an der die Verkrümmung ausgerichtet wird. | Vertikal, Horizontal | Vertikal |
| **Begradigen** | Schaltet den Verkrümmungseffekt basierend auf der gemalten Maske ein oder aus. | Umschalten (Ein/Aus) | Aus |
| **Eingabe anzeigen** | Eine Helfer-Überlagerung, die Hilfslinien anzeigt, die die Malgenauigkeit unterstützen. | Umschalten (Ein/Aus) | Aus |
| **Nahtlose Verkrümmung** | Steuert den Abfall und die Smoothness der Deformation zwischen den bemalten Hilfslinien. | 0.0 - 1.0 | 0.5 |

## Tipps und Best Practices

* **Eingabe anzeigen:** Aktivieren Sie den Schalter **Eingabe anzeigen** beim Malen. Auf diese Weise erhalten Sie eine Raster-Überlagerung, die es einfacher macht, genau zu erkennen, wo der Originalscan von einem einwandfreien Raster abweicht.
* **Nicht überschreiben:** Sie müssen nicht jede einzelne Malen in einem Muster nachzeichnen. In der Regel reichen 3 bis 5 gut platzierte Linien über die Textur aus, damit der Algorithmus die erforderliche Verformung berechnen kann.
* **Mit Kachelung kombinieren:** Verwenden Sie die Malen-Verkrümmung, bevor Sie den Filter **Kachelung** anwenden. Ein begradigtes Muster lässt sich deutlich leichter ohne sichtbare Nähte oder &quot;unterbrochene&quot; Kanten kacheln.
* **Zuerst ausgleichen:** Wie in der Schnellaktion zu sehen, können Sie durch Platzieren eines **Ausgleichen**-Filters vor der Malen-Verkrümmung Beleuchtungsverläufe entfernen, sodass Sie die Musterdetails, die Sie ausrichten möchten, leichter sehen können.

## Verwandte Artikel

* [Tonwertangleichung](../adjustments/equalize.md)
* [Kacheln](tiling.md)
* [Schnellaktionen](../../features-and-workflows/quick-actions.md)
* [Best Practices zum Scannen](../../pipeline-and-integrations/hp-z-captis-support/scanning-best-practices.md)
