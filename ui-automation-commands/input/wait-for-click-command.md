<!--TITLE: Wait For Click Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Input group. -->
[Go To Automation Commands Overview](/automation-commands)


# Wait For Click Command


## What does this command do?
This command pauses execution until the indicated key press is detected.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Click Type|Select the appropriate click type.|||
|Desktop Region (Optional)|If provided, the command will only trigger when the mouse is clicked in the specified region.|"[5,0,10,20]" \|\| vRegionString|Region should be in format [TopLeftXCoordinate, TopLeftYCoordinate, RegionWidth, RegionHeight].|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Output Event Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WaitForClickCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Input
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
