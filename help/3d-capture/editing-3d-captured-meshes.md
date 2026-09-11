---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/3d-capture/editing-3d-captured-meshes.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie in Substance 3D Sampler erfasste 3D-Mesh bearbeiten können, um die Geometrie zu verfeinern, Probleme zu beheben und die Qualität des Meshs zu optimieren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Bearbeiten von in 3D aufgenommenen Meshs
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '806'
ht-degree: 0%

---


# Bearbeiten von in 3D aufgenommenen Meshs

>[!WARNING]
>
> Die Unterstützung für 3D-Erfassungen wurde ab der Sampler-Version 5.1 entfernt.

## Bearbeiten von in 3D aufgenommenen Meshs

In diesem Benutzerhandbuch werden einige Techniken zur Bearbeitung und Nachbearbeitung von in 3D erfassten Objekten in Substance 3D Sampler vorgestellt.

Sie möchten dies als Video-Tutorial ansehen? Sie finden ihn hier [.](https://youtu.be/6_EZEAR0Uy8?si=6AaCUHD6nnWZyKUE "Tutorial-Video zur erweiterten 3D-Erfassung - Mesh-Nachbearbeitung")

![](../assets/post-processing-3d-capture.png)

Nachdem du die 3D-Erfassung abgeschlossen und einen Mesh zu deinem Sampler-Projekt hinzugefügt hast, kannst du den Vorgang bearbeiten. Dabei kann es sich entweder um Änderungen am Mesh oder am Material handeln. Mesh-Filter sind seit Sampler 4.0 neu. Bei Materialfiltern kommen alle bekannten Filter zum Einsatz, die zuvor in Sampler verwendet wurden.

Wenn Sie ein aufgenommenes 3D-Objekt in Sampler <b>bearbeiten, können Sie Mesh und Materialfilter in gemischten Stapel bearbeiten</b>. Diese werden automatisch auf den richtigen Teil Ihrer Daten angewendet. Die Liste der Schnellfilter unterscheidet nicht zwischen den beiden Typen.

## Gitterfilter

Zuerst schaue ich mir die Mesh-Filter an. In Sampler gibt es zwei: <b>Mesh Transformieren</b> und <b>Mesh nach Prozess </b>.

<b>Mesh transformieren</b> ist ein einfacher Filter, mit dem Sie Ihren Mesh <b>Kamera bewogen</b>, <b>drehen</b> und <b>skalieren</b> können. In der Regel können Sie ein Objekt umdrehen oder seine Skalierung anpassen. Jeder Scan wird mit einem transformieren vorab angewendeten Filter geliefert.

Der <b>Mesh-Nachbearbeitungsprozess</b> ist derselbe wie der Nachbearbeitungsschritt am Ende des Dialogfelds &quot;3D-Erfassung&quot;, jedoch in einem Dynamikfilter. Sie können Ihre Texturen <b>remesh</b> , <b>re-uv</b> und <b>rebake</b>. Mit diesem Filter sollen <b>Ihre Gitter optimiert werden, indem die Tricount reduziert, die UVs verbessert und die Textur herunterskaliert wird</b>. Eines der besten Ergebnisse der Verwendung ist das verbesserte UV-Layout. Standardmäßig haben Original-3D-Erfassung-Ausgaben sehr fragmentierte UVs, in der Regel sind die neuen automatischen UVs eine Verbesserung.

Dies ist kein schneller Filter, wenn Sie einen Parameter ändern, wird der Mesh verarbeitet. Es ist am besten, ein bisschen Geduld damit zu haben.

## Materialfilter

Die Materialfilter sind viel vielfältiger. Alles, was du auf regulären Materialien verwenden kannst, kann auf dem Material des 3D-Erfassung-Meshs verwendet werden. Bedenke jedoch, dass die Ergebnisse möglicherweise nicht immer funktionieren, da viele Filter für gleichmäßige Kachelung-Materialien vorgesehen sind.

Die nützlichsten Filter sind in der Regel Korrekturen wie heller <b>Kontrast</b>, <b>Farbtonsättigung</b> sowie einige der fortschrittlicheren Filter für die Bearbeitung von Kanälen. Da wir die Rauheit des Objekts nicht erfassen konnten, verwenden wir einige Filter, um es wiederherzustellen.

Sie können einen <b>Farbtonsättigungsfilter</b> verwenden, um die Farben noch besser an die tatsächlichen Farben Ihres Objekts anzupassen. Es gibt bessere Möglichkeiten, Farbgenauigkeit zu erreichen, aber sie sind viel aufwändiger als dieser schnelle Filter.

Als Nächstes möchten Sie möglicherweise die Spiegelungen wiederherstellen, die in Ihrem Objekt vorhanden waren. Hier können wir den <b>Farbersetzungsfilter</b> verwenden. Mit &quot;Farbe ersetzen&quot; können Sie eine Farbe aus Ihrer Textur aufnehmen und alle Bereiche mit dieser Farbe ändern.

Standardmäßig wird alles in der von Ihnen ausgewählten Farbe eingefärbt. Wenn Sie jedoch <b>Erweiterte Segmentierung</b> aktivieren und dann die Farbe auf <b>Rauheit aus Grundfarbe</b> und <b>Ersetzen</b> in <b>Rauheit</b> setzen, können Sie die Bereichsfarbe der ausgewählten Farbe viel schärfer einstellen. Wenn Sie mit der Luminanzvariation und dem Maskenbereich spielen, können Sie die Feinabstimmung der Maske unterstützen.

Schließlich möchtest du vielleicht wieder ein wenig Details aus der Grundfarbe in die Rauheit bringen. Mit dem <b>Kanalwechselfilter</b> kann ich Details zwischen verschiedenen Kanälen mischen und überblenden. Sie können die <b>-Eingabe auf Basecolo</b>r, die <b>-Ausgabe auf Rauheit</b> festlegen und dann mit der Überblendung und der Deckkraft spielen, um etwas Interessantes und dem realen Leben nahe genug zu bringen.

Wenn du die endgültige Rauheit besser steuern willst, kannst du den Helligkeitskontrastfilter verwenden und ihn so einstellen, dass er sich auf den Rauheit-Kanal auswirkt. Passe dann die Werte an, damit die Rauheit etwas knackiger wird.

Jedes Objekt ist anders, und je nach Datensatz sind möglicherweise spezifische Anpassungen erforderlich. Sie können sogar das <b>Klon Stamp-Tool</b> verwenden, um Teile Ihrer Textur zu löschen, die Sie entfernen möchten, z. B. Markierungen für Hilfsmittel. Denke einfach daran, dass jeder Material-Filter, der bestimmte Speicherorte auf deiner Textur verwendet, vom UV-Layout abhängt. Das gilt auch für die Mesh-Verarbeitung, bevor Material-Filter angewendet werden.

Wenn Sie mit Ihrem Objekt und Ihren Texturen zufrieden sind, können Sie <b>Ihr Ergebnis exportieren</b>und das Ergebnis mit dem Dialogfeld <b>Freigeben > Exportieren als</b> exportieren. Mit den allgemeinen Einstellungen können Sie den Namen und den Pfad auswählen, mit den Mesh-Einstellungen können Sie das 3D-Mesh-Format auswählen, und mit den Material-Einstellungen können Sie das Material des Meshs konfigurieren. Sie können Mesh oder Material deaktivieren, um nur einen davon einzeln zu exportieren. Der exportierte Mesh kann in anderen 3D-Anwendungen verwendet werden.
