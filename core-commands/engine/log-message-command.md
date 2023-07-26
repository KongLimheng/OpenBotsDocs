<!--TITLE: Log Message Command -->
<!-- SUBTITLE: a command in the Core Commands\Engine group. -->
[Go To Automation Commands Overview](/automation-commands)


# Log Message Command


## What does this command do?
This command logs text data to either an engine file or a custom file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Log File Path|Specify the corresponding logging option to save logs to Engine Logs or to a custom File.|"Engine Logs" \|\| @"C:\temp\myFile.txt" \|\| ProjectPath + @"\myFile.txt" \|\| vFilePath|Selecting 'Engine Logs' will result in writing execution logs in the 'Engine Logs'. The current Date and Time will be automatically appended to a local file if a custom file name is provided. Logs are all saved in the OpenBots Studio Root Folder in the 'Logs' folder.|
|Log Text|Specify the log text.|"Third Step is Complete" \|\| vLogText|Provide only text data.|
|Log Type|Specify the log type.|||
|Bitmap Image (Optional)|Enter the input image Bitmap.|vBitmap|Use the Capture Image, Load Image, or Take Screenshot commands in ImageAutomation to generate an image Bitmap.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: LogMessageCommand
Parent Namespace: OpenBots.Commands.Core.Engine
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
