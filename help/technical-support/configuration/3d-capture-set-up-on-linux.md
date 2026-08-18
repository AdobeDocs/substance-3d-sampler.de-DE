---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/technical-support/configuration/3d-capture-set-up-on-linux.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie 3D-Erfassungen zu Linux für Substance 3D Sampler einrichten, indem Sie Wine 8 installieren und die Systemanforderungen konfigurieren.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 3D-Erfassung-Setup unter Linux
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 0%

---


# 3D-Erfassung-Setup unter Linux

Um <b>3D-Erfassung</b> unter Linux verwenden zu können, müssen Sie <b>Wine 8</b> mit einem Administratorkonto installieren.

Ubuntu

apt-get install wine

Red Hat Enterprise Linux (RHEL 8)

sudo subscription-manager repos —enable codeready-builder-for-rhel-8-x86\_64-rpms

dnf install wine

Red Hat Enterprise Linux (RHEL 9)

sudo subscription-manager repos —enable codeready-builder-for-rhel-9-x86\_64-rpms

dnf install wine
