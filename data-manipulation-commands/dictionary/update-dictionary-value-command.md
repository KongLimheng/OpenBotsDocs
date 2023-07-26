<!--TITLE: Update Dictionary Value Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\Dictionary group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Dictionary Value Command


## What does this command do?
This command updates the value in an existing Dictionary variable for a specified key.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Dictionary|Provide a Dictionary variable.|vDictionary \|\| new Dictionary<string, int>() {{ "Hello", 1 }}|Any type of variable other than Dictionary will cause error.|
|Key|Enter the Key where the value will be updated.|"Hello" \|\| 1 \|\| vKey|Providing a non existing key will produce an exception.|
|Value|Enter the value to write to the Dictionary.|"Hello" \|\| 1 \|\| vValue|Value can only be a String, DataTable, OBMailItem or IWebElement.|
|Output Dictionary Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateDictionaryValueCommand
Parent Namespace: OpenBots.Commands.DataManipulation.Dictionary
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
