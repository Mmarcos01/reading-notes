[Home](README.md)

## JavaScript: Continued

### More on Operators

Comparison operators usually return single values of true or false.

Boolean: true or false

**==** means is equal to, it compares two values (numbers, strings, or Booleans) to see if they are the same

- 'Hello' = 'Goodbye' returns false
- 'Hello' = 'Hello' returns true

**===** is a more strict method of equal to, this operator compares two values to check that both the *data type and value* are the same.

- '3' === 3 returns false
- '3' === '3' returns true

**!=** means is not equal to, compares two values (numbers, strings, or Booleans) to see if they are *not* the same.

- 'Hello' != 'Goodbye' returns true
- 'Hello' != 'Hello' returns true

**!==** is the more strict method, compares two values to check that both the *data type and value* are *not* the same.

- '3' !== 3 returns true
- '3' !== '3' returns falseS

> Programmers refer to the testing or checking of a condition as **evaluating** the condition.  

Conditions can be complex and usually result in a value of true or false. With a few exceptions. (p 157, 167)  

**>** greater than, checks if the number on the left is *greater* than the number on the right.  

- 4 > 3 returns true  
- 3 > 4 returns false  

**>=** greater than or equal to  

**<** Less than  

**<=** less than or equal to  

### Logical Operators  

Logical operators allow you to compare the results of more than one comparison operator.  

**&&** Logical AND, tests more than one condition  

- ((2 < 5) && (3 >=2)) returns true  
    true && true returns true, otherwise returns false  

**\|\|** Logical OR, tests at least one condition.

- ((2 < 5) \|\| (2 < 1)) returns true  
    false \|\| false returns false, otherwise returns true  

**!** Logical NOT, takes a single Boolean value and inverts it  

- !(2 < 1) returns true  
    !true returns false  
    !false returns true  

**Short-Circuit Evaluation**  
    - Logical expressions are evaluated from left to right. If the first condition provides enough information to get the answer, there is no need to evaluate the second condition.

### Loops  

Loops check a condition. If it returns true, a code block will run. It wil rerun until the condition returns false. There are 3 common types of loops.  

1. FOR  
    (the most common) If you need to run code a specific number of times use a for loop. In a for loop, the condition is usually a counter to tell how many times the loop should run.

1. WHILE  
    If you don't know how many times a loop should run, you can use a while loop. The condition can be something other than a counter, and the code will continue to loop for as long as the condition is true.

1. DO WHILE  
    The do...while loop is similar to the while loop, the only difference is that it will always run the statements inside the curly braces at least once, even if the condition evaluates as false.

#### Loop Counters (p170-173)  

**for (var i = 0; i < 10; i++>) {**  
    **document.write(i);**  
**}**  

- In this for loop, the condition is made up of 3 statements:  
    1. var i = 0;  
        Initialization; create a variable and set it to 0, this variable is commonly called i and acts as a counter
    1. i < 10;  
        Condition; the loop should continue to run until the counter reaches a specified number. In this case the loop will run 10 times before stopping.
    1. i++  
        Update; everytime the loop has run the statements in the curly braces, it adds one to the counter. Another way of reading this is "Take the variable i, and add one using the ++ operator."  

> When the condition is no longer true, the loop ends. The script moves to the next line of code.  

#### Using While Loops  

**var i = 1;** // Set couter to 1
**var msg = '';** // Message

// Store 5 times table in a variable
**while (i < 10) {**
    **msg += i + ' x 5 = ' + (i * 5) + '<*br* />';**
    **i++;**
    **}**

**document.getElementById('answer').innerHTML = msg;**

This is an example of a while loop that writes out the 5 times table. Each time the loop is run, another calculation is written into the variable called msg. In this example, the condition specifies that the code should run nine times. The loop will continue to run as long as the condition in the parentheses is true.

[Home](README.md)