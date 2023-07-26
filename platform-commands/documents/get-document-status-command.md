<!--TITLE: Get Document Status Command -->
<!-- SUBTITLE: a command in the Platform Commands\Documents group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Document Status Command


## What does this command do?
This command retrieves the current status of the document being processed. It can wait for the document's completion.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Task Id|Task Identifier that was provided while submiting the document.|new Guid("13db91cf-1f65-4a14-a1cc-bf7aff751b83") \|\| vTaskId||
|Await Completion|Define if the activity should wait until the document processing is completed. Defaults to False. Awaiting queries the service for status every 10 seconds until completed.|true \|\| vAwaitCompletion||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Output Document Status Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output IsCompleted Bool Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output HasError Bool Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output IsCurrentlyProcessing Bool Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Output IsSuccessful Bool Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GetDocumentStatusCommand
Parent Namespace: OpenBots.Commands.Platform.Documents
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
