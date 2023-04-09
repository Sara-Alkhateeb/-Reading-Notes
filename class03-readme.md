# Class03
### Here is different concepts will help as python developer.
## What is the purpose of the ‘`with`’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
The `with` statement in Python is a powerful tool for managing resources like files. It ensures that a resource is properly initialized and cleaned up after its usage, even in the presence of exceptions. When working `with` files, the `with` statement is often used to open the file and create a context within which the file is used. This context ensures that the file is properly closed after it has been used, regardless of whether an exception occurs while the file is being used or not. Using the `with` statement to open files is considered better practice than using the traditional `open()` function, because it helps to ensure that files are properly closed, which is important when working `with` limited resources like file descriptors. If you don't use the `with` statement and manually close the file, you run the risk of leaving files open and using up valuable system resources. In summary, the `with` statement is a useful feature in Python for managing resources and helps ensure that your code is robust and efficient when working `with` files.

## Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.
### - `read()`

The `read()` method reads the entire contents of the file and returns them as a string. all the content

     Example: 
     with open('file.txt', 'r') as f:
       content = f.read()
     out put : Hello,
               as ASAC student!

#In this example, the entire contents of the file `(file.txt) `are read and returned as a string in the `(content variable)`.

### - `readline()`

The `readline()` method reads a single line from the file and returns it as a string.

     Example: 
     with open('file.txt', 'r') as f:
        line = f.readline()
     out put: Hello,

#In this example, a single line from the file `(file.txt)` is read and returned as a string in the `(line variable)`.

## Note
The appropriate usage of each method depends on the specific needs of the code. If require the complete contents of a file at once, use `read()`. However, if code needs to process the file one line at a time, use `readline()`. Generally, for small files that can fit into memory, `read()` is preferred. On the other hand, for large files that don't fit into memory or need to be processed line by line, `readline()` is the way to go.

## Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

In Python, `exception` handling errors and other exceptional conditions that may arise during the execution of a code.

The `try`, `except`, and `finally` blocks are used to handle exceptions of code. The `try` block contains the code that may `raise` an `exception`. The `except` block catches the `exception` and handles it. The `finally` block contains code that should be executed regardless of whether an `exception` was `raised` or `not`.

     Example:
     `try`:
        n1 = int(input("Enter first number: "))
        n2 = int(input("Enter secound number: "))
        result = n1 / n2
          print(f"{result}")
       `except` ZeroDivisionError:
          print("Error divide by zero.")
       `finally`:
          print("Good bye!")

In this example, the `try` block contains the code may raise an exception, like a ZeroDivisionError if n2=0 the `except` block catches the exception and prints error message("Error divide by zero."). 
The `finally` block should be executed regardless of whether an exception was raised or not. It will print a message indicating that the program done ("Good bye!").

By using `try` , `except` , and `finally` blocks, you can ensure that  program handles exceptions such as closing files or releasing resources, even if there is an error.