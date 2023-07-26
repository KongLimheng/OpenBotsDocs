<!--TITLE: Merge PDF Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\PDF group. -->
[Go To Automation Commands Overview](/automation-commands)


# Merge PDF Command


## What does this command do?
This command merges a specified list of PDF files.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PDF File Path(s)|Provide a list of pdf file paths to merge.|@"C:\temp\myFile1.pdf" \|\| new List<string>() { @"C:\temp\myFile1.pdf", @"C:\temp\myFile2.pdf" } \|\| vFileList||
|Output Folder Path|Enter or select the path of the folder to save the PDF to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|PDF File Name|Enter or select the name of the PDF file.|"myFile.pdf" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MergePDFCommand
Parent Namespace: OpenBots.Commands.DataManipulation.PDF
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
