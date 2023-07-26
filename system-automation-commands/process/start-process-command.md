<!--TITLE: Start Process Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Process group. -->
[Go To Automation Commands Overview](/automation-commands)


# Start Process Command


## What does this command do?
This command starts a program or process.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Process Name/File Path|Provide a valid process name or enter a full path to the script/executable including the extension.|"notepad" \|\| "excel" \|\| "calc" \|\| vAppName \|\| @"C:\temp\myFile.exe \|\| ProjectPath + @"\myFile.exe" \|\| vFilePath||
|Arguments (Optional)|Enter any arguments or flags if applicable.|"-a" \|\| "-version" \|\| vArg|You will need to consult documentation to determine if your executable supports arguments or flags on startup.|
|Window Style|Select the window style of the process from the list of available styles.|||
|Use Shell Execute|Indicate whether to use the operating system shell to start the process.|||
|Wait For Load|Indicate whether to wait for the user interface to finish loading.|||
|Wait For Exit|Indicate whether to wait for the process to be completed.|||
|Output Process Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: StartProcessCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Process
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
