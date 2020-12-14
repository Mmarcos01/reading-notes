[Home](README.md)

## JavaScript

JavaScript is the behavior layer and provides **logic** and interactivity to your webpage. It can **access** content by selecting any element, attribute, or text in html. It can **modify** content by adding or removing elements, attributes, or text. With JavaScript you can **program** rules for the browser to follow and have the script **react** to certain events, such as when the user clicks a button or hovers over an image.


### Objects and Methods

**Object** -containers for named values called properties or methods.
**Methods** -are actions that can be performed on objects.

### Script

A script is a series of instructions for the computer to follow to achieve a goal. Each instruction should start on a new line, each instruction is known as a **statement**. You can think of a script as a recipe, handbook, or manual.

### Writing Scripts

When writing a script, first state your goal, then list the tasks that need to be completed in order to reach it. Start with the big picture of what you want to achieve, and break that down to smaller steps.
  1. Define the goal
  1. Design the script -this can be a flowchart
  1. Code each step

The <*script*> element is used with embed JavaScript code. When  the browser encounters the script element it stops to load the script and checks to see if it needs to do anything.

*Remember JavaScript is case sensitive*

### Statements

Each individual instruction or step in a script is a **statement**. Each statement should start on a new line and end in a semicolon; which indicates the that the step is over and JavaScript should move to the next line. Statements can be organized into **code blocks** (areas surrounded by curly braces) Code blocks can be used to group together many more statements.

### Comments

Comments should be used to explain what your code does and can be written as such:
  - for multiline comments use /* this is a comment */
  - for singleline comments use // this is a comment

### Variables

Variables are used to "remember" bits of information, or "values", the values can change or (vary) each time a script runs. Results are *calculated* or *computed* using data stored in variables.

> This concept of variables is similar to those in algebra; where letters are used to represent numbers.

- Declare the variable -create the variable and give it a name

var quantity;

Where **var** is the variable keyword and **quantity** is the variable name (sometimes called an identifier) If the variable name is more than one word it is usually written in camelCase.

- Assign a variable a value -tell it what information you would like it to store for you.

quanity = 3; 

Where **quantity** is the variable name, (A name should describe the kind of data a variable holds.) **=** sign is the assignment operator (saying you are going to assign a value to the variable) and **3** is the value. (if there is no value, the value is **undefined**)

### Data Types

> JavaScript distinguishes between numbers, strings, and true or false values known as **Booleans**

- **Numeric Data Type** (p63)-handles numbers:
  
  0.75

  var el = document.getElementById('cost'); <-- find the element by the id of *cost*
el.textContent = '$' + total; <-- replace content of cost with total

- **String Data Type** (p64)-consists of letters and other characters within single or double quotes, (using backward slash escapes the quotation, ref. page 65):
  
  'Hello, world!'
  
  Strings are frequently used to add new content into a page and can contain html markup.

- **Boolean Data Type** (p67) -can have one of two values; true or false:

  true

  Like a light switch it can either be on or off (can also think of as off/on or 0/1). Booleans are helpful when determining which part of a script should run, when the code can take more than one path; different code may run in different circumstance.

  ### Short hand for creating variables (p67)

  More advanced way to write JavaScript code, makes code a little harder to follow.

  ### Changing the value of a variable (p68)

  ### 6 rules to always follow when giving a variable a name (p69)
    1. name must begin with $, _, or a letter and **NOT** a number
    1. the name can contain letters, numbers, $, or _, and **NOT** -, or .
    1. cannot use **keywords** or **reserved words** 
    1. all variables are case sensitive
    1. use a name that describes the kind of information that the variable stores
    1. if the name is more than one word, use camelCase or underscores 

### Expressions

An expression results in a single value; there are two types of expressions:
  
  1. Those that assign a value to a variable; using an assignment operator such as '=' 
  **Example:** var color = 'blue'; The value of color is now blue.
  
  1. Those that use two or more values to return a single value.
  **Example:** var area = 2 * 4; The value of area is now 8.

### Operators 

Operators allow programmers to create a single value from one or more values.

#### Types of Operators

  - Assignment Operators -the = sign, assigns a value to a variable
  **Ex:** colr = 'blue';
  - Arithmetic Operators -perform basic math, 
  **Ex:** area = 2 * 4
  - String Operators -combine two strings, 
  **Ex:** greeting = 'Hello' + 'world'; The value is now Hello world
  - Comparison Operators -compare two values and return true or false,
  **Ex:** buy = 2 > 4; the value of buy is false
  - Logical Operators -combine expessions and return true or false,
  **Ex:** buy = (4 > 2) && (2 < 4); The value of buy is now true

Operator | Name | Purpose | Example | Result
------ | ------ 
\+ | Addition |
\- | Subtraction |
/ | Division |
\* | Multiplication |
++ | Increment | Adds one to the current number | i = 10; 
&nbsp; | &nbsp; | &nbsp; | i++; | 11
-- | Decrement | Subtracts one from the current number | i = 10; 
&nbsp; | &nbsp; | &nbsp; | i--; | 9
% | Modulus | Divides two values and returns the remainder | 10 % 3 | 1

> Order of execution: * and / are performed *before* + and -
To change the order, place calculation you want done first inside parantheses.