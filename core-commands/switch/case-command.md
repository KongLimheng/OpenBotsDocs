<!--TITLE: Case Command -->
<!-- SUBTITLE: a command in the Core Commands\Switch group. -->
[Go To Automation Commands Overview](/automation-commands)


# Case Command


## What does this command do?
This command defines a case block whose commands will execute if the value specified in the case is equal to that of the preceding Switch Command.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Case|This block will be executed if the specified case value matches the value in the Switch Command.|1 \|\| "hello"||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CaseCommand
Parent Namespace: OpenBots.Commands.Core.Switch
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
