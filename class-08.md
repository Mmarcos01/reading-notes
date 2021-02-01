## Layouts

### Page Sizes 

Screen sizes and display resolutions vary between users. For this reason designers try to create their pages around 960-1000 pixels wide, since most people will be able to see designs this wide on their screens. Within the top 570-600 pixels its common for the designer to let the user know what the site is about.  

### 960 Pixel Grid

Grids help set out a proportional and professional looking layout. Many designers use a grid structure to help them position items on a page. The 960 pixel grid is widely used by web designers. There are many different layouts possible using this one grid.

Advantages of using a grid:
  - create continuity between pages
  - help users predict where to find information
  - make it easier to add new content in a consistent way
  - helps people collaborate on the design in a consistent way  

## CSS Frameworks

  CSS frameworks provide code for common tasks, such as creating layout grids, styling forms, creating printer friendly versions of pages ect., this code can be used in your projects rather than writing the CSS from scratch.  

  Advantages:  
    - saves time from repeatedly writing code for the same tasks
    - will have been tested across different browsers versions (helps avoid browser bugs)  
  
  Disadvantages:  
    - often require that you use class names in your HTML code that only control the presentation of the page (rather than describe its content)
    - often contain more code than you need for your particular web page (aka code "bloat")  

### 960.gs

  The 960.gs website provides a style sheet, once linked to your HTML, you can provide the appropriate classes to your HTML code and it will create multiple column layouts. 960.gs also provides templates you can download to help design your page using a 12 column grid, or a variation using 16 columns.  

  **Grid-based framework resources:**  
  [960.gs](https://www.960.gs)  
  [blueprintcss.org](https://blueprintcss.dev)  
  [lessframework.com](https://lessframework.com)

### Adding multiple CSS files in one page

  Two ways:  
    1. Your HTML page can link to one style sheet and that one style sheet can use the @import rule to import other style sheets. @ import url("tables.css")  
    2. In the HTML you can use a seperate \<link> element for each style sheet.

[Home](README.md)|[Back to Top](class-08.md)

