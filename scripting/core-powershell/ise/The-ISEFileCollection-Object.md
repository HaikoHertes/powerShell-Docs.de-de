---
description: 
manager: carmonm
ms.topic: article
author: jpjofre
ms.prod: powershell
keywords: powershell,cmdlet
ms.date: 2016-12-12
title: Das ISEFileCollection-Objekt
ms.technology: powershell
ms.assetid: 0f86a427-ea38-4bce-85f8-06c98d30d508
ms.openlocfilehash: eb88b6256d1d053e4c5c28439d3a80552883204f
ms.sourcegitcommit: 8acbf9827ad8f4ef9753f826ecaff58495ca51b0
translationtype: HT
---
# <a name="the-isefilecollection-object"></a>Das ISEFileCollection-Objekt
  Das **ISEFileCollection**-Objekt ist eine Sammlung von **ISEFile**-Objekten. Ein Beispiel ist die $psISE.CurrentPowerShellTab.Files-Sammlung.

## <a name="methods"></a>Methoden

### <a name="add-fullpath-"></a>Add\( \[fullPath\] \)
  In Windows PowerShell ISE 2.0 und höher unterstützt. 

 Erstellt eine neue unbenannte Datei, gibt diese zurück und fügt sie der Sammlung hinzu. Die **IsUntitled**-Eigenschaft der neu erstellten Datei ist **$true**.

 **\[fullPath\]** – Optionale Zeichenfolge – der vollständig angegebene Pfad der Datei Eine Ausnahme wird erstellt, falls Sie den **fullPath**-Parameter und den relativen Pfad angeben oder falls Sie einen Dateinamen statt dem vollständigen Pfad verwenden.

```
# Adds a new untitled file to the collection of files in the current PowerShell tab.
$newFile = $psISE.CurrentPowerShellTab.Files.Add()

# Adds a file specified by its full path to the collection of files in the current PowerShell tab.
$psISE.CurrentPowerShellTab.Files.Add("$pshome\Examples\profile.ps1")

```

### <a name="remove-file-force-"></a>Remove\( File, \[Force\] \)
  In Windows PowerShell ISE 2.0 und höher unterstützt. 

 Entfernt eine angegebene Datei aus der aktuellen PowerShell-Registerkarte.

 **File** – Zeichenfolge – Die ISEFile-Datei, die Sie aus der Sammlung entfernen möchten Falls die Datei nicht gespeichert wurde, löst diese Methode eine Ausnahme aus. Verwenden Sie den Schalter **Force**, um das Entfernen einer ungespeicherten Datei zu erzwingen.

 **\[Force\]** – Optionaler boolescher Wert: Falls er auf **$true** festgelegt wird, erteilt er die Berechtigung dafür, die Datei zu entfernen, auch wenn sie nach der letzten Verwendung nicht gespeichert wurde. Der Standardwert ist **$false**.

```
# Removes the first opened file from the file collection associated with the current PowerShell tab.
# If the file has not yet been saved, then an exception is generated.
$firstfile = $psISE.CurrentPowerShellTab.Files[0]
$psISE.CurrentPowerShellTab.Files.Remove($firstfile)

# Removes the first opened file from the file collection associated with the current PowerShell tab, even if it has not been saved.
$firstfile = $psISE.CurrentPowerShellTab.Files[0]
$psISE.CurrentPowerShellTab.Files.Remove($firstfile, $true)
```

### <a name="setselectedfile-selectedfile-"></a>SetSelectedFile\( selectedFile \)
  In Windows PowerShell ISE 2.0 und höher unterstützt. 

 Wählt die Datei aus, die durch den **selectedFile**-Parameter angegeben wird.

 **selectedFile** – Microsoft.PowerShell.Host.ISE.ISEFile – Die ISEFile-Datei, die Sie auswählen möchten

```

# Selects the specified file.
$firstfile = $psISE.CurrentPowerShellTab.Files[0]
$psISE.CurrentPowerShellTab.Files.SetSelectedFile($firstfile)

```

## <a name="see-also"></a>Weitere Informationen
- [Das ISEFile-Objekt](The-ISEFile-Object.md) 
- [Das Windows PowerShell ISE-Skriptobjektmodell](The-Windows-PowerShell-ISE-Scripting-Object-Model.md) 
- [Referenz zum Windows PowerShell ISE-Objektmodell](Windows-PowerShell-ISE-Object-Model-Reference.md) 
- [Die ISE-Objektmodellhierarchie](The-ISE-Object-Model-Hierarchy.md)

  
