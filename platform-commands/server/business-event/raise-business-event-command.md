<!--TITLE: Raise Business Event Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Business Event group. -->
[Go To Automation Commands Overview](/automation-commands)


# Raise Business Event Command


## What does this command do?
This command raises a Business Event in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Business Event Name|Enter the name of the Business Event.|"Event Name" \|\| vBusinessEventName||
|Entity Name|Enter an Entity name for the Business Event.|"Entity Name" \|\| vEntityName|If no value is entered, the Business Event's default Entity name will be used by default.|
|Entity Identifier|Enter an Entity id for the Business Event.|"012345" \|\| vEntityId||
|Message|Enter a message for the Business Event.|"Message" \|\| vMessage||
|Payload JSON|Enter a payload JSON for the Business Event.|"{ \"key1\": \"value1\", \"key2\": \"value2\" }" \|\| vPayloadJson|If no value is entered, the Business Event's default payload JSON will be used by default.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RaiseBusinessEventCommand
Parent Namespace: OpenBots.Commands.Platform.Server.BusinessEvent
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
