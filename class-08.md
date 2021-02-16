# layout wtih CSS
* Key Concepts in Positioning Elements:
- CSS treats each HTML element as if it is in its own box.
- Block-level elements: start on a new line. exp:(`<h1>` `<p>` `<ul>` `<li>`)
- Inline elements : flow in between surrounding text. exp: (`<img>` `<b>` `<i>`)
- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
- A box may be nested inside several other block-level elements. The containing element is always the direct parent of that element.
* *box offset* properties to tell the browser how far from the top or bottom and left or right it should be placed.
* Controll ing the Position of Elements
- positioning schemes: that allow you to control the layout of a page: 
1. normal flow :Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.
2. relative positioning :This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
3. absolute positioning :This positions the element in relation to its containing element. 
* Fixed Positioning
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
* Floating Elements
Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box
* When you move any element from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.

### Screen Sizes
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens
* Screen Resolution:
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens
* Page Sizes : 
- Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).
* Fixed Width Layouts:
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
* Liquid Layouts: 
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.
* Layout Grids: 
Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements — how they are organized on a page. Many designers use a grid structure to help them position items on a page, and the same is true for web designers.
