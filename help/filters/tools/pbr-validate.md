---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/filters/tools/pbr-validate.html"
breadcrumb-title: ''
description: Verwende das PBR-Validierung-Tool in Substance 3D Sampler, um zu prüfen, ob Materialien den physikalisch basierten Rendering-Standards entsprechen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > PBR Validate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: PBR-Validierung
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '653'
ht-degree: 0%

---


# PBR-Validierung

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pbrvalidate-18-n-d.png)

**In:** Tools

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Verwenden Sie den **Materialfilter**, um sicherzustellen, dass die PBR-Werte Ihres PBR-Validierung korrekt sind. Im Gegensatz zu den meisten Filtern ist der **Materialfilter** nicht als permanenter Teil des Ebenenstapels gedacht. Verwenden Sie ihn stattdessen, um das PBR-Validierung zu validieren und dann zu entfernen, damit es das Material nicht ändert.

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Validierungsmodus**:\
  Legen Sie fest, ob die Werte für die Albedo (Grundfarbe oder Diffus), die metallischen Werte oder sowohl die Albedo- als auch die metallischen Werte validiert werden sollen. Andere Parameter werden basierend auf dieser Auswahl aktualisiert.
  * **Validierungsmodus: Albedo**
    * **Schwellenwert für dunklen Bereich der Albedo**:\
      Legen Sie den Schwellenwert fest, mit dem dunkle Werte vom Filter als ungültig erkannt werden.
    * **Überlagerungszuordnung**: Knebel\
      Zwischen Überlagerungsmodus wechseln: Wenn diese Option aktiviert ist, wird die Grundfarbzuordnung mit den ungültigen Pixeln überlagert.
    * **Validierung in der Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen im Grundfarbkanal aus.
  * **Validierungsmodus: Metal**
    * **Reflexionsbereich des Metalls**:\
      Legen Sie den Bereich der vom Filter aufzunehmenden Reflexionswerte als ungültig fest.
    * **Überlagerungszuordnung**: Knebel\
      Zwischen Überlagerungsmodus wechseln: Wenn diese Option aktiviert ist, wird die Grundfarbzuordnung mit den ungültigen Pixeln überlagert.
    * **Validierung in der Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen im Grundfarbkanal aus.
  * **Validierungsmodus: Kombiniert**
    * **Schwellenwert für dunklen Bereich der Albedo**:\
      Legen Sie den Schwellenwert fest, mit dem dunkle Werte vom Filter als ungültig erkannt werden.
    * **Reflexionsbereich des Metalls**:\
      Legen Sie den Bereich der vom Filter aufzunehmenden Reflexionswerte als ungültig fest.
    * **Validierung in der Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen im Grundfarbkanal aus.

## Benutzerhandbuch

Mit **PBR-Validierung** **filter** können Probleme mit Albedo und metallischen Werten in einem Material vermieden werden. Um zu verstehen, wie der **Datenfilter** funktioniert, ist es hilfreich, zunächst ein wenig darüber zu sprechen, was PBR ist.

## Was ist PBR?

PBR steht für &quot;Physically Based Rendering&quot; (Physikalisch basiertes Rendering). Bei dieser Methode werden Objekte und Materialien gerendert, indem die physikalischen Eigenschaften einer Oberfläche mit verschiedenen Kanälen dargestellt werden. PBR wurde entwickelt, um die reale, physische Welt genauer darzustellen als vorherige Render- und Schattierung-Methoden.

In der realen Welt gibt es einige Farben und Kombinationen von Eigenschaften, die entweder unmöglich oder unglaublich selten sind. Zum Beispiel hat fast nichts in der realen Welt eine reine Weiß- oder Schwarz-Albedo oder -Grundfarbe.

Da PBR versucht, reale Werte darzustellen, und da einige Werte nicht oder selten in der realen Welt erscheinen, ist es möglich, &quot;falsche&quot; PBR-Werte zu haben. Dies ist der Zweck des **PBR-Validierung-Filters**.

## PBR-Validierungen verwenden

Um **PBR-Validierungen** zu verwenden, fügen Sie sie oben in Ihrem Ebenenstapel hinzu. Das Erscheinungsbild des Materials sollte sich drastisch ändern. Dies liegt daran, dass der **Datenfilter** die Ergebnisse der PBR-Validierung im Kanal &quot;Albedo&quot; anzeigt.

Der Filter verwendet eine rote bis grüne Skala, um anzuzeigen, wo Fehler sind. Wenn das gesamte Material grün ist, dann ist an den Farben oder den metallischen Werten Ihres Materials nichts auszusetzen. Wenn Sie jedoch gelbe, orange oder rote Bereiche sehen, gibt es Probleme mit Ihrem Material.

Wenn Sie den Farbvalidierungsmodus verwenden, bedeuten nicht grüne Bereiche in der Regel, dass es in Ihrer Grundfarbe Werte gibt, die entweder vollständig schwarz oder vollständig weiß sind. Verwenden Sie Korrekturfilter wie **Farbton/Sättigung** oder **Helligkeit/Kontrast**, um die Werte Ihres Farbkanals anzupassen, bis der **PBR-Validierung-Filter** keine Fehler mehr anzeigt.

Wenn Sie den Metall-Validierungsmodus verwenden, bedeuten nicht grüne Bereiche in der Regel, dass die Kombination aus Ihrer Farbe, Raueit und metallischen Karten in diesen Bereichen unrealistisch ist. Dies geschieht in der Regel bei dunklen Farbwerten, 0 Raueit und 1 metallischen Werten. Um diese Fehler zu beheben, können Sie die Raueit, die metallischen Werte oder die Farbwerte ändern, bis der **PBR-Validierung-Filter** keine Fehler mehr anzeigt.
