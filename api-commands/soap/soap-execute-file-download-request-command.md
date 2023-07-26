<!--TITLE: SOAP Execute File Download Request Command -->
<!-- SUBTITLE: a command in the API Commands\SOAP group. -->
[Go To Automation Commands Overview](/automation-commands)


# SOAP Execute File Download Request Command


## What does this command do?
This command calls a SOAP API with a specific HTTP method expecting a file download.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Download URL|Provide the URL for the download.|"https://example.com" \|\| vMyUrl||
|Request Headers (Optional)|Specify request headers.|["Header Name" \| "Header Value"] \|\| [vHeaderName \| vHeaderValue]||
|Method Type|Select the necessary method type.|||
|Request Body Format|Select the necessary request format.|||
|Body Parameters|Specify request body parameters.|["Parameter Name" \| "Parameter Value"] \|\| [vParamName \| vParamValue]||
|Raw Data|Provide raw body data.|vJsonVariable \|\| "{ propName: \"propValue\" }"||
|Output Folder Path|Provide the folder path to save to.|@"C:\temp" \|\| ProjectPath + @"\temp" \|\| vDirectoryPath||
|File Name|Enter or select the name of the file to save.|"myFile.txt" \|\| vFileName||
|Authentication Type|Select the necessary authenticator.|||
|Username|Provide the username required for authentication.|"myRobot@openbots.ai" \|\| vUsername \|\| vCredential.Username||
|Password|Provide the password required for authentication.|vPassword \|\| vCredential.Password|Password input must be a SecureString variable.|
|Bearer Token|Provide the bearer token required for authentication.|"AbCdEf123456" \|\| vBearerToken||
|Query String Parameters (Optional)|Parameters to append to the request as a query string.|["Parameter Name" \| "Parameter Value"] \|\| [vParamName \| vParamValue]||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SOAPExecuteFileDownloadCommand
Parent Namespace: OpenBots.Commands.API.SOAP
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
