So when i started this project I figured that I would do something extra to
incorperate extra implentation to show that I know most of CS 2...
These are the extra things that I have implemented...
----------GUI-----------------
I made this program using c# and windows form with a little bit
of .NET, I made 4 button objects, 2 picture box objects, a few text
and labels and a listBox object.
I used the listBox object to show my debugging method as it's easier
to manage and scroll through.
I used the second picture box to display the gif and it gets disposed of
when one of the four buttons is pressed.
I also made an ico for the ksu logo so the program would look a little bit
nicer.
---------I/O-----------------
I figure that people do not like IO since it could be considered a dangerous
system library, however I needed bitmaps for drawing out the array on a pictureBox.
So what I did is implement a function that takes an array of colors and store all
the data including a format that allows the user to copy and paste a file into their
code to allow them to have bitmaps without using IO.

EX:star.SetPixel(0,0,Color.FromArgb(0,0,0,0));

This is repeated a couple of hundreds of times. All of this data is included in the method
formBitmapsFromData();
--------GRAPHICS---------------
in order to prevent memory leakage every time the background image is refreshed, it has to be
disposed of first in order to prevent the build up of memory. I also have it set so there is no
need for bitmaps to have attachments in the IO side of things with the color for pixels already
being stored in the program. There are also no memory leaks for the pictureBoxs as whenever a
bitmap is assigned to the background image it properly gets rid of the previous one.
--------NESTED FOR LOOPS-------
in order to get each x in y, i had to use nested for loops for getting the colors in the bitmap
array and to set the colors in the bitmap array. I also had to use nested loops in order
figure out how to arrange each star and line pattern.
--------USER INTERFACE---------
The user interface is pretty simple with the main purpose of the lab being in the front and 
using a simple checkBox in order to show the extra functions that I added onto the application,
also being shown is the debugging method that I used(Not alot since it was a pretty simple task).
 