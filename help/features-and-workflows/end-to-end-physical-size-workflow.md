---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/features-and-workflows/end-to-end-physical-size-workflow.html"
breadcrumb-title: ''
description: Lernen Sie, wie Sie mit Substance 3D Sampler nahtlose Physische Größen erstellen, die realitätsgetreu skaliert werden.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > End to end Physical Size Workflow
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arbeitsablauf für End-to-End-Physische Größe
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Arbeitsablauf für End-to-End-Physische Größe

Stimmen Sie die Physische Größe gescannter Samples und Bilder in einem digitalen Kontext ab, um in allen Anwendungen präzise Visuals zu erstellen.

## Scans importieren

1. Wählen Sie die Materialerstellungsvorlage aus.
1. Aktivieren Sie das Kontrollkästchen Physische Größe .

   ![](../assets/screenshot-2022-01-20-at-16-15-53.png)
1. Zwei Ansätze zur Festlegung der Physische Größe:

   3a. Klicken Sie auf manuelles Messen - Mit dem Messwerkzeug können Sie die Physische Größe zwischen zwei Merkmalen der Probe kalibrieren.\
   Track zwischen zwei Punkten -> Eingeben

   ![](../assets/screenshot-2022-01-20-at-16-31-26.png)

   3b. Automatisch messen - Mit dem Werkzeug zum automatischen Messen können Sie eine geschätzte Physische Größe Ihrer Stichprobe basierend auf den Bildmetadaten (dpi) erhalten. Es ist schneller, funktioniert aber nur mit Scans, da es die gespeicherte dpi verwendet, um eine genaue Anfangsgröße zu berechnen.

   <b>Sie können die Scans jetzt verarbeiten</b>
1. Schneide das Bild zu. Passe es an die Vorlage an. Sie können sehen, dass die Physische Größe unten rechts im 2D-Viewport aktualisiert wurde.

   Zeigt das physikalische Verhältnis im 2D-Viewport an, um die Karten, an denen ihr arbeitet, genau zu sehen.\
   Sie können die 2D-Ansicht an die Physische Größe anpassen, sodass der DPI-Wert Ihres Bildschirmverhältnisses mit Ihrer Materialskala übereinstimmt. Mit anderen Worten, Sie können Ihr echtes Muster neben Ihren Bildschirm setzen, um die Abmessungen zu überprüfen.

   ![](../assets/cq5dam.web.1280.png)
1. Mit dem Regler &quot;Tonwertangleichung&quot; kannst du Verläufe entfernen.
1. Kachel hinzufügen, um die Kachelung zu korrigieren
1. Bei Bedarf ist die Verkrümmungstransformation hilfreich, um nur Teile der Karte neu auszurichten.

   <b>Bereit zum Exportieren</b>
1. Exportieren als

   Wählen Sie das SBSAR-Format aus. Sampler speichert die Physische Größe als Metadaten in das Format. Andere Anwendungen können diese Informationen ebenfalls lesen und verwenden.\
   Sie können auch Bilder exportieren. die Physische Größe wird eingehalten.

   Wenn Sie die Physische Größe zu einem beliebigen Zeitpunkt verwenden müssen, verwenden Sie den Bereich *Physische Größe*.

   Beim Exportieren als Bilder ist es jetzt möglich, die Physische Größe der Bilder auf das Bildverhältnis zu zwingen.

## Video-Tutorial

Außerdem finden Sie Video-Tutorials, die Ihnen diese Funktion erleichtern:
