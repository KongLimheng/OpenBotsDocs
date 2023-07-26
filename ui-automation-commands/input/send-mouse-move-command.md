<!--TITLE: Send Mouse Move Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Input group. -->
[Go To Automation Commands Overview](/automation-commands)


# Send Mouse Move Command


## What does this command do?
This command simulates a mouse movement to a specified position.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|X Position|Input the new horizontal coordinate of the mouse. Starts from 0 on the left and increases going right.|0 \|\| vXPosition|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range would be 0-1920.|
|Y Position|Input the new vertical coordinate of the mouse. Starts from 0 at the top and increases going down.|0 \|\| vYPosition|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range would be 0-1080.|
|Click Type (Optional)|Indicate the type of click required.||You can simulate a custom click by using multiple mouse click commands in succession, adding **Pause Command** in between where required.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SendMouseMoveCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Input
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
