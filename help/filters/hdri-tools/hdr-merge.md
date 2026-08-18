---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Verwende das HDR-Zusammenfügungs-Tool in Substance 3D Sampler, um Fotos mit mehreren Belichtungen zu einer einzigen High Dynamic Range zusammenzufügen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: HDR verbinden
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# HDR verbinden

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**In:** HDRI-Werkzeugs

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit der **HDR-Zusammenführung** **filter** können Sie eine Sammlung von SDR-Bildern (Standard Dynamic Range) zusammenführen, um ein HDR-Bild zu erstellen.

Die folgenden Bilder zeigen die Ergebnisse der **HDR-Zusammenfügung**.

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

Bevor die **HDR-Zusammenführung** abgeschlossen ist, spiegelt die Kugel in der **3D-Ansicht** das Standardumgebungslicht wider. Die **2D-Ansicht** zeigt standardmäßig die importierten Bilddaten für das erste Scanbild an, das in diesem Fall das am wenigsten exponierte Bild ist.

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

Nachdem der **HDR-Merge** **filter** hinzugefügt wurde, reflektiert die Kugel ein neues Umgebungslicht - das HDR-Bild, das aus den Eingabebildern generiert wurde.

</td>
</tr>
</table>

## TParameter

**Basisparameter**

* **Eingangsbelichtungsdelta (EV)**: 0-2\
  Legen Sie die Belichtungsdifferenz zwischen der höchsten und der niedrigsten Eingangsbelichtung fest. Ein Delta mit hoher Belichtung erhöht den resultierenden Kontrast des Zusammenfügungsvorgangs.
* **Automatische Belichtung der Ausgabe**: Knebel\
  Aktivieren oder deaktivieren Sie die automatische Belichtungskorrektur.
* **Ausgabe-Belichtungskorrektur (EV)**: -5 bis 5\
  Versetze die Belichtung.

## Benutzerhandbuch

Im Folgenden erfahren Sie, wie Sie den **HDR-Zusammenführungsfilter** sowie weitere Filter verwenden, die beim Konvertieren von SDR-Bildern in eine HDR-Umgebungsbeleuchtung helfen können.

Die grundlegenden Schritte zur Verwendung der **HDR-Zusammenführung** **Filter** sind wie folgt:

1. Importieren Sie den Satz von Bildern, die in den Ebenenstapel eingelesen werden sollen.
1. Fügen Sie den **HDR-Zusammenführungsfilter** zum Ebenenstapel hinzu.
1. Ändern Sie die Parameter, um sicherzustellen, dass die Belichtungswerte korrekt sind.
