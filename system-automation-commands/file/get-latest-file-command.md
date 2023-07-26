<!--TITLE: Get Latest File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\File group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Latest File Command


## What does this command do?
This command returns the path of the most recently created or modified file from a specified location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Source Folder Path|Enter or select the path to the folder.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|File Sorting Option|Select a criteria to search for the file from the list of available options.|||
|Output File Path Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetLatestFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.File
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
