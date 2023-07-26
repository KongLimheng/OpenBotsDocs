<!--TITLE: Write/Create Text File Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Text File group. -->
[Go To Automation Commands Overview](/automation-commands)


# Write/Create Text File Command


## What does this command do?
This command writes specified data to an existing or newly created text file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Output Folder Path|Enter or select the path to the folder.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Text File Name|Enter the name of the CSV file to write out.|"myFile.txt" \|\| vFileName||
|Text|Indicate the Text to write.|"Hello World!" \|\| vText||
|Overwrite Option|Indicate whether this command should append the text to or overwrite all existing text in the file|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WriteCreateTextFileCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.TextFile
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
