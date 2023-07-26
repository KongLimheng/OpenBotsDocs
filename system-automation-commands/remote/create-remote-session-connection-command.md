<!--TITLE: Create Remote Session Connection Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Remote group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Remote Session Connection Command


## What does this command do?
This command creates a remote session.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Remote Session Instance Name|Enter a unique name that will represent the application instance.|MyRemoteInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Remote Desktop Instance Name|Enter the unique instance that was specified in the **Launch Remote Desktop** command.|MyRemoteDesktopInstance|Failure to enter the correct instance name or failure to first call the **Launch Remote Desktop** command will cause an error.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateRemoteSessionCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Remote
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
