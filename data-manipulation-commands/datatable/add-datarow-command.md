<!--TITLE: Add DataRow Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Add DataRow Command


## What does this command do?
This command adds a DataRow to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter an existing DataTable to add a DataRow to.|vDataTable||
|Input Type|Select the preferred input type.|||
|Data|Enter Column Names and Data for each column in the DataRow.|[ "First Name" \| "John" ] \|\| [ vColumn \| vData ]||
|Object List|Provide the object list representing the data row to add.|1 \|\| new List<object>{1, "2", 3} \|\| vDataRowToAdd|Object types should match that of the same index in the data table.|
|Output DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: AddDataRowCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
