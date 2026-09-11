---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/pbr-validate.html"
breadcrumb-title: ''
description: Mit dem PBR-Validierung-Tool in Substance 3D Sampler können Sie überprüfen, ob Materialien den physikalisch basierten Rendering-Standards entsprechen.
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

Verwenden Sie den **Datenfilter**, um sicherzustellen, dass die PBR-PBR-Validierungen Ihres Materials korrekt sind. Im Gegensatz zu den meisten Filtern ist der **Datenfilter** nicht als permanenter Teil des Ebenenstapels gedacht. Verwenden Sie ihn stattdessen, um Ihr Material zu überprüfen und es dann zu entfernen, damit es Ihr Material nicht ändert. PBR-Validierung:

</td>
</tr>
</table>

## Parameter

**Basisparameter**

* **Validierungsmodus**:\
  Legen Sie fest, ob die Werte für die Albedo (Grundfarbe oder Diffus), die metallic Werte oder sowohl die Albedo als auch die metallic Werte validiert werden sollen. Andere Parameter werden basierend auf dieser Auswahl aktualisiert.
  * **Validierungsmodus: Albedo**
    * **Schwellenwert für dunklen Bereich der Albedo**:\
      Legen Sie den Schwellenwert fest, mit dem dunkle Werte vom Filter als ungültig erkannt werden.
    * **Überlagerungszuordnung**: Knebel\
      Zwischen Überlagerungsmodus wechseln: Wenn diese Option aktiviert ist, wird die Grundfarbe-Map mit den ungültigen Pixeln überlagert.
    * **Validierung in Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen aus dem Kanal der Grundfarbe aus.
  * **Validierungsmodus: Metal**
    * **Reflexionsbereich des Metalls**:\
      Legen Sie den Bereich der vom Filter aufzunehmenden Reflexionswerte als ungültig fest.
    * **Überlagerungszuordnung**: Knebel\
      Zwischen Überlagerungsmodus wechseln: Wenn diese Option aktiviert ist, wird die Grundfarbe-Map mit den ungültigen Pixeln überlagert.
    * **Validierung in Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen aus dem Kanal der Grundfarbe aus.
  * **Validierungsmodus: Kombiniert**
    * **Schwellenwert für dunklen Bereich der Albedo**:\
      Legen Sie den Schwellenwert fest, mit dem dunkle Werte vom Filter als ungültig erkannt werden.
    * **Reflexionsbereich des Metalls**:\
      Legen Sie den Bereich der vom Filter aufzunehmenden Reflexionswerte als ungültig fest.
    * **Validierung in Grundfarbe ausblenden**: Knebel\
      Blenden Sie die Validierungsinformationen aus dem Kanal der Grundfarbe aus.

## Benutzerhandbuch

Mit **PBR-Validierung** **filter** können Probleme mit der Albedo und metallic Werten in einem Material vermieden werden. Um zu verstehen, wie der **Datenfilter** funktioniert, ist es hilfreich, zunächst ein wenig darüber zu sprechen, was PBR ist.

## Was ist PBR?

PBR steht für &quot;Physically Based Rendering&quot; (Physikalisch basiertes Rendering). Bei dieser Methode werden Objekte und Materialien gerendert, indem die physikalischen Eigenschaften einer Oberfläche mit verschiedenen Kanälen dargestellt werden. PBR wurde entwickelt, um die reale, physische Welt genauer darzustellen als vorherige Render- und Schattierung-Methoden.

In der realen Welt gibt es einige Farben und Kombinationen von Eigenschaften, die entweder unmöglich oder unglaublich selten sind. Zum Beispiel hat fast nichts in der realen Welt eine reine weiße oder reine schwarze Albedo oder Grundfarbe.

Da PBR versucht, reale Werte darzustellen, und da einige Werte nicht oder selten in der realen Welt erscheinen, ist es möglich, &quot;falsche&quot; PBR-Werte zu haben. Dies ist der Zweck des **PBR-Validierung-Filters**.

## PBR-Validierungen verwenden

Um **PBR-Validierungen** zu verwenden, fügen Sie sie oben auf Ihrem Ebenenstapel hinzu. Das Erscheinungsbild Ihres Materials sollte sich stark ändern. Dies liegt daran, dass der **Datenfilter** die Ergebnisse der PBR-Validierung im Albedo-Kanal anzeigt.

Der Filter verwendet eine rote bis grüne Skala, um anzuzeigen, wo Fehler sind. Wenn das gesamte Material grün ist, sind die Farben oder metallic Werte des Materials in Ordnung. Wenn Sie jedoch gelbe, orangefarbene oder rote Bereiche sehen, gibt es Probleme mit Ihrem Material.

Wenn Sie den Farbvalidierungsmodus verwenden, bedeuten nicht grüne Bereiche in der Regel, dass es Werte in Ihrer Grundfarbe gibt, die entweder vollständig schwarz oder vollständig weiß sind. Verwenden Sie Korrekturfilter wie **Farbton/Sättigung** oder **Helligkeit/Kontrast**, um die Werte Ihres Farbkanals anzupassen, bis der **PBR-Validierung-Filter** keine Fehler mehr anzeigt.

Wenn Sie den Metall-Validierungsmodus verwenden, bedeuten nicht grüne Bereiche in der Regel, dass die Kombination Ihrer Farben, Rauheiten und metallic Karten in diesen Bereichen unrealistisch ist. Dies geschieht in der Regel bei dunklen Farbwerten, 0 Rauheiten und 1 metallic Werten. Um diese Fehler zu beheben, können Sie die Rauheit, die metallic Werte oder die Farbwerte ändern, bis der **Datenfilter** keine PBR-Validierungen mehr anzeigt.
