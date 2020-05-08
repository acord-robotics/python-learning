I'm going back to the fourth tutorial in the intro to pygame series (may have to catch up on Python as well soon). The reason for that is simple: I don't fully understand/remember the reasons for going OO (object oriented /programming) and what we do to do so, and how it works. I'll send my notes in here.

We can also see commits in https://github.com/Gizmotronn/python-learning/tree/master/Applets/TWT that reference https://github.com/Gizmotronn/python-learning/issues/22

* Everything you can do OO, you can do non-OO

https://www.youtube.com/watch?v=v_Jp11xqCzg&list=PLzMcBGfZo4-l1MqB1zoYfqzlj_HH-ZzXt

Characteristics of our character (before OOP):

```python
x = 50 # x position of character
y = 400 # y position of character
width = 64 # width of character
height = 64 # heigh of character
vel = 5 # velocity of character in terms of pixels // He moves this many pixels per "step" or frame/
isJump = False # a variable that helps identify when the player is jumping; / this helps with doublejump (prevention), as well as other things
left = False
right = False 
walkCount = 0
```

## Create a player class:

```python
class player(object):
    def __init__(self) # initialisation function
```



# OOP Tutorial

## Tutorial 1

```python
variable1 = 5 # integer variable, value = 5
variable2 = "10" # string variable, value = "10" (not a number)
variable2Number = int(variable2) # converting the string (or other variable type) to an integer
variable1String = str(variable1) # converting the integer (or other variable type) to a string

print(type(variable1)) # prints the type of variable that "variable1" is
>>> <class 'int'> # it says it's an integer variable
print(type(variable2))
>>> <class 'str'>
```

**Class**

* Whenever a new object (variable, for example) is created in python, it automatically creates an *instance* of that object
* In the code block above, it could be read that `variable1` is equal to `an instance of the int class; and it's value is 5`.  