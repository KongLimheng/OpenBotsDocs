<!--TITLE: Desktop Set Dropdown Option Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Desktop group. -->
[Go To Automation Commands Overview](/automation-commands)


# Desktop Set Dropdown Option Command


## What does this command do?
This command sets the dropdown option of a UI element in a targeted window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Windows Selection Rule|Determine the attribute by which a dropdown option will be selected.||If *Select By Search Parameter*, the selector should include the desired ListItem option.
Otherwise, the selector should point to the dropdown control.|
|Java Selection Rule|Determine the attribute by which a dropdown option will be selected.||If *Select By Search Parameter*, the selector should include the desired ListItem option.
Otherwise, the selector should point to the dropdown control.|
|Browser Selection Rule|Select the method by which the dropdown option should be selected.|||
|Selection Index|Enter the index that will be used to select the option in the dropdown.|0 \|\| vIndex||
|Selection Value|Enter the value that will be used to select the option in the dropdown.|"Hello World" \|\| vText||
|Instance Name (Native Browser Only)|Enter the unique instance that was specified in the **Create Browser** command.|MyNativeBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Element Search Parameter|Utilize the Element Recorder to generate a listing of potential search parameters.|[ "Name" \| "ElementName" ]||
|Data not specified|Data not specified|Data not specified|Data not specified|
|Data not specified|Data not specified|Data not specified|Data not specified|
|Automation Type|Specify the UI automation application type.|||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Wait For Visible|Wait for the targeted element to be active and visible before performing an action|||
|Data not specified|Data not specified|Data not specified|Data not specified|
|Data not specified|Data not specified|Data not specified|Data not specified|
|Data not specified|Data not specified|Data not specified|Data not specified|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DesktopSetDropdownOptionCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Desktop
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
