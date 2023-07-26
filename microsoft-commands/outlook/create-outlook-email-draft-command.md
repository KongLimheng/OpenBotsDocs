<!--TITLE: Create Outlook Email Draft Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Outlook group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Outlook Email Draft Command


## What does this command do?
This command saves an email draft with optional attachment(s) in Outlook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sender Account (Optional)|Enter the address of the Outlook mail account to set as the sender account.|"test@openbots.ai" \|\| vAccountName|If no value is provided, the command will utilize the primary account set by the Outlook application.|
|Recipient(s)|Enter the email address(es) of the recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList|Failure to send an email may be due Auto-Complete List corruption.
Navigate to Outlook > File > Options > Mail > Empty Auto-Complete list to clear the cache.|
|CC Recipient(s) (Optional)|Enter the email address(es) of the CC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|BCC Recipient(s) (Optional)|Enter the email address(es) of the BCC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|Email Subject|Enter the subject of the email.|"Hello" \|\| vSubject||
|Email Body|Enter text to be used as the email body.|"Dear John, ..." \|\| vBody||
|Email Body Type|Select the email body format.|Data not specified||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Output Draft MailItem Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateOutlookEmailDraftCommand
Parent Namespace: OpenBots.Commands.Microsoft.Outlook
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
