<!--TITLE: Excel Create Pivot Table Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\PivotTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Create Pivot Table Command


## What does this command do?
This command creates a Pivot Table from an Excel Range or Table.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Excel Data Source Worksheet|Enter the name of the Worksheet containing the Excel Table/Range being used to create the Pivot Table.|"Sheet1" \|\| vSheet|An error will be thrown in the case of an invalid Worksheet Name.|
|Excel Data Source Type|Indicate whether to the data source of the Pivot Table should come from an Excel Table or Range.|||
|Excel Range/Table Name|Enter the Range or the name of the Excel Table to extract data from for the Pivot Table.|"A1:" \|\| "A1:B5" \|\| "MyTable" \|\| vData||
|Pivot Table Worksheet|Enter the name of the Worksheet where the Pivot Table will be set.|"Sheet1" \|\| vSheet|An error will be thrown in the case of an invalid Worksheet Name.|
|Pivot Table Name|Enter the name of the new Pivot Table to be created.|"PivotTable" \|\| vPivotTable||
|Cell Location|Enter the location where the Pivot Table will be set.|"A1" \|\| vCellLocation||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelCreatePivotTableCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.PivotTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
