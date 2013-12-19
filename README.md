# Iterm to Sublime Alfred Workflow


Alfred workflow to add the current iTerm directory as a folder in the Sublime Text project window.

## Set up


Make sure you have a directory to link Sublime to in your user's home folder. I like to use `/bin`  

```
mkdir -p ~/bin
```
Create a symlink to the Sublime executable if you don't have one already.  

```
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl 
```

## Usage
Install the [workflow](https://raw.github.com/kevinSuttle/alfred-iterm-sublime/master/iTermSublimeText.alfredworkflow) and enter `is` as a keyword:

![Finder → Terminal](https://raw.github.com/kevinSuttle/alfred-iterm-sublime/master/screenshot.png)

Hat tip
-------

This workflow was inspired by [LeEnno's TerminalFinder workflow](https://github.com/LeEnno/alfred-terminalfinder "LeEnno/AlfredWorkflows · GitHub").