<!--TITLE: Create Folder Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Folder group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Folder Command


## What does this command do?
This command creates a folder in a specified location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|New Folder Name|Enter the name of the new folder.|"OpenBots Folder" \|\| vFolderName||
|Output Folder Path|Enter or select the path to the directory to create the folder in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Delete Existing Folder|Specify whether the folder should be deleted first if it already exists.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateFolderCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Folder
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
