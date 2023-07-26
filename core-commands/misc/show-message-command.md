<!--TITLE: Show Message Command -->
<!-- SUBTITLE: a command in the Core Commands\Misc group. -->
[Go To Automation Commands Overview](/automation-commands)


# Show Message Command


## What does this command do?
This command displays a message to the user.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Message|Specify any text or variable value that should be displayed on screen.|"Hello World" \|\| vMyVar \|\| "Hello " + vName||
|Close After X (Seconds)|Specify how many seconds to display the message on screen. After the specified time,
the message box will be automatically closed and script will resume execution.|0 \|\| 5 \|\| vSeconds|Set value to 0 to remain open indefinitely.|
|Send Notification|Select whether to send a notification or to just allow for normal execution to occur.||In the case of 'Yes', a notification will be sent to OpenBots Assistant or Business Center.|
|Notification Timeout|Specify how many seconds to wait for a response to the notification. After the specified time,
the notification will be cleared out and script execution will resume.|0 \|\| 5 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ShowMessageCommand
Parent Namespace: OpenBots.Commands.Core.Misc
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
