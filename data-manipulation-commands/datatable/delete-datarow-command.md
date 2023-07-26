<!--TITLE: Delete DataRow Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Delete DataRow Command


## What does this command do?
This command deletes specific DataRows from a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter an existing DataTable.|vDataTable||
|Delete Option|Indicate whether DataRow(s) will be deleted by index or tuple.|||
|Index|Enter the index of the DataRow to delete.|0 \|\| vIndex||
|Data|Enter the column name and item of the row to delete.|[ "First Name" \| "John" ] \|\| [ vColumn \| vData ]||
|Overwrite Option|Indicate whether this command should remove rows with all the constraints (And) or remove those with 1 or more constraints (Or).|||
|Output DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DeleteDataRowCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
