<!--TITLE: Selenium Create Browser Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Selenium group. -->
[Go To Automation Commands Overview](/automation-commands)


# Selenium Create Browser Command


## What does this command do?
This command creates a new Selenium web browser session which enables automation for websites.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Browser Instance Name|Enter a unique name that will represent the application instance.|MyBrowserInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|Browser Engine Type|Select the browser engine to execute the Selenium automation with.||The recommended browser option for web automation is Chrome.|
|URL (Optional)|Enter the URL that you want the selenium instance to navigate to.|"https://mycompany.com/orders" \|\| vURL|This input is optional.|
|Window State|Select the window state that the browser should start up with.|||
|Selenium Command Line Options (Chrome - Optional)|Select options to be passed to the Selenium command.|@"user-data-dir=c:\users\public\SeleniumOpenBotsProfile" \|\| vOptions|This input is optional.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SeleniumCreateBrowserCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Selenium
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
