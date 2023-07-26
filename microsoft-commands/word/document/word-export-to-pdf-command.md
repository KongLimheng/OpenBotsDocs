<!--TITLE: Word Export To PDF Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Word\Document group. -->
[Go To Automation Commands Overview](/automation-commands)


# Word Export To PDF Command


## What does this command do?
This command exports a Word Document to a PDF file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Word Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyWordInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Output Folder Path|Enter or select the path of the folder to export the PDF to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|PDF File Name|Enter or select the name of the PDF file.|"myFile.pdf" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WordExportToPDFCommand
Parent Namespace: OpenBots.Commands.Microsoft.Word.Document
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
