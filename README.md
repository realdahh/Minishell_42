# Minishell_42
| function        | Description
|-----------------|--------------------------------------------------------|
|rl_clear_history |This function clears the entire history list maintained by Readline. The history list stores previously entered commands, and can be accessed using the arrow keys or other similar keybindings|
|rl_on_new_line  |This function tells Readline that a new line of input is about to be entered. It is typically called after the user presses the Enter key to submit a command|
|rl_replace_line |This function replaces the entire contents of the input line with the specified text. The clear_undo parameter determines whether the undo buffer should be cleared|
|rl_redisplay|This function updates the display to reflect changes made to the input line. It is typically called after rl_replace_line() to ensure that the new line of text is properly displayed|
|add_history|is used to add a command to the history list.|
|access|is used to check whether the calling process has permission to access a particular file or directory|
