<!--TITLE: Write CSV File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\CSV group. -->
[Go To Automation Commands Overview](/automation-commands)


# Write CSV File Command


## What does this command do?
This command writes a DataTable to a CSV file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|DataTable|Enter an existing DataTable to write out.|vDataTable||
|Delimiter|Select the delimiter to use when writing to the csv file.|||
|Add Headers|When selected, the column headers from the specified DataTable are also written.|||
|Output Folder Path|Enter or select the path to the folder.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|CSV File Name|Enter the name of the CSV file to write out.|"myFile.csv" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WriteCSVFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.CSV
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
