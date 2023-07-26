<!--TITLE: Work Queue Item Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Queue Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Work Queue Item Command


## What does this command do?
This command gets and locks a Queue Item from an existing Queue in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Queue Name|Enter the name of the Queue.|"Name" \|\| vQueueName|Queue Item Text/Json values are stored in the 'DataJson' property of a Queue Item.
If a Queue has no workable items, the output value will be set to null.|
|Queue Item (Optional)|Enter a Queue Item variable.|vQueueItem|When left blank, the highest priority and/or oldest Queue Item will be worked.|
|Save Attachments|Specify whether to save the Queue Item attachments to a local directory.|||
|Output Folder Path|Enter or select the path to the directory to store the attachments in.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|Decryption Key (Optional)|If Queue Item is encrypted, provide a base64 string representing the key to use for decryption.|"dGVzdA=="\|\| vKey|RSA keys should be provided in PEM format.|
|Should Poll|Specify whether to poll the next Queue Item in the Queue to be worked.||Selecting 'Yes' will continuously check to see if a Queue Item in the Queue is ready to be worked. Selecting 'No' will only work one Queue Item at a time.|
|Continue Polling|Specify whether to continue polling for new Queue Items.|true \|\| vContinuePolling|This variable value can be changed at runtime to continue or stop polling at any time before the timeout.|
|Polling Interval (Seconds)|Specify the interval to poll for a new Queue Item.|30 \|\| vSeconds||
|Timeout (Minutes)|Specify how many minutes to wait to poll for a Queue Item.|0 \|\| 15 \|\| vMinutes|Setting a timeout of 0 would continuously poll until the value for 'Continue Polling' is set to false.|
|Output Queue Item Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: WorkQueueItemCommand
Parent Namespace: OpenBots.Commands.Platform.Server.QueueItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
