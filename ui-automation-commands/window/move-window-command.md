<!--TITLE: Move Window Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Window group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move Window Command


## What does this command do?
This command moves an open window to a specified location on screen.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Window Name|Select the name of the window to move.|"Untitled - Notepad" \|\| "Current Window" \|\| vWindow||
|X Position|Input the new horizontal coordinate of the window. Starts from 0 on the left and increases going right.|0 \|\| vXPosition|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range would be 0-1920.|
|Y Position|Input the new vertical coordinate of the window. Starts from 0 at the top and increases going down.|0 \|\| vYPosition|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range would be 0-1080.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Data not specified|Data not specified|Data not specified|Data not specified|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MoveWindowCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Window
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
