<!--TITLE: PowerPoint Create Application Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\PowerPoint group. -->
[Go To Automation Commands Overview](/automation-commands)


# PowerPoint Create Application Command


## What does this command do?
This command creates a PowerPoint application instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PowerPoint Instance Name|Enter a unique name that will represent the application instance.|MyPowerPointInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|New/Open Presentation|Indicate whether to create a new Presentation or to open an existing Presentation.|||
|Presentation File Path|Enter or select the path to the Presentation file.|@"C:\temp\myFile.ppt" \|\| ProjectPath + @"\myFile.pptx" \|\| vFilePath|This input should only be used for opening existing Presentation.|
|Read-Only Behavior Option|Select behavior when opening an instance of a read-only Presentation.|||
|Visible|Indicate whether the PowerPoint automation should be visible or not.|||
|Close All Existing PowerPoint Instances|Indicate whether to close any existing PowerPoint instances before executing PowerPoint Automation.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: PowerPointCreateApplicationCommand
Parent Namespace: OpenBots.Commands.Microsoft.PowerPoint
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
