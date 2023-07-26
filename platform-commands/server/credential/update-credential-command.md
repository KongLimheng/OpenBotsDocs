<!--TITLE: Update Credential Command -->
<!-- SUBTITLE: a command in the Platform Commands\Server\Credential group. -->
[Go To Automation Commands Overview](/automation-commands)


# Update Credential Command


## What does this command do?
This command updates a Credential in OpenBots Server.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Credential Name|Enter the name of the Credential.|"Name" \|\| vCredentialName||
|Credential Provider|Specify the provider type of the Credential.|||
|Credential Username (Optional)|Enter the Credential username.|"john@openbots.com" \|\| vUsername \|\| vCredential.Username||
|Credential Password|Enter the Credential password.|vPassword \|\| vCredential.Password|Password input must be a SecureString variable.Password is required for TOTP but optional for Application, Active Directory, and Machine Account.|
|Credential Public Key (Optional)|Enter the Credential public key.|"65cdf86a" \|\| vPublicKey \|\| vCredential.PublicKey||
|Credential Private Key (Optional)|Enter the Credential private key.|vPrivateKey \|\| vCredential.PrivateKey|Private Key input must be a SecureString variable.|
|Output Credential Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: UpdateCredentialCommand
Parent Namespace: OpenBots.Commands.Platform.Server.Credential
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
