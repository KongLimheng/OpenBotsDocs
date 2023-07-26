<!--TITLE: Update Job With Business Entity Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Job group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Job With Business Entity Command


## What does this command do?
This command associates the current job with Business Center properties from OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Business Entity|Specify the Business Entity you would like to associate with the running job.|"Entity" \|\| vBusinessEntity||
|Business Activity|Specify the Business Activity you would like to associate with the running job.|"Activity" \|\| vBusinessActivity||
|Business Entity Identifier|Specify the Business Entity Identifier you would like to associate with the running job.|"Entity Identifier" \|\| vBusinessEntityId||
|Work Item (Optional)|Enter a Work Item Dictionary variable to associate with the running job.|vWorkItem||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateJobWithBusinessEntityCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Job
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
