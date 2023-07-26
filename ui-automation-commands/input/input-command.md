<!--TITLE: Input Command -->
<!-- SUBTITLE: a command in the UI Automation Commands\Input group. -->
[Go To Automation Commands Overview](/automation-commands)


# Input Command


## What does this command do?
This command provides the user with a form to input and store a collection of data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Header Name|Define the header to be displayed on the input form.|"Please Provide Input" \|\| vHeader||
|Input Directions|Define the directions to give to the user.|"Directions: Please fill in the following fields" \|\| vDirections||
|Input Parameters (Optional)|Define the required input parameters.|[TextBox \| "Name" \| "500,100" \| "John" \| vName]
[CheckBox \| "Developer" \| "500,30" \| "True" \| vDeveloper]
[ComboBox \| "Gender" \| "500,30" \| "Male,Female,Other" \| vGender]||
|Send Notification|Select whether to send a notification or to just allow for normal execution to occur.||In the case of 'Yes', a notification will be sent to OpenBots Assistant or Business Center.|
|Notification Timeout|Specify how many seconds to wait for a response to the notification. After the specified time,
the notification will be cleared out and script execution will resume.|0 \|\| 5 \|\| vSeconds||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: InputCommand
Parent Namespace: OpenBots.Commands.UIAutomation.Input
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
