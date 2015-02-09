Scratch Hue Extension
=====================

Installation & Setup
--------------------

1. Install the Scratch 2 Offline Editor. Instructions are here:
   http://scratch.mit.edu/scratch2download/
2. Install the Scratch Hue Extension by running these commands in Terminal.
   When you are asked to enter your password, you will not see the letters
   you type appear on the screen. This is normal.

        sudo easy_install pip
        sudo pip install scratch_hue_extension

4. Start the Scratch Hue Helper by running this command in Terminal. Right
   before you run this for the first time, press the button on the Hue Base
   Station in Room 6.

        scratch_hue_helper

5. Start the Scratch 2 Offline Editor. Then, holding down the shift key, click 
   on the "File" menu and select "Import Experimental HTTP Extension." You will 
   be asked to select a file; choose the file called "Scratch Hue Extension.s2e"
   on your Desktop.

6. Now you can write programs that interact with the lights in Room 6! Look in
   the "More Blocks" pane to see the available commands.


About
-----

This package provides a helper app to allow the Scratch 2 Offline Editor to 
control a set of Philips Hue lights. Currently, only three lights are supported,
but more could be added  by configuration if necessary. Instructions for implementing 
a helper app are at http://wiki.scratch.mit.edu/w/images/ExtensionsDoc.HTTP-9-11.pdf.

This extension was written by Chris Proctor, who teaches 6th and 7th grade 
Computer Science at the Girls' Middle School in Palo Alto, CA. His students 
are now in control of the lights. 
