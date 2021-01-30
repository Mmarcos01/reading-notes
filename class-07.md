[Home](README.md)  

## Domain Modeling

Domain modeling the process of creating a coceptual model in code for a specific problem that incorporates behavior and data. A well articulated domain model can verify and validate understanding of the problem, and define vocabulay that can be used between technical and business teams.  

Object-oriented programming in Javascript at its most fundamental level:
  1. The **new** keyword creates an object.
  1. The constructor function initializes properties inside that object using the **this** variable.
  1. The object is stored in a variable for later use.  

Constructor Function's Prototype - When a function is created in JavaScript, a prototype function is added and can be accessed by functionName.prototype. Think of the prototype as an object's stunt double.

## HTML: Tables

A table represents information in grid format. Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.  

**<\table>** - creates a table
**<\tr>** - indicate the start of each row using the opening <\tr> tag; standing for table row. This is followed by one or more <\td> elements; one for each cell in the row. At the end of the row use a a closing <\tr> tag.
**<\td>** - stands for table data and represents a table cell, some browsers automatically draw lines around the table and/or cells
**<\th>** - stands for table headings and represents the heading for a column or row
**colspan** - attribute that can be used on <\th> or <\td> elements and indicate how many columns that cell should run across
**rowspan** - attribute that can be used on <\th> or <\td> elements and indicate how many rows that cell should run down  

### Long Tables

**<\thead>** - the headings (<\th>) of the table should sit inside this element
**<\tbody>** - the table body should sit inside this element
**<\tfoot>** - the footer should be inside this element  

## JavaScript: Functions, Methods, and Objects

### Creating an Object: Constructor Notation

The *new** keyword and the object constructor create a blank object, to which properties and methods can then be added.  

To update the value of properties, use dot notation or square brackets. For example, using the **delete** keyword:  

delete object.key;  

You create *instances* of the objecct using the constructo function. The **new** keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function.  

Example: (pg. 109)

var quayHotel = new Hotel ('Quay', 40, 25);
var parkHotel = new Hotel ('Park', 120, 77);  

### Ways to create Objects

  1. Create the object, then add properties and methods
      Literal Notation or Object Constructor Notation

  1. Create an object *with* properties and methods
      Literal Notation or Object Constructor Notation

*See examples on page 113 for creating objects and storing data*  

## Build-In Objects




[Home](README.md)|[Back to Top](class-07.md)