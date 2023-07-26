<!--TITLE: Microsoft OCR Command -->
<!-- SUBTITLE: a command in the Image Automation Commands\Cloud OCR group. -->
[Go To Automation Commands Overview](/automation-commands)


# Microsoft OCR Command


## What does this command do?
This command extracts text from an image file using Microsoft OCR.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Image Input Type|Select the method through which to input your image.|||
|Image File Path|Enter the image file path.|@"C:\temp\myFile.png" \|\| ProjectPath + @"\myFile.png" \|\| vFilePath|Supported file formats: JPEG, PNG, BMP, and TIFF|
|Image Bitmap|Enter the image Bitmap.|vBitmap|Use the Capture Image or Load Image commands to generate an image bitmap.|
|Microsoft OCR Service API Key|The access key to use when calling the Microsoft OCR service.|vAPIKey|Password input must be a SecureString variable.|
|Microsoft OCR Service Endpoint|The endpoint to target when calling the Microsoft OCR service.|"myEndpoint" \|\| vEndpoint||
|Output OCR Result Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MicrosoftOCRCommand
Parent Namespace: OpenBots.Commands.ImageAutomation.CloudOCR
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
