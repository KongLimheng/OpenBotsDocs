<!--TITLE: Get Queue Items Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Queue Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Queue Items Command


## What does this command do?
This command gets a list of up to 100 Queue Items from OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Queue Name|Enter the name of the Queue.|"Name" \|\| vQueueName||
|Queue Item Name (Optional)|Enter the name of the Queue Item.|"Name" \|\| vQueueItemName||
|Queue Item State (Optional)|Specify the state of the Queue Item.||To work a specific Queue Item from the list, the state should be set to 'New.' To return all Queue Items, use 'None.'|
|Output Queue Item List Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetQueueItemsCommand
Parent Namespace: OpenBots.Commands.Platform.Server.QueueItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
