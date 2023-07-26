<!--TITLE: Execute Transaction Query Command -->
<!-- SUBTITLE: a command in the Database Commands\Transaction group. -->
[Go To Automation Commands Overview](/automation-commands)


# Execute Transaction Query Command


## What does this command do?
This command performs an OleDb database query within the context of a transaction.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Transaction Instance Name|Enter the unique instance that was specified in the **Create Database Transaction** command.|MyTransactionInstance|Failure to enter the correct instance or failure to first call the **Create Database Transaction** command will cause an error.|
|Query|Define the OleDb query to execute.|"SELECT OrderID, CustomerID FROM Orders" \|\| vQuery||
|Query Parameters (Optional)|Define the query parameters.|[ STRING \| "@name" \| vNameValue ]||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Output Affected Row Count Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExecuteTransactionQueryCommand
Parent Namespace: OpenBots.Commands.Database.Transaction
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
