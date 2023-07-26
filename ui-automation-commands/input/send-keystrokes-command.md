<!--TITLE: Send Keystrokes Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Input group. -->
[Go To Automation Commands Overview](/automation-commands)


# Send Keystrokes Command


## What does this command do?
This command sends keystrokes to a targeted window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Window Name|Select the name of the window to send keystrokes to.|"Untitled - Notepad" \|\| "Current Window" \|\| vWindow||
|Text to Send|Enter the text to be sent to the specified window.|"Hello World" \|\| vText \|\| "Hello World{ENTER}"|Hotkey interpolation only works when activated by *Enable Interpolated Hotkeys*.|
|Enable Interpolated Hotkeys|Select whether to enable sending hotkeys within the text.|||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SendKeystrokesCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Input
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
