<!--TITLE: Excel 365 Create Session Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365\Excel 365 group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel 365 Create Session Command


## What does this command do?
This command creates an Excel 365 session instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Microsoft 365 Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyMicrosoft365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Excel 365 Instance Name|Enter a unique name that will represent the application instance.|MyExcel365Instance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|SharePoint Site Name|Enter the name of the SharePoint site.|"MyTestSite" \|\| vMySite|The SharePoint site should be followed by the user account used for authentication.|
|Drive Id (Optional)|Enter the id of the drive to use.|"55BBAC51A4E4017D!104" \|\| vDriveId|If not provided, the root drive will be used.|
|DriveItem|Provide the DriveItem to be used.|vDriveItem||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: Excel365CreateSessionCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365.Excel365
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
