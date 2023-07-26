<!--TITLE: Get Latest SharePoint 365 Item Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365\SharePoint 365 group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Latest SharePoint 365 Item Command


## What does this command do?
This command returns the most recently created or modified item from a folder in SharePoint 365.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Microsoft 365 Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyMicrosoft365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|SharePoint Site Name|Enter the name of the SharePoint site.|"MyTestSite" \|\| vMySite|The SharePoint site should be followed by the user account used for authentication.|
|Drive Id (Optional)|Enter the id of the drive to retrieve from.|"55BBAC51A4E4017D!104" \|\| vDriveId|If not provided, the root drive will be used.|
|Folder DriveItem|Provide the Folder DriveItem to retrieve the children of.|vDriveItem|The 'Microsoft.Graph' assembly reference must be added to 'Imports' to access this type.|
|Item Sorting Option|Select a criteria to search for the file from the list of available options.|||
|Output DriveItem Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.
The 'Microsoft.Graph' assembly reference must be added to 'Imports' to access this type.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetLatestSharePoint365ItemCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365.SharePoint365
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
