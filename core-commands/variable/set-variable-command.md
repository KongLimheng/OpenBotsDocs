<!--TITLE: Set Variable Command -->
<!-- SUBTITLE: a command in the Core Commands\Variable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Set Variable Command


## What does this command do?
This command assigns a value to a variable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input Value|Enter the input value for the variable.|"Hello" \|\| vNum \|\| vNum + 1|You can use variables in input if you encase them within braces {vValue}. You can also perform basic math operations.|
|Output Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SetVariableCommand
Parent Namespace: OpenBots.Commands.Core.Variable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
