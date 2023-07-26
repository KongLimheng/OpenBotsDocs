<!--TITLE: Read CSV File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\CSV group. -->
[Go To Automation Commands Overview](/automation-commands)


# Read CSV File Command


## What does this command do?
This command reads a DataTable from a CSV.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|CSV File Path|Enter or select the path to the file.|@"C:\temp\myFile.csv" \|\| ProjectPath + @"\myFile.csv" \|\| vFilePath||
|Delimiter|Select the delimiter to use when reading from the csv file.|||
|Add Headers|When selected, the first row is used as the DataTable's headers.|||
|Ignore Quotes|Select whether to ignore quotes in the read text.|||
|Output DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ReadCSVFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.CSV
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
