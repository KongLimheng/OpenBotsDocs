<!--TITLE: Lookup DataTable Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Lookup DataTable Command


## What does this command do?
This command searches for a value inside a DataTable and returns the DataRow containing the cell. If the target column is set, it also returns the value of the cell from the specified DataRow.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter an existing DataTable to lookup from.|vDataTable||
|Lookup Value|Enter the value to search for in the specified DataTable.|"hello" \|\| vLookupValue||
|Search Option (Lookup Column)|Select whether the Lookup Column should be found by column index or column name.|||
|Search Value (Lookup Column)|Enter a valid DataColumn index or column name.|0 \|\| vIndex \|\| "Column1" \|\| vColumnName||
|Search Option (Target Column)|Select whether the Target Column should be found by column index or column name.|||
|Search Value (Target Column)|Enter a valid DataColumn index or column name.|1 \|\| vIndex \|\| "Column2" \|\| vColumnName||
|Output DataRow Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output Cell Value Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: LookupDataTableCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
