<!--TITLE: Sheets Create Session Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets group. -->
[Go To Automation Commands Overview](/automation-commands)


# Sheets Create Session Command


## What does this command do?
This command creates an Sheets session instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Google Workspace Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyGoogleWorkspaceInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Sheets Instance Name|Enter a unique name that will represent the application instance.|MySheetsInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|New/Open Spreadsheet|Indicate whether to create a new Document or to open an existing Document.|||
|New Spreadsheet Name|Enter the name of the new Spreadsheet.|"mySpreadsheet" \|\| vSpreadsheetName||
|FileItem|Provide the FileItem to be used.|vFileItem||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SheetsCreateSessionCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Sheets
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
