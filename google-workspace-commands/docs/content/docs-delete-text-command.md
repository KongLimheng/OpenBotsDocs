<!--TITLE: Docs Delete Text Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Docs\Content group. -->
[Go To Automation Commands Overview](/automation-commands)


# Docs Delete Text Command


## What does this command do?
This command deletes text from a Google Document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Docs Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyDocsInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Range|Enter the start and end indexes of the text to remove from the document.|"1" \|\| "1:10" \|\| "1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DocsDeleteTextCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Docs.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
