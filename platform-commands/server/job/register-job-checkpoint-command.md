<!--TITLE: Register Job Checkpoint Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Job group. -->
[Go To Automation Commands Overview](/automation-commands)


# Register Job Checkpoint Command


## What does this command do?
This command registers a checkpoint on the OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Checkpoint Name|Enter the name of the new Checkpoint.|"CheckpointName" \|\| vCheckpointName||
|Message (Optional)|Enter a message for the new Checkpoint.|"Your Message" \|\| vMessage||
|Iterator (Optional)|Enter the Iterator name|"Name" \|\| vIterator||
|Iterator Value (Optional)|Enter a value for the new Checkpoint.|"Value" \|\| vIteratorValue||
|Iterator Position (Optional)|Enter the Iterator Position for the new Checkpoint.|3 \|\| vIteratorPosition||
|Iterator Count (Optional)|Enter the Iterator Count for the new Checkpoint.|5 \|\| vIteratorCount||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RegisterJobCheckpointCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Job
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
