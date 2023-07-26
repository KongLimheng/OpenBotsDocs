<!--TITLE: String Contains Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\Text group. -->
[Go To Automation Commands Overview](/automation-commands)


# String Contains Command


## What does this command do?
This command checks if a string contains a specified substring and returns the result.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Full Text|Provide a variable or text value.|"Hello World" \|\| vFullText|Providing data of a type other than a 'String' will result in an error.|
|Comparison Text|Provide a variable or text value.|"Hello" \|\| vComparisonText|Providing data of a type other than a 'String' will result in an error.|
|Output Bool Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: StringContainsCommand
Parent Namespace: OpenBots.Commands.DataManipulation.Text
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
