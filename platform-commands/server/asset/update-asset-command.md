<!--TITLE: Update Asset Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Asset group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Asset Command


## What does this command do?
This command updates an Asset in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Asset Name|Enter the name of the Asset.|"Name" \|\| vAssetName||
|Asset Type|Specify the type of the Asset.|||
|Asset File Path|Enter or select the path of the file to upload.|@"C:\temp\myFile.txt" \|\| ProjectPath + @"\myFile.txt" \|\| vFilePath|This input should only be used for File type Assets.|
|Asset Value|Enter the new value of the Asset.|"John" \|\| 0.8 \|\| 1 \|\| vAssetValue||
|Output Asset Value Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateAssetCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Asset
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
