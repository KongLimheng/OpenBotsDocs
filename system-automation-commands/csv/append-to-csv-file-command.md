<!--TITLE: Append To CSV File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\CSV group. -->
[Go To Automation Commands Overview](/automation-commands)


# Append To CSV File Command


## What does this command do?
This command appends a DataTable to a CSV file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|CSV File Path|Enter or select the path to the file.|@"C:\temp\myFile.csv" \|\| ProjectPath + @"\myFile.csv" \|\| vFilePath||
|DataTable|Enter an existing DataTable to append.|vDataTable||
|Delimiter|Select the delimiter to use when appending to the csv file.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: AppendToCSVFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.CSV
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)