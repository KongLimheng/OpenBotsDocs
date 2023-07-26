<!--TITLE: Raise Alert Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Alert group. -->
[Go To Automation Commands Overview](/automation-commands)


# Raise Alert Command


## What does this command do?
This command raises an Alert in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Alert Type|Select the type of Alert.|||
|Business Entity Name (Optional)|Enter the name of the Business Entity.|"Entity Name" \|\| vBusinessEntity||
|Business Entity Identifier (Optional)|Enter an identifier for the Business Entity.|"012345" \|\| vBusinessEntityIdentifier||
|Alert Severity|Select the level of severity for the Alert.|||
|Alert Title|Enter the title of the raised Alert.|"Title Name" \|\| vTitle||
|Description (Optional)|Enter a description for the Alert.|"Description" \|\| vDescription||
|Payload JSON (Optional)|Enter a payload JSON for the Alert.|"{ \"key1\": \"value1\", \"key2\": \"value2\" }" \|\| vPayloadJson||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: RaiseAlertCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Alert
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
