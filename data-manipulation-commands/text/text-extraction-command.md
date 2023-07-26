<!--TITLE: Text Extraction Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\Text group. -->
[Go To Automation Commands Overview](/automation-commands)


# Text Extraction Command


## What does this command do?
This command performs advanced text extraction.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Text Data|Provide a variable or text value.|"Hello, welcome to OpenBots" \|\| vTextData|Providing data of a type other than a 'String' will result in an error.|
|Text Extraction Type|Select the type of extraction.||For trailing text, use 'After Text'. For leading text, use 'Before Text'. For text between two substrings, use 'Between Text'.|
|Extraction Parameters|Define the required extraction parameters, which is dependent on the type of extraction.|["Welcome", 0] \|\| [vSubstring, vOccurences]|Set parameter values for each parameter name based on the extraction type.|
|Output Text Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: TextExtractionCommand
Parent Namespace: OpenBots.Commands.DataManipulation.Text
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
