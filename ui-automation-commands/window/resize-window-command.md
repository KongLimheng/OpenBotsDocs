<!--TITLE: Resize Window Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Window group. -->
[Go To Automation Commands Overview](/automation-commands)


# Resize Window Command


## What does this command do?
This command resizes an open window to a specified size.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Window Name|Select the name of the window to resize.|"Untitled - Notepad" \|\| "Current Window" \|\| vWindow||
|Width (Pixels)|Input the new width size of the window.|800 \|\| vWidth|Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid width range would be 0-1920.|
|Height (Pixels)|Input the new height size of the window.|500 \|\| vHeight|Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid height range would be 0-1080.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ResizeWindowCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Window
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
