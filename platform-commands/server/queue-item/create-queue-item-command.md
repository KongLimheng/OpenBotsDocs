<!--TITLE: Create Queue Item Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Queue Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Queue Item Command


## What does this command do?
This command adds a Queue Item to an existing Queue in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Queue Name|Enter the name of the existing Queue.|"Name" \|\| vQueueName||
|Queue Item Name|Enter the name of the new Queue Item.|"Name" \|\| vQueueItemName|Queue Item name must be between 3 and 100 characters consisting of letters, numbers, underscores, hyphens, and/or periods.|
|Encrypt Queue Item|Specify whether to encrypt the queue item text value and any attachments.|||
|Encryption Algorithm|Select the encryption algorithm to utilize.|||
|Encryption Key|Provide a base64 string representing the key to use for encryption.|"dGVzdA==" \|\| vKey|RSA keys should be provided in PEM format.|
|Source (Optional)|If the item being enqueued is a business event, define the source of the event.
This is typically the system name that caused the business event.|"Loan Origination System" \|\| "Lead Generation System" \|\| vSource||
|Event (Optional)|If the item being enqueued is a business event, define the name of the event.
This is typically what has occured.|"Payment Rejected" \|\| "New Employee Onboarded" \|\| vEvent||
|Expire On (Optional)|Determine when the queue item will expire.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now|If not provided, the queue item will have no expiration time.|
|Postpone Until (Optional)|Determine when the queue item will be postponed until.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now|If not provided, the queue item can be worked on immediately.|
|Queue Item Type|Specify the type of the new Queue Item.|||
|Json Type|Specify the type of the Json.|"Company" \|\| vJsonType||
|Queue Item Value|Enter the value of the new Queue Item.|"Value" \|\| vQueueItemValue||
|Priority|Enter a priority value between 0-100.|100 \|\| vPriority|Priority determines the order in which Queue Items will be worked. If priority is set to
the same value for each Queue Item, all Queue Items will be ordered by time of creation.|
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Add to Queue|Specify whether to add to the Queue or save to a QueueItem object.|||
|Output Queue Item Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: CreateQueueItemCommand
Parent Namespace: OpenBots.Commands.Platform.Server.QueueItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
