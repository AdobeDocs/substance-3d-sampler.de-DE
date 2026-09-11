---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/getting-started/export/default-presets/corona-renderer.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie Materials aus Substance 3D Sampler exportieren, indem Sie die Voreinstellung "Corona Renderer" für Workflows zur Architekturvisualisierung verwenden.
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
| Corona Renderer | <ul data-preserve-html="true"><li data-preserve-html="true">PBR Metallic/Rauheit</li><li data-preserve-html="true">PBR Specular/Glanz</li></ul> | **Diffuse**&#x200B;**ReflectionGlossiness** (\*)**ReflectionColor** (\*\*)**FresnelIOR** (\*\*\*)**Normal &#x200B;**&#x200B;**Versatz**&#x200B;**&#x200B; Emissive**&#x200B;**Opacity** |

>[!NOTE]
>
> **(\*)** Reflektions-Glanz: Quadratische Version des Glanz-Kanals (Glanz \* Glanz)
> 
> **(\*\*)** Reflexionsfarbe: Exportieren einer Map, wobei Weiß ein dielektrisches Material und andere Farben für metallic Material angibt
> 
> **(\*\*\*)** FRANZÖSISCH ODER: 1 dividiert durch den Seniorwert, Senior wird aus der metallic Karte generiert: 1.4 für Dielektrika, 100 für Metalle (schwarze Farbe)
