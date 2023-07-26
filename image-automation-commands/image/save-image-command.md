<!--TITLE: Save Image Command -->
<!-- SUBTITLE: a command in the Image Automation Commands\Image group. -->
[Go To Automation Commands Overview](/automation-commands)


# Save Image Command


## What does this command do?
This command Saves an image from a file and stores it to a Bitmap.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Image|Provide the image to be saved.|vBitmap||
|Output Folder Path|Enter or select the path of the folder to save the image to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Image File Name|Enter or select the name of the image file.|"myFile.png" \|\| vFileName|Supported File Extensions: .jpeg, .png, .bmp, .tiff, .gif |
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SaveImageCommand
Parent Namespace: OpenBots.Commands.ImageAutomation.Image
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
