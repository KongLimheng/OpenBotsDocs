<!--TITLE: Get Form Responses Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Forms group. -->

[Go To Automation Commands Overview](/automation-commands)

# Get Form Responses Command

## What does this command do?

This command gets a list of responses from a Google Form.

## Command Parameters

| Parameter Question                                                                                  | What to input                                                                                                        | Sample Data                                                                               | Remarks                                                                                                            |
| --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Google Workspace Instance Name                                                                      | Enter the unique instance that was specified in the **Create Session** command.                                      | MyGoogleWorkspaceInstance                                                                 | Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error. |
| Form Id                                                                                             | Enter the id of the form to get responses from.                                                                      | "55BBAC51A4E4017D!104" \|\| vFormId                                                       | This is an Id of a form DriveItem, it can be fetched using "Find Drive Items".                                     |
| Filter Query (Optional)                                                                             | Enter a filter query to retrieve specified responses.                                                                | "2014 - 10 - 02T15: 01:23Z" and "2014 - 10 - 02T15: 01:23.045123456Z" \|\| vMyFilterQuery |                                                                                                                    |
| Output Response List Variable                                                                       | Create a new variable or select a variable from the list.                                                            | vUserVariable                                                                             | New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.                              |
| The 'Google.Apis.Forms.v1.Data' assembly reference must be added to 'Imports' to access this type.. |
| Private (Optional)                                                                                  | Optional field to mark the command as private (data sensitive) in order to avoid its logging.                        |                                                                                           |                                                                                                                    |
| Remote (Optional)                                                                                   | Optional field to mark the command as remote in order to execute it on a remote machine.                             |                                                                                           |                                                                                                                    |
| Error Handling                                                                                      | Optional field for how to handle errors encountered.                                                                 |                                                                                           |                                                                                                                    |
| Comment (Optional)                                                                                  | Optional field to enter a custom comment which could potentially describe this command or the need for this command. | I am using this command to...                                                             |                                                                                                                    |
