<!--TITLE: Google Workspace Create Session Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands group. -->

<!-- [Go To Automation Commands Overview](/automation-commands) -->

# Google Workspace Create Session Command

## What does this command do?

This command creates a Google Workspace session instance.

## Command Parameters

| Parameter Question             | What to input                                                                                 | Sample Data                                                                           | Remarks                                                                                                                                                      |
| ------------------------------ | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Google Workspace Instance Name | Enter a unique name that will represent the application instance.                             | MyGoogleWorkspaceInstance                                                             | This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application. |
| App Name                       | Enter the name of the app asking for consent.                                                 | "My App" \|\| vAppName                                                                |                                                                                                                                                              |
| Credential File Path           | Provide the filepath of the credential file downloaded from the Google Console.               | @"C:\credential.json" \|\| ProjectPath + @"\credential.json" \|\| vCredentialFilePath |                                                                                                                                                              |
| Private (Optional)             | Optional field to mark the command as private (data sensitive) in order to avoid its logging. |                                                                                       |                                                                                                                                                              |
| Remote (Optional)              | Optional field to mark the command as remote in order to execute it on a remote machine.      |                                                                                       |                                                                                                                                                              |
| Error Handling                 | Optional field for how to handle errors encountered.                                          |                                                                                       |                                                                                                                                                              |
