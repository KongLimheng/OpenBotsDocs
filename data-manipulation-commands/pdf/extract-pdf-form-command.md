<!--TITLE: Extract PDF Form Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\PDF group. -->
[Go To Automation Commands Overview](/automation-commands)


# Extract PDF Form Command


## What does this command do?
This command gets all values from a PDF form.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|PDF File Path(s)|Provide a list of pdf file paths to extract the forms.|@"C:\temp\myFile1.pdf" \|\| new List<string>() { @"C:\temp\myFile1.pdf", @"C:\temp\myFile2.pdf" } \|\| vFileList||
|Password(s) (Optional)|Optional field to define the password in the case of a password protected PDF.|vPassword \|\| new List<SecureString>() { vPassword0, vPassword1 }|If not defined when opening a password protected PDF File, a password prompt will appear when the command runs.|
|Output DataTable Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExtractPDFFormCommand
Parent Namespace: OpenBots.Commands.DataManipulation.PDF
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
