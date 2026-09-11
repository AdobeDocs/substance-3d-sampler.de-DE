---
helpx_url: "https://helpx.adobe.com/de/substance-3d-sampler/interface/panels/share-panel.html"
breadcrumb-title: ''
description: Erfahren Sie, wie Sie das Exportierenbedienfeld in Substance 3D Sampler verwenden, um Materials als Dateien zu exportieren oder direkt an andere Anwendungen zu senden.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Export panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Exportbedienfeld
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 3%

---


# Exportbedienfeld

Im <b>Exportierenbedienfeld</b> können Sie Ihre Assets als allgemeine Dateien exportieren oder Assets direkt an andere Anwendungen senden.

## Senden an...

Mit den Optionen Senden an... können Sie Ihr Element direkt an andere auf Ihrem System installierte Anwendungen senden. Dies ist in der Regel viel schneller als der Import und Export von Assets.

Derzeit unterstützt Sampler das Senden an:

* **Substance 3D Painter**: Importieren Sie Materialien und Umgebungen, die Sie beim Texturieren Ihrer Elemente verwenden können.
* **Substance 3D Stager**: importiert Umgebungslichter, um die Stimmung Ihrer Szene zu ändern. Nur verfügbar mit Umgebungslichtern, für Materialien deaktiviert.

Materialien werden immer als SBSAR gesendet, Umgebungen als EXR.

## Exportieren

Klicken Sie auf **Exportieren als...** zum Exportieren des Assets, an dem Sie gerade arbeiten. Wählen Sie links, ob die allgemeinen oder die Material-Einstellungen geändert werden sollen.

### Allgemeine Einstellungen

Wenn die Option &quot;Allgemeine Einstellungen&quot; aktiviert ist, können Sie den Namen des Materials und den Speicherort ändern. Sie können auch festlegen, ob ein Unterordner für das Material erstellt werden soll. Dies kann beim Exportieren in ein Bildformat nützlich sein, bei dem mehrere Dateien erstellt werden.

### Materialeinstellungen

Wenn die Material-Einstellungen ausgewählt sind, können Sie verschiedene Parameter ändern, um zu steuern, wie das Material exportiert wird:

| Einstellung | Beschreibung |
| --- | --- |
| Format | Wählen Sie aus, ob der Export als SBS, SBSAR oder als Sammlung von Bildern in einem bestimmten Bildformat erfolgen soll |
| Voreinstellung | Wählen Sie eine Vorgabe aus, um den Export für eine bestimmte Anwendung automatisch zu organisieren. [Weitere Informationen zu Vorgaben finden Sie hier](../../getting-started/export/default-presets/default-presets.md). Vorgaben sind nur verfügbar, wenn ein Bildformat ausgewählt ist. |
| Komprimierung | Wählen Sie aus, ob bei der Komprimierung die Geschwindigkeit oder Effizienz <br> Priorität hat. <ul> <li> **Auto**: Erlaube Sampler die Auswahl. <li> **Beste**: Maximiere die Komprimierungseffizienz für kleinere Dateien. <li> **Keine**: Keine Komprimierung bedeutet, dass die exportierten Dateien schneller geöffnet und geschlossen werden, aber die Dateien größer sind. </ul> |
| Auflösung | Ändern Sie die Auflösung Ihres Exports. Diese Option wird unterschiedlich angezeigt, je nachdem, welches Format <br> ausgewählt ist. <ul> <li> **SBSAR/SBS**: Wählen Sie eine Standardbreite und ein Height für das Material aus. Diese können später aktualisiert werden. <li> **Bildformat**: Wählen Sie zwischen **Ebenenausgabe**, die jede Map in der vom Ebenenstapel definierten Größe exportiert, oder **Alle überschreiben**, mit der Sie eine Breite und ein Height für den Export angeben können. |
| Materialmodell | Wählen Sie aus, ob der Export als Adobe-Standardmaterial oder als OpenPBR-Material erfolgen soll. Welche Option Sie auswählen, sollte davon abhängen, welche anderen Anwendungen Sie in Ihrer Pipeline verwenden. Je nach Materialmodell werden verschiedene Kanäle verfügbar sein. |
| Kanäle | Legen Sie fest, welche Kanäle als Teil des Elements exportiert werden sollen. |

>[!NOTE]
>
> Weitere Informationen zu den Optionen des Exportdialogs und andere Informationen wie Dateiformate finden Sie im [Exportartikel](../../getting-started/export/export.md) und seinem [Unterartikel im Exportfenster](../../getting-started/export/export-window/export-window.md).

Wenn Sie mit den Exporteinstellungen zufrieden sind, klicken Sie auf **Exportieren**. Ihr Export wird in der Exportwarteschlange angezeigt, die eine Liste der letzten Exporte anzeigt. Klicken Sie auf das Ordnersymbol bei einem beliebigen Export, um den Dateispeicherort dieses Exports zu öffnen.
