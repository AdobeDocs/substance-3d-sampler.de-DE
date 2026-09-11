---
breadcrumb-title: ''
description: Lerne, wie du das Basismaterial in Sampler einsetzt - ein guter Ausgangspunkt für effiziente Videobearbeitung.
title: Als Bitmap verwenden
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 4%

---


# Basismaterial

Das **Basismaterial** ist eine grundlegende Materialebene, die Ihnen einen schnellen, flexiblen Ausgangspunkt beim Erstellen von Materialien in Sampler bietet. Es legt einen umfangreichen Parametersatz, der sich automatisch an das von Ihrem Material (OpenPBR oder ASM) verwendete **Materialmodell** anpasst, sodass Sie alles von einfachen Oberflächen bis hin zu komplexen, physikalisch reichhaltigen Materialien erstellen können.
Unabhängig davon, ob Sie mit einer Vorgabe beginnen oder ein neues Material erstellen, stellt das Basismaterial sicher, dass Sie immer mit einem **klaren, vorhersehbaren und bearbeitbaren Fundament beginnen**.

## Materialmodell-Bewusstsein (OpenPBR vs. ASM)

Das Basismaterial ist **Material-Model-fähig**.
Das bedeutet, dass sich die verfügbaren Eigenschaften und Standardwerte ändern, je nachdem, ob Ihr Material mit den folgenden Optionen erstellt wird:

* OpenPBR
* ASM (Adobe Standard Material)

Beide Versionen dienen zwar dem gleichen Zweck, aber sie legte **verschiedene Parametergruppen und Verhaltensweisen**, die dem zugrunde liegenden Materialmodell entsprechen:

### OpenPBR Basismaterial

Zu den Parametergruppen gehören:

* Basis
* Glanz
* Übertragung
* Volumen
* Mantel
* Fuzz
* Emission
* Dünnfilm
* Geometrie
* Verschiedenes

Diese Parameter entsprechen der vereinheitlichten, physikalisch basierten Darstellung von OpenPBR und wurden für die Interoperabilität im weiteren 3D-Ökosystem entwickelt.

### ASM-Basismaterial

Zu den Parametergruppen gehören:

* Oberfläche
* Absorption
* Streuung
* Lichtdurchlässigkeit
* Mantel
* Schimmern
* Emission
* Geometrie

Dieses Layout spiegelt das ASM-Schattierung-Modell wider und stellt die Kontinuität mit bestehenden ASM-basierten Workflows sicher.

>[!NOTE]
>
>Das Basismaterial passt sich immer dem Materialmodell des Materials an, auf das es angewendet wurde. Ein auf ein OpenPBR-Material angewendetes Basismaterial legt keine ASM-Parameter, und umgekehrt.

## Einheitliche Werte und benutzerdefinierte Karten

Für jeden freigelegte Parameter bietet das Basismaterial zwei Arbeitsweisen:

### Einheitliche Werte (Standard)

Standardmäßig verwenden Parameter einheitliche Werte (Schieberegler oder Farbwähler).
Auf diese Weise kannst du schnell den Gesamteindruck deines Materials definieren, ohne dass Texturen eingegeben werden müssen.

Einheitliche Werte sind ideal für:

* Aussperren von Materialien
* Erstellen sauberer, einfacher Oberflächen
* Visueller Ausgangspunkt

### Benutzerdefinierte Karten

Wenn Sie bereits über Zuordnungen von Texturen verfügen, können Sie **einen beliebigen einheitlichen Wert** überschreiben, indem Sie die **benutzerdefinierte Zuordnungseingabe** aktivieren.

* Umschalten der benutzerdefinierten Map-Option für den Parameter
* Eine bestehende Textur anschließen
* Die Karte ersetzt den einheitlichen Wert vollständig.

## Voreinstellungen

Das Basismaterial umfasst eine Gruppe von **Vorgaben**, die als Miniaturansichten oben im Eigenschaftenfenster angezeigt werden.
Vorgaben bieten:

* Vorkonfigurierte Basismaterial-Werte
* Schneller Einstieg in eine visuell relevante Umgebung
* Konsistente, lesbare Ausgangspunkte für gängige Oberflächentypen

Wenn Sie eine Vorgabe auswählen, wird das Material nicht gesperrt. Alle Parameter bleiben vollständig editierbar.

## &quot;Anwenden von Vorgabewerten&quot; beim Erstellen eines Materials

Wenn Sie ein neues Material erstellen, können Sie im Bedienfeld &quot;Neues Material erstellen&quot; die Vorgabewerte anwenden.
Was dies bewirkt

* Ersetzt die Standardwerte des Basismaterials durch die Werte, die durch die ausgewählte Miniaturansicht der Vorgabe dargestellt werden
* Zeigt Ihnen sofort einen visuellen Ausgangspunkt anstelle von neutralen Standardeinstellungen
* Hilft, den Effekt &quot;Leere Seite&quot; zu reduzieren, wenn ein neues Material beginnt

Nicht funktionierende Funktionen

* Es werden keine Werte Baking geführt oder eingefroren.
* Weitere Bearbeitungen werden nicht verhindert.
* Textur Maps werden nicht automatisch hinzugefügt.

Sie können sich das so vorstellen, als würden Sie auswählen, wo Sie anfangen, und nicht einschränken, wo Sie hingehen können.

## Kanalaktivierung: Ein wichtiger Schritt

Damit ein Kanalparameter einen sichtbaren Effekt hat, muss der entsprechende Basismaterial in den Kanaleinstellungen Ihres Materials aktiviert sein.

### Best Practice.

Überprüfen Sie vor dem Anpassen eines Parameters, ob sein Kanal aktiviert ist.
Nur die Kanäle aktivieren, die Sie benötigen, um Ihr Material sauber und effizient zu halten