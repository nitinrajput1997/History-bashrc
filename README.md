# History-bashrc

To remove command history in Ubuntu, you can follow these steps:

Open a terminal by pressing Ctrl+Alt+T.

Once the terminal is open, type the following command to open the Bash history file in a text editor:

```
vi ~/.bash_history
```

This will open the .bash_history file in the Vim text editor.

In the Vim text editor, you will see a list of all the commands you have executed in the terminal. Delete the lines that contain the commands you want to remove from the history.

After deleting the lines, save and exit the file.

To make sure the changes take effect, you can run the following command to reload the Bash history:

```
history -c && history -r
```

This clears the current history and reloads the modified history file.
