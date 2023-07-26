<!--TITLE: Native Browser Legacy Attach Application Command -->
<!-- SUBTITLE: a command in the Native Browser Commands\Legacy group. -->
[Go To Automation Commands Overview](/automation-commands)


# Native Browser Legacy Attach Application Command


## What does this command do?
This command attaches to an already existing browser to enable automation for websites.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Native Browser Instance Name|Enter a unique name that will represent the application instance.|MyNativeBrowserInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Browser Engine Type|Select the browser engine containing the tab to search for.|||
|Browser Tab Title|Enter the title of the tab to activate.|"OpenBots" \|\| vTabTitle||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: NativeBrowserLegacyAttachApplicationCommand
Parent Namespace: OpenBots.Commands.NativeBrowser.Legacy
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
