<!--TITLE: Parse JSON Model Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\JSON group. -->
[Go To Automation Commands Overview](/automation-commands)


# Parse JSON Model Command


## What does this command do?
This command runs a number of queries on a JSON Object and saves the results in the specified List variables.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|JSON|Provide a variable or JSON object value.|@"{animals: ['cat', 'dog']}" \|\| vJsonObject|Providing data of a type other than a 'JSON Object' will result in an error.|
|JObject Parameters|Specify JSON Selector(s) (JPath) and Output Variable(s).|["$.animals.length" \| vOutputList] \|\| ["animals" \| vOutputList] \|\| [vSelector \| vOutputList]|'$.animals.length' is a JSON Selector to query on an inputted JSON Object and store its results in vOutputList.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: ParseJSONModelCommand
Parent Namespace: OpenBots.Commands.DataManipulation.JSON
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
