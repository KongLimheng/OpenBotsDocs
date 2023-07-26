<!--TITLE: Stop Process Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Process group. -->
[Go To Automation Commands Overview](/automation-commands)


# Stop Process Command


## What does this command do?
This command stops a program or process.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Display Property Option|Select a value from the list of available display properties.|||
|Process Name|Provide a valid process name.|"notepad" \|\| "excel" \|\| "calculatorapp" \|\| vAppName||
|Process|Provide a Process variable containing the program to close/kill.|vProcess||
|Stop Option|Indicate whether the program should be closed or killed.||*Close* will close any open process windows while *Kill* will close all processes, including background ones.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: StopProcessCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Process
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
