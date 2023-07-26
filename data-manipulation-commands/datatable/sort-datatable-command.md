<!--TITLE: Sort Datatable Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Sort Datatable Command


## What does this command do?
This command sorts a DataTable by a specified column name/index.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter the DataTable to sort.|vDataTable||
|Search Option|Select whether the DataRow value should be found by column index or column name.|||
|Search Value|Enter a valid DataTable index or column name.|0 \|\| vIndex \|\| "Column1" \|\| vColumnName||
|Sort Type|Select whether the DataTable should be sorted by ascending or descending order.|||
|Sort Order|Select whether the DataTable should be sorted alphabetically or numerically.|||
|Output Sorted DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SortDataTableCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
