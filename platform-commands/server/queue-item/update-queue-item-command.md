<!--TITLE: Update Queue Item Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Queue Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Queue Item Command


## What does this command do?
This command updates a Queue Item's message and/or adds file attachments in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Queue Item|Enter a Queue Item variable.|vQueueItem||
|Message (Optional)|Enter the message to be updated.|"Queue item has been updated" \|\| vMessage||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Encryption Key (Optional)|Provide a base64 string representing the key to use for encryption.|"dGVzdA==" \|\| vKey|RSA keys should be provided in PEM format.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateQueueItemCommand
Parent Namespace: OpenBots.Commands.Platform.Server.QueueItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
