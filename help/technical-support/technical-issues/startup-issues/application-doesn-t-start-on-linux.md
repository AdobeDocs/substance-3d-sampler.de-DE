---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie Startprobleme bei Substance 3D Sampler unter Linux beheben, um Startprobleme bei Anwendungen und Fehlermeldungen zu lösen.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Die Anwendung wird unter Linux nicht gestartet
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# Die Anwendung wird unter Linux nicht gestartet

Die Anwendung kann unter Linux nicht gestartet werden, wenn die folgende Fehlermeldung in einem Terminal angezeigt wird:

```
error while loading shared libraries: libicui18n.so.50
```


Dies bedeutet, dass die ICU der Bibliothek ([Internationale Komponenten für Unicode](http://site.icu-project.org/)) entweder fehlt oder die installierte Version zu neu ist. Die Anwendung benötigt Version 50.

Um diese Probleme zu beheben, installieren Sie entweder Version 50 aus dem Paketmanager oder [laden Sie die fehlende Version ](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm) manuell herunter, wenn Sie sie in **/usr/lib64** installieren.
