## Summary
Control flow is a fairly important topic because programming is really just dictating how data moves around. We do this a few different ways, but the important two right now are **loops and condition statements.**
 - The two basic loops, **for loop** and **while loop** are used for repeating blocks of code
 - **If statements** allow for conditional code execution

### Loops
The two basic types of loop are a **for** and a **while** loop.
 - They both require a **condition**, which is a rule telling the loop how long to run
 - The way this condition is implemented is what differs looping structures. While loops run until a condition is met, for loops run a variable amount of times as defined by the condition.
 
 Here are both loops printing 1 to 100.

 While loop:
 
	 i =0
	 while i<100:
	     print(i)
	     i +=1

For Loop:

    for i in range(101):
	    print(i)

For loops are generally preferable to While loops due to readability and the ease of iterating through data types. 

### If statement 
The if statement takes a condition (like loops) and will make a decision with it:

    x = 7
    if x == 7:
        print(x)

You can also make **if else** statements, allowing you to give multiple scenarios for the condition:

    x = 6
    if x == 7:
        print("not 7")
    else:
        print("not seven")

