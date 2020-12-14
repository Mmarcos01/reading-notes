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

- **Numeric Data Type** -handles numbers:
  0.75

- **String Data Type** -consists of letters and other characters within single or double quotes:
  'Hello, world!'
  Strings are frequently used to add new content into a page and can contain html markup.

- **Boolean Data Type** -can have one of two values; true or false:
  true