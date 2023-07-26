<!--TITLE: Slides Add Text Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Slides\Content group. -->
[Go To Automation Commands Overview](/automation-commands)


# Slides Add Text Command


## What does this command do?
This command adds text to a slide.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Slides Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyDocsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Shape Id|Enter the Id of the Shape to set text to.|_A1 \|\| vShapeId||
|Text to set|Enter the text you want to set.|"Hello World" \|\| vTextToSet||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SlidesAddTextCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Slides.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
