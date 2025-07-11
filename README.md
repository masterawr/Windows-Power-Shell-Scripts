If you can't run the script the conventional way, save the script as a text file and input this in the command line:

Get-Content "C:\Folder Where txt file is in\awake.txt" | Out-String | Invoke-Expression
