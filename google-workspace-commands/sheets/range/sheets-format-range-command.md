<!--TITLE: Sheets Format Range Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets\Range group. -->
[Go To Automation Commands Overview](/automation-commands)


# Sheets Format Range Command


## What does this command do?
This command sets the format of a selected range in an Sheets Sheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sheets Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySheetsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Sheet Name|Specify the Sheet within the Spreadsheet to use.|"Sheet1" \|\| vSheet||
|Range|Enter the location of the range to format.|"A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Data Type|Select a value from the list of available data types.|||
|Thousands Separator|Select whether to place the thousands separator.|||
|Number of Decimals|Enter the number of decimals.|2 \|\| vDecimals||
|Date Format|Select a value from the list of available date formats.|||
|Time Format|Select a value from the list of available time formats.|||
|Custom Format (Optional)|Enter your custom string format.|"0.00_);[Red](0.00)" \|\| vCustomFormat||
|Alignment|Select a value from the list of available alignments.|||
|Font|Select a value from the list of available fonts.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SheetsFormatRangeCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Sheets.Range
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
