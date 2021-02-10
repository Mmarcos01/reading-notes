[Home](README.md)

## Execution Context and Hoisting

Each time a script enters a new execution context, there are two phases of activity:

1. Prepare 
  - The new scope is created
  - Variables, functions, and arguments are created  

2. Execute
  - Now it can assign values to variables
  - Reference functions and run their code
  - Execute statements  

Understanding these two phases helps with understanding the concept of *hoisting*.  

Functions in JavaScript are said to have **lexical scope**. The are linked to the object they were difined in.

## Errors

If a JavaScript statement generates an error, then it throws an exception. The interpreter stops and looks for exception-handling code.  
Error Objects can help find where your mistakes are and browsers have tools to help read them. An error object will contain the following properties:
  - name - type of error
  - message - description
  - fileNumber - name of javascript file
  - lineNumber - line number of error  

There are seven types of built-in error objects in JavaScript: Error, SyntaxError, ReferenceError, TypeError, RangeError, URIError, EvalError  

Two things you can do with errors:
1. Debug the script to fix the errors
2. Handle errors gracefully (using try, catch, throw, and finally statements)  

## A Debugging Workflow

Where is the problem?
What exactly is the problem?  

Debugging is about deduction. Try to narrow down where the problem might be, then look for clues. Utilizing the console helps narrow down where the error lives.

### Breakpoints

You ocan pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time. If you set multiple breakpoints you can step through them one by one. You can indicate that a breakpoint should be triggered only if a condition you specify is met.  

### Handling Exceptions

If you know your code may fail, use try, catch, finally:  

try {  
  // try to execute this code  
} catch (exception) {  
  // if there is an exception, run this code  
} finally {  
  // this always gets executed  
}  

### Throwing Errors

If you know something in your script may cause a problem, you can generate your own errors before the interpreter creates them. To create your own error:  

throw new Error('message');  

This creates a new Error object, the message should be as descriptive as possible.

[Home](README.md)|[Back to Top](class-10.md)

