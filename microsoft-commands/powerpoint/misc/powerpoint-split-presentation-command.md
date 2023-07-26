<!--TITLE: PowerPoint Split Presentation Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\PowerPoint\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# PowerPoint Split Presentation Command


## What does this command do?
This command splits a PowerPoint Presentation and places the selected slides in a new Presentation.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PowerPoint Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyPowerPointInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Starting Slide Index|Enter the starting index of the range of slides to split from the Presentation.|1 \|\| vStartIndex||
|Ending Slide Index|Enter the ending index of the range of slides to split from the Presentation.|2 \|\| vEndIndex||
|Output Folder Path|Enter or select the path of the folder to save the new Presentation to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|New Presentation File Name|Enter or select the name of the new Presentation file.|"myFile.ppt" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: PowerPointSplitPresentationCommand
Parent Namespace: OpenBots.Commands.Microsoft.PowerPoint.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
