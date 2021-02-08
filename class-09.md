[Home](README.md)

# Forms

Forms on the web can be used in various ways; they allow the user to search, register for services, and sign up for mailing lists. To differentiate between various pieces of inputted data, information is sent from the browser to the server using name/value pairs.

### Adding Text

Text input - used for single line of text such as an email or name  
Password input - like a single line text box but hides the characters when entered  
Text area - for longer areas of text such as messages and comments  

### Choices

Radio buttons - when a user must select one of a number of options
Checkboxes - when the user can select one or more options
Drop-down boxes - when a user must pick one of a number of options from a list  

### Submitting

Submit buttons - submit data from your form to another page
Image buttons - similar to submit buttons but allow you to use an image
File upload - allows users to upload files to a website

## Form Structure

\<form> - form controls live inside this element and carry the following attributes:
  - action - holds url for the page on the server that will receive the information in the form when submitted
  - method - forms can be sent using one of two methods: get or post
  - id - identifies the form distinctively from other elements  

\<input> - used to create several different form controls with attributes :
  - type="text" or type="password"; also "radio", "checkbox", "file", "submit", "image", "date", "email", "search"
  - name - names the form 
  - maxlength - limits characters  
  - attributes value and checked for selection forms

  \<textarea> - creates multiline input form

  \<select> - allows users to select from a dropdown box (attributes: name, value, selected)
    - \<option> - this element will hold the words in the select drop down list
    - Multiple select box use \<select> with attributes: size and multiple  

### Labelling form controls

\<label> - can be used in two ways:
  1. It can wrap around both text description and the form input
  2. It can be kept seperate from the form control and use the for attribute to indicate which form control it is a label for.  

for - attribute states which form control the label belongs to  

\<fieldset> - you can group related form controls together inside this element
\<legend> - can come directly after the opening \<fieldset> tag and contains a caption which helps indentify the purpose of that group of form controls.

## Lists, Tables, and Forms

### Lists
list-style-type - indicates type of bullet you want in your list
list-style-image - allows image to be used as bullet point
list-style-position - indicates if marker should be inside or outside the box containing the main point
list-style - allows you to express the markers' style, image and position properties in any order  

### Tables
empty-cells - you can show, hide or inherit borders on empty cells
border-spacing - allows control over distance between adjacent cells
border-collapse - borders are collapsed into a single border where possible

### Forms
People don't generally enjoy filling out forms, utilize CSS and style forms to make them more attractive to the user.  

Commom cursor styles: auto, crosshair, default, pointer, move, text, wait, help, url("cursor.gif);  

### Web Developer Toolbar
 [www.chrispederick.com](https://www.chrispederick.com/work/web-developer)  

 The Web Developer Toolbar is a helpful extension for the browser that provides tools to show the CSS styles being applied to an element when you hover over it, along with structure of HTML.

## Events

Events occur when the user makes an interaction, such as click, tap, hover or swipe, type or resize a window. When an event occurs or fires, it can trigger a particular function; reacting to the event. Events fire and trigger Scripts.  

List of event types (pg 246)  

Event handling - the steps involved in getting user interations to trigger JavaScript code
  1. Select the element node(s) you want the script to respond to
  2. Indicate which event on the selected node(s) will trigger the response (called binding)
  3. State the code you want to run when the event occurs

### Three ways to bind an event to an element




[Home](README.md)|[Back to Top](class-09.md)