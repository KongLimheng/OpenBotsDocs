<!--TITLE: Generate Strong Password Command -->
<!-- SUBTITLE: a command in the Authentication Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Generate Strong Password Command


## What does this command do?
This command generates a strong password.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Password Length|Provide the length of the generated password.|12 \|\| vLength||
|Include Symbols|When selected, symbols will be included in the password.|||
|Include Numbers|When selected, numbers will be included in the password.|||
|Include Lowercase Characters|When selected, lowercase characters will be included in the password.|||
|Include Uppercase Characters|When selected, uppercase characters will be included in the password.|||
|Include Ambiguous Characters|When selected, ambiguous characters will be included in the password.|||
|Output Password Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GenerateStrongPasswordCommand
Parent Namespace: OpenBots.Commands.Authentication
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
