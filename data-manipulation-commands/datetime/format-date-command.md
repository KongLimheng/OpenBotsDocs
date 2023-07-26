<!--TITLE: Format Date Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DateTime group. -->
[Go To Automation Commands Overview](/automation-commands)


# Format Date Command


## What does this command do?
This command converts a DateTime into a string of a specified format.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input Date|Determine the date that requires formatting.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now||
|Date String Format|Specify the output data format.|"G" \|\| "MM/dd/yyyy hh:mm:ss" \|\| vDateFormat|You should specify a valid input data format; invalid formats will result in an error.|
|Output Text Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: FormatDateCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DateTime
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
