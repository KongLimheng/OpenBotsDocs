<!--TITLE: Stopwatch Command -->
<!-- SUBTITLE: a command in the Core Commands\Engine group. -->
[Go To Automation Commands Overview](/automation-commands)


# Stopwatch Command


## What does this command do?
This command measures time elapsed during the execution of the process.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Stopwatch Instance Name|Enter a unique name that will represent the application instance.|MyStopwatchInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Stopwatch Action|Select the appropriate stopwatch action.|||
|String Format (Optional)|Specify a TimeSpan string format if required.|"c" \|\| "hh\\:mm\\:ss" \|\| vFormat|This input is optional.|
|Output Elapsed Time Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: StopwatchCommand
Parent Namespace: OpenBots.Commands.Core.Engine
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
