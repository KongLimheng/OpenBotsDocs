<!--TITLE: Create Database Connection Command -->
<!-- SUBTITLE: a command in the Database Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Database Connection Command


## What does this command do?
This command connects to an OleDb database.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Database Instance Name|Enter a unique name that will represent the application instance.|MyDatabaseInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Connection String|Define the string to use when connecting to the OleDb database.|"Provider=sqloledb;Data Source=myServerAddress;Initial Catalog=myDataBase;Integrated Security=SSPI;" \|\| vConnectionString|When using the 'Test Connection' utility, the password needs to be explicitly defined in the 'Connection String Password' field.
The 'Provider' set by the 'Build Connection String' utility may need to be modified to match the database, i.e. 'MSDATASHAPE'.
Additionally, the bitness of the database driver should match the bitness of the Application (x32).|
|Connection String Password (Optional)|Optional field to define the password to use when connecting to the OleDb database.|vPassword \|\| vCredential.Password|If storing the password in the UITextBox below, please ensure the connection string above contains a database-specific placeholder with #pwd to be replaced at runtime. (;Password=#pwd)|
|Test Connection Before Proceeding|Select the appropriate option.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateDatabaseConnectionCommand
Parent Namespace: OpenBots.Commands.Database
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
