<!--TITLE: Parse JSON Array Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\JSON group. -->
[Go To Automation Commands Overview](/automation-commands)


# Parse JSON Array Command


## What does this command do?
This command parses a JSON Array into a List.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|JSON Array|Provide a variable or JSON array value.|@"['Small','Medium','Large']" \|\| vArrayVariable|Providing data of a type other than a 'JSON Array' will result in an error.|
|Output List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ParseJSONArrayCommand
Parent Namespace: OpenBots.Commands.DataManipulation.JSON
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
