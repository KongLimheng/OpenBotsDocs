<!--TITLE: Get PDF Text Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\PDF group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get PDF Text Command


## What does this command do?
This command extracts all text from a PDF file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Source Type|Select source type of PDF file.||Select 'File Path' if the file is locally placed or 'File URL' to read a file from a web URL.|
|PDF File Path/URL|Specify the local path or URL to the applicable PDF file.|@"C:\temp\myFile.pdf" \|\| ProjectPath + @"\myFile.pdf" \|\| vFilePath \|\| https://temp.com/myfile.pdf|Providing an invalid File Path/URL will result in an error.|
|Password (Optional)|Optional field to define the password in the case of a password protected PDF.|vPassword|If not defined when opening a password protected PDF File, a password prompt will appear when the command runs.|
|Range (Optional)|Optional field to define the range of pages of the PDF file from which text will be extracted.|"1" \|\| "1:"  "1:10" \|\| vRange \|\| vPageStart + ":" + vPageEnd \|\| vPageStart + ":"||
|PDF Extraction Engine|Select the engine to process PDF Text.|||
|Output Text Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetPDFTextCommand
Parent Namespace: OpenBots.Commands.DataManipulation.PDF
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
