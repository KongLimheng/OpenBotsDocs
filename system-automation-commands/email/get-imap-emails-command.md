<!--TITLE: Get IMAP Emails Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Email group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get IMAP Emails Command


## What does this command do?
This command gets selected emails and their attachments using IMAP protocol. Antivirus software and 2FA may need to be disabled.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Source Mail Folder Name|Enter the name of the mail folder the emails are located in.|"INBOX" \|\| "INBOX/SubFolder" \|\| vFolderName||
|Filter Parameters (Optional)|Define the filter parameters.|[ "Subject Contains" \| "Hello" ]
[ "Delivered After" \| DateTime.Now.AddDays(-1) ]|*Warning* Not providing filter parameters will return every email in the selected Mail Folder.|
|Unread Only|Specify whether to retrieve unread email messages only.|||
|Mark As Read|Specify whether to mark retrieved emails as read.|||
|Max Email Limit|Enter the maximum number of emails to fetch.|50 \|\| vTop||
|Save MimeMessages and Attachments|Specify whether to save the email attachments to a local directory.|||
|Include Embedded Images|Specify whether to consider images in body as attachments.|||
|Output MimeMessage Folder Path|Enter or select the path of the directory to store the messages in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath|This input is optional and will only be used if *Save MimeMessages and Attachments* is set to **Yes**.|
|Output Attachment Folder Path|Enter or select the path to the directory to store the attachments in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath|This input is optional and will only be used if *Save MimeMessages and Attachments* is set to **Yes**.|
|Output MimeMessage List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
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
Automation Class Name: GetIMAPEmailsCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Email
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
