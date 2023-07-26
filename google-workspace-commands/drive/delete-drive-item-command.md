<!--TITLE: Delete Drive Item Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Drive group. -->
[Go To Automation Commands Overview](/automation-commands)


# Delete Drive Item Command


## What does this command do?
This command deletes an item from Drive.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Google Workspace Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyGoogleWorkspaceInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Supports All Drives|Select whether the requesting application supports both My Drives and shared drives.|||
|DriveItem|Provide the DriveItem to delete.|vDriveItem|The 'Google.Apis.Drive.v3.Data' assembly reference must be added to 'Imports' to access this type.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DeleteDriveItemCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Drive
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
