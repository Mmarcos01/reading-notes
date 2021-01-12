[Home](README.md)

## CSS

CSS (short for Cascading Style Sheets) is used in the **presentation** of a file. It is a language used to stylize html elements, such as it can be used to control the layout and colors displayed.

### CSS Style Rules:
 	1. Selector -selects which element the rules apply to, for example p
	1. Declaration -declares how the elements in the selector should be modified, for example p {*font family: Arial;*} A declaration has two parts, a property and a value separated by :

### Example:
	
h1, h2, h3 {font family: Arial;
	   color: blue;}

This says headings 1, 2, and 3 will be in the Arial font and colored blue.

### Using external CSS

When using an external CSS file to style your html file, the link element would live in the <head> of the html file and look like this:

<link href="css/styles.css" type="text/css" rel="stylesheet" />

This element includes the link to the file, the type of file it is, and it's relationship to the html.
	- Advantages: smaller file size, quicker loading, easier to maintain on multi page site

### Using internal CSS

When writing CSS within the html file you would write it between the tags <style></style> and this would live within the <head> element.

### CSS Selectors

Selectors are patterns used to select elements you want to style, for a list check [W3Schools](https://www.w3schools.com/cssref/css_selectors.asp)

### How CS rules cascade:

If there area two or more rules applied to an element:
 - If two selectors are identical, the latter will take precedence
 - The more specific selector will take precedence
 - You can use !important after any property value to indicate that it should take precedence over any other rules applied to the same element
 
### Inheritance

Properties can be inherited from parent to their child elements. This saves time from having to apply the property to each element. You can force properties to inherit values from their parent by using **inherit** for the value of the property.

### Open your site in multiple browsers and operating systems before launch.

Your code may display differently on some browsers, this would be a browser quirk or CSS bug. Try google for fixes.

<!-- 
Helpful css to see boxes around different sections of css

* {
  border: 1px solid white;
  margin: 25px;
  padding: 10px;
} -->

[Home](README.md) | [Back to Top](css.md)