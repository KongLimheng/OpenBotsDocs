<!--TITLE: Move/Copy IMAP Email Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Email group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move/Copy IMAP Email Command


## What does this command do?
This command moves or copies a selected email using IMAP protocol. Antivirus software and 2FA may need to be disabled.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|MimeMessage|Enter the MimeMessage to move or copy.|vMimeMessage||
|Destination Mail Folder Name|Enter the name of the mail folder the emails are being moved/copied to.|"NewFolder" \|\| "Inbox/NewFolder" \|\| vFolderName||
|MimeMessage Operation|Specify whether to move or copy the selected emails.||Moving will remove the emails from the original folder while copying will not.|
|Unread Only|Specify whether to move/copy unread email messages only.|||
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
Automation Class Name: MoveCopyIMAPEmailCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Email
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
