<!--TITLE: Execute Database Query Command -->
<!-- SUBTITLE: a command in the Database Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Execute Database Query Command


## What does this command do?
This command performs a OleDb database query.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Database Instance Name|Enter the unique instance that was specified in the **Define Database Connection** command.|MyBrowserInstance|Failure to enter the correct instance name or failure to first call the **Define Database Connection** command will cause an error.|
|Define Query Execution Type|Select the appropriate query execution type. Return Dataset in the case of a query to retrieve data. Execute NonQuery in the case of a non-retrieval action.|||
|Query|Define the OleDb query to execute.|"SELECT OrderID, CustomerID FROM Orders" \|\| vQuery||
|Query Parameters (Optional)|Define the query parameters.|[ STRING \| "@name" \| vNameValue ]||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Output Dataset Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output Affected Row Count Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExecuteDatabaseQueryCommand
Parent Namespace: OpenBots.Commands.Database
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
