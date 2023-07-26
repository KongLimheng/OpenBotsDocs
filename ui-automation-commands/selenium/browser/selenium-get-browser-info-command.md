<!--TITLE: Selenium Get Browser Info Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Selenium\Browser group. -->
[Go To Automation Commands Overview](/automation-commands)


# Selenium Get Browser Info Command


## What does this command do?
This command retrieves information from a Selenium web browser session.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Browser Instance Name|Enter the unique instance that was specified in the **Create Browser** command.|MyBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Info Property|Indicate which info property to retrieve.|||
|Output Info Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SeleniumGetBrowserInfoCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Selenium.Browser
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
