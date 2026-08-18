---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/fill.html"
breadcrumb-title: ''
description: Verwenden Sie den Füllfilter in Substance 3D Sampler, um Texturbereiche mit Volltonfarben oder Mustern für Materialerstellungs-Workflows zu füllen.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Fill
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Fläche
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '741'
ht-degree: 4%

---


# Fläche

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/Fill_Icon_1.png)

**In:** Korrekturen

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Beschreibung

Mit dem **Füllfilter** können Sie die Werte bestimmter Kanäle auf der Grundlage eines ausgewählten Werts ersetzen oder anpassen.
Ab Sampler 6.0 passt der Füllfilter seine Parameter basierend auf dem Kanaltyp an, auf den er angewendet wird. Dadurch wird sichergestellt, dass die verfügbaren Steuerelemente immer mit der physischen Bedeutung und dem Datentyp des ausgewählten Kanals übereinstimmen und dass der Filter auf jede Karte angewendet werden kann, auch über benutzerdefinierte Workflows.

In den folgenden Bildern wurde der Grundfarbkanal ersetzt.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/fillnobc.png.img.png){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/fillbc.png){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parameter

<b>Angewendet auf...</b>

Die Dropdown-Liste Angewendet auf ... bestimmt, auf welchen Kanal sich der Füllfilter auswirkt.
**Nur Kanäle, die derzeit in den Kanaleinstellungen des Materials aktiviert sind, werden in dieser Liste angezeigt.** Wenn der Kanal, den Sie ausfüllen möchten, nicht verfügbar ist:

* Öffnen Sie das Bedienfeld &quot;Kanaleinstellungen&quot; (ganz unten in der linken Navigationsleiste).
* Auf &quot;Liste bearbeiten&quot; klicken
* Den gewünschten Kanal aktivieren.
* Erneutes Anwenden oder Aktualisieren des Füllfilters

Nach der Aktivierung wird der Kanal in der Dropdown-Liste Angewendet auf ... verfügbar.

<b>Basisparameter</b>

Die Parameter für den Füllfilter &quot;**&quot; ändern sich dynamisch in Abhängigkeit vom Typ des Kanals &quot;**&quot;, der unter &quot;Angewendet auf&quot; ausgewählt ist.... Es gibt vier Parametersätze, die jeweils einem bestimmten Typ von Karte entsprechen.

### Farbmapparameter

Wird verwendet, wenn der Füllfilter auf Farbkanäle angewendet wird.

#### Beispielkanäle:

* Grundfarbe
* Farbe der Schicht
* Untergrundfarbe...

#### Verfügbare Parameter

* Farbe
Wählt die RGB-Farbe aus, die zum Füllen des Kanals verwendet wird.
* Benutzerdefinierter Wert
Wechseln Sie zum Öffnen der benutzerdefinierten Karte. Wählen Sie ein Bild aus, mit dem der ausgewählte Kanal ersetzt werden soll, oder malen Sie direkt in der **2D-Ansicht**.
* Zufällige Verteilung
Ändert die bei aktivierten prozeduralen Varianten verwendete Randomisierung.
* Überblendmodus
Legt fest, wie sich die Füllung mit den darunter liegenden Ebenen vermischt (z. B.: Kopieren, Hinzufügen, Multiplizieren).
* Deckkraft
Passen Sie die Deckkraft der neuen Kanalinformationen im Verhältnis zu den vorhandenen Kanalinformationen an. Mit anderen Worten, dadurch wird die Deckkraft der Maske gesteuert, die zum Anwenden der neuen Kanalfüllung verwendet wird.

Dieser Modus wird in der Regel verwendet, um Farbinformationen zu initialisieren oder zu überschreiben.

### Graustufen-Map-Parameter

Wird verwendet, wenn der Füllfilter auf skalare Graustufenkanäle angewendet wird.

#### Beispielkanäle:

* Glanzlichtrauheit
* Basis-Metallik
* Deckkraft
* Height...

#### Verfügbare Parameter

* Value
Legt einen einzelnen Graustufenwert für den Kanal fest.
* Zufällige Verteilung
Ändert die bei aktivierten prozeduralen Varianten verwendete Randomisierung.
* Benutzerdefinierter Wert
Wechseln Sie zum Öffnen der benutzerdefinierten Karte. Wählen Sie ein Bild aus, mit dem der ausgewählte Kanal ersetzt werden soll, oder malen Sie direkt in der **2D-Ansicht**.
* Überblendmodus
Kopieren, Hinzufügen (linear abwedeln), Subtrahieren, Multiplizieren, Sub hinzufügen, Max (aufhellen), Min (abdunkeln), Umschalten, Unterteilen, Überlagerung, Bildschirm, Weiches Licht.
Wählen Sie den Mischmodus aus, um die benutzerdefinierten Eingaben mit den darunter liegenden Ebenen zu mischen.
* Deckkraft
Passen Sie die Deckkraft der neuen Kanalinformationen im Verhältnis zu den vorhandenen Kanalinformationen an. Mit anderen Worten, dadurch wird die Deckkraft der Maske gesteuert, die zum Anwenden der neuen Kanalfüllung verwendet wird.

Dieser Modus eignet sich zum Definieren einheitlicher physikalischer Eigenschaften, z. B. für einen konstanten Raueit- oder Deckkraftwert.

#### Normale Map-Parameter

Wird verwendet, wenn der Füllfilter auf **Normal** Kanäle angewendet wird.

##### Beispielkanäle:

* Normal
* Schicht „Normal“

##### Verfügbare Parameter

* Zufällige Verteilung
Ändert die bei aktivierten prozeduralen Varianten verwendete Randomisierung.
* Benutzerdefinierter Wert
Wechseln Sie zum Öffnen der benutzerdefinierten Karte. Wählen Sie ein Bild aus, mit dem der ausgewählte Kanal ersetzt werden soll, oder malen Sie direkt in der **2D-Ansicht**.
* Deckkraft
Passen Sie die Deckkraft der neuen Kanalinformationen im Verhältnis zu den vorhandenen Kanalinformationen an. Mit anderen Worten, dadurch wird die Deckkraft der Maske gesteuert, die zum Anwenden der neuen Kanalfüllung verwendet wird.

Dieser Modus wird hauptsächlich verwendet, um normale Informationen zurückzusetzen oder zu neutralisieren oder um eine saubere Grundlinie festzulegen, bevor normale Details hinzugefügt werden.

### Einheitliche Werteparameter

Wird für Kanäle verwendet, die auf einem einzelnen einheitlichen physischen Wert anstatt auf einer Texturmap basieren.

#### Beispielkanäle

* Specular IOR.

#### Verfügbare Parameter

* Zufällige Verteilung
Ändert die bei aktivierten prozeduralen Varianten verwendete Randomisierung.
* Value
Definiert den konstanten Wert, der auf den Kanal angewendet wird.
* Füllmethode
Zwischen Normal und Multiplizieren

Dieser Modus ist besonders nützlich, wenn Sie mit erweiterten Materialverhalten arbeiten, die durch Vorlagen eingeführt wurden, wobei einige Eigenschaften durch Skalarwerte anstatt durch Maps gesteuert werden.

## Typische Anwendungsfälle

Der Filter &quot;Füllung&quot; wird häufig für folgende Zwecke verwendet:

* Kanäle beim Erstellen eines neuen Materials initialisieren
* Vorhandene Kanalwerte überschreiben
* Festlegen einheitlicher physikalischer Eigenschaften (z. B. feste Raueit oder Metallität)
* Neutralisieren Sie Kanäle wie &quot;Normal&quot;, bevor Sie Details neu erstellen
* Schnelle Anpassung erweiterter Eigenschaften wie Fuzz, Lichtdurchlässigkeit oder Beschichtungswerte

Da sich der Filter &quot;Füllung&quot; automatisch an den ausgewählten Kanal anpasst, bietet er einen konsistenten und vorhersehbaren Workflow für alle Materialtypen.
