<!--TITLE: Excel Write Range Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Range group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Write Range Command


## What does this command do?
This command writes a DataTable to an Excel Worksheet starting from a specific cell address.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Cell Location|Enter the location of the cell to set the DataTable at.|"A1" \|\| vCellLocation||
|DataTable|Enter the DataTable to write to the Worksheet.|vDataTable||
|Add Headers|When selected, the column headers from the specified DataTable are also written.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelWriteRangeCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Range
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
