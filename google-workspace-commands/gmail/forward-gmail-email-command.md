<!--TITLE: Forward Gmail Email Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Gmail group. -->
[Go To Automation Commands Overview](/automation-commands)


# Forward Gmail Email Command


## What does this command do?
This command forwards an email using the Gmail API.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Google Workspace Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyGoogleWorkspaceInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|MimeMessage|Enter the MimeMessage to forward.|vMimeMessage||
|Recipient(s)|Enter the email address(es) of the recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|CC Recipient(s) (Optional)|Enter the email address(es) of the CC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|BCC Recipient(s) (Optional)|Enter the email address(es) of the BCC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|Email Body (Optional)|Enter text to be used as the email body.|$"Everything ran ok at {DateTime.Now}" \|\| vBody||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ForwardGmailEmailCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Gmail
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
