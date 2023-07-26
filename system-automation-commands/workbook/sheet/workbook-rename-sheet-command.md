<!--TITLE: Workbook Rename Sheet Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Workbook\Sheet group. -->
[Go To Automation Commands Overview](/automation-commands)


# Workbook Rename Sheet Command


## What does this command do?
This command renames a specific Worksheet in a Workbook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Workbook Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyWorkbookInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Original Worksheet Name|Specify the original name of the Worksheet to rename.|"Sheet1" \|\| vSheet||
|New Worksheet Name|Specify the new name of the Worksheet.|"Sheet1" \|\| vSheet||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkbookRenameSheetCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Workbook.Sheet
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
