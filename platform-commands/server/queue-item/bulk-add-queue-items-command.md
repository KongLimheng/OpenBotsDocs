<!--TITLE: Bulk Add Queue Items Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Queue Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Bulk Add Queue Items Command


## What does this command do?
This command adds many Queue Items to an existing Queue in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Queue Items|Enter the Queue Items to add to the Queue.|vQueueItem1 \|\| new List<OBQueueItem>() { vQueueItem1, vQueueItem2 } \|\| vList|Queue Item objects are created using CreateQueueItemCommand.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: BulkAddQueueItemsCommand
Parent Namespace: OpenBots.Commands.Platform.Server.QueueItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
