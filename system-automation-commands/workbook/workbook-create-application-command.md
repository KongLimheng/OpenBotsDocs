<!--TITLE: Workbook Create Application Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Workbook group. -->
[Go To Automation Commands Overview](/automation-commands)


# Workbook Create Application Command


## What does this command do?
This command creates a Workbook application instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Workbook Instance Name|Enter a unique name that will represent the application instance.|MyWorkbookInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|New/Open Workbook|Indicate whether to create a new Workbook or to open an existing Workbook.|||
|Workbook Location|Enter or select the path of the folder to save the Workbook to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Workbook File Name|Enter or select the name of the Workbook file.|"myFile.xlsx" \|\| vFileName||
|Workbook File Path|Enter or select the path to the Workbook file.|@"C:\temp\myFile.xlsx" \|\| ProjectPath + @"\myFile.xlsx" \|\| vFilePath|This input should only be used for opening existing Workbooks.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkbookCreateApplicationCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Workbook
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
