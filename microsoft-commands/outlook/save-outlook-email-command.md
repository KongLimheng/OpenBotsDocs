<!--TITLE: Save Outlook Email Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Outlook group. -->
[Go To Automation Commands Overview](/automation-commands)


# Save Outlook Email Command


## What does this command do?
This command saves an Outlook OBMailItem as as .msg file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|OBMailItem|Enter the OBMailItem to retrieve attachments from.|vOBMailItem||
|Output Folder Path|Enter or select the path to the directory to store the OBMailItem in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|OBMailItem File Name|Enter or select the name of the email file.|"myFile.msg" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SaveOutlookEmailCommand
Parent Namespace: OpenBots.Commands.Microsoft.Outlook
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
