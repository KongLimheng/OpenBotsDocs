<!--TITLE: Worksheet Create Table Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Workbook\Table group. -->
[Go To Automation Commands Overview](/automation-commands)


# Worksheet Create Table Command


## What does this command do?
This command creates a Workbook Table from a provided range of data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Workbook Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyWorkbookInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Range Worksheet Name|Enter the name of the Worksheet containing the Range being used to create the Worksheet Table.|"Sheet1" \|\| vSheet|An error will be thrown in the case of an invalid Worksheet Name.|
|Source Range|Enter the Range to extract data from for the creation of an Worksheet Table.|"A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Workbook Table Name|Enter the name of the Workbook Table to be created.|"TableName" \|\| vTableName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkbookCreateTableCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Workbook.Table
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
