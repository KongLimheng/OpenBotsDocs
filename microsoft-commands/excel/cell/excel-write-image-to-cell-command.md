<!--TITLE: Excel Write Image To Cell Command -->
<!-- SUBTITLE: a command in the Microsoft Commands\Excel\Cell group. -->
[Go To Automation Commands Overview](/automation-commands)


# Excel Write Image To Cell Command


## What does this command do?
This command writes an image to a specific cell in an Excel Worksheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Excel Instance Name|Enter the unique instance that was specified in the **Create Application** command.|MyExcelInstance|Failure to enter the correct instance or failure to first call the **Create Application** command will cause an error.|
|Cell Location|Enter the location of the cell to write image.|"A1" \|\| vCellLocation||
|Image Input Type|Please specify the method to use to input the image.|||
|Image File Path|Enter or select the path to the image file.|@"C:\temp\myFile.png" \|\| ProjectPath + @"\myFile.png" \|\| vFilePath||
|Input Image|Enter an existing Bitmap image.|vBitmap|Use the Capture Image or Load Image commands to generate an image bitmap.|
|Image Scale Percentage|Enter the image scale percentage to enlarge or reduce the size of the rendered image.|75 \|\| vImageScalePercentage||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ExcelWriteImageToCell
Parent Namespace: OpenBots.Commands.Microsoft.Excel.Cell
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
