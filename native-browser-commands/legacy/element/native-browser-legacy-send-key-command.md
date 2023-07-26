<!--TITLE: Native Browser Legacy Send Key Command -->
<!-- SUBTITLE: a command in the Native Browser Commands\Legacy\Element group. -->
[Go To Automation Commands Overview](/automation-commands)


# Native Browser Legacy Send Key Command


## What does this command do?
This command sends a key(s) to a specified input in a browser.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Native Browser Instance Name|Enter the unique instance that was specified in the **Create Browser** command.|MyNativeBrowserInstance|Failure to enter the correct instance name or failure to first call the **Create Browser** command will cause an error.|
|Element Search Parameter|Use the Element Recorder to generate a listing of potential search parameters.Select the specific search type(s) that you want to use to isolate the element on the web page.|XPath : "//*[@id='features']/div[2]/div/h2/div[" + var1 + "]/div"<br>Relative XPath : //*[@id='features']<br>ID: "1"<br>Name: "my" + var2 + "Name"<br>Tag Name: "h1"<br>Class Name: "myClass"<br>CSS Selector: "[attribute=value]"<br>Link Text: "https://www.mylink.com/"|If multiple parameters are enabled, an attempt will be made to find the element(s) that match(es) all the selected parameters.|
|Keystroke Parameters|Define the parameters for the keystroke actions.|[Enter [Return] \| Key Press (Down + Up)]||
|Raise All Keys|Select whether to return all keys to the 'UP' position after execution.|||
|Timeout (Seconds)|Specify how many seconds to wait before throwing an exception.|30 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: NativeBrowserLegacySendKeyCommand
Parent Namespace: OpenBots.Commands.NativeBrowser.Legacy.Element
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
