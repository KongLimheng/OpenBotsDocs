<!--TITLE: Save MimeMessage Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Email\MimeMessage group. -->
[Go To Automation Commands Overview](/automation-commands)


# Save MimeMessage Command


## What does this command do?
This command saves an IMAP MimeMessage as an .eml file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|MimeMessage|Enter the MimeMessage to retrieve attachments from.|vMimeMessage||
|Output Folder Path|Enter or select the path to the directory to store the MimeMessage in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|MimeMessage File Name|Enter or select the name of the email file.|"myFile.eml" \|\| vEmailName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SaveMimeMessageCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Email.MimeMessage
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
