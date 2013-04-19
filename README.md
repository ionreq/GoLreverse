GoLreverse
==========

calculate previous generations for Conway's Game of Life

This is a program for calculating previous configurations for a given configuration in Conway's Game of Life.
It is written in Dyalog APL.
You can run it anytime!
Download the demo version of Dyalog APL here: www.dyalog.com
This will also install an ALP font, that you can use in text editors.
There's an abundance of help, tutorials and examples available.
When you are familiar with APL after a few hours it should be no problem for you to input your desired configuration for which you want to know the previous ones.
They are small, 4x4 upto 13x13, it's more a proof of concept.
There's a torus wrap at the edges, which eliminates many configurations.
The stable 2x2 block in a 4x4 torus space has 7 previous configurations.

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
And you can edit any function by entering ")ed functionname" while also haveing access to all the other functions.
Finally, save the whole workspace as a Dyalog workspace file, in order to have the display function always ready at start.

If there's an error "WS FULL", you can increase the workspace memory size.
Go to "Options/Configuration/Workspace" and enter a bigger workspace size.
You have to restart Dyalog APL for this to take effect.
If you still have trouble finding a solution, and your array is higher than wide,
you can try computing a solution for the transposed array (so that it is wider than high).
Because the algorithm as it is, first processes all the rows until only one row is left.
Then many configurations fall away due to the periodic boundary conditions.
After that it processes the columns.
So there's a difference there in how many configurations are left, and one case may use less memory than the other.

Have fun!

