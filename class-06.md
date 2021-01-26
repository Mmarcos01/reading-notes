[Home](README.md)  

## Objects

Objects group together a set of variables and functions to create a model of something you world recognize in the real world.
  - In an object: 
      - variabless become known as properties (properties tell us about the object)
      - functions become known as methods (methods represent tasks that are associated with the object)  

**Key** - properties and methods have a name and a value (like variables and named functions) in an object the name is called a key (Ex. Pg. 101)  

### Literal Notation 

There are several ways to create objects but Literal Notation is the easiest and most popular way.  (Ex. Pg. 102)  

**this** - The *this* keyword refers to the current object in a method or constructor.

### Dot Notation

You access properties or methods of an object using dot notation: use the name of the object, followed by a period, then the name of the property or method you want to access. The period is known as the **member operator**, the property or method on its right is a member of the object on its left.  

You can also access properties using square brackets, where the object name is followed by square brackets, with the property or method inside them. This notation is most commonly used when:
  - The name of the property or method contains special characters (such as a dash)
  - The name of the property is a number (allowed but should be avoided)
  - A variable is being used in a place of the property name 

## Document Object Model

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how Javascript can access and update the contents of a web page while its in the browser window.

> The DOM is neither part of HTML or Javascript. It is implemented by all major browser makers and covers two primary areas: Making a model of the HTML page and Accessing and changing the HTML page.  

People my call the DOM an Application Programming Interface (API), which lets programs (and scripts) talk to eachother.  

DOM Tree - model of a web page, consists of four main types of nodes: (Ex. Pg. 188)
  1. The Document Node - represents entire page
  2. Element Nodes - describe structure (such as HTML elements)
  3. Attribute Nodes
  4. Text Nodes  

Accessing and updating the DOM tree has two steps:
  1. Locate the node that represents the element you want to work with (access elements)
  1. Use its text content, child elements, and attributes (work with those elements)



[Home](README.md)|[Back to Top](class-06.md)