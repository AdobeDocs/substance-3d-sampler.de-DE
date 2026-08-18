---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/3d-capture/editing-3d-captured-meshes.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie in Substance 3D Sampler erfasste 3D-Gitter bearbeiten, um Geometrie zu verfeinern, Probleme zu beheben und die Gitterqualität zu optimieren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Bearbeiten von 3D-erfassten Netzen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '806'
ht-degree: 0%

---


# Bearbeiten von 3D-erfassten Netzen

>[!WARNING]
>
> Die Unterstützung für 3D-Erfassungen wurde ab der Sampler-Version 5.1 entfernt.

## Bearbeiten von 3D-erfassten Netzen

In diesem Benutzerhandbuch werden einige Techniken zur Bearbeitung und Nachbearbeitung von in 3D erfassten Objekten in Substance 3D Sampler vorgestellt.

Sie möchten dies als Video-Tutorial ansehen? Sie finden ihn hier [.](https://youtu.be/6_EZEAR0Uy8?si=6AaCUHD6nnWZyKUE "Tutorial-Video zur erweiterten 3D-Erfassung - Mesh-Nachbearbeitung")

![](../assets/post-processing-3d-capture.png)

Sobald du die 3D-Erfassung abgeschlossen und ein Gitter zu deinem Sampler-Projekt hinzugefügt hast, kannst du es bearbeiten. Dabei kann es sich entweder um Änderungen am Gitter oder am Material handeln. Gitterfilter gibt es seit Sampler 4.0. Bei Materialfiltern kommen alle bekannten Filter zum Einsatz, die zuvor in Sampler verwendet wurden.

Wenn Sie ein erfasstes 3D-Objekt in Sampler <b>bearbeiten, können Sie Mesh- und Materialfilter gemischt stapeln</b>. Diese Filter werden automatisch auf den richtigen Teil Ihrer Daten angewendet. Die Liste der Schnellfilter unterscheidet nicht zwischen den beiden Typen.

## Gitterfilter

Schauen wir uns zuerst die Gitterfilter an. In Sampler gibt es zwei: <b>Mesh-Transformation</b> und <b>Mesh-Nachbearbeitungsprozess</b>.

<b>Meshtransformation</b> ist ein einfacher Filter, mit dem Sie Ihr Mesh <b>übersetzen</b>, <b>drehen</b> und <b>skalieren</b> können. In der Regel können Sie ein Objekt umdrehen oder seine Skalierung anpassen. Jeder Scan wird mit einer vordefinierten Transformation geliefert.

<b>Der Mesh-Nachbearbeitungsprozess </b> ist derselbe wie der Nachbearbeitungsschritt am Ende des Dialogfelds &quot;3D-Erfassung&quot;, jedoch in einem Dynamikfilter. Sie können Ihre Texturen <b>remesh</b> , <b>re-uv</b> und <b>rebake</b>. Mit diesem Filter sollen <b>Ihre Gitter optimiert werden, indem die Tricount reduziert, die UVs verbessert und die Textur herunterskaliert wird</b>. Eines der besten Ergebnisse der Verwendung ist das verbesserte UV-Layout. Standardmäßig haben Original-3D-Erfassung-Ausgaben sehr fragmentierte UVs, in der Regel sind die neuen automatischen UVs eine Verbesserung.

Es ist kein schneller Filter, wenn Sie einen Parameter ändern, wird das Gitter verarbeitet. Es ist am besten, ein bisschen Geduld damit zu haben.

## Materialfilter

Die Materialfilter sind sehr viel vielfältiger. Alles, was du für reguläre 3D-Erfassungen verwenden kannst, kann auf das Material im Gitter angewendet werden. Bedenke jedoch, dass die Ergebnisse möglicherweise nicht immer funktionieren, da viele Filter für gleichmäßige Kachelmaterialien vorgesehen sind.

Die nützlichsten Filter sind in der Regel Korrekturen wie heller <b>Kontrast</b>, <b>Farbtonsättigung</b> sowie einige der fortschrittlicheren Filter für die Bearbeitung von Kanälen. Da ich die Raueit des Objekts nicht erfassen konnte, wird es mit Filtern wieder sichtbar.

Sie können einen <b>Farbtonsättigungsfilter</b> verwenden, um die Farben noch besser an die tatsächlichen Farben Ihres Objekts anzupassen. Es gibt bessere Möglichkeiten, Farbgenauigkeit zu erreichen, aber sie sind viel aufwändiger als dieser schnelle Filter.

Als Nächstes möchten Sie möglicherweise die Spiegelungen wiederherstellen, die in Ihrem Objekt vorhanden waren. Hier können wir den <b>Farbersetzungsfilter</b> verwenden. Mit &quot;Farbe ersetzen&quot; kannst du eine Farbe aus der Struktur übernehmen und alle Bereiche mit dieser Farbe ändern.

Standardmäßig wird alles in der von Ihnen ausgewählten Farbe eingefärbt. Wenn Sie jedoch <b>Erweiterte Segmentierung</b> aktivieren und dann die Farbe auf <b>Maske aus Grundfarbe</b> und <b>Ersetzen</b> in <b>Raueit</b> setzen, können Sie die Raueit der gesamten ausgewählten Farbe wesentlich schärfer einstellen. Wenn Sie mit der Luminanzvariation und dem Maskenbereich spielen, können Sie die Feinabstimmung der Maske unterstützen.

Zum Schluss kannst du noch ein wenig Details aus der Grundfarbe in die Raueit zurückbringen. Mit dem <b>Kanalwechselfilter</b> kann ich Details zwischen verschiedenen Kanälen mischen und überblenden. Sie können die <b>Eingabe auf Basecolo</b>r, die <b>Ausgabe auf Raueit</b> setzen und dann mit dem Mischmodus und der Deckkraft experimentieren, um etwas Interessantes und dem realen Leben nahe genug zu bringen.

Wenn du die endgültige Raueit genauer steuern möchtest, kannst du den Filter &quot;Helligkeitskontrast&quot; verwenden und ihn auf den Raueitskanal anwenden. Passe dann die Werte an, um die Raueit etwas schärfer zu machen.

Jedes Objekt ist anders, und je nach Datensatz sind möglicherweise spezifische Anpassungen erforderlich. Sie können sogar das <b>Kopierstempel-Werkzeug</b> verwenden, um Teile Ihrer Textur zu löschen, die Sie entfernen möchten, z. B. Markierungen für Hilfsmittel. Denke einfach daran, dass jeder Materialfilter, der bestimmte Positionen auf deiner Textur verwendet, von deinem UV-Layout abhängt, ebenso wie die Gitterverarbeitung vor allen Materialfiltern.

Wenn Sie mit Ihrem Objekt und Ihren Texturen zufrieden sind, können Sie <b>Ihr Ergebnis exportieren </b>und das Ergebnis im Dialogfeld <b>Freigeben > Exportieren als</b> verwenden. Mit allgemeinen Einstellungen können Sie Namen und Pfad auswählen. Mit Gittereinstellungen können Sie das 3D-Gitterformat auswählen, und mit Materialeinstellungen können Sie das Material des Gitters konfigurieren. Sie können das Gitter oder Material deaktivieren, um nur eines davon einzeln zu exportieren. Das exportierte Gitter kann in anderen 3D-Anwendungen verwendet werden.
