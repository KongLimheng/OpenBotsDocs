<!--TITLE: Slides Add Video Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Slides\Content group. -->
[Go To Automation Commands Overview](/automation-commands)


# Slides Add Video Command


## What does this command do?
This command adds a Video to a slide.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Slides Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySlidesInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Slide Options|Indicate the input option for target slide.|||
|Slide Id|Enter the Id of the slide where the video will be added.|_A1 \|\| vSlideId||
|Slide Location|Indicate the position of the slide where the image will be added.|||
|Slide Index|Enter the index of the slide where the image will be added.|2 \|\| vSlideIndex||
|Translate X|Enter the X coordinate translation element.|30.0 \|\| vTranslateX||
|Translate Y|Enter the Y coordinate translation element.|30.0 \|\| vTranslateY||
|Source|Select the video source.|||
|Video Id|Enter the video source's unique identifier for this video.|"7U3axjORYZ0" \|\| "1xCgQLFTJi5_Xl8DgW_lcUYq5e-q6Hi5Q" \|\| vVideoId|"e.g. For YouTube video https://www.youtube.com/watch?v=7U3axjORYZ0, the ID is 7U3axjORYZ0. For a Google Drive video https://drive.google.com/file/d/1xCgQLFTJi5_Xl8DgW_lcUYq5e-q6Hi5Q the ID is 1xCgQLFTJi5_Xl8DgW_lcUYq5e-q6Hi5Q. To access a Google Drive video file, you might need to add a resource key to the HTTP header for a subset of old files. For more information, see Access link - shared files using resource keys.|
|Output ObjectId Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SlidesAddVideoCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Slides.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
