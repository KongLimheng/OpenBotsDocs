<!--TITLE: Filter DataTable Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Filter DataTable Command


## What does this command do?
This command filters specific rows from a DataTable into a new Datatable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input DataTable|Enter the DataTable to filter through.|vDataTable||
|Filter Option|Indicate whether this command should filter datatable based on a Tuple or RowFilter|||
|RowFilter|Enter a RowFilter|"[Employee Age] > 30" \|\| "Name <> 'John'" \|\| vRowFilter|DataRows must match all provided tuples to be included in the filtered DataTable. Column names containing spaces should be surrounded by [].|
|Filter Data|Enter the column name and item you would like to filter by.|[ "First Name" \| "John" ] \|\| [ vColumn \| vData ]||
|Output Filtered DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: FilterDataTableCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)