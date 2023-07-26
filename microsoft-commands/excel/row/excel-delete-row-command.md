<!--TITLE: Excel Delete Row Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Row group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Delete Row Command


## What does this command do?
This command deletes a specific row in an Excel Worksheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Row Number|Enter the number of the row to be deleted.|1 \|\| vRowNumber||
|Shift Cells Up|'Yes' removes the entire row. 'No' only clears the row of its cell values.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelDeleteRowCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Row
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
