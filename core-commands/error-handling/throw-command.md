<!--TITLE: Throw Command -->
<!-- SUBTITLE: a command in the Core Commands\Error Handling group. -->
[Go To Automation Commands Overview](/automation-commands)


# Throw Command


## What does this command do?
This command throws an exception during script execution.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Exception Option|Select whether to create the exception using C# or with the exception builder|||
|Exception|Provide an exception to throw.|new System.Exception("Error!") \|\| new OpenBots.Core.Model.ApplicationModel.OBBusinessException("Error!") \|\| vException||
|Exception Type|Select the appropriate exception type to throw.|||
|Exception Message|Enter a custom exception message.|"Error!" \|\| vExceptionMessage|The selected exception with this custom message will be thrown.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ThrowCommand
Parent Namespace: OpenBots.Commands.Core.ErrorHandling
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
