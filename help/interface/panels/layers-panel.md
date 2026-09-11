---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/interface/panels/layers-panel.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie das Ebenenbedienfeld in Substance 3D Sampler verwenden, um Filterebenen zu verwalten und komplexe Material-Stapel zu erstellen.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Layers panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ebenenbedienfeld
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '970'
ht-degree: 2%

---


# Ebenenbedienfeld

<table>
<tr style="border: 0;">
<td style="border: 0; width: 70%" valign="top">

Das **Ebenenbedienfeld** enthält den Ebenenstapel und Verknüpfungen zum Verwalten Ihrer Ebenen. Das **Ebenenbedienfeld** arbeitet eng mit dem **Eigenschaftenbedienfeld** zusammen. Wählen Sie eine Ebene aus dem **Ebenenbedienfeld** aus, um ihre Eigenschaften im **Eigenschaftenbedienfeld anzuzeigen.**

Das **Ebenenbedienfeld** besteht aus drei Hauptabschnitten:

1. Der Werkzeugbereich enthält Schaltflächen, mit denen Sie
   1. Ebenenauflösung ein-/ausblenden
   1. Ebenenauflösungsstrategie ändern
   1. Ebene hinzufügen
   1. Grundmaterial hinzufügen
   1. Benutzerdefinierten Filter importieren
   1. Ebene entfernen
1. Mit dem Selektor &quot;**Füllmethode&quot; &quot;**&quot; können Sie anpassen, wie eine Ebene mit den darunter liegenden Ebenen überblendet wird. Der Auswahlbereich &quot;**&quot; für den Überblendung-Modus &quot;**&quot; ist nur verfügbar, wenn eine Material-Ebene ausgewählt wurde. Filter verwenden keine Füllmethoden.
1. Der **Ebenenstapel** enthält alle Ebenen, aus denen das Element besteht.

</td>
<td style="border: 0;" valign="top">

![Animation des Ebenenbedienfelds von keiner Ebene zu einem vollständigen Stapel, der ein Material erstellt](../../assets/Layers-panel-gen.png.img.png)

</td>
</tr>
</table>

## Der Ebenenstapel

Der Ebenenstapel ist die Sammlung von Materialien, Filtern und anderen Ressourcen, aus denen das aktuelle Material besteht. Wie in Photoshop und Substance 3D Painter funktioniert der Ebenenstapel von der unteren Ebene zuerst bis zur oberen Ebene zuletzt. Das bedeutet, dass sich jede Ebene auf die Ebenen darunter auswirken kann.

Es gibt mehrere Möglichkeiten, den Ebenenstapel zu verwalten:

| Aktionen | Anleitung |
| --- | --- |
| Ebene hinzufügen | Ziehen Sie ein Element aus dem Bedienfeld **Elemente** in den Viewport, um es an oberster Stelle im Ebenenstapel hinzuzufügen. Ziehen Sie ein Element aus dem Bedienfeld **Elemente** in den Ebenenstapel, um es an einer bestimmten Position im Ebenenstapel hinzuzufügen. Verwenden Sie die Schaltfläche **Ebene hinzufügen** im Werkzeugbereich, um einen Filter aus einer Liste auszuwählen. |
| Verschieben einer Ebene | Ziehen Sie eine Ebene im Ebenenstapel, um sie zu verschieben. Wenn Sie eine Ebene verschieben, wird ein Balken angezeigt, der angibt, wo die Ebene platziert wird. |
| Löschen einer Ebene | Klicken Sie auf eine Ebene, um sie auszuwählen, und drücken Sie **Entf**, oder verwenden Sie die Schaltfläche **Ebene entfernen** im Werkzeugbereich. |
| Sichtbarkeit ein/aus | Bewegen Sie den Mauszeiger über eine Ebene, um den Schalter **Sichtbarkeit** auf der rechten Seite der Ebene anzuzeigen. Wenn die Sichtbarkeit einer Ebene deaktiviert ist, wird sie nicht berechnet. |
| Ebeneneigenschaften anzeigen | Klicken Sie auf eine Ebene, um ihre Eigenschaften im Bereich **Eigenschaften anzuzeigen.** |
| Auflösung ein-/ausblenden | Klicken Sie auf die Schaltfläche links oben im **Ebenenbedienfeld**. |
| Alle Ebenenauflösung wechseln | Klicke auf den Pfeil neben der Schaltfläche &quot;Auflösung ein-/ausblenden&quot;. Wähle die Strategie für alle Ebenen im Stapel aus. |
| Ebenenauflösung ändern | Klicken Sie auf eine Ebene, um ihre Eigenschaften zu öffnen, klicken Sie auf die Auflösung im **Eigenschaftenfenster**, und wählen Sie die Auflösungsstrategie aus, die die Ebene verwenden soll. |

## Ebenentypen

Es gibt drei Arten von Ebenen:

* Materialien
* Filter
* Bilder

### Material-Ebenen

Eine Material-Ebene enthält Informationen in mehreren Kanälen und kann mit den darunter liegenden Ebenen gemischt werden. Die Anzeige von Materialebenen unterscheidet sich geringfügig, je nachdem, ob sie sich am unteren Rand des Stapels befinden oder nicht. Zum Beispiel zeigt das Bild unten ein Felsmaterial, das zweimal in den Ebenenstapel gezogen wurde. Beachten Sie, dass die untere Ebene kein Symbol enthält, um die Überblendung zu steuern, während die obere Ebene dies tut.

![Material-Ebenen im Ebenenstapel. Die oberste Ebene verfügt über eine Überblendungsoption.](../../assets/Material-Layer.png)

Die allgemeinen Regeln für Materialschichten sind:

* Eine Material-Ebene verwendet immer die Dokumentauflösung.
* Eine Material-Ebene am unteren Rand des Stapels hat keine Überblendungen, sodass der Auswahlbereich &quot;**Überblendung-Modus&quot; &quot;**&quot; nicht verfügbar ist.
* Eine Material-Ebene, die sich nicht am unteren Rand des Stapels befindet, kann mit den darunter liegenden Ebenen überblendet werden. Sie können daher den Mischmodus mithilfe der Modusauswahl &quot;**Überblendung&quot;** ändern. Außerdem wird neben dem **Ebenensymbol** ein **Überblendungssymbol** angezeigt. Wählen Sie das Symbol **Angleichen** aus, um die Angleichungseinstellungen für die Ebene anzupassen, je nachdem, welcher Angleichungsmodus ausgewählt wurde.

### Filtern von Ebenen

![Eigenschaften des Farbton-/Sättigungsfilters, die die darunter liegenden Ebenen anpassen.](../../assets/HueSaturation_LayerFilter.gif)

Filter führen Vorgänge auf den darunter liegenden Ebenen aus, um bestimmte Effekte zu erzeugen. Im Bild über dem **Filter &quot;Farbton/Sättigung&quot;** können Sie beispielsweise den Farbton, die Sättigung und die Helligkeit der darunter liegenden Ebenen anpassen.

Einige Filter können eine oder mehrere andere Ebenen als Eingaben verwenden. Beispiel:

* Der **Atlas Scatter-Filter** kann ein Material als Eingabe verwenden.
* Der **Atlas Scatter-Filter** führt die Streuung von Instanzen aus dem Material des Eingabeatlas auf der Grundlage der **Atlas Scatter**-Parameter durch.

Ziehen Sie ein Material über einen Einschub für Ebenen, um es als Eingabe zu verwenden.

Eine Filterebene verwendet die in den Voreinstellungen festgelegte Standardauflösungsstrategie. Sie können die Auflösung ändern, die der Filter im Eigenschaftenfenster verwendet.

![Auflösung einer Filterebene wechseln](../../assets/SwitchLayerResolution.gif)

### Bildebenen

Bildebenen verwenden ihre eigene Auflösung und werden hauptsächlich im Workflow &quot;Bild zu Material&quot; verwendet. Wie Bildebenen können Sie eine Bildebene erstellen, indem Sie ein Material aus dem **Bedienfeld &quot;Elemente&quot;** ziehen.

Sie können ein Bild aus dem Dateibrowser Ihres Systems in Sampler ziehen. Wenn sich bereits Ebenen in Ihrem Ebenenstapel befinden, wird die Bildebene oben im Stapel hinzugefügt. Wenn der Ebenenstapel keine Ebenen enthält, wird ein Dialogfeld angezeigt, in dem Sie auswählen können, wie das Bild verarbeitet werden soll:

* Mit **Image zu Material** können Sie mithilfe von KI ein Bild in ein Material konvertieren.
* Mit **Mehrwinkel zu Material** können Sie mehrere Bilder mit unterschiedlichen Lichtverhältnissen verwenden, um ein Material zu erstellen.
* Mit **Texturen importieren** können Sie importierte Texturen als Bilderkanäle verwenden, um ein Material aufzubauen.
* **Als Bitmap verwenden** importiert das Bild als einfache Bitmapebene.

Sie können auch mehrere ausgewählte Bilder gleichzeitig in den Ebenenstapel ziehen, um sie alle als eine Ebene zu importieren. Dies kann für Multibildfilter wie **HDR hilfreich sein. Merge** und **Mehrwinkel zu Material**. Wählen Sie die Ebene mit mehreren Bildern aus, um die Kanaldaten für jedes Bild zu ändern.
