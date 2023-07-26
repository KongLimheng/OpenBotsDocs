<!--TITLE: Microsoft 365 Create Session Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365 group. -->
[Go To Automation Commands Overview](/automation-commands)


# Microsoft 365 Create Session Command


## What does this command do?
This command creates a Microsoft 365 session instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Microsoft 365 Instance Name|Enter a unique name that will represent the application instance.|MyMicrosoft365Instance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Client Id|Enter the Id of your Azure Active Directory application.|"xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" \|\| vClientId||
|Tenant Id|Enter the Azure Tenant Id.|"xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" \|\| vTenantId||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: Microsoft365CreateSessionCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
