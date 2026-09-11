---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Erfahre, wie du Texturen in Substance 3D Sampler importierst, um bestehende Bilddateien in deinen Workflows zur Material-Erstellung zu verwenden.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Import von Texturen
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 8%

---


# Import von Texturen

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

Die **Textur Import**-Vorlage lädt mehrere Bilder und verbindet sie automatisch anhand ihrer Dateinamen mit den richtigen Ausgabekanälen.

Der Kanalabgleich basiert auf den im Folgenden beschriebenen spezifischen Namenskonventionen. Bei Duplikaten oder Texturen ohne Entsprechung werden die Bilder in der Benutzeroberfläche als solche markiert.

## OpenPBR

Sampler gleicht Dateien mit den folgenden OpenPBR-Bezeichnern mit dem entsprechenden Kanal im Material ab.

>[!NOTE]
>
> Height-Kanal-Identifizierungen sind die gleichen wie für ASM verwendet.


| OpenPBR Identifizierung | SBSAR-Nutzung |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | metallisch/metallisch |
| base_diffuse_Rauheit | baseDiffuseRoughness |
| Specular_weight | specularWeight |
| Specular_color | specularColor |
| Specular_Rauheit | specularRoughness/Rauheit |
| Specular_Rauheit_Anisotropie | specularRoughnessAnisotropy/AnisotropyLevel |
| Specular_ior | specularIOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | transmissionColor/absorptionColor |
| Tiefe_Übertragung | transmissionDepth/absorptionDistance |
| Streuung_Übertragung | transmissionScatter |
| Streuung_Übertragung_Anisotropie | transmissionScatterAnisotropy |
| Streuung_Übertragung_Skalierung | transmissionDispersionScale |
| transmission_Streuung_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsurfaceWeight/translucency |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_Streuung_Anisotropie | subsurfaceScatterAnisotropy |
| coat_weight | FellGewicht/FellDeckkraft |
| coat_color | coatColor |
| coat_Rauheit | coatRoughness |
| coat_Rauheit_Anisotropie | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| coat_darkening | coatDarkening |
| fuzz_weight | fuzzWeight/sheenOpacity |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_Rauheit | fuzzRoughness/sheenRoughness |
| emission_weight | emissionWeight |
| emission_Luminanz | emissionLuminanz |
| emission_color | emissionColor/emisive |
| thin_film_weight | thinFilmWeight |
| thin_film_Thickness | thinFilmThickness |
| thin_film_ior | thinFilmIOR |
| Deckkraft | Deckkraft |
| dünnwandig | thinWalled |
| normal | normal |
| Tangente | Tangente |
| coat_normal | coatNormal |
| coat_tangent | coatTangent |

## Adobe-Standardmaterial

Im Folgenden finden Sie eine Liste der unterstützten Dateibenennungskonventionen für jeden Kanal:

| **Kanal** | **Adobe Standard Material** |
| --- | --- |
| **Umgebungs-Verdeckung** | <ul><li>Ambientokklusion</li><li>ao</li><li>Verdeckung</li><li>Umgebungsverdeckung</li></ul> |
| **Grundfarbe** | <ul><li>Grundfarbe</li><li>Farbe</li><li>Albedo</li><li>base_color</li><li>Basis</li><li>Gebirgsstock</li><li>Farbe</li><li>base_color</li><li>Grundfarbe</li></ul> |
| **Diffus** | <ul><li>diffus</li><li>diff</li></ul> |
| **Ausstrahlend** | <ul><li>Ausstrahlend</li></ul> |
| **Glossarität** | <ul><li>Glanzintensität</li><li>Gloss</li></ul> |
| **Height** | <ul><li>Höhe</li><li>Höhenplan</li><li>Versatz</li><li>Disp</li></ul> |
| **Metallisch** | <ul><li>Metallisch</li><li>mtl</li><li>Metallisierung</li></ul> |
| **Normal** | <ul><li>normal</li><li>nrm</li></ul> |
| **Deckkraft** | <ul><li>Deckkraft</li><li>Alpha</li></ul> |
| **Raueit** | <ul><li>Rauheit</li><li>rau</li></ul> |
| **Specular** | <ul><li>Glanz</li><li>Spezifikation</li></ul> |
| **Specular level** | <ul><li>Spiegelebene</li><li>Specular_Level</li></ul> |

