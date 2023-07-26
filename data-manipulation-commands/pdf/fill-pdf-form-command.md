<!--TITLE: Fill PDF Form Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\PDF group. -->
[Go To Automation Commands Overview](/automation-commands)


# Fill PDF Form Command


## What does this command do?
This command sets the value of several PDF form fields.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PDF File Path|Specify the local path to the applicable PDF file.|@"C:\temp\myFile.pdf" \|\| ProjectPath + @"\myFile.pdf" \|\| vFilePath||
|Password (Optional)|Optional field to define the password in the case of a password protected PDF.|vPassword|If not defined when opening a password protected PDF File, a password prompt will appear when the command runs.|
|PDF Form Data Input Type|Select the input type for the PDF form data.|Data not specified||
|PDF Form Field Data|Enter the Keys and Values required for the new record.|[ "Name" \| "OpenBots" ] \|\| [ vFieldName \| vFieldValue ]||
|PDF Form DataTable Values|Specify the DataTable from where the values ​​will be taken|vDataTable||
|Output Folder Path|Enter or select the path of the folder to save the PDF to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|PDF File Name|Enter or select the name of the PDF file.|"myFile.pdf" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: FillPDFFormCommand
Parent Namespace: OpenBots.Commands.DataManipulation.PDF
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
