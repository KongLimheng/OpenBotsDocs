<!--TITLE: Deserialize XML Command -->
<!-- SUBTITLE: a command in the Data Manipulation Commands\XML group. -->
[Go To Automation Commands Overview](/automation-commands)


# Deserialize XML Command


## What does this command do?
This command deserializes an XML String and returns the resulting XDocument.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|XML String|Provide a variable or XML object value.|@"<note><to>User</to></note>" \|\| vXmlObject|Providing data of a type other than an 'XML Object' will result in an error.|
|Output XDocument Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: DeserializeXMLCommand
Parent Namespace: OpenBots.Commands.DataManipulation.XML
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
