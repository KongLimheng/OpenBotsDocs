<!--TITLE: Delete Outlook 365 Email Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365\Outlook 365 group. -->
[Go To Automation Commands Overview](/automation-commands)


# Delete Outlook 365 Email Command


## What does this command do?
This command deletes a selected email in Outlook 365.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Microsoft 365 Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyMicrosoft365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Source Mail Account (Optional)|Enter the address of the Outlook mail account the emails are located in.|"test@openbots.ai" \|\| vAccountName|If no value is provided, the command will utilize the primary account set by the Outlook application.|
|Message|Enter the Message to delete.|vMessage|The 'Microsoft.Graph' assembly reference must be added to 'Imports' to access this type.|
|Delete Read Emails Only|Specify whether to delete read email messages only.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DeleteOutlook365EmailCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365.Outlook365
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
