---
description: 
manager: carmonm
ms.topic: article
author: jpjofre
ms.prod: powershell
keywords: powershell,cmdlet
ms.date: 2016-12-12
title: Erstellen einer PowerShell-Registerkarte in Windows PowerShell ISE
ms.technology: powershell
ms.assetid: c10c18c7-9ece-4fd0-83dc-a19c53d4fd83
ms.openlocfilehash: 1c57e557e2fefbdf67b6a3c71721cd2a916a0ec5
ms.sourcegitcommit: 8acbf9827ad8f4ef9753f826ecaff58495ca51b0
translationtype: HT
---
# <a name="how-to-create-a-powershell-tab-in-windows-powershell-ise"></a>Erstellen einer PowerShell-Registerkarte in Windows PowerShell ISE
Registerkarten in Windows PowerShell® Integrated Scripting Environment (ISE) ermöglichen Ihnen, mehrere Ausführungsumgebungen innerhalb derselben Anwendung gleichzeitig zu erstellen und zu verwenden. Jede PowerShell-Registerkarte entspricht einer separaten Ausführungsumgebung bzw. Sitzung.

> [!NOTE]
> Variablen, Funktionen und Aliase, die Sie auf einer Registerkarte erstellen, werden nicht auf andere übertragen. Sie sind in verschiedenen Windows PowerShell-Sitzungen enthalten.

Gehen Sie folgendermaßen vor, um eine Registerkarte in Windows PowerShell zu öffnen oder zu schließen. Legen Sie zum Umbenennen einer Registerkarte die Eigenschaft [DisplayName](The-PowerShellTab-Object.md#Displayname) im Skriptobjekt für die Windows PowerShell-Registerkarte fest.

## <a name="to-create-and-use-a-new-powershell-tab"></a>So erstellen und verwenden Sie eine neue PowerShell-Registerkarte
Klicken Sie im Menü **Datei** auf **Neue PowerShell-Registerkarte**. Die neue PowerShell-Registerkarte wird immer als aktives Fenster geöffnet. PowerShell-Registerkarten sind in der Reihenfolge ihres Öffnens aufsteigend nummeriert. Jede Registerkarte ist einem eigenen Windows PowerShell-Konsolenfenster zugeordnet. Sie können bis zu 32 PowerShell-Registerkarten mit jeweils eigener Sitzung gleichzeitig geöffnet haben (bei Windows PowerShell ISE 2.0 maximal 8.)

Beachten Sie, dass durch Klicken auf die Symbole **Neu** oder **Öffnen** auf der Symbolleiste keine neue Registerkarte mit einer separaten Sitzung erstellt wird.  Über diese Schaltflächen wird stattdessen eine neue oder vorhandene Skriptdatei auf der derzeit in einer Sitzung aktiven Registerkarte geöffnet. Auf jeder Registerkarte und in jeder Sitzung können mehrere Skriptdateien geöffnet sein. Die Skriptregisterkarten für eine Sitzung werden nur unter den Sitzungsregisterkarten angezeigt, wenn die zugehörige Sitzung aktiv ist.

Um eine PowerShell-Registerkarte zu aktivieren, klicken Sie auf die Registerkarte. Zum Auswählen aller PowerShell-Registerkarten, die im Menü **Ansicht** geöffnet sind, klicken Sie auf die PowerShell-Registerkarte, die Sie verwenden möchten.

## <a name="to-create-and-use-a-new-remote-powershell-tab"></a>So erstellen und verwenden Sie eine Remote-PowerShell-Registerkarte
Klicken Sie im Menü **Datei** auf **Neue Remote-PowerShell-Registerkarte**, um eine Sitzung auf einem Remotecomputer zu starten. Ein Dialogfeld wird angezeigt und fordert Sie zur Eingabe von Details auf, die zum Herstellen der Remoteverbindung erforderlich sind. Die Remoteregisterkarte funktioniert wie eine lokale PowerShell-Registerkarte, doch die Befehle und Skripts werden auf dem Remotecomputer ausgeführt.

## <a name="to-close-a-powershell-tab"></a>So schließen Sie eine PowerShell-Registerkarte
Zum Schließen einer Registerkarte können Sie eine der folgenden Methoden verwenden:

-   Klicken Sie auf die Registerkarte, die Sie schließen möchten.

-   Klicken Sie im Menü **Datei** auf **PowerShell-Registerkarte schließen**, oder klicken Sie auf einer aktiven Registerkarte auf die Schaltfläche „Schließen“ (**X**), um sie zu schließen.

Wenn Sie auf der PowerShell-Registerkarte nicht gespeicherte Dateien geöffnet sind, werden Sie aufgefordert, sie zu speichern oder zu verwerfen. Weitere Informationen zum Speichern eines Skripts finden Sie unter [Speichern eines Skripts](https://technet.microsoft.com/library/162f594d-efd3-4234-9960-45e56e6eadc8).

## <a name="see-also"></a>Weitere Informationen
- [Verwenden der Windows PowerShell ISE](Using-the-Windows-PowerShell-ISE.md)
- [Verwenden des Konsolenbereichs in der Windows PowerShell ISE](How-to-Use-the-Console-Pane-in-the-Windows-PowerShell-ISE.md)

