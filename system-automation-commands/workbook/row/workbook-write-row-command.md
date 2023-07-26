<!--TITLE: Workbook Write Row Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Workbook\Row group. -->
[Go To Automation Commands Overview](/automation-commands)


# Workbook Write Row Command


## What does this command do?
This command writes a DataRow to a Workbook Worksheet starting from a specific cell address.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Workbook Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyWorkbookInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Worksheet Name|Specify the Worksheet within the Workbook to use.|"Sheet1" \|\| vSheet||
|Target Cell Location|Enter the location of the cell to write the row to.|"A1" \|\| vCellLocation||
|Row|Enter the row value to set at the selected cell.|new List<string>() { "Hello", "World" } \|\| vList \|\| vDataRow||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkbookWriteRowCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Workbook.Row
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
