<!--TITLE: Surface Automation Set Text Command -->
<!-- SUBTITLE: a command in the Image Automation Commands\Surface Automation group. -->
[Go To Automation Commands Overview](/automation-commands)


# Surface Automation Set Text Command


## What does this command do?
This command attempts to find, click and set text in an existing image on screen.


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
|Text To Set|Enter the text value to set in the input.|"Hello World" \|\| vText \|\| "Hello World{ENTER}"|Hotkey interpolation only works when activated by *Enable Interpolated Hotkeys*.|
|Text Position|Specify where the text should be set relative to the captured image.|||
|X Adjustment|Enter the value for adjusting horizontal coordinate of the mouse.|0 \|\| -50 \|\| 50 \|\| vXAdjustment|This number will be added to the horizontal axis pixel location of the provided element to adjust the position.|
|Y Adjustment|Enter the value for adjusting vertical coordinate of the mouse.|0 \|\| -50 \|\| 50 \|\| vYAdjustment|This number will be added to the vertical axis pixel location of the provided element to adjust the position.|
|Accuracy (0-1)|Enter a value between 0 and 1 to set the match Accuracy. Set to 1 for a perfect match.|0.8 \|\| 1 \|\| vAccuracy|Accuracy must be a value between 0 and 1.|
|Enable Interpolated Hotkeys|Select whether to enable sending hotkeys within the text.|||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SurfaceAutomationSetTextCommand
Parent Namespace: OpenBots.Commands.ImageAutomation.SurfaceAutomation
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
