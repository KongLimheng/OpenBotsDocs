<!--TITLE: Excel 365 Create Table Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Microsoft 365\Excel 365\Table group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel 365 Create Table Command


## What does this command do?
This command creates an Excel 365 Table from a provided range of data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel 365 Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MyExcel365Instance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Range Worksheet Name|Enter the name of the Worksheet containing the Range being used to create the Excel Table.|"Sheet1" \|\| vSheet|An error will be thrown in the case of an invalid Worksheet Name.|
|Source Range|Enter the Range to extract data from for the creation of an Excel Table.|"A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Excel Table Name|Enter the name of the Excel Table to be created.|"TableName" \|\| vTableName||
|Has Headers|Whether the Data in the Range includes column headers.||If false, Excel 365 will automatically generate headers and shift the data down 1 row.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: Excel365CreateTableCommand
Parent Namespace: OpenBots.Commands.Microsoft.Microsoft365.Excel365.Table
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
