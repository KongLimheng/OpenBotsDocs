<!--TITLE: Get Work Item Command -->
<!-- SUBTITLE: a command in the Platform Commands\Business Center\Work Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Work Item Command


## What does this command do?
This command gets a Work Item from an existing Work Queue in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Work Item Key|Enter the key of the existing Work Item.|"TSK-17" \|\| "APR-17" \|\| vWorkItemKey||
|Save Attachments|Specify whether to save the Work Item attachments to a local directory.|||
|Output Attachment Directory|Enter or select the path to the directory to store the attachments in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Output Work Item Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetWorkItemCommand
Parent Namespace: OpenBots.Commands.Platform.BusinessCenter.WorkItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
