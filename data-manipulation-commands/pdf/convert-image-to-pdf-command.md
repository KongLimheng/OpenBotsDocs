<!--TITLE: Convert Image To PDF Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\PDF group. -->
[Go To Automation Commands Overview](/automation-commands)


# Convert Image To PDF Command


## What does this command do?
This command converts HTML into a PDF file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input Type|Please specify the method to use to input the image.|||
|Capture Search Image|Use the tool to capture an image that will be located on screen during execution.||Images with larger color variance will be found more quickly than those with a lot of white space. 
For images that are primarily white space, tagging color to the top-left corner of the image and setting 
the relative click position will produce faster results.|
|Image File Path|Enter the file path to the image that will be loaded.|@"C:\temp\myFile.png" \|\| ProjectPath + @"\myFile.png" \|\| vFilePath||
|Input Image|Enter the input image Bitmap.|vBitmap|Use the Capture Image or Load Image commands to generate an image bitmap.|
|Page Size|Select the appropriate page size.|||
|Page Orientation|Select the appropriate page orientation.|||
|Margin|Enter the appropriate margin size.|20 \|\| vMargin||
|Output Folder Path|Enter or select the path of the folder to save the PDF to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|PDF File Name|Enter or select the name of the PDF file.|"myFile.pdf" \|\| vFileName||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ConvertImageToPDFCommand
Parent Namespace: OpenBots.Commands.DataManipulation.PDF
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
