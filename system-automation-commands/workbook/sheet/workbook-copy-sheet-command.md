<!--TITLE: Workbook Copy Sheet Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Workbook\Sheet group. -->
[Go To Automation Commands Overview](/automation-commands)


# Workbook Copy Sheet Command


## What does this command do?
This command copies a Worksheet from a Workbook to a new Workbook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Workbook Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyWorkbookInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Worksheet Name|Specify the name of the new Worksheet to copy.|"Sheet1" \|\| vSheet||
|Output Workbook File Path|Enter or select the path to the Workbook file.|@"C:\temp\myFile.xlsx" \|\| ProjectPath + @"\myFile.xlsx" \|\| vFilePath|This input should only be used for opening existing Workbooks.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkbookCopySheetCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Workbook.Sheet
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
