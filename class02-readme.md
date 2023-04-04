# class02 
1. ### (TDD) in Python are designed to help developers write high-quality, bug-free code that meets the requirements of the project. 
2. ### __name__ == '__main__'  helpful for developers who are new to Python and want to understand the purpose and use cases for this conditional statement.
3. ### Modules and packages allow you to organize your code and reuse functions and variables across multiple files and programs

## The key principles of Test-Driven Development (TDD) in Python 
•	Think about the test and write it before actual code to be sure that the code will match the requirements.

•	Unit test focuses on testing small units of code or some pieces of the code for certain functions or methods. This helps to discover any error in the development process.

•	Run tests on each step it will be ensure that any issues are caught early in development process.

•	Refactoring involves improving the structure and design of the code without changing its external behavior.

### All of these principles will help us to
•	Catch the errors early according to run it frequently.

•	Improve code design through refactoring.

•	Reduce the maintenance costs because you are ensuring about code correctness.
 
## Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?
this statement in Python is used to specify the code that should be executed only when the script is run directly from the command line, and not when it is imported as a module into another Python script.
When a Python script is run, the interpreter sets the __name__ variable to "__main__" to indicate that it is the main program being executed. When the script is imported as a module, the __name__ variable is set to the name of the module.
By using the if __name__ == '__main__': statement, you can write code that is only executed when the script is run directly, and not when it is imported as a module. This is useful for separating out the test code from the library code in a module, allowing you to write unit tests that are only run when the module is executed directly.
 
### Some use cases for including this conditional in your code are:
To provide a simple command-line interface for a module.

To separate out test code from library code.

To define a script that can be run from the command line or imported as a module.

## Describe Recursion.
The process in which a function calls itself directly or indirectly.
recursion makes a program more readable and because of latest enhanced CPU systems, recursion is more efficient than iterations, so it used to solve problems that have an infinite number of possible solutions.
A recursive function can go infinite like a loop. To avoid infinite running of recursive function,
Use Base criteria − There must be at least one base criteria or condition, such that, when this condition is met the function stops calling itself recursively.

## What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.

Packages is collection of modules in directory and module is file that contain python code the purpose of them to organize the code.
 
### create, import, use module.
•	Create a new file with a .py extension. For example, my_module.py.

•	Write the Python code you want to include in the module.
For example:  def greet(name):
                          print (f"Hello, {name}!")

•	Save the file in a directory that is in the Python path. For example, in the same directory as your main Python program.

•	Import the module in your Python program using the import statement followed by the name of the module. For example:    import my_module

•	Use functions or variables from the module by prefixing them with the module name. For example:  my_module.greet("Alice")
                 print(my_module.PI)

 
### create, import, use package
•	Create a new directory with any name you like. For example, my_package.

•	Add an __init__.py file to the directory. This file can be empty, or it can contain initialization code.

•	Add one or more .py files to the directory, each containing the code for a module. For example, module1.py and module2.py.

•	Save the directory in a directory that is in the Python path. For example, in the same directory as your main Python program.

•	Import a module from the package in your Python program using the import statement followed by the package name and module name, separated by a dot. For example
import my_package.module1


## Things I want to know more about
Test methodes - Subpackges - Recursion 