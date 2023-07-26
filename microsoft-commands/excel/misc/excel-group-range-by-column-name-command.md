<!--TITLE: Excel Group Range By Column Name Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Group Range By Column Name Command


## What does this command do?
This command takes a specific Excel range, groups it into separate ranges by column, and stores them in new Workbooks.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Range|Enter the location of the range to group.|"A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Column to Group By|Enter the name of the column you wish to group the selected range by.|"ColA" \|\| vColumnName||
|Output Folder Path|Enter or select the new directory for the grouped range files.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Output File Type|Specify the file format type for the split range files.|||
|Output DataTable List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelGroupRangeByColumnNameCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
