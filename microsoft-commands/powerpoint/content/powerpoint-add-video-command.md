<!--TITLE: PowerPoint Add Video Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\PowerPoint\Content group. -->
[Go To Automation Commands Overview](/automation-commands)


# PowerPoint Add Video Command


## What does this command do?
This command adds a Video to slide.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PowerPoint Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyPowerPointInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Slide Location|Indicate the position of the slide where the Video will be added.|||
|Slide Index|Enter the index of the slide where the Video will be added.|2 \|\| vSlideIndex||
|Shape Name (Placeholder)|Enter the name of the placeholder shape where the Video will be inserted.|"Hello World" \|\| vShapeName|Search for 'selection pane' to view all existing shapes.|
|Video File Path|Enter the file path to the video that will be loaded.|@"C:\temp\myFile.avi" \|\| ProjectPath + @"\myFile.avi" \|\| vFilePath||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: PowerPointAddVideoCommand
Parent Namespace: OpenBots.Commands.Microsoft.PowerPoint.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
