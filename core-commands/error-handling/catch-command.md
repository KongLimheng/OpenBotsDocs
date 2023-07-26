<!--TITLE: Catch Command -->
<!-- SUBTITLE: a command in the Core Commands\Error Handling group. -->
[Go To Automation Commands Overview](/automation-commands)


# Catch Command


## What does this command do?
This command defines a catch block whose commands will execute if an exception is thrown from the associated try.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Exception Option|Select whether to create the exception using C# or with the exception builder|||
|Exception Type|Provide the appropriate exception type.|typeof(System.Exception) \|\| typeof(OpenBots.Core.Model.ApplicationModel.OBBusinessException) \|\| vType||
|Exception Type|Select the appropriate exception type.||This command will be executed if the type of the exception that occurred in the try block matches the selected exception type.|
|Output Exception Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CatchCommand
Parent Namespace: OpenBots.Commands.Core.ErrorHandling
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
