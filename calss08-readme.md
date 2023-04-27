# Class 08
## What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
    [expression for item in iterable if condition]

`expression` is the operation to be performed on each item in the iterable.

`item` is the variable representing the current item in the iteration.

`iterable` is the sequence of items that will be iterated over.

`condition` (optional) is a filter that allows you to only include items that meet a certain criterion.

### Example of a list comprehension that extracts the even numbers from a given list of integers:
     
     numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
     even_numbers = [num for num in numbers if num % 2 == 0]
     print(even_numbers)


### Output :
     [2, 4, 6, 8, 10]


In this example, we use a list comprehension to create a new list called `even_numbers` by iterating over the elements in the `numbers` list and checking if each element is even using the modulo operator `(%)`. If an element is even, it is included in the new list. This is done in one line of code, which makes the code more concise and easier to read than using a for loop to accomplish the same task.


## What is a decorator in Python?
Decorators are used to wrap a function with another function, providing additional functionality to the original function. They allow you to modify the behavior of a function or class method dynamically at runtime, without changing its original code.

     def greeting_decorator(func):
     def defintion():
        print("Hello")
        func()
        print("Nice to meet you!")
     return defintion

     @greeting_decorator
     def greet():
        print("My name is Sara")

     greet()

Output : 

     Hello
     My name is Sara
     Nice to meet you!


## Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading

Decorators are a powerful feature of Python that allow you to add functionality to functions and methods dynamically, without modifying their source code. A decorator is a special kind of function that takes another function as input, modifies it, and returns the modified function. The modified function can then be called in the same way as the original function, but with additional functionality.

Example:

     def greeting_decorator(func):
     def defintion():
        print("Hello")
        func()
        print("Nice to meet you!")
     return defintion

     @greeting_decorator
     def greet():
        print("My name is Sara")

     greet()

Output : 

     Hello
     My name is Sara
     Nice to meet you!


In the example above, define a decorator function called `greeting_decorator` that takes a function as its argument. Inside the decorator, we define a nested function called defintion` that adds a greeting message before and after calling the original function.

then use the decorator by placing the `@greeting_decorator` syntax above the `greet()` function definition. This tells Python to apply the `greeting_decorator` to the `greet` function.

When we call the `greet()` function, the decorator adds the greeting message before and after the function call, modifying its behavior dynamically without changing its original code


Some common use cases for decorators include:

1. Logging: Decorators can be used to log function calls and their parameters, making it easier to debug and analyze the behavior of your program.

2. Timing: Decorators can be used to measure the execution time of a function, helping you identify performance bottlenecks and optimize your code.


3. Validation: Decorators can be used to validate the inputs and outputs of a function, ensuring that they conform to certain requirements or constraints.

4. Retry: Decorators can be used to retry a function call in case of errors or failures, helping you build more resilient and fault-tolerant systems.

5. Memoization: Decorators can be used to cache the results of a function for the same input arguments, avoiding the need to recalculate them again.

Overall, decorators are a powerful tool for extending and customizing the behavior of functions and methods in Python. By adding new functionality to existing code, decorators can help you write more reusable, maintainable, and efficient programs.