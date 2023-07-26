<!--TITLE: Set NLG Parameter Command -->
<!-- SUBTITLE: a command in the NLG Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Set NLG Parameter Command


## What does this command do?
This command defines a Natural Language Generation parameter.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|NLG Instance Name|Enter the unique instance that was specified in the **Create NLG Instance** command.|MyNLGInstance|Failure to enter the correct instance name or failure to first call the **Create NLG Instance** command will cause an error.|
|NLG Parameter Type|Select the appropriate Natural Language Generation Parameter.|||
|Input Value|Enter the value that should be associated with the parameter|"Hello" \|\| vValue||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SetNLGParameterCommand
Parent Namespace: OpenBots.Commands.NLG
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
