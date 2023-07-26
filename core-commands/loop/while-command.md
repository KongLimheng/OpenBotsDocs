<!--TITLE: While Command -->
<!-- SUBTITLE: a command in the Core Commands\Loop group. -->
[Go To Automation Commands Overview](/automation-commands)


# While Command


## What does this command do?
This command evaluates a specified logical statement and executes the contained commands repeatedly (in loop) until that logical statement becomes false.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Condition Option|Select whether to create the condition using C# or with the condition builder|||
|While Condition|Enter the condition to evaluate in C#.|true \|\| vCount > 0 \|\| vCondition||
|While Condition|Select the necessary condition type.|||
|Additional Parameters|Supply or Select the required comparison parameters.|Param Value \|\| vParamValue||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: BeginWhileCommand
Parent Namespace: OpenBots.Commands.Core.Loop
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
