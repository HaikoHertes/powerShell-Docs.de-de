---
description: 
manager: carmonm
ms.topic: article
author: jpjofre
ms.prod: powershell
keywords: powershell,cmdlet
ms.date: 2016-12-12
title: "Anhang 2 – Erstellen einer benutzerdefinierten PowerShell-Verknüpfung"
ms.technology: powershell
ms.assetid: 5d4fd421-5d43-4ec7-86fd-acfe887b066e
ms.openlocfilehash: 299c0721162621b72d032e0bb5603d535d341fb9
ms.sourcegitcommit: 8acbf9827ad8f4ef9753f826ecaff58495ca51b0
translationtype: HT
---
# <a name="appendix-2---creating-a-custom-powershell-shortcut"></a>Anhang 2: Erstellen einer benutzerdefinierten PowerShell-Verknüpfung
In der folgenden Vorgehensweise wird beschrieben, wie Sie eine Verknüpfung zu Windows PowerShell erstellen, in der mehrere praktische Optionen angepasst sind.

1.  Erstellen Sie eine Verknüpfung, die auf „Powershell.exe“ verweist.

2.  Klicken Sie mit der rechten Maustaste auf die Verknüpfung, und klicken Sie dann auf **Eigenschaften**.

3.  Klicken Sie auf die Registerkarte **Optionen**.

4.  Aktivieren Sie im Abschnitt **Bearbeitungsoptionen** das Kontrollkästchen **QuickEdit**.

    Diese Einstellung ermöglicht es Ihnen, Text im Windows PowerShell-Konsolenfenster durch Ziehen bei gedrückter linker Maustaste zu markieren sowie Text in die Zwischenablage zu kopieren, indem Sie die EINGABETASTE drücken oder mit der rechten Maustaste klicken.

5.  Aktivieren Sie im Abschnitt **Bearbeitungsoptionen** das Kontrollkästchen **Einfügemodus**. Diese Einstellung ermöglicht es Ihnen, Text aus der Zwischenablage automatisch durch Klicken mit der rechten Maustaste im Konsolenfenster einzufügen.

6.  Geben Sie im Abschnitt **Befehlsspeicher** direkt oder durch Auswählen eine Zahl zwischen 1 und 999 in das Feld **Puffergröße** ein. Hiermit wird die Anzahl von eingegebenen Befehlen festgelegt, die im Konsolenpuffer aufbewahrt werden.

7.  Aktivieren Sie im Abschnitt **Befehlsspeicher** das Kontrollkästchen **Alte Duplikate löschen**, damit wiederholte Befehle aus dem Konsolenpuffer entfernt werden.

8.  Klicken Sie auf die Registerkarte **Layout**.

9. Geben Sie im Abschnitt **Fensterpuffergröße** eine Zahl zwischen 1 und 9999 in das Feld **Höhe** ein. Diese Höhe entspricht der Anzahl von Ausgabezeilen, die gepuffert werden. Dies ist die maximale Anzahl von Zeilen, die für die Anzeige beibehalten werden, wenn Sie durch das Konsolenfenster scrollen. Ist diese Anzahl kleiner als der Wert für die Höhenangabe im Abschnitt **Fenstergröße**, wird die Fensterhöhe automatisch auf denselben Wert verringert.

10. Geben Sie im Abschnitt **Fenstergröße** eine Zahl zwischen 1 und 9999 für die Breite ein. Diese Zahl entspricht der Anzahl von Zeichen, die horizontal im Konsolenfenster angezeigt werden. Die Standardbreite beträgt 80, und die Ausgabeformatierung von Windows PowerShell ist für diese Breite konzipiert.

11. Wenn Sie die Konsole beim Öffnen an einer bestimmten Stelle auf dem Desktop platzieren möchten, deaktivieren Sie im Abschnitt **Fensterposition** das Kontrollkästchen **Automatisch positionieren**, und ändern Sie die Werte in den Feldern **Links** und **Oben** im Abschnitt **Fensterposition**.

12. Klicken Sie auf **OK**.

