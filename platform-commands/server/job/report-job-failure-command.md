<!--TITLE: Report Job Failure Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Job group. -->
[Go To Automation Commands Overview](/automation-commands)


# Report Job Failure Command


## What does this command do?
This command stores an exception type and message that are reported to the server at the end of a successful Job.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Exception Type|Select the appropriate exception type to report.|||
|Exception Message|Enter a custom exception message.|"A Custom Message" \|\| vExceptionMessage|The selected exception with this custom message will be thrown.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ReportJobFailureCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Job
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
