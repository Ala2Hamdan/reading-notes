#  Chart.js, Canvas

* Charts :
> A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. `<canvas></canvas>` 
- the `<canvas>` element has only two attributes, `width` and `height`./ and not using CSS.
- the `<canvas>` element requires the closing tag `</canvas>`.
- The `<canvas>` element has a method called `getContext()`, used to obtain the rendering context and its drawing functions. takes one parameter`2d`
- Drawing rectangles :
- There are three functions that draw rectangles on the canvas:
1. `fillRect(x, y, width, height)`
Draws a filled rectangle.
2. `strokeRect(x, y, width, height)`
Draws a rectangular outline.
3. clearRect(x, y, width, height)`
Clears the specified rectangular area, making it fully transparent.
* Drawing paths :
- beginPath()

* Drawing text:
`fillText(text, x, y [, maxWidth])` ` strokeText(text, x, y [, maxWidth])`
* Styling text :
- `font = value` `textAlign = value` `textBaseline = value` `direction = value`
* Advanced text measurements:
- `measureText()`

