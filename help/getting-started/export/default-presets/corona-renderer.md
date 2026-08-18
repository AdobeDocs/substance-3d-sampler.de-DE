---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/export/default-presets/corona-renderer.html"
breadcrumb-title: ''
description: Lerne, wie du in Substance 3D Sampler Materialien mithilfe des Renderers "Corona" für Workflows zur Visualisierung von Architekturen exportieren kannst.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Default Presets > Corona Renderer
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Corona Renderer
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '91'
ht-degree: 2%

---


# Corona Renderer

| Voreinstellung | Kompatibilität | Beschreibung der Packing-Ausgabe |
| --- | --- | --- |
| Corona Renderer | <ul data-preserve-html="true"><li data-preserve-html="true">PBR Metallisch/Raueit</li><li data-preserve-html="true">PBR Specular/Glanz</li></ul> | **Diffuse****ReflectionGlossiness** (\*)**ReflectionColor** (\*\*)**FresnelIOR** (\*\*\*)**Normal ****Versatz**** Emissive****Opacity** |

>[!NOTE]
>
> **(\*)** Reflexionsglanz: Quadratische Version des Glanzkanals (Glanzgrad \* Glanzgrad)
> 
> **(\*\*)** Reflexionsfarbe: Exportieren einer Karte, bei der Weiß auf ein dielektrisches Material und andere Farben für metallische Materialien hinweist
> 
> **(\*\*\*)** FRANZÖSISCH ODER: 1 dividiert durch den älteren Wert, der aus der metallischen Karte generiert wird: 1.4 für Dielektrika, 100 für Metalle (schwarze Farbe)
