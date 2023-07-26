<!--TITLE: Calculate Number Asset Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Asset group. -->
[Go To Automation Commands Overview](/automation-commands)


# Calculate Number Asset Command


## What does this command do?
This command increments, decrements, adds, or subtracts an Asset in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Number Asset Name|Enter the name of the Asset.|"Name" \|\| vCredentialName|This command will throw an exception if an asset of the wrong type is used.|
|Asset Action Type|Specify the type of calculation of the Asset.|||
|Asset Action Value|Enter the new value you would like to add or subtract from the Asset.|5 \|\| vAssetValue||
|Output Asset Value Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CalculateNumberAssetCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Asset
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
