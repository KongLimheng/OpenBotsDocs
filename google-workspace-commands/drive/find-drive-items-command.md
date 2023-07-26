<!--TITLE: Find Drive Items Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Drive group. -->
[Go To Automation Commands Overview](/automation-commands)


# Find Drive Items Command


## What does this command do?
This command searches for items in Drive.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Google Workspace Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyGoogleWorkspaceInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Drive Id (Optional)|Enter the id of the drive to search from.|"55BBAC51A4E4017D!104" \|\| vDriveId|If not provided, the root drive will be used.|
|Search Query|Enter a search query to retrieve matching DriveItems.|"name='data.xlsx'" \|\| vMySearchQuery|For files that contains the "\" character, the character should be replaced by "\\\\".And for files that contains the "'" character, the character should be replaced by "\\'".|
|Output DriveItem List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.
The 'Google.Apis.Drive.v3.Data' assembly reference must be added to 'Imports' to access this type..|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: FindDriveItemsCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Drive
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
