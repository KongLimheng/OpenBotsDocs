<!--TITLE: Reply To Outlook Email Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Outlook group. -->
[Go To Automation Commands Overview](/automation-commands)


# Reply To Outlook Email Command


## What does this command do?
This command replies to a selected email in Outlook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|OBMailItem|Enter the OBMailItem to reply to.|vOBMailItem||
|Mail Operation|Specify whether you intend to reply or reply all.||Replying will reply to only the original sender. Reply all will reply to everyone in the recipient list.|
|Additional Recipient(s) (Optional)|Enter the email address(es) of the additional recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|CC Recipient(s) (Optional)|Enter the email address(es) of the CC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|BCC Recipient(s) (Optional)|Enter the email address(es) of the BCC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|Email Body|Enter text to be used as the email body.|"Dear John, ..." \|\| vBody||
|Email Body Type|Select the email body format.|Data not specified||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|"C:\temp\myFile1.xlsx" \|\| new List<string>() { "C:\temp\myFile1.xlsx", "C:\temp\myFile2.xlsx" } \|\| vFileList||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ReplyToOutlookEmailCommand
Parent Namespace: OpenBots.Commands.Microsoft.Outlook
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
