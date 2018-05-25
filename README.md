Jump Script for BASH
====================

The j function (which stands for 'jump') lets you create short-cut references to any directory and then jump to it later without having to type long, arduous directory paths over and over again.

It has 2 primary functions:
   
  * j -m tagname  # creates a jumpmark for the current directory
  * j tagname     # jump to the directory associated with tagname
 
Install the tool by naming this file something like .bash_jump in your home
directory, and then adding the following line to your .bashrc:

   . ~/.bash_jump
 
This simple trick saves me several hundred keystrokes per day. 
If you want to know just how much it's saving you, try: j -s
 
Jefferson Smith\
Exploring the intersection between software, creativity theory, and fiction at: http://creativityhacker.ca
