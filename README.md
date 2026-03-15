# ki-tutor

## For Vim/Neovim users

### Open and close Ki

This is simple tutorial aimed at Vim/Neovim users.

Ki as a standalone program works in a terminal. Ki can also be embedded in other applications.

To open Ki Editor, open some terminal, type `ki` and press `Enter`.

To close Ki: `Space ⇒ Editor (j) ⇒ Quit No Save (v)`.

Now you have the basics.

## Add some text and save the file

Let's edit some file. In terminal type `ki file.txt` and press Enter.

Ki, like Vim/Neovim, has normal mode and insert mode. Default mode is normal mode.

You can see that in status bar which says `NORM`.

To enter some text, switch to insert mode by pressing `;`.

Now status bar at the bottom left, says `INST` which means insert mode.

Now type some text, press `Esc`. You have exited insert mode.

To save the file, just press Enter.

### Navigating between lines and status bar

Now press `;` to switch to insert mode. Press `Enter` to add new line, and add some text.

Now you have two lines. You are doing great.

Now I want you to press `Esc` to switch to normal mode.

Press `j` to go to previous line. Now press `l` to go to next line.

In Ki, you navigate lines by default. You can see that in status bar at the bottom right which says `LINE`.

## Navigate between characters

You are in normal mode `NORM`. To navigate between characters, press `q`.

In status bar at the bottom right you will see `CHAR`, which means you are navigating between characters.

Now press `l` to go to next characters or `j` to go to previous character.

Now navigate to center of some word, press `;` and enter some text.

Go to normal mode by pressing `Esc` and save changes by pressing `Enter`.