<!--TITLE: Selenium Switch Browser Frame Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Selenium\Browser group. -->
[Go To Automation Commands Overview](/automation-commands)


# Selenium Switch Browser Frame Command


## What does this command do?
This command switches between browser frames provided a valid search parameter.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Browser Instance Name|Enter the unique instance that was specified in the **Create Browser** command.|MyBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Frame Search Type|Select an option which best fits the search type you would like to use.|||
|Frame Search Parameter|Provide the parameter to match (ex. Index, Name or ID).|1 \|\| "name" \|\| vSearchData||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SeleniumSwitchBrowserFrameCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Selenium.Browser
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
