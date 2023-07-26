<!--TITLE: Native Browser Legacy Refresh Tab Command -->
<!-- SUBTITLE: a command in the Native Browser Commands\Legacy\Tab group. -->
[Go To Automation Commands Overview](/automation-commands)


# Native Browser Legacy Refresh Tab Command


## What does this command do?
This command refreshes the currently active browser tab.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Native Browser Instance Name|Enter the unique instance that was specified in the **Create Browser** command.|MyNativeBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: NativeBrowserLegacyRefreshTabCommand
Parent Namespace: OpenBots.Commands.NativeBrowser.Legacy.Tab
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
