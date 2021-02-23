#
## Transforms:
* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
- Transform Syntax:
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
* 2D Transforms (with x and y) :
* the value  
- Rotate: provides the ability to rotate an element from 0 to 360 degrees.
-  Scale (x,y):allows you to change the appeared *size* of an element
- Translate:pushing and pulling an element in different directions without interrupting the normal flow of the document
- Skew(x,y) :is used to distort elements on the horizontal axis, vertical axis, or both// skewX // skewY
*Combining Transforms*
- `transform: rotate(25deg) scale(.75);`
- `transform: skew(10deg, 20deg) translateX(20px);`
- Transform Origin: top left bottom right .
- Perspective : can be seen in three-dimensional drawings.
*3D Transforms
Rotate / Scale / Translate / Skew 
* Transform Style :
- preserve-3d :allows the transformed children elements to appear in their own three-dimensional plane
- flat : value forces the transformed children elements to lie flat on the two-dimensional plane.
* Backface Visibility: By default the elements are shown from the back.values //  hidden // visible .
 ## Transitions & Animations 
 There are four transition related properties in total, including `transition-property`, `transition-duration`(seconds (s) and milliseconds (ms).), `transition-timing-function`, and `transition-delay`. Not all of these are required to build a transition, with the first three are the most popular.
- Transition Timing : is used to set the speed in which a transition will move.
- Transition Delay
* *Shorthand Transitions*`transition: background .2s linear, border-radius 1s ease-in 1s;`
##  Animations 
- Animations Keyframes 
- Animation Name
- Animation Duration, Timing Function, & Delay
- Customizing Animations 
- Animation Iteration 
*Shorthand Animations* ` animation: slide 2s ease-in-out .5s infinite alternate;`
* Square to circle :`border-radius`
