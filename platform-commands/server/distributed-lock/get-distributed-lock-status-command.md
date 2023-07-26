<!--TITLE: Get Distributed Lock Status Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Distributed Lock group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Distributed Lock Status Command


## What does this command do?
This command acquires a Distributed Lock and/or retrieves the latest Distributed Lock Status from OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Action|Specify whether to acquire a distributed lock or get the latest distributed lock status.|||
|Distributed Lock Name|Enter the name of the Distributed Lock.|"Name" \|\| vLockName|Data not specified|
|Distributed Lock Status|Enter a Distributed Lock Status variable.|vLockStatus||
|Output Lock Status Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetDistributedLockStatusCommand
Parent Namespace: OpenBots.Commands.Platform.Server.DistributedLock
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
