<!--TITLE: Run Task Command -->
<!-- SUBTITLE: a command in the Core Commands\Task group. -->
[Go To Automation Commands Overview](/automation-commands)


# Run Task Command


## What does this command do?
This command executes a Task.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Task File Path|Enter or select a valid path to the Task file.|@"C:\temp\myFile.obscript" \|\| ProjectPath + @"\myFile.obscript" \|\| vFilePath||
|Assign Arguments|Select to assign arguments to the Task.||If selected, arguments will be automatically generated from the Task's *Argument Manager*.|
|Task Arguments (Optional)|Enter an ArgumentValue for each input argument.|"test" \|\| vMyVar \|\| new List<string>() { "Hello", "World" }|For inputs, set ArgumentDirection to *In*. For outputs, set ArgumentDirection to *Out*. Failure to assign an ArgumentDirection value will result in an error.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RunTaskCommand
Parent Namespace: OpenBots.Commands.Core.Task
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
