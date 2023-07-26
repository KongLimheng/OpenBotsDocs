<!--TITLE: Tesseract OCR Command -->
<!-- SUBTITLE: a command in the Image Automation Commands\OCR group. -->
[Go To Automation Commands Overview](/automation-commands)


# Tesseract OCR Command


## What does this command do?
This command extracts text from an image using Tesseract.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Tesseract Executable Path|Enter or select the path to the tesseract executable.|@"C:\temp\tesseract.exe" \|\| ProjectPath + @"\tesseract.exe" \|\| vFilePath||
|Input Type|Please specify the method to use to input the image.|||
|Capture Image|Use the tool to capture an image that will be utilized during execution.|||
|Image File Path|Enter the file path to the image that will be loaded.|@"C:\temp\myFile.png" \|\| ProjectPath + @"\myFile.png" \|\| vFilePath||
|Input Image|Enter the input image Bitmap.|vBitmap|Use the Capture Image or Load Image commands to generate an image bitmap.|
|Output OCR Result Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: TesseractOCRCommand
Parent Namespace: OpenBots.Commands.ImageAutomation.OCR
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
