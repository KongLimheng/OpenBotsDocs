<!--TITLE: Date Calculation Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DateTime group. -->
[Go To Automation Commands Overview](/automation-commands)


# Date Calculation Command


## What does this command do?
This command performs a specific operation on a date and saves the result in a variable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Date|Determine the text or variable that contains the date.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now||
|Calculation Method|Select the date operation.||The selected operation will be applied to the input date value and result will be stored in the output variable.|
|Increment Value|Specify how many units to increment by.|15 \|\| vIncrement|You can use negative numbers which will do the opposite, ex. Subtract Days and an increment of -5 will Add Days.|
|Date Format (Optional)|Specify the output date format.|"MM/dd/yy hh:mm:ss" \|\| "MM/dd/yyyy" \|\| vDateFormat|You can specify either a valid DateTime, Date or Time Format; an invalid format will result in an error.|
|Output Date Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DateCalculationCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DateTime
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
