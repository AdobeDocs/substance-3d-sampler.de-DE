---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/cross-polarising-for-3d-capturesubstance-3d-sampler.html"
breadcrumb-title: ''
description: Lerne, wie du in Substance 3D Sampler mit Kreuzpolarisationstechniken Reflexionen reduzieren und die Qualität der 3D-Erfassung verbessern kannst.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Kreuzpolarisation für die 3D-Erfassung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---


# Kreuzpolarisation für die 3D-Erfassung

>[!WARNING]
>
> Die Unterstützung für 3D-Erfassungen wurde ab der Sampler-Version 5.1 entfernt.

## Kreuzpolarisation

In diesem Benutzerhandbuch erfährst du, wie du mit reflektierenden Objekten umgehst und welche Probleme sie verursachen und wie du die Lichtpolarisation einsetzt, um dies zu beheben.

Sie möchten mehr über dieses Thema in einem Video-Tutorial erfahren? Finden Sie es [hier](https://youtu.be/VWsbP56MDk0?si=Hdp7vblJB6L1RPxK "Tutorial zur Kreuzpolarisierung").

![](../assets/polarized-lens-3d-capture.png)

Trifft Licht auf eine Oberfläche, wird es in der Regel diffus reflektiert, springt gleichmäßig und verleiht der Oberfläche ihren farblichen Look. Je nach Rauheit der Wasseroberfläche kann jedoch etwas Licht direkt in Richtung des Auges oder der Kamera reflektiert werden. Diese <b>Specular-Reflexion</b> ändert sich je nach Betrachtungswinkel.

Bei der Photogrammmetrie werden visuelle Muster und Elemente zwischen Fotos ausgerichtet. Es wird davon ausgegangen, dass sich das Aussehen eines Objekts nicht bei jedem aufeinander folgenden Foto ändert. Also, Specular-Reflexion ist hier ein unerwünschter Effekt. Ein Lightcase-Objekt hat vielleicht nur eine reflektierende Beschichtung, aber bei Objekten, die aus Metall bestehen, kann es viel schwieriger sein und es kann mehr Aufwand erfordern, sie zu lösen. Dieses Benutzerhandbuch befasst sich mit diesem milden Fall. Wir müssen nur eine perfekte Grundfarbe einfangen, unberührt von Specular-Highlights. Wenn du den Reflexionsgrad nach der Aufnahme wieder in 3D zeichnest, kannst du ihn leicht hinzufügen.

Um dies zu beheben, können wir unsere Specular-Reflexionen mit einer Methode namens <b>Kreuzpolarisation</b> filtern. Wenn Licht polarisiert ist, sind alle Wellen in dieselbe Richtung gerichtet. Wenn Sie ihn dann wieder polarisieren, wird er in senkrechter Richtung komplett blockiert und somit unsichtbar.

Die Polarisation beeinflusst meistens das Specular-Licht, da es sich um fokussierte Lichtstrahlen handelt, die sich in eine bestimmte Richtung bewegen, im Gegensatz zu dem gestreuten diffusen Licht, das wir behalten wollen.

Du polarisierst Licht mit einem Polarisationsfilter, einer speziellen transparenten Folie, die die Wellen filtert. Es gibt sie in vielen Varianten. Wir werden angeschraubte Glasfilter für deine Objektive verwenden, sowie polarisierende Folien im Do-it-Yourself-Stil

Die Grundidee besteht darin, <b>Ihrem Licht einen Filter </b> und <b>Ihrem Objektiv</b> hinzuzufügen und diese so einzurichten, dass sie <b> senkrecht zueinander stehen</b>. Das bedeutet, dass Sie die Filterausrichtung durch Drehen anpassen müssen. Sobald sie eingerichtet sind, werden die Specular-Reflexionen aus diesem Licht unsichtbar. Das Besondere an dieser Aufnahme ist, dass durch Verdrehen der Filter plötzlich der gesamte Blendeffekt des polarisierten Lichts vollständig eliminiert wird.

![](../assets/polarizing-before-after-3d-capture.png)

Du solltest einen Polarisationsfilter für dein Objektiv kaufen, da du eine optimale Optik möchtest, der aber dennoch klare, scharfe Fotos ermöglicht. Objektive haben verschiedene Größen, auf die du Filter schrauben kannst. Sorge also dafür, dass das richtige Objektiv deiner Wahl ist, oder ein paar Größen für mehrere Objektive, wenn du experimentierst.

Die Polarisation Ihrer Lichter ist billiger und einfacher:<b> polarisierende Filmblätter</b> sind relativ kostengünstig. Du kannst ein ganzes Blatt verwenden oder Teile ausschneiden. Es empfiehlt sich, runde Teile zu schneiden, die das gesamte Licht abdecken, da sie sich so leichter drehen lassen. Manche Lampen sind dafür besser geeignet, da sie einen kleinen Filterhalter haben können, oder Magnete, um die Blätter an Ort und Stelle zu halten. Wenn nicht, funktioniert Klebeband immer!

Stellen Sie sicher, dass Sie <b>den Polarisator nach allen Diffusoren hinzufügen</b>, da das Diffundieren des Lichts jede Polarisation unterbricht.

Die meisten billigeren Ringblitze verschrauben sich in Ihren Filterschlitz und lassen Sie möglicherweise keinen Objektivfilter mehr anbringen. Es gibt auch keine Möglichkeit, Polarisationsfilter am Blitzlicht anzubringen. Du musst also selbst einen solchen Filter erstellen. Nur Modelle der obersten Ebene unterstützen dies ordnungsgemäß.

<b>Das Drehen und Abgleichen von Polarisatoren über Ihre Einrichtung muss ständig erfolgen</b>. Dein Objektivfilter muss vollständig senkrecht zu all deinen Kameras stehen. Die einzige Möglichkeit dazu ist, auf dein Kameradisplay zu schauen und Einstellungen vorzunehmen. Ich möchte zuerst ein einzelnes Blatt auf mein Blitzlicht kleben und dann den Linsenfilter anpassen, um die Reflexionen des Blitzes zu blockieren. Das geht nur, wenn du ein Foto machst oder den Blitz trocken feuerst. Es ist ein bisschen aufwändig: Du kannst die richtige Ausrichtung auf deinem Objektivfilter mit einer Marke markieren und dann versuchen, das Objektiv und den Blitzfilter nicht mehr zu berühren.

Die Polarisierung an den Videolichtern anzupassen ist anders, aber einfacher. Du musst deine Lichter ständig anpassen, während du sie bewegst oder wenn du das Height der Kamera anpasst. <b>Drehen Sie das Blatt einfach, bis es auf Ihrem Kamera-Display gut aussieht</b>.

<b>Jede einzelne Lichtquelle, die in Reflexionen auftaucht, muss polarisiert sein</b>, sodass Sie möglicherweise Fenster schließen oder Bildschirme ausschalten müssen.

Bei der richtigen Einrichtung solltest du in der Lage sein, ein Objekt so einzufangen, als wäre es vollständig matt, ohne Reflexionen und sogar Beleuchtung. So wie Sie Ihren Mesh sehen, auf den nur die Textur der Grundfarbe angewendet wurde, können Sie auch schwierige reflektierende Objekte einfangen.

Erfahren Sie jetzt mehr über [wie Sie Ihre 3D-Erfassungen mit Substance 3D Sampler verarbeiten](processing-advanced-3d-captures.md)!
