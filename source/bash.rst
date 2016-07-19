.. _bash:


Bash Scripting
==============

What is Bash scripting and what is it's uses?
---------------------------------------------
A Bash script is a plain text file which contains a series of commands. These commands then tell your computer what it should do.

Loops
-----
```
#!/bin/bash
for filename in *.dat
do
	cp $filename original-$filename
done 
```

* ``for`` starts the loop
* ``do`` indicates a command
* ``done`` ends and restarts the loop
