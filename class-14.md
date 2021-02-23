[Home](README.md)

## Transforms
[Resource: CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)  

The transforms property has two different settings; two dimensional and three dimensional. The syntax is the transform property followed by a value (specifying the transform type) followed by a specific amount inside parenthesis. It's good to use vendor prefixes to get the best support across all browsers. The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property.  

div {  
  -webkit-transform: scale(1.5);  
     -moz-transform: scale(1.5);  
       -o-transform: scale(1.5);  
          transform: scale(1.5);  
}

### 2D Transforms
Elements may be distorted or transformed on a 2D or 3D plane. 2D transforms on the x and y axes, while 3D also utilizes the z axis.

#### 2D Translate
Translate works similar to relative positioning. Using translateX value will change the position of an element on the horizontal axis and using translateY will change position on the vertical.

#### 2D Skew
Skew is used to distort elements on either or both axis. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical. To distort on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.

#### Combining Transforms
 To combine transforms, list the transform values within the transform property one after the other without the use of commas.

#### Transform Origin
The default transform origin is dead center of an element. The origin can be changed with the transform-origin property.

#### Perspective
For 3D transforms to work, the elements need a perspective from which to transform. The perspective can be thought of as the vanishing point.

### 3D Transforms

#### 3D Rotate
Can include rotateZ property.

#### 3D Scale
Can include scaleZ property.

#### 3D Translate
A negative value will push an element further away, while a positive will bring it closer on the z axis.

#### 3D Skew
Skew is the one 2D transform that cannot be transformed on a three dimensional scale and skewed on the z axis.

### Transform Style
Three-dimensional transforms will sometimes be applied on an element that is nested within a parent element which is also being transformed. To allow nested elements to transform in their own three-dimensional plane use the transform-style property on the parent with the preserve-3d value.

### Backface Visibility
Set the backface-visibility property to hidden, and you will hide the element whenever it is facing away from the screen.

## Transitions and Animations
[Resource: Transitions and Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

Transitions allow alteration of the appearance and behavior of an element whenever a state change occurs.

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.


[Simple CSS Transitions](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)
[Animated Buttons](https://codepen.io/retyui/pen/ByoaXV)
[CSS Animations Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)
[404](https://codepen.io/kieranfivestars/pen/MYdQxX)
[Bounce](https://codepen.io/dp_lewis/pen/gCfBv)

[Home](README.md)|[Back to Top](class-14.md)