# Class07
## Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
Variable scope in Python:
Variable scope refers to the part of a program where a variable is accessible or visible. In Python, there are two main types of variable scopes: local and global.

Local scope: A variable defined inside a function or a block of code is said to have local scope. This means that the variable can only be accessed within that function or block of code. Once the function or block of code is exited, the variable is destroyed and its value cannot be accessed anymore.

Global scope: A variable defined outside of any function or block of code is said to have global scope. This means that the variable can be accessed from anywhere in the program, including inside functions and blocks of code.

### Example:
        
    x = 10   # Global variable

    def my_function():
            print(x)

    my_function()  # Output: 10

    def my_function2():
           x = 5  # Local variable with the same name as the global variable
           print(x)

    my_function2()  # Output: 5
    print(x)        # Output: 10 (global variable value is unchanged)


## How do the global and nonlocal keywords work in Python, and in what situations might you use them?

Global keyword: When used inside a function, the global keyword allows the function to modify a variable in the global scope.

Nonlocal keyword: When used inside a nested function, the nonlocal keyword allows the function to modify a variable in the outer (enclosing) function's scope

## In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
Big O notation is a way to describe the time complexity of an algorithm, which is the amount of time it takes for an algorithm to complete as the input size increases. It is important because it allows us to compare the efficiency of different algorithms, and to choose the most appropriate one for a given problem.


## Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.

To simulate a dice roll using Python, we can use the `random` module which has a function called `randint` that returns a random number between two values. So we can use this function to simulate a `dice roll` that returns a number between `1 and 6`.

To calculate the probability of rolling a specific number, like a 6, we can repeat the dice roll many times (e.g., 1000 times), and then count the number of times a 6 appears. Finally, we can divide the number of times a 6 appeared by the total number of rolls to get the probability of rolling a 6.

To do this in Python, we can define two functions: one to simulate a dice roll and one to calculate the probability. The probability function should take the number of rolls as an input, and then use a loop to simulate that many rolls and count the number of times a 6 appears. Finally, it should divide the count by the total number of rolls to get the probability