<!--TITLE: For Each Command -->
<!-- SUBTITLE: a command in the Core Commands\Loop group. -->
[Go To Automation Commands Overview](/automation-commands)


# For Each Command


## What does this command do?
This command iterates over a collection to let user perform actions on the collection items.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input Collection|Provide a collection variable.|vMyList \|\| vMyDictionary.ToList() \|\| vMyDataTable.Rows \|\| new List<int>() { 1, 2, 3 }||
|Output Collection Item Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: BeginForEachCommand
Parent Namespace: OpenBots.Commands.Core.Loop
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
