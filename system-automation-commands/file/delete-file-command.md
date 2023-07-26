<!--TITLE: Delete File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\File group. -->
[Go To Automation Commands Overview](/automation-commands)


# Delete File Command


## What does this command do?
This command deletes a file from a specified destination.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|File Path|Enter or select the path to the file.|@"C:\temp\myFile.txt" \|\| ProjectPath + @"\myFile.txt" \|\| vFilePath||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DeleteFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.File
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
