---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/interface/panels/channel-settings-panel.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie das Bedienfeld "Kanaleinstellungen" in Substance 3D Sampler verwenden, um Material-Kanäle zu verwalten und die Kanalsichtbarkeit zu steuern.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Channel Settings panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Bereich "Kanaleinstellungen"
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 1%

---


# Bereich &quot;Kanaleinstellungen&quot;

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


Der Bereich &quot;**Kanaleinstellungen**&quot; steuert die Liste der Kanäle, die für das aktuelle Material berechnet wurden. Sie können die Kanalsichtbarkeit verwalten, Kanäle zu Ihrem Material hinzufügen oder daraus entfernen oder das verwendete Materialmodell ändern.

</td>
<td style="border: 0;" valign="top">

![Das Bedienfeld für Kanaleinstellungen.](../../assets/6.0_ChannelSettingsPanel.png)

</td>
</tr>
</table>

## Materialmodell

Verwenden Sie diese Dropdown-Liste, um das Shader-Framework auszuwählen, das zum Rendern Ihres Materials verwendet wird. Die Optionen im Bereich &quot;**Kanaleinstellungen&quot;** ändern sich je nach ausgewähltem Materialmodell.

Wenn du das Materialmodell änderst, muss dein Ebenenstapel für das neue Modell neu berechnet werden, und es werden verschiedene Kanäle verfügbar gemacht. Sampler versucht, Datenverluste bei der Konvertierung zu minimieren. Es ist jedoch möglich, dass die Änderung mit einem neuen Materialmodell zu subtilen Aussehen-Unterschieden führt.

>[!NOTE]
>
> Es ist möglich, von Adobe Standard Material (ASM) zu OpenPBR zu wechseln, aber es ist derzeit nicht möglich, von OpenPBR zu ASM zu wechseln.


## Materialkanäle

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


In diesem Abschnitt wird die Liste der Kanäle angezeigt, die standardmäßig basierend auf dem Workflow berechnet werden.

Sie können die Schaltfläche **Liste bearbeiten** verwenden, um die **Kanalauswahl** zu öffnen und zu ändern, welche Kanäle für Ihr Material berechnet werden.

</td>
<td style="border: 0;" valign="top">

![Das Bedienfeld &quot;Kanaleinstellungen&quot; mit hervorgehobenem Abschnitt &quot;Material Channels&quot;](../../assets/6.0_ChannelSettingsPanel_MaterialChannels.png){width="200px"}

</td>
</tr>
</table>

>[!NOTE]
>
> Einige Material aus Substance Source geben beispielsweise keine Deckkraft oder ambient occlusion aus. Auch wenn der Deckkraftkanal als &quot;berechnet&quot; markiert ist, wenn die Substance-Datei ihn nicht ausgibt, generiert Sampler ihn nicht.

### Kanalauswahl

Im Kanalauswahlfenster können Sie Kanäle zu Ihrem Material hinzufügen oder daraus entfernen.

![Ein Screenshot des Kanalauswahlfensters, in dem das Adobe Standard Material als Materialmodell ausgewählt ist.](../../assets/6.0_ChannelSelectionWindow.png)

Um Ihrem Material einen Kanal hinzuzufügen, wählen Sie einen verfügbaren Kanal aus und verwenden Sie die Schaltfläche **>**.
Um einen Kanal aus Ihrem Material zu entfernen, wählen Sie den Kanal aus der Liste **Ausgewählte Kanäle** aus und verwenden Sie die Schaltfläche **&lt;**.
Mit der Schaltfläche **≫** können Sie Ihrem Material alle verfügbaren Kanäle hinzufügen. Mit der Schaltfläche **≪** können Sie alle Kanäle aus Ihrem Material entfernen.

Sie können auch Vorgaben verwenden, um schnell eine Kanalliste für Ihr Material auszuwählen. Standardmäßig umfasst Sampler eine Reihe von Vorgaben, Sie können jedoch auch eigene Vorgaben erstellen:

1. Fügen Sie die gewünschten Kanäle zu Ihrem Material hinzu.
1. Verwenden Sie die Schaltfläche **Als Vorgabe speichern**.
1. Benennen Sie Ihre Vorgabe.

>[!NOTE]
>
>Beim Speichern einer Vorgabe wird die Vorgabe nicht auf Ihr Material angewendet.

## Benutzerdefinierte Kanäle

Schalten Sie zusätzliche Kanäle ein, die standardmäßig nicht im ausgewählten Arbeitsablauf enthalten sind.

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">

Jeder benutzerdefinierte Kanal verfügt über zwei Optionen, die Sie verwenden können, um ihn zu steuern:

1. Mit dem Schalter &quot;Sichtbarkeit&quot; können Sie den Kanal in der 2D-Ansicht ein- oder ausblenden.
2. Verwenden Sie die **Schaltfläche &quot;Auto&quot;**, um zwischen der automatischen Kanalberechnung und der Kanalberechnung umzuschalten.
   * Ist diese Option aktiviert, wird der Kanal berechnet, wenn eine Ebene darüber im Stapel dies anfordert.
   * Bei deaktivierter Funktion wird der Kanal immer berechnet.

</td>
<td style="border: 0;" valign="top">

![Das Bedienfeld &quot;Kanaleinstellungen&quot; mit dem Abschnitt &quot;Benutzerdefinierte Kanäle&quot; ist hervorgehoben.](../../assets/6.0_ChannelSettingsPanel_CustomChannels.png){width="200px"}


</td>
</tr>
</table>



