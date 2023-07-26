<!--TITLE: Slides Add Slide Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Slides\Slide group. -->
[Go To Automation Commands Overview](/automation-commands)


# Slides Add Slide Command


## What does this command do?
This command adds a Google Slide.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Slides Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyDocsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Slide Location|Indicate the position of the slide to add.|||
|Slide Index|Enter the index of the slide to add.|0 \|\| vSlideIndex||
|Slide Layout|Select the layout of the slide.|||
|Output ObjectId Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SlidesAddSlideCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Slides.Slide
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
