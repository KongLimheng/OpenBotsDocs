<!--TITLE: Run CSharp Script Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Process group. -->
[Go To Automation Commands Overview](/automation-commands)


# Run CSharp Script Command


## What does this command do?
This command runs a C# script and waits for it to exit before proceeding.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|CSharp Script File Path|Enter a fully qualified path to the script, including the script extension.|@"C:\temp\myFile.cs" \|\| ProjectPath + @"\myFile.cs" \|\| vFilePath|This command differs from *Start Process* because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using *Start Process* instead.|
|Argument Style|Whether to pass a string[] (command line) or object[] (variables) to your script.|||
|Argument Values (Optional)|Enter the values to pass into the script.|"hello" \|\| vValue|This input is passed to your script as a object[].|
|Command Line Arguments (Optional)|Enter any arguments as a single string.|"-message Hello -t 2" \|\| vArguments \|\| "-message " + vMessage + " -t 2"|This input is passed to your script as a string[].|
|Output Script Result Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RunCSharpScriptCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Process
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
