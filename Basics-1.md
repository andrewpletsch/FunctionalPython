# Basics and Structuring Your Code


This is the start to a 8(ish?) part series that will go through the basics of coding in Python. Hoping to do two a day. All the pages will have some sort of challenge at the end except for the first two. I recommend using the online interpreter, I'll go over creating an environment later but it isn't necessary to start.

All this code can be ran on any online Python 3 interpreter, I like [this one](https://www.onlinegdb.com/online_python_interpreter). I recommend you do run the code, play around with the values and see what you can do. 

## Summary

 - Variables hold values for us to use. 
 - Functions keep code neat and organized.
 - Code is the recipe, Input/Output are the ingredients and result.

## Variables

Variables are the base of how we work with data. They work very similar to variables in math, but instead of solving for them, we assign them values. This can be done in two different ways, we can assign it a **fixed** value like this:

    x = 3
    z = "This is a string"
Or you can tell Python what the answer looks like:

    y = 3 + 7
    g = x
Python automatically gives variables a **type**, it defines what the variables value looks like. These are the types for the variables above:

 - **x** is an integer, different word for number 
 - **z** is a string, which is effectively text
 - **y** is also an integer because after the calculation it becomes 10
 - **g** is assigned **x** which is an integer. 
**One thing to know is **g** gets **x**'s value when it is assigned. If you re-assign the **x** value after you've already assigned **g** it's value, **g** will stay the original **x**'s value, it will not update with the **x** value.

## Functions
A function works the same way a variable does. The difference is instead of storing a value, it stores multiple lines of code, known as a block.

This is what it looks like:

    def main():  
      var = 0 + 4 + 6  
And then to run the block of code, you **call** the function:

    main()

There are also functions that are pre-built for us to use in Python's **Standard Library**, like creating an output.

## I/O: Input and Output
**Input** is what you give a function, often in the form of arguments. You can also ask for input from the user using **input()**.
**Output** is what a function produces, it can be almost anything, for our purpose, it will be printed to you through a console. This is done via a pre-built function called **print()**. Using functions is just like how you called the main function, but it needs an **argument**.

    def main():  
      var = input("This is where you can put a question: ") 
      print(var)
    
    main()

So in this case, the input/argument was taken by the **input()** function and assigned to the variable **var**. The function **print()** was then called with the argument **var**. The output was **var** being printed to the console. 


## Summary

 - Variables hold values for us to use. 
 - Functions keep code neat and organized.
 - Code is the recipe, Input/Output are the ingredients and result.

### Things you don't need to know, but if you're interested

#### Variables
Little bit more about types. I'll also talk more about them later.

**Integers** in Python are built on signed long integers in C. While this gives you a lot of flexibility, you should be aware that there is a limit, in this case it is -2,147,483,647 to +2,147,483,647. 

**Strings** are a sequence of characters. Now, this almost always means text or at least a sequence of characters but you can also have bit or byte strings. Binary data is often represented in two different forms: bits (0 or 1) with a lowercase b and bytes (8 bits) with an uppercase B. This is how all data is represented at it's most basic level. A string can be used to represent this data. 

