<!--TITLE: Remove Dictionary KeyValuePair Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\Dictionary\KeyValuePair group. -->
[Go To Automation Commands Overview](/automation-commands)


# Remove Dictionary KeyValuePair Command


## What does this command do?
This command removes a KeyValuePair from an existing Dictionary variable at a specified key.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Dictionary|Provide a Dictionary variable.|vDictionary \|\| new Dictionary<string, int>() {{ "Hello", 1 }}|Any type of variable other than Dictionary will cause error.|
|Key|Enter key where the KeyValuePair will be removed|"Hello" \|\| 1 \|\| vKey|Providing a non existing key will produce an exception.|
|Output Dictionary Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RemoveDictionaryKeyValuePairCommand
Parent Namespace: OpenBots.Commands.DataManipulation.Dictionary.KeyValuePair
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
