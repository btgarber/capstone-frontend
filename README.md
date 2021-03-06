# Capstone Front End

Program entry point is in the main.py file. All other source is in the src/
folder.


## Software Versions

I have been using Python 2.7.3 on my machine. And pylint 0.25.0.


## How to Contribute

Fork my repo. Make some changes. Commit. Repeat. When you are done submit a pull
request: https://help.github.com/articles/using-pull-requests

Also, run pylint on your source before committing it, and don't commit if pylint
returns warnings or errors (especially errors...). Try to fix them or leave a
comment if there is a good reason not to. Please try to follow conventions too
when reasonable. This is a very necessary tool when working with a language like
Python so our code does not crash in the middle of our demo ;)


## Python Modules

Python modules you might need to install:
    1. wxPython
	-follow the instructions @ wiki.wxpython.org/CheckInstall to install wxPython 2.9
	NOTE: you might need to specify the path to some shared libraries for python. Do 
	export LD_LIBRARY_PATH=/usr/local/lib 
	in terminal.
    2. fdpexpect

## Running the application
You must run the application in 'administrator' mode: 
$sudo ./main.py

## Arduino Connection
Yellow from LEDs = yellow on connector = pin 2
Green from LEDs = green on connector = pin 3
Dark blue from LEDs = red on connector = GND
Red from LEDs = black on connector = Vin

