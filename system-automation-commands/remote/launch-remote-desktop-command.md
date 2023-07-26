<!--TITLE: Launch Remote Desktop Command -->
<!-- SUBTITLE: a command in the System Automation Commands\Remote group. -->
[Go To Automation Commands Overview](/automation-commands)


# Launch Remote Desktop Command


## What does this command do?
This command launches a remote desktop session.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Remote Desktop Instance Name|Enter a unique name that will represent the application instance.|MyRemoteDesktopInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Machine Name|Define the name of the machine to log on to.|"myMachine" \|\| vMachineName||
|Username|Define the username to use when connecting to the machine.|"myRobot" \|\| vUsername \|\| vCredential.Username||
|Password|Define the password to use when connecting to the machine.|vPassword \|\| vCredential.Password|Password input must be a SecureString variable.|
|RDP Window Width|Define the width for the Remote Desktop Window.|1000 \|\| vWidth||
|RDP Window Height|Define the height for the Remote Desktop Window.|800 \|\| vHeight||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: LaunchRemoteDesktopCommand
Parent Namespace: OpenBots.Commands.SystemAutomation.Remote
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
