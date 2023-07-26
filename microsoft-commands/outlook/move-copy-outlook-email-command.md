<!--TITLE: Move/Copy Outlook Email Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Outlook group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move/Copy Outlook Email Command


## What does this command do?
This command moves or copies a selected email in Outlook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|OBMailItem|Enter the OBMailItem to move or copy.|vOBMailItem||
|Destination Mail Folder Name|Enter the name of the Outlook mail folder the emails are being moved/copied to.|"Inbox" \|\| "Inbox\\SubFolder" \|\| vFolderName||
|OBMailItem Operation|Specify whether to move or copy the selected emails.||Moving will remove the emails from the original folder while copying will not.|
|Unread Only|Specify whether to move/copy unread email messages only.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MoveCopyOutlookEmailCommand
Parent Namespace: OpenBots.Commands.Microsoft.Outlook
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
