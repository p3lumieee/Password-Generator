# Password-Generator
This is a program written in C programming lanuguage.

	 _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
|											                                               |	
|	PROJECT TITLE								                                       |
|											                                               |
|											                                               |
|				PASSWORD GENERATOR				                                   |
|											                                               |
|											                                               |
|											                                               |
|											                                               |
|	AUTHORS:     AKINBINU MORAANUOLUWA		                             |
|  _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _   |



PROJECT DESCRIPTION
===================

This program is a password generator that is written in C languange and 
compiled using the gcc compiler (on development of the code). I encountered
some problems like learning C from an extra source to get a better understanding
of how the programming language works. We included functions to make sure our
code  is less clumpsy.
The program takes an input of integer 3 or 4, it generates a password from a list
of given dictionary files.

Instructions
============
To run this code, you will need to compile it using a C compiler like GCC. As the
code is terminal base, you will get an output on the command prompt.

Functions included (2)
======================
As the program is not a complex code, we only used two functions which are:
	1. The randomize() function which takes two parameters is used to generate 
	random numbers and we implemented this when iterating through the words in
	the dictionary files.
	
  2. The program uses the fill_unique function to generate an array of unique 
	random numbers between 1 and the length of the password. 
	These numbers are used to determine which dictionary file to read . 
	The program reads the selected 
	line from the dictionary file and stores the word in a buffer.
