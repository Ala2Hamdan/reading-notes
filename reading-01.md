# RESPONSIVE WEB DESIGN and FLOATS

## Responsive Web Design (RWD)

- Responsive web design
 is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
- Responsive generally means to react quickly and positively to any change
- adaptive means to be easily modified for a new purpose or situation, such as change
> Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.

* ***Flexible Layouts***
- Responsive web design is broken down into three main components:
   - flexible layouts
   - media queries
   - flexible media

1. flexible layouts:
- new units , specifically related to the viewport size of the browser or device:
* vw : Viewports width
* vh : Viewports height
* vmin : Minimum of the viewport’s height and width
* vmax : Maximum of the viewport’s height and width
- the formula to  identify the proportions of a flexible layout using relative values 
`target ÷ context = result`
*** flexible layouts with the formula are very useful  to create a completely dynamic website,scaling to every viewport size, but sometimes not enough when the viewport very small or very large ***  

2. Media Queries :
- Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example

* Initializing Media Queries 
There are a couple different ways to use media queries:
- `@media` rule 
- `@import` rule or by linking to a separate style sheet from within the HTML document
***`@media` rule is recommended***
>The media query expression that follows the media type may include different media features and values, which then allocate to be true or false. When a media feature and value allocate to true, the styles are applied. If the media feature and value allocate to false the styles are ignored.
* Logical Operators in Media Queries 
- `and` allows an extra condition to be added,Multiple individual media queries can be comma separated.
- `not` negates the query, specifying any query but the one identified.
- `only`  is a new operator and is not recognized by user agents using the HTML4 algorithm, thus hiding the styles from devices or browsers that don’t support media queries
* Media Features in Media Queries
- Height & Width Media Features `min-width` `max-width`
The `min` prefix indicates a values of greater than or equal to while the `max` prefix indicates a value of less than or equal to
- Orientation Media Feature `orientation`
- Aspect Ratio Media Features `min-device-aspect-ratio`
- Resolution Media Feature `resolution`
- Other Media Features `color` `color-index` `monochrome`
*** Media Query Browser Support  ***
- media queries do not work within Internet Explorer 8 and below, as well as other legacy browsers
- There are a couple suitable polyfills written in Javascript ( Respond.js ,MediaQueries.js)
* Mobile First
One popular technique with using media queries ,includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows
example :
`/* Default styles first then media queries */`
` @media screen and (min-width: 400px)  {...}`
` @media screen and (min-width: 600px)  {...}`
` @media screen and (min-width: 1000px) {...}`
` @media screen and (min-width: 1400px) {...} `
- Viewport 
`<meta name="viewport" content="width=device-width">`
3. Flexible Media
it is way to make media (Images, videos, and other media types ) scalable and changing their size as the size of the viewport changes

## All About Floats
- Float is a CSS positioning property
float values :
1. `None` (the default)
2. `Inherit` (inherit from parent element)
3. `Left`  
4. `Right`

* floats can be used to create entire web layouts.
* Clearing the Float  `clear`
An element that has the `clear` property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float
* `Clear` has four valid values
1.  `None` (the default) 
2. ` Both `(clears floats coming from either direction ***most commonly used***)
3. `Left` 
4. `Right` 
***Left and Right can be used to only clear the float from one direction respectively***
- Techniques for Clearing Floats
* The Empty Div Method `<div style="clear: both;"></div>`
* The Overflow Method
* The Easy Clearing Method uses a clever CSS pseudo selector (`:after`) to clear floats 

- Problems with Floats 
* Pushdown : fix: Make sure you don’t have any images that do this, use overflow: hidden to cut off excess.
* Double Margin Bug : fix: set display: inline on the float, and don’t worry it will remain a block-level element.
* The 3px Jog : fix: set a width or height on the affected text.
* In IE 7, the Bottom Margin Bug : fix: using bottom padding on the parent instead.
- Alternatives 
Faux Absolute Positioning technique
