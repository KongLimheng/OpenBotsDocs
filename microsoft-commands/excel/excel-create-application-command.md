<!--TITLE: Excel Create Application Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Create Application Command


## What does this command do?
This command creates an Excel application instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter a unique name that will represent the application instance.|MyExcelInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|New/Open Workbook|Indicate whether to create a new Workbook or to open an existing Workbook.|||
|Workbook File Path|Enter or select the path to the Workbook file.|@"C:\temp\myFile.xlsx" \|\| ProjectPath + @"\myFile.xlsx" \|\| vFilePath|This input should only be used for opening existing Workbooks.|
|Read-Only Behavior Option|Select behavior when opening an instance of a read-only Workbook.|||
|Visible|Indicate whether the Excel automation should be visible or not.|||
|Update External Links|Indicate workbook's setting for updating external links.|||
|Password (Optional)|Optional field to define the password in the case of a password protected worksheet.|vPassword|If not defined when opening a password protected worksheet, a password prompt will appear when the command runs.|
|Close All Existing Excel Instances|Indicate whether to close any existing Excel instances before executing Excel Automation.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelCreateApplicationCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
