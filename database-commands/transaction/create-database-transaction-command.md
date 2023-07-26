<!--TITLE: Create Database Transaction Command -->
<!-- SUBTITLE: a command in the Database Commands\Transaction group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Database Transaction Command


## What does this command do?
This command creates a database transaction OBAppInstance from a database connection OBAppInstance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Database Instance Name|Enter the unique instance that was specified in the **Define Database Connection** command.|MyDatabaseInstance|Failure to enter the correct instance name or failure to first call the **Define Database Connection** command will cause an error.|
|Transaction Instance Name|Enter a unique name that will represent the application instance.|MyTransactionInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateDatabaseTransactionCommand
Parent Namespace: OpenBots.Commands.Database.Transaction
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
