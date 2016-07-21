.. _bash:


Bash Scripting
==============

What is Bash scripting and what is it's uses?
---------------------------------------------
A Bash script is a plain text file which contains a series of commands. These commands then tell your computer what it should do.

Tutorial
========
Step 0
------
We should first locate your bash interpreter. To do so we enter ``which bash`` into the terminal.  
It should look like this: 

.. image:: step0bash.png
        :align: center
        :height: 400 px
        :width: 400 px
        :alt: Step0

We should also find a text editor for bash. I use `TextWrangler <http://www.barebones.com/products/textwrangler/download.html>`_. Download one you like and learn how to use it.

Step 1: Variables
------
All bash shell scripts start with a **shebang** ``#!`` followed by the location of your bash interpreter.
Create a directory named Learning_Bash. In Learning_Bash create a file named step1.sh (all bash scripts end in .sh)

.. image:: step1variables_rtd.png
        :align: center
        :height: 400 px
        :width: 400 px
        :alt: Variables

before running the file, you must first make it executable. To make it executable you must type into terminal ``chmod +x step1.sh``. To run the bash script you must then type into terminal ``./step1.sh``

Step 2: Shell Commands in Bash
------------------------------

.. image:: step2shellcommands_rtd.png
        :align: center
        :height: 400 px
        :width: 400 px
        :alt: Shell
        
*Again you must make every file executable by typing* `chmod +x filename` *into the command line and to run the file you must type* `./filename` *in the command line.*


