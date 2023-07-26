<!--TITLE: Native Browser Legacy Click Element Command -->
<!-- SUBTITLE: a command in the Native Browser Commands\Legacy\Element group. -->
[Go To Automation Commands Overview](/automation-commands)


# Native Browser Legacy Click Element Command


## What does this command do?
This command performs a click on a specified element in a browser.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Native Browser Instance Name|Enter the unique instance that was specified in the **Create Browser** command.|MyNativeBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Element Search Parameter|Use the Element Recorder to generate a listing of potential search parameters.Select the specific search type(s) that you want to use to isolate the element on the web page.|XPath : "//*[@id='features']/div[2]/div/h2/div[" + var1 + "]/div"<br>Relative XPath : //*[@id='features']<br>ID: "1"<br>Name: "my" + var2 + "Name"<br>Tag Name: "h1"<br>Class Name: "myClass"<br>CSS Selector: "[attribute=value]"<br>Link Text: "https://www.mylink.com/"|If multiple parameters are enabled, an attempt will be made to find the element(s) that match(es) all the selected parameters.|
|Click Button|Please specify the mouse button used for the click action.|||
|Click Type|Please specify how an element should be clicked.||If selected, *Simulate Click* will simulate a background click using javascript. Otherwise it will be a regular mouse click.|
|Open Link Option|Please specify where to open a link on a webpage.||This will only affect elements that contain a link.|
|New Native Browser Instance Name|Enter a unique name that will represent the application instance.|MyNativeBrowserInstance|This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|
|X Adjustment|Enter the value for adjusting the horizontal coordinate of the mouse.|0 \|\| -50 \|\| 50 \|\| vXAdjustment|This number will be added to the horizontal axis pixel location of the provided element to adjust click position.|
|Y Adjustment|Enter the value for adjusting the vertical coordinate of the mouse.|0 \|\| -50 \|\| 50 \|\| vYAdjustment|This number will be added to the vertical axis pixel location of the provided element to adjust click position.|
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: NativeBrowserLegacyClickElementCommand
Parent Namespace: OpenBots.Commands.NativeBrowser.Legacy.Element
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
