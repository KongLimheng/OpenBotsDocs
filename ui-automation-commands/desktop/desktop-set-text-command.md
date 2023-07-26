<!--TITLE: Desktop Set Text Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Desktop group. -->
[Go To Automation Commands Overview](/automation-commands)


# Desktop Set Text Command


## What does this command do?
This command sets text in a UI element in a targeted window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Text To Set|Enter the text value to set in the input.|"Hello World" \|\| vText \|\| "Hello World{ENTER}"|Hotkey interpolation only works when activated by *Enable Interpolated Hotkeys*.|
|Input Type|Specify how the text should be set in the element.|||
|Enable Interpolated Hotkeys|Select whether to enable sending hotkeys within the text.|||
|Clear Text|Select whether the element should be cleared before setting text.|||
|Click Element|Select whether the element should be clicked before setting text.|||
|Instance Name (Native Browser Only)|Enter the unique instance that was specified in the **Create Browser** command.|MyNativeBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Element Search Parameter|Utilize the Element Recorder to generate a listing of potential search parameters.|[ "Name" \| "ElementName" ]||
|Data not specified|Data not specified|Data not specified|Data not specified|
|Data not specified|Data not specified|Data not specified|Data not specified|
|Automation Type|Specify the UI automation application type.|||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Wait For Visible|Wait for the targeted element to be active and visible before performing an action|||
|Data not specified|Data not specified|Data not specified|Data not specified|
|Data not specified|Data not specified|Data not specified|Data not specified|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DesktopSetTextCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Desktop
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
