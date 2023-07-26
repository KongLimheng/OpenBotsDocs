<!--TITLE: Excel 365 Get Range Color Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365\Excel 365\Range group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel 365 Get Range Color Command


## What does this command do?
This command gets the colors in a range from an Excel 365 Worksheet and stores them in a Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel 365 Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyExcel365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Worksheet Name|Specify the Worksheet within the Workbook to use.|"Sheet1" \|\| vSheet||
|Range|Enter the location of the range to extract the colors of.|"A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Output Color Dictionary Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: Excel365GetRangeColorCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365.Excel365.Range
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
