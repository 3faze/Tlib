```
#Tlib doesn't concern about this module being integrated in other
#librarie/programming language!

#Tlib.py is a module that consists of speed and easy usage of the following
#libraries

"""
Tlib.py was first created on March of 2022, its an on-developing module made by
Tomás Pereira | IMPORTANT: NO DISTRIBUTIONS OF THIS MODULE ALLOWED! | The positions
of screen widgets/objects start at (0, 0)X and Y, use of strings aren't required on
functions but apreciated!
"""

#IMPORTANT: IF YOU ARE GOING TO CHANGE THE CODE, IT ISN'T PROPERLY ORGANIZED BECAUSE
#OF THE SEQUENCIES! RESHARING NOT ALLOWED SINCE TLIB IS A REGISTERED MARK!

version = "Tlib.py -- 1.3 -- python 3 -- 2022"

import turtle as t
import random as rd
import time as ti
import sys as sy
import math as ma

def p_version():
    print(version + "\n")

def greet_user_now():
    print("Welcome from the Tlib community! " + "Version: " + version)
greet_user_now()

def greet_user(user):
    print("Welcome from the Tlib community, " + user + "!")

def sum3(n_1, n_2, n_3):
    print("This is the result of your sum!\n" + str(n_1 + n_2 + n_3))

def sum2(n_1, n_2):
    print("This is the result of your sum!\n" + str(n_1 + n_2))

def calculator():
    operation = input("What operation do you want to perform?")
    print("The result of the operation is: \n", eval(operation))

def puts(wtp):
	print(wtp)

def wait(NUMBER):
    ti.sleep(NUMBER)
	
def sleep(NUMBER):
    ti.sleep(NUMBER)
	
def round(NUMBER):
    int(float(NUMBER))
    puts(float(NUMBER))
	
def gets(TEXT):
    global inp
    inp = input(TEXT + "\n")

def getsr(VAR):
    print(VAR)
```
