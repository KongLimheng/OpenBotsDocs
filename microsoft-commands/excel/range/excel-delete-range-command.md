<!--TITLE: Excel Delete Range Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Range group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Delete Range Command


## What does this command do?
This command deletes a specific cell or range in an Excel Worksheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Range|Enter the location of the cell or range to delete.|"A1" \|\| "A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Shift Cells Up|'Yes' removes the entire range. 'No' only clears the range of its cell values.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelDeleteRangeCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Range
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
