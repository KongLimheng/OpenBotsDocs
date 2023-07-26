<!--TITLE: Extract Files Command -->
<!-- SUBTITLE: a command in the System Automation Commands\File group. -->
[Go To Automation Commands Overview](/automation-commands)


# Extract Files Command


## What does this command do?
This command extracts file(s) from a Zip file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Compressed File Path|Enter or select the Path to the source zip file.|@"C:\temp\myFile.zip" \|\| ProjectPath + @"\myFile.zip" \|\| vFilePath||
|Password (Optional)|Define the password to use if required to extract files.|vPassword|Password input must be a SecureString variable.|
|Output Folder Path|Enter or select the Folder Path to move extracted file(s) to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Output Extracted File Path List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExtractFilesCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.File
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
