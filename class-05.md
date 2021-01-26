[Home](README.md)  

## HTML Images

When adding images to your site it is good practice to keep them in their own images folder. Images should, be relevant, convey information, mood, and fit the color palette.

\<img> - is the image tag that carries the attributes of:
  - src - tells the browser where it can find the image
  - alt - provides text description of the image if you can't see it
  - title - provides additional information about the image, some browsers will show when the user hovers over the image
  - height - specifies height
  - width - specifies width  

  > The align attribute has been removed from HTML5, but can still be come across in older code.  

\<figure> - contains images and their caption (\<figcaption>) so that the two are associated
\<figcaption> - allow web page authors to add a caption to an image

### Three Rules for Creating Images
  1. Save images in the right format
  1. Save images at the right size
  1. Measure images in pixels

**Image Formats**  

JPEG - chose JPEG when you have many different colors/shades in the image
GIF or PNG - use when saving images with few colors or large areas of the same color  
Animated GIF - show several frames of an image in sequence; each frame increases the size of the file- adding time for the image to download, therefore best suited for simple animations

Images on your website should preferably be saved at the same height and width you want them to appear on the page.

## Color

**Three ways to specify color in CSS:**  

  1. RGB values - Example: rgb(100,100,90)
  1. HEX Codes - Example: #ee3e80
  1. Color Names- Example: blue  

  **CSS3 introduces new and intuitive way to specify color using hue, saturation, and lightness values:**  

   HSL -  
    - Hue - color
    - Saturation - the amount of gray in a color; represented from 0% - 100%
    - Lightness - amount of white or black in a color from 0% (black) - 100% (white), 50% lightness is normal. Lightness is sometimes referred to as luminosity. (Lightness differs from brightness, brightness only adds black)

   HSLA - HSL but includes Alpha
    - Alpha - represents transparency as a number between 0 - 1.0; whereas 0.5 represents 50% transparency

  > Older browsers won't recognize HSL, so it is a good idea to add an extra rule specifying color by name, RGB, or HEX value.

## Text
  **Typeface**
    - Serif - extra details on the end of strokes
    - Sans Serif - straight ends, cleaner design
    - Monospace - each letter has the same width
    - Cursive - have joining strokes or handwriting style
    - Fantasy - usually decorative, often used for titles

## Ch. 12 Text Review:

1. What are some properties you can use to control font?
1. What can text-decoration property be used for?
1. What are pseudo-classes?
1. What is leading and kearning?  

[Home](README.md)|[Back to Top](class-05.md)