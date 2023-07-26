<!--TITLE: Word Create Application Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Word group. -->
[Go To Automation Commands Overview](/automation-commands)


# Word Create Application Command


## What does this command do?
This command creates a Word Instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Word Instance Name|Enter a unique name that will represent the application instance.|MyWordInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|New/Open Document|Indicate whether to create a new Document or to open an existing Document.|||
|Document File Path|Enter or select the path to the Document file.|@"C:\temp\myFile.docx" \|\| ProjectPath + @"\myFile.docx" \|\| vFilePath|This input should only be used for opening existing Documents.|
|Read-Only Behavior Option|Select behavior when opening an instance of a read-only Document.|||
|Visible|Indicate whether the Word automation should be visible or not.|||
|Close All Existing Word Instances|Indicate whether to close any existing Word instances before executing Word Automation.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WordCreateApplicationCommand
Parent Namespace: OpenBots.Commands.Microsoft.Word
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
