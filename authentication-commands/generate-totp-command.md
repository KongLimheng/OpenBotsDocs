<!--TITLE: Generate TOTP Command -->
<!-- SUBTITLE: a command in the Authentication Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Generate TOTP Command


## What does this command do?
This command generates a time-based one time password.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|TOTP Secret Key|Provide the TOTP secret key as a Base32 encoded string.|"JBSWY3DPEHPK3PXP" \|\| vKey||
|Output TOTP Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: GenerateTOTPCommand
Parent Namespace: OpenBots.Commands.Authentication
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
