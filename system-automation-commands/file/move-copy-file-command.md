<!--TITLE: Move/Copy File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\File group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move/Copy File Command


## What does this command do?
This command moves/copies a file to a specified destination.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|File Operation|Specify whether you intend to move the file or copy the file.||Moving will remove the file from the original path while Copying will not.|
|File Path|Enter or select the path to the file.|@"C:\temp\myFile.txt" \|\| ProjectPath + @"\myFile.txt" \|\| vFilePath||
|Output Folder Path|Enter or select the new (destination) path to the file.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Create Folder|Specify whether the directory should be created if it does not already exist.|||
|Overwrite File|Specify whether the file should be overwritten if it already exists.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MoveCopyFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.File
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
