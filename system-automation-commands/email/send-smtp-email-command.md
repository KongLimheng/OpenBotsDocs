<!--TITLE: Send SMTP Email Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Email group. -->
[Go To Automation Commands Overview](/automation-commands)


# Send SMTP Email Command


## What does this command do?
This command sends an email with optional attachment(s) using SMTP protocol. Antivirus software and 2FA may need to be disabled.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Recipient(s)|Enter the email address(es) of the recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|CC Recipient(s) (Optional)|Enter the email address(es) of the CC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|BCC Recipient(s) (Optional)|Enter the email address(es) of the BCC recipient(s).|"test@test.com" \|\| new List<string>() { "test@test.com", "test2@test.com" } \|\| vEmailsList||
|Email Subject|Enter the subject of the email.|"Hello" \|\| vSubject||
|Email Body|Enter text to be used as the email body.|"Dear John, ..." \|\| vBody||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Host|Define the host/service used by the service.|"imap.gmail.com" \|\| "smtp.gmail.com" \|\| "outlook.office365.com" \|\| "smtp.office365.com" \|\| vHost||
|Port|Define the port number used by the service.|"993" \|\| "465" \|\| "587" \|\| vPort||
|Secure Connection|Specify the SSL or TLS encryption to be used by the service.|||
|OAuth2 Authentication Type|Select the necessary OAuth2 authenticator.|||
|Username|Define the username to use when contacting the service.|"myRobot" \|\| vUsername \|\| vCredential.Credential||
|Password|Define the password to use when contacting the service.|vPassword \|\| vCredential.Password|Password input must be a SecureString variable.|
|Client Id|Enter the Client Id of the application.|"xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" \|\| vClientId||
|Client Secret|Enter the secret string that the application uses to prove its identity when requesting a token.|vClientSecret||
|Tenant Id|Enter the Azure Tenant Id.|"xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" \|\| vTenantId||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SendSMTPEmailCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Email
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
