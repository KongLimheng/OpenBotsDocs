<!--TITLE: Update Work Item Command -->
<!-- SUBTITLE: a command in the Platform Commands\Business Center\Work Item group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Work Item Command


## What does this command do?
This command updates a Work Item in an existing Work Queue in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Work Item|Enter a Work Item variable.|vWorkItem||
|Work Queue Name (Optional)|Enter the name of an existing Work Queue.|"Name" \|\| vWorkQueueName||
|Work Goal Name (Optional)|Enter the name of an existing Work Goal.|"Name" \|\| vWorkGoalName|If you would like to run an automation from this work item, a Work Goal needs to be assigned|
|Work Item Name (Optional)|Enter the name of the new Work Item.|"Name" \|\| vWorkItemName|Work Item name must be between 3 and 100 characters consisting of letters, numbers, underscores, hyphens, and/or periods.|
|Work Item Status (Optional)|Specify the new status of the Work Item.|||
|Due On (Optional)|Determine when the Work Item will be due to be completed.|new DateTime(2020, 2, 20) \|\| vDate \|\| DateTime.Now|If not provided, the Work Item will have no completion date.|
|Project Number (Optional)|Specify the project number.|"12345" \|\| vProjectNumber||
|Business Entity (Optional)|Specify the business entity.|"Entity" \|\| vBusinessEntity||
|Business Entity Identifier (Optional)|Specify the business entity identifier.|"Entity Identifier" \|\| vBusinessEntityId||
|Business Activity (Optional)|Specify the business activity.|"Activity" \|\| vBusinessActivity||
|Description (Optional)|Specify the description.|"Description" \|\| vDescription|Support for Markdown is enabled for the Work Item description.|
|Source (Optional)|Specify the source.|"Source" \|\| vSource||
|Priority (Optional)|Specify the priority of the Work Item.|||
|Assigned To (Optional)|Assign the Work Item to a user.|"test@test.com" \|\| vAssignedTo||
|Reference Number (Optional)|Specify the reference number.|"12345" \|\| vReferenceNumber||
|Reference Type (Optional)|Specify the reference type.|"Reference Type" \|\| vReferenceType||
|Attachment File Path(s) (Optional)|Enter the file path(s) of the file(s) to attach.|@"C:\temp\myFile1.xlsx" \|\| new List<string>() { @"C:\temp\myFile1.xlsx", @"C:\temp\myFile2.xlsx" } \|\| vFileList||
|Output Work Item Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateWorkItemCommand
Parent Namespace: OpenBots.Commands.Platform.BusinessCenter.WorkItem
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
