<!--TITLE: Submit Document Command -->
<!-- SUBTITLE: a command in the Platform Commands\Documents group. -->
[Go To Automation Commands Overview](/automation-commands)


# Submit Document Command


## What does this command do?
This command submits a file for processing by creating a new Task.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Document File Path|Path of the file to be submitted.|@"C:\temp\myFile.pdf" \|\| ProjectPath + @"\myFile.pdf" \|\| vFilePath|ProjectPath is the directory path of the current project.|
|Task Queue Name (Optional)|Name of the Queue that this task would be created in. If unspecified, it will be defaulted to the 'Default' queue.|"My Queue Name" \|\| vQueueName||
|Task Name/Title|Name or Title of the task to be created.|"My OB Document" \|\| vTaskName||
|Description (Optional)|Description of the task for reviewers or other downstream processing.|"Hello World" \|\| vDescription||
|Case Number (Optional)|A case number for reference.|"123" \|\| vCaseNumber||
|Case Type (Optional)|A case type for reference.|"Test" \|\| vCaseType||
|Assign To User (Optional)|Name of the user to assign the task.|"Test User" \|\| vUser||
|Task Due Date (Optional)|Determine the Due Date for the Task.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now|If not provided, the Task will have no expiration time.|
|Invoice|Specify whether to save the document as an invoice.|||
|Output Task Id Guid Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output Document Status Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SubmitDocumentCommand
Parent Namespace: OpenBots.Commands.Platform.Documents
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
