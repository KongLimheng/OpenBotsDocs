<!--TITLE: Excel Run Macro Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Run Macro Command


## What does this command do?
This command runs a macro in an Excel Workbook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Macro Name|Enter the name of the macro as it exists in the Worksheet.|"Macro1" \|\| vMacro||
|Macro Parameters (Optional)|Enter the parameter values to be passed to the Macro.|vParameterValue|Macros only support non-object parameters ex. Integer, String, Boolean. Parameters are passed in order top to bottom.|
|Output Result Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelRunMacroCommand
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
