[Home](README.md)  

## HTML Links

Links are created using the \<a> element which has an attribute called href- which will hold the outside page you wish the user to link to, or **absolute url**.  

**Ex:**  
\<a href="http://www.weblink.com">Text to link goes here.\</a>  

When linking to a page within the same site you can use a shorthand known as **relative url** If all pages are in the same folder, the href attribute is just the name of the file.  

**Ex:**  
\<a href="index.html">Home\</a>
\<a href="about.html">About\</a>  

**URL** - Uniform Resource Locator

### Email Links

To create a link that starts up the user's email program and addresses an email to a specific email address, the href attribute will start with mailto: followed by the email address you want the email to be sent to.  

**EX:**  
\<a href="mailto:you@example.org">Email to you\<a>

### Open Link in New Window

To create a link that opens up in new window, use the **target** attribute on the opening \<a> tag. The value should be _blank.  

**EX:**  
\<a href="http://www.imdb.com" target="_blank">Email to you\<a>


### Linking to a Specific Part of the Same Page

You need to first identify the parts of the page to link to, using the **id attribute.**  

**Ex:**  
\<h1 id="top">Top Header\</h1>
\<p>\<a hred= "#top">Goes to Top Header\</a>\</p>

### Linking to a Specific Part of Another Page

As long as the page you are linking to has id attributes that identify specific parts for linking, you can add the same syntax to the end of the link for that page.  

**Ex:**  
<a href="http://www.websiteurl.com/#bottom">

## HTML Layouts and Positioning

**Block-level elements** - start on a new line (\<h1>, \<p>, \<ul>, \<ui>)
**Inline elements** - flow in between surrounding text (\<img>, \<b>, \<i>)  

###Positioning Schemes

**Normail flow** - every block element appears on a new line
**Relative Positioning** - moves an element from the position it would be in normal flow, does not effect surrounding element positions
**Absolute Positioning** - positions the element in relation to it's parent element
**Fixed Positioning** - do not move when user scrolls up or down page. Sets position relative to browser window.
**Floating Elements** - makes a block level element around which other content can flow  

**Fixed Width Layouts** - dont change size as user increases or decreases the size of their browser window
**Liquid Layouts** - stretch and contract as the user increases or decreases the size of their browser window  

>Use of grids in web design is useful in creating consistent proportions and spaces between items for a professional look

## Javascript Review

1. What is a function? (p88)
2. First you must \___ a function before calling a function. (p90)
3. Statements needed to achieve the task of a function is written in ___ ? (p90) 
4. What is variable scope? The difference between local and global variables. Which uses more memory? (p98) 

**Function expession** - If you put a function where the interpreter expects to see an expression, then it is treated as an expression, and is known as a function expression.

**Anonymous expression** - a function with no name

### Immediately Invoked Function Expressions (IIFE, pronounced "iffy")

These functions are not given a name, and are executed once as the interpreter comes across them. Final parenthesis () tell the interpreter to call the function immediately. Anonymous and IIFE functions are used when the code only needs to run once within a task.  

## Pair Programming

[Read Article: Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

Pair programming is the practice of two developers sharing a single work station in order to foster a collaborative work environment.  

The two parts to the pair are the Driver- who does the typing and hands-on portion of coding; and the Navigator - who thinks about how an algorithm might work in code and guides the driver with words.  

**Advantages of Pair Programming:**
- Greater efficiency
- Engaged collaboration
- Learning from fellow students
- Practice social skills
- Job interview readiness
- Work environment readiness  

[Home](README.md)|[Back to Top](class-04.md)