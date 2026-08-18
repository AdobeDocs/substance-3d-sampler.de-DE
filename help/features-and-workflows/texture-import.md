---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Lerne, wie du Strukturen in Substance 3D Sampler importierst, um vorhandene Bilddateien in deinen Workflows zur Materialerstellung zu verwenden.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Texturimport
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 8%

---


# Texturimport

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

Die **Texturimport**-Vorlage lädt mehrere Bilder und verbindet sie basierend auf ihren Dateinamen automatisch mit den richtigen Ausgabekanälen.

Der Kanalabgleich basiert auf den im Folgenden beschriebenen spezifischen Namenskonventionen. Bei Duplikaten oder Texturen ohne Entsprechung werden Bilder in der Benutzeroberfläche als solche markiert.

## OpenPBR

Sampler gleicht Dateien mit den folgenden OpenPBR-Bezeichnern mit dem entsprechenden Kanal im Material ab.

>[!NOTE]
>
> Height-Kanal-Bezeichner sind dieselben wie für ASM.


| OpenPBR-ID | SBSAR-Nutzung |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | metallisch/metallisch |
| base_diffuse_roughness | baseDiffuseRoughness |
| Specular_weight | specularWeight |
| Specular_color | specularColor |
| Specular_Raueit | specularRaueit/Raueit |
| Specular_Raueit_Anisotropie | specularRoughnessAnisotropy/AnisotropyLevel |
| Specular_ior | specularIOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | transmissionColor/absorptionColor |
| Tiefe_Übertragung | transmissionDepth/absorptionDistance |
| Streuung_Übertragung | transmissionScatter |
| Streuung_Übertragung_Anisotropie | transmissionScatterAnisotropy |
| transmission_dispersion_scale | transmissionDispersionScale |
| transmission_dispersion_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsurfaceGewicht/Lichtdurchlässigkeit |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_Streuung_Anisotropie | subsurfaceScatterAnisotropy |
| coat_weight | FellGewicht/FellDeckkraft |
| coat_color | coatColor |
| coat_rauness | coatRoughness |
| coat_rauheit_Anisotropie | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| coat_darkening | coatDarkening |
| fuzz_weight | fuzzWeight/sheenOpacity |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_roughness | fuzzRoughness/sheenRoughness |
| emission_weight | emissionWeight |
| emission_luminance | emissionLuminanz |
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

| **Kanal** | **Adobe-Standardmaterial** |
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

