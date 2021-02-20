[Home](README.md)

## Chart.js

Charts are better for displaying data visually than tables. They're easier to look at and convey data quickly. However, aren't always easy to make. Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw the graph on the page and makes creating charts much easier. All that is required is the script and a single \<canvas> node to render the chart.

## The Canvas Element

[MDN Web Docs: Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)  
[MDN Web Docs: Drawing](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)  
[MDN Web Docs: Styling](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)  
[MDN Web Docs: Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)  

\<canvas> - the canvas element has only two attributes of width and height; both are optional and can also be set using DOM properties. When no width and height attributes are specified the canvas will initially be 300x150 pixels. The element can ve sized by CSS, but during rendering the image is scaled to fit its layout size; if the CSS sizing doesn't consider the ratio of the initial canvas, it will appear distorted.  

The canvas element can be styled like any normal image. However, the rules don't affect the actual drawing on the canvas; that can be done separately. When no styling rules are applied to the canvas, it will appear transparent.  

> It's a good idea to supply an id to your element because it makes it easier to identify it in a script.  

### Fallback Content

You should define some fallback content for your canvas element in case a browser can not support it. Just insert the alternate content inside the \<canvas> element. Browsers that do support canvas will ignore the content inside the container and just render the canvas normally.

### Rendering

The canvas element creates a fixed-sized drawing surface that exposes one or more **rendering contexts**, which are used to create and manipulate the content shown. The canvas is initially blank, to display something, a script first needs to access the rendering context and draw on it. The method **getContext()** is used to obtain the rendering context and its drawing functions, it takes one parameter: the type of context.  

For 2D graphics, you specify "2d" : getContext('2d')  

[Home](README.md)