# Python
- Python is a coding language that has gain a lot of popularity in the last few years

## The basics
### Built-in Functions 

- I started learning python by knowing the types of texts there are
    - Str: This is the type of text, that is in fact, a text. Text="Hello world". Code= str(input())
    - Int: This is the natural numbers we use, they can also be negative. 12 + int = int
    - Float: Like the one before, it represents numbers, but the difference is that in float you can use decimal numbers, like 1.21312
    - Bool: Is used to set a True or False value to a variable, like: Interrupter = False

### Control flow statements

- These are used to condition the process of the code.

- If: It's used for doing something only if something else is true, the composition of the command is:
    - If (Something that can be True or False):
        - Do this
- Elif: This one is really similar to the last one, but the key difference is the order, "If" always is first, and "Elif" comes after
    - If (x>7):

        Do this
    - Elif (x<2):

        Do that
    - Else: The last one of this kind, it's used in the end of the statement, like this:
    - If (x>7):

        Do this    
    - Elif (x<2):

        Do that    
    - Else:
        
        Do nothing(or anything you like)

### Looping ir iteration Statements

- In this category the commands i've learned, are while and for:

    - While: The use of this statement, summarize in looping something, until something else changes the value of true of the proposition
        - While (i<7):
            Suma = Suma + i * x
            i = i + 1
        - This statement makes everything inside the while to repeat until i becomes bigger than 7, you need to be careful of infinite loops

    - For: This is like the last one, but in a set list, like, numbers from 1 to 10, or letters in the word "Hello"
            - For "Variable" in "List":
                - Do something
        - Note: this complements pretty well with the function RANGE, what this does is creating a list for a range of numbers, using a starting one, the one after the last one and a step
            - Range(1, 12, 2): 1,3,5,7,9,11
            - This is because you're asking for numbers between one and eleven, with a step of 2
