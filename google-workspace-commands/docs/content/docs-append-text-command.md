<!--TITLE: Docs Append Text Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Docs\Content group. -->
[Go To Automation Commands Overview](/automation-commands)


# Docs Append Text Command


## What does this command do?
This command appends text to a Google Document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Docs Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyDocsInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Text|Enter the text to append to the Document.|"Hello World" \|\| vText||
|Font Name|Select or provide a valid font name.|||
|Font Size|Select or provide a valid font size.|||
|Bold|Specify whether the text font should be bold.|||
|Italic|Specify whether the text font should be italic.|||
|Underline|Specify whether the text font should be underlined.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DocsAppendTextCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Docs.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
