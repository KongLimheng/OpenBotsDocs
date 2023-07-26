<!--TITLE: Native Browser Create Application Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Desktop\Native Browser group. -->
[Go To Automation Commands Overview](/automation-commands)


# Native Browser Create Application Command


## What does this command do?
This command creates a new native browser session to enable automation for websites.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Native Browser Instance Name|Enter a unique name that will represent the application instance.|MyNativeBrowserInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Browser Engine Type|Select the browser engine to execute the Native automation with.|||
|URL|Enter the URL that you want the browser instance to navigate to.|"https://mycompany.com/orders" \|\| vURL|This input is optional.|
|Window State|Select the window state that the browser should start up with.|||
|Disable Download Shelf|Select whether to disable the gray download shelf at the bottom of every window.|||
|Command Line Arguments (Optional)|Select command line arguments to be passed while opening browser.|"--incognito" \|\| vCommandLineArguments|This input is optional.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: NativeBrowserCreateApplicationCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Desktop.NativeBrowser
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
