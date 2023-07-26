<!--TITLE: Sheets Rename Sheet Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets\Sheet group. -->
[Go To Automation Commands Overview](/automation-commands)


# Sheets Rename Sheet Command


## What does this command do?
This command renames a specific Sheet in an Sheets Spreadsheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sheets Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySheetsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Original Sheet Name|Specify the original name of the Sheet to rename.|"Sheet1" \|\| vSheet||
|New Sheet Name|Specify the new name of the Sheet.|"Sheet1" \|\| vSheet||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SheetsRenameSheetCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Sheets.Sheet
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
