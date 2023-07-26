<!--TITLE: Insert DataRow Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\DataTable group. -->
[Go To Automation Commands Overview](/automation-commands)


# Insert DataRow Command


## What does this command do?
This command inserts a DataRow to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter an existing DataTable to insert a DataRow to.|vDataTable||
|DataRow Position Index|Enter a valid row position index value to insert the DataRow at.|0 \|\| vIndex||
|Data|Enter Column Names and Data for each column in the DataRow.|[ "First Name" \| "John" ] \|\| [ vColumn \| vData ]||
|Output DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: InsertDataRowCommand
Parent Namespace: OpenBots.Commands.DataManipulation.DataTable
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
