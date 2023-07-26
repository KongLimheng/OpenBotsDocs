<!--TITLE: Send Server Email Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Email group. -->
[Go To Automation Commands Overview](/automation-commands)


# Send Server Email Command


## What does this command do?
This command sends an email with optional attachment(s) in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Account Name (Optional)|Define the account name to use when contacting the Server email service.|"myRobot" \|\| vAccountName|If no account name is specified, the default account will be used.|
|To Recipient(s)|Enter the email address(es) of the 'To' recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|CC Recipient(s) (Optional)|Enter the email address(es) of the 'CC' recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|BCC Recipient(s) (Optional)|Enter the email address(es) of the BCC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|Email Subject|Enter the subject of the email.|"Hello" \|\| vSubject||
|Email Body|Enter text to be used as the email body.|"Dear John, ..." \|\| vBody||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SendServerEmailCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Email
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
