<!--TITLE: Surface Automation Wait For Image Text To Exist Command -->
<!-- SUBTITLE: a command in the Image Automation Commands\Surface Automation group. -->
[Go To Automation Commands Overview](/automation-commands)


# Surface Automation Wait For Image Text To Exist Command


## What does this command do?
This command waits until it finds a text inside an image on screen.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Input Type|Please specify the method to use to input the image.|||
|Capture Search Image|Use the tool to capture an image that will be located on screen during execution.||Images with larger color variance will be found more quickly than those with a lot of white space. 
For images that are primarily white space, tagging color to the top-left corner of the image and setting 
the relative click position will produce faster results.|
|Image File Path|Enter the file path to the image that will be loaded.|@"C:\temp\myFile.png" \|\| ProjectPath + @"\myFile.png" \|\| vFilePath||
|Input Image|Enter the input image Bitmap.|vBitmap|Use the Capture Image or Load Image commands to generate an image bitmap.|
|Window Name|Select the name of the window to activate and bring forward.|"Untitled - Notepad" \|\| vWindow||
|OCR Engine|Specify the OCR engine to be used for text search.|||
|Google API Credentials File Path|The API credentials file to reference when calling the Google OCR service.|@"C:\temp\myFile.txt" \|\| ProjectPath + @"\myFile.txt" \|\| vFilePath||
|Microsoft OCR Service API Key|The access key to use when calling the Microsoft OCR service.|vAPIKey|Password input must be a SecureString variable.|
|Microsoft OCR Service Endpoint|The endpoint to target when calling the Microsoft OCR service.|"myEndpoint" \|\| vEndpoint||
|AWS Access Key|The access key to use when calling AWS textract service.|vAccessKey|Password input must be a SecureString variable.|
|AWS Secret Key|The secret key to use when calling AWS textract service.|vSecretKey|Password input must be a SecureString variable.|
|AWS Region Endpoint|Select the AWS Region Endpoint to use.|||
|Image Text|Enter the text you want to find and click inside the given image.|"hello world" \|\| vImageText||
|Case Sensitive Search|Specify if search should be case senitive or not.|||
|Accuracy (0-1)|Enter a value between 0 and 1 to set the match Accuracy. Set to 1 for a perfect match.|0.8 \|\| 1 \|\| vAccuracy|Accuracy must be a value between 0 and 1.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SurfaceAutomationWaitForImageTextToExistCommand
Parent Namespace: OpenBots.Commands.ImageAutomation.SurfaceAutomation
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
