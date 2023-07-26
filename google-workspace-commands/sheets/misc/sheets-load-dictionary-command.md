<!--TITLE: Sheets Load Dictionary Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# Sheets Load Dictionary Command


## What does this command do?
This command reads an Sheets Config Sheet and stores it in a Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sheets Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySheets365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Sheet Name|Specify the Sheet within the Spreadsheet to use.|"Sheet1" \|\| vSheet||
|Key Column Name|Enter the name of the column to be loaded as Dictionary Keys.|"Name" \|\| vKeyColumn||
|Value Column Name|Enter the name of the column to be loaded as Dictionary Values.|"Value" \|\| vValueColumn||
|Output Dictionary Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SheetsLoadDictionaryCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Sheets.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
