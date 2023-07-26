<!--TITLE: Retry Command -->
<!-- SUBTITLE: a command in the Core Commands\Error Handling group. -->
[Go To Automation Commands Overview](/automation-commands)


# Retry Command


## What does this command do?
This command defines a retry block which will retry the contained commands as long as the condition is not met or an error is thrown.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Number of Retries|Enter or provide the number of retries.|3 \|\| vRetryCount||
|Retry Interval (Seconds)|Enter or provide the amount of time (in seconds) between each retry.|5 \|\| vRetryInterval||
|Condition Option|Select whether to create the condition using C# or with the condition builder|||
|Retry Condition|Enter the condition to evaluate in C#.|true \|\| vCount > 0 \|\| vCondition||
|Logic Type|Select the logic to use when evaluating multiple Ifs.|||
|Retry Condition|Add or edit multiple If conditions.||Items in the retry scope will be executed if the condition doesn't satisfy.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: BeginRetryCommand
Parent Namespace: OpenBots.Commands.Core.ErrorHandling
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
