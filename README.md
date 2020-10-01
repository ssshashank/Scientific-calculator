An advanced Calculator implemented in Python Programming Language using Tkinter Module.

Project Title : "Scientic-Calculator"

Operations Available = 1. Addition 
                       2. Substraction 
                       3. Division 
                       4. Multiplication and many more.

Advantages = 1. Bigger Buttons 
             2. Compact and Fast 
             3. Lots of functionalities
             4. Attractive GUI

------------------------------------BASICS------------------------------------------------
Python = is a Dynamically Typed, Object Oriented Programming Language
Tkinter = Inbuilt Python module --> to create simple GUI apps.
        = Standard Python interface to Tk GUI toolkit.

Tk = is the toolkit

mainloop() = Most important function while working with Tkinter. = You must call mainloop only one time. = It is an infinite loop.

-----------------------------BASIC Code for Tkinter---------------------------------- 
from tkinter import *

root = Tk()                 # 'root' is object of 'Tk' class 
                            # creates a basic gui 
                            # basic default compoments present in GUI
                            # A base is created -> for GUI Development # we can create button, menu bar,etc on this base

root.mainloop() # event loop -> called only once
