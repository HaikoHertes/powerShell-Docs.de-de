# <a name="new-temporaryfile"></a>New-TemporaryFile
Mitunter müssen Sie in Ihren Skripts eine temporäre Datei erstellen. Hierfür dient das Cmdlet **New-TemporaryFile**:

PS C:\\&gt; $tempFile = New-TemporaryFile

PS C:\\&gt; $tempFile.FullName

C:\\Users\\slee\\AppData\\Local\\Temp\\tmp375.tmp
