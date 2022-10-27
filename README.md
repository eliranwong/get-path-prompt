# get-path-prompt

source: https://github.com/eliranwong/getpath
'get-path-prompt' prompts terminal users for entry of a file or directory path.

# Recommended:
You can run 'get-path-prompt' with or without prompt_toolkit.
With prompt_toolkit installed, however, you can use all features we will mention below.

To install prompt_toolkit, run:
> pip install prompt_toolkit

Features:
* prompts for a file or folder path entry
* option to define prompt indicator and text colors
* option to check existence of the entered path
* option to create directories if they do not exist
* auto-history-saving - use up or down keys to get previous entered records
* auto-suggestion from history - use right arrow key to complete a suggestion
* auto-completion of file or directory path
* support command 'cd' to change directories
* support command 'ls' to list directory content
* customise cancel entry or allow empty entry to close the prompt
* built-in key bindings - ctrl+q to quit prompt, ctrl+l to list directory content
* confirm if users want to continue if invalid option is entered
* easily integrated into python project,

For example, we integrate this utility into a text editor we developed:

https://github.com/eliranwong/UniqueBible/blob/main/util/terminal_text_editor.py

