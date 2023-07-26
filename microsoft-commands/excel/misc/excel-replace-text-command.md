<!--TITLE: Excel Replace Text Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Replace Text Command


## What does this command do?
This command finds occurences of a string in the active Worksheet of an Excel Workbook and replaces them with a new string.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Find|Enter the text to find.|"old text" \|\| vFindText||
|Replace|Enter the text to replace with.|"new text" \|\| vReplaceText||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelReplaceTextCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
