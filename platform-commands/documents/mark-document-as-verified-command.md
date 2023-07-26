<!--TITLE: Mark Document As Verified Command -->
<!-- SUBTITLE: a command in the Platform Commands\Documents group. -->
[Go To Automation Commands Overview](/automation-commands)


# Mark Document As Verified Command


## What does this command do?
This command marks a specific document in a bundle as 'Verified'. The remaining documents typically go for 'Human Review'.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Task Id|Task Identifier that was provided while submitting the document.|new Guid("13db91cf-1f65-4a14-a1cc-bf7aff751b83") \|\| vTaskID||
|Document Id|Document Identifier that was provided while retrieving the processing results.|new Guid("13db91cf-1f65-4a14-a1cc-bf7aff751b83") \|\| vDocumentId||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: MarkDocumentAsVerifiedCommand
Parent Namespace: OpenBots.Commands.Platform.Documents
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
