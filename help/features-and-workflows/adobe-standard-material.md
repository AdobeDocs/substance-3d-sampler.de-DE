---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/adobe-standard-material.html"
breadcrumb-title: ''
description: Erfahre, wie du mit Adobe Standard Material in Substance 3D Sampler Material erstellst, die mit dem Material-Standard von Adobe kompatibel sind.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Adobe Standard Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Adobe-Standardmaterial
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 1%

---


# Adobe-Standardmaterial

>[!NOTE]
>
> Substance 3D Sampler verwendet jetzt standardmäßig das Materialmodell [OpenPBR](openpbr.md) und nicht das Adobe Standard Material.


## Standardeigenschaften von Materialien

## Eigenschaften der Basisoberfläche

**Grundfarbe**

Die Farbe der Oberfläche.

**Raueit**

Wie glatt oder matt die Oberfläche ist.

![](../assets/surface-roughness.jpg)

**Metallisch**

Der metallic Glanzgrad der Oberfläche.

![](../assets/surface-metallic.jpg)

**Deckkraft**

Die Sichtbarkeit der Oberfläche.

![](../assets/surface-opacity.jpg)

**Ambient occlusion**

Schatten aus Hohlräumen und Falten, die verhindern, dass Licht auf die Oberfläche trifft.

**Specular level**

Die Stärke von Lichtreflexionen auf der Oberfläche.

![](../assets/surface-specularlevel.jpg)

**Specular edge color**

Die Farbe von Lichtreflexionen. Wirkt sich auf die Blickwinkel bei metallic Materialien aus.

![](../assets/surface-specularedgecolor.jpg)

**Normal**

Simuliert Oberflächendetails wie Unebenheiten und Risse.

**Normale Skalierung**

Die Stärke des Normaleffekts.

**Normal und Height kombinieren**

Wendet die normale Textur auf die Textur des Heights an.

**Height**

Erstellt Oberflächendetails mithilfe eines Bump- oder Geometrie-Versatzes.

**Height-Skalierung**

Die Skala des Heights in Szenen. Gilt sowohl für Bump als auch für Versatz.

**Height-Ebene**

Der Wert der Textur des Heights, der Null-Versatz darstellt.

**Anisotropy level**

Der Grad, in dem die Reflexionen entlang der Oberfläche in eine Richtung gedehnt werden.

![](../assets/surface-anisotropy.jpg)

**Winkel der Anisotropie**

Die Drehung des anisotropen Effekts im Gegenuhrzeigersinn.

**Emissionsintensität**

Die Intensität des von der Oberfläche emittierten Lichts.

![](../assets/surface-emission.jpg)

**Emissionsfarbe**

Die Farbe des emittierten Lichts.

![](../assets/surface-emissioncolor.jpg)

**Deckkraft des Glanzes**

Simuliert die Wirkung mikroskopischer Fasern oder Fuzz auf die Oberfläche.

![](../assets/surface-sheen.jpg)

**Glanzfarbe**

Die Farbe des Effekts &quot;Glanz&quot;.

![](../assets/surface-sheencolor.jpg)

**Glanz Rauheit**

Weichheit des Effekts &quot;Glanz&quot;.

![](../assets/surface-sheenroughness.jpg)

## Innen-Eigenschaften

**Translucency**

Die Menge an Licht, die durch die Oberfläche übertragen werden kann.

![](../assets/interior-translucency.jpg)

**Absorptionsfarbe**

Das Farblicht wird bei der Absorption konvergiert.

**Entfernung von der Absorption**

Ungefähre Entfernung in Szene, die das Licht zurücklegt, bevor es die Absorptionsfarbe erreicht. Bei einem Wert von Null wirkt sich die Thickness nicht auf die Absorptionsfarbe aus.

![](../assets/interior-absorptiondistance.jpg)

**Brechungsindex**

Die Menge an Licht, die sich beim Durchdringen des Objekts beugt.

![](../assets/interior-indexofrefraction.jpg)

**Dispersion**

Der Wert, um den sich das Farbspektrum beim Brechen ausbreitet.

**Volumenstreuung**

Streuungen werden unter der Wasseroberfläche beleuchtet, anstatt direkt durch die Oberfläche zu gehen.

**Streufarbe**

Die Farbe unterhalb der Oberfläche, in der das gestreute Licht erscheint.

![](../assets/interior-scattercolor.jpg)

**Streuungsabstand**

Ungefähre Entfernungen müssen erfasst werden, bevor die Streuung vollständig erreicht wird.

![](../assets/interior-scatterdistance.jpg)

**Streudistanzskala**

Ein Multiplikator des Abstands der Streuung. Kann für jeden Farbkanal unterschiedlich sein.

![](../assets/interior-scatterdistancescale.jpg)

**Rote Schicht**

Legt fest, dass sich rotes Licht weiter bewegt als andere Lichtfarben. Nützlich für Haut.

![](../assets/interior-scatterredshift.jpg)

**Rayleigh-Streuung**

Legt fest, dass sich orangefarbenes Licht weiter unter der Oberfläche bewegt und blaues Licht weniger.

![](../assets/interior-scatterraleigh.jpg)

**Volume-Thickness**

Die Thickness der Fläche relativ zum Begrenzungsrahmen des Objekts. Wird für Inneneffekte verwendet, wenn die tatsächliche Thickness nicht bekannt ist.

**Skalierung der Volume-Thickness**

Multiplikator der Lautstärke-Thickness.

## Fellbeschaffenheit

**Coat opacity**

Simuliert eine Ebene über dem Material. Wird verwendet, um klare Schichten, Lacke und Lacke zu erzeugen.

![](../assets/coat-coatopacity.jpg)

**Mantelfarbe**

Die Farbe des Fells.

![](../assets/coat-coatcolor.jpg)

**Coat roughness**

Glätten oder Matte der Felloberfläche

![](../assets/coat-coatroughness.jpg)

**Brechungsindex der Beschichtung**

Die Lichtmenge bricht sich beim Durchgang durch das Fell.

![](../assets/cooat-coatior.jpg)

**Coat specular level**

Die Stärke von Lichtreflexionen auf dem Fell bei Blickwinkeln.

![](../assets/coat-coatspecular.jpg)

**Coat normal**

Simuliere Oberflächendetails wie Unebenheiten und Risse auf der Mantelfläche.

![](../assets/coat-coatnormal.jpg)

**Normale Skala beschichten**

Die Festigkeit des Effekts &quot;Fell-Normal&quot;.
