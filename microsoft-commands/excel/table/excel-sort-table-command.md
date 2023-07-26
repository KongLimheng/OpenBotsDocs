<!--TITLE: Excel Sort Table Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Table group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Sort Table Command


## What does this command do?
This command sorts an Excel Table by the ascending or descending order of a specified column.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Worksheet Name|Enter the name of the Worksheet containing the existing Excel Table.|"Sheet1" \|\| vSheet|An error will be thrown in the case of an invalid Worksheet Name.|
|Excel Table Name|Enter the name of the Excel Table to sort.|"TableName" \|\| vTableName||
|Column Search Option|Select whether the column used to sort the Excel Table should be referenced by index or name.|||
|Column Search Value|Enter a valid column index or column name.|1 \|\| vIndex \|\| "Column1" \|\| vColumnName||
|Sort Type|Select whether the Table should be sorted by ascending or descending order.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelSortTableCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Table
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
