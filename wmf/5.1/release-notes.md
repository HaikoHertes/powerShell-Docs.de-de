---
title: "Anmerkungen zu dieser Version – WMF 5.1"
ms.date: 2017-01-20
keywords: PowerShell, DSC, WMF
description: 
ms.topic: article
author: keithb
manager: carmonm
ms.prod: powershell
ms.technology: WMF
ms.openlocfilehash: 48821f41b7a05860dc9f6a8916817f8e9ca28e6d
ms.sourcegitcommit: 9fe4d1ef90fd11267a00e955d80ed6d27c8d7d5a
translationtype: HT
---
# <a name="windows-management-framework-wmf-51-release-notes"></a>Windows Management Framework (WMF) 5.1 – Anmerkungen zu dieser Version #

WMF 5.1 umfasst PowerShell, WMI und WinRM sowie SIL-Komponenten (Softwareinventur und -lizenzierung), die mit Windows Server 2016 veröffentlicht wurden.
WMF 5.1 kann auf Windows 7, Windows 8.1, Windows Server 2008 R2, 2012 und 2012 R2 installiert werden und bietet gegenüber WMF 5.0 RTM eine Reihe von Vorteilen. Dazu zählen u. a.:

- Neue Cmdlets: lokale Benutzer und Gruppen; Get-ComputerInfo
- PowerShellGet-Verbesserungen wie z. B. die Durchsetzung von signierten Modulen und die Installation von JEA-Modulen
- Bei PackageManagement wurde Unterstützung für Container, CBS-Setup, EXE-basiertes Setup und CAB-Pakete hinzugefügt
- Debuggingverbesserungen für DSC und PowerShell-Klassen
- Sicherheitsverbesserungen wie u. a. die Durchsetzung von katalogsignierten Modulen vom Pullserver und bei Verwendung von PowerShellGet-Cmdlets
- Antworten auf verschiedene Benutzeranfragen und zu Problemen

**Wichtige Hinweise:**

- **Für WMF 5.1 ist .NET Framework 4.5.2 erforderlich**. Die Installation ist erfolgreich, wichtige Features können jedoch nicht ausgeführt werden, wenn .NET 4.5.2 nicht installiert ist. Anweisungen finden Sie im Thema [Installieren und Konfigurieren von WMF 5.1 (Preview)](https://msdn.microsoft.com/en-us/powershell/wmf/5.1/install-configure).
- WMF 5.1 Preview muss vor der Installation von WMF 5.1 RTM deinstalliert werden.
- WMF 5.1 kann direkt über WMF 5.0 oder WMF 4.0 installiert werden.
- Es ist __nicht erforderlich__, WMF 4.0 vor der Installation von WMF 5.1 unter Windows 7 und Windows Server 2008 R2 zu installieren. Dieses Problem der Preview-Version von WMF 5.1 wurde behoben.  


