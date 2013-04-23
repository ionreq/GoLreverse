GoLreverse
==========

calculate previous generations for Conway's Game of Life

This is a program for calculating previous configurations for a given configuration in Conway's Game of Life.
It is written in Dyalog APL.
You can run it anytime!
Download the demo version of Dyalog APL here: www.dyalog.com
This will also install an APL font, that you can use in text editors.
There's an abundance of help, tutorials and examples available.
When you are familiar with APL after a few hours it should be no problem for you to input your desired configuration for which you want to know the previous ones.
They are small, 4x4 upto 13x13, it's more a proof of concept.

How to run it:

Start Dyalog APL.
Enter ")copy dfns display", we need this standard display function.
Enter ")ed x" in the clear workspace, this opens the editor.
In the editor menu go to "File/Change type or name...".
Select the "Class or Namespace" radio button and press OK.
Now delete the "x" and paste the whole source code file from a text editor like Notepad or a browser into the editor window.
Press the big "X" button to save (or "fix") the source code and close the editor window.
Now you have created the golreverse namespace, but we are still in the root namespace.
To change to the new namespace enter ")cs golreverse".
Now you can run the program by simply entering "main".
And you can edit any function by entering ")ed functionname" while also having access to all the other functions.
Finally, save the whole workspace as a Dyalog workspace file, in order to have the display function always ready at start.

If there's an error "WS FULL", you can increase the workspace memory size.
Go to "Options/Configuration/Workspace" and enter a bigger workspace size.
You have to restart Dyalog APL for this to take effect.

Have fun!
