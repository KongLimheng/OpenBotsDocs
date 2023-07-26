<!--TITLE: Export Drive File To PDF Command Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Drive group. -->
[Go To Automation Commands Overview](/automation-commands)


# Export Drive File To PDF Command Command


## What does this command do?
This command exports an item from Drive to a PDF.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Google Workspace Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyGoogleWorkspaceInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|DriveItem|Provide the DriveItem to export.|vDriveItem|The 'Google.Apis.Drive.v3.Data' assembly reference must be added to 'Imports' to access this type.|
|Output Folder Path|Enter or select the destination folder path.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Output File Path Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExportDriveFileToPDFCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Drive
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
