<!--TITLE: Move/Copy Folder Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Folder group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move/Copy Folder Command


## What does this command do?
This command moves/copies a folder to a specified location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Folder Operation|Specify whether you intend to move or copy the folder.||Moving will remove the folder from the original path while Copying will not.|
|Source Folder Path|Enter or select the path to the original folder.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Output Folder Path|Enter or select the destination folder path.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Create Output Folder|Specify whether the destination directory should be created if it does not already exist.|||
|Delete Existing Folder|Specify whether the folder should be deleted first if it already exists in the destination directory.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MoveCopyFolderCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Folder
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
