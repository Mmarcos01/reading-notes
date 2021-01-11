
[Home](README.md)

HTML has six levels of headings: \<h1> for main headings, \<h2> for sub headings, \<h3>-\<h6> for sections under sub heeadings.  

Text size for headings will range from \<h1>: the biggest to \<h2> the smallest.

\<p> -paragraphs  
\<b> -bolden  
\<i> -italicize  
\<sup> -superscript (such as in 2<sup>2</sup>)  
\<sub> -subscript (such as in H<sub>2</sub>O)  
white space collapsing -browser displaying two or more spaces as one space  
empty element -only one tag, no closing tag  

\<br /> -creates line break  
\<hr /> -creates orizontal rule between sections  

## Semantic Markup

Semantic markup is intended to add extra information to the page  

\<strong> -indicates strong importance, will display as bold  
\<em> -indicates emphasis, will display italic  
\<blockquote> -used for longer quotes, the \<p> element is used within  
\<q> -for shorter quotes, should put quotes around the text however some do not  
\<abbr> -used for abbreviations or acronyms  
\<cite> -used for referencing, will display italic  
\<dfn> -indicates the defining instance of a new term  
\<address> -contains contact details  
\<ins> -shows text that has been inserted into a document (underlined)  
\<del> -shows text that has been deleted from a document (crossed out)  
\<s> -indicates something is no longer relevant but needs not be deleted (crossed out) such as a previous price  

## CSS

CSS (Cascading Style Sheets) associates rules with HTML elements and affect how elements are displayed. A CSS rule contains two parts:  
1. selector - specifies the element
1. declaration - indicates how the elements should appear
    - a declaration contains a property and its value, such as color: blue;

[See also: 101 CSS notes](css.md)

## Javascript

JavaScript provides **logic** and interactivity to your webpage. It can **access** content by selecting any element, attribute, or text in html. It can **modify** content by adding or removing elements, attributes, or text. With JavaScript you can **program** rules for the browser to follow and have the script **react** to certain events, such as when the user clicks a button or hovers over an image.

Script - series of instructions for a computer to follow one by one, each individual instruction is known as a **statement**.
Variables - temporarily store pieces of information used in the script

## Arrays

 An array stores a list of values, when creating an array you give it a name like any other variable and followed by the name array. 

### Array Literal
The values are assigned to an array inside square brackets [], each value being separated by a comma. Such as:  

var: colors;
colors = ['red', 'blue', 'green'];

### Array Constructor
Uses the new keyword followed by Array(); and values are specified in parenthesis as oppsed to square brackets. Such as:  

var colors = new Array ('red', 'blue', 'green');

> Values in an array are accessed as a numbered list starting at 0. Each item is automatically given a number called an index.  

var: colors;
colors = ['red', 'blue', 'green'];  

The index for these values are:  

0 'red'
1 'blue'
2 'green'

Each array has a property called **length**, which holds the number of items in the array. Here numColors value is set to be the number of items in the array:   

var numColors;
numcolors = colors.length;

### Accessing and changing array values

After the array name, specify the index number for that value within the square brackets  

**Create Array:**  

var: colors;
colors = ['red', 'blue', 'green'];  

**Update second item in the array:**  

colors\[1] = 'black';

**Get the element with an id of colors:**  

var el = document.getElementById('colors');  

**Replace with second item in from the array:**  

el.textContent = colors\[1];

## Decision Making

Decisions can be made in script to determine which line of could should be run next. There are two components to a decision:  
1. An expression is evaluating, which returns a value
1. A conditional statement says what to do in a given situation  

if (score > 50) {
    document.write('You passed!');
} else {
    document.write('Try again.');
}  

This code is saying that:
If the condition is true (score is greater than 50); execute the message 'You passed!', otherwise execute the message 'Try again.'

[See Also: Class 101 Notes Part 1](javascript.md)
[See Also: Class 101 Notes Part 2](morejs.md)  

[Home](README.md)

