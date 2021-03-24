# Grid
- CSS Grid Layout (Grid), is a two-dimensional grid
- to use it we need to define html element to be  Grid Container  and in CSS through give it properties;

*** Note: float, display: inline-block, display: table-cell, vertical-align and column-* properties have no effect on a grid item *** 
* Properties for the Parent
Grid Container
- `display`
values:
 `grid` – generates a block-level grid
`inline-grid` – generates an inline-level grid
- `grid-template-columns` `grid-template-rows`
values 
`<track-size>` – can be a length, a percentage, or a fraction of the free space in the grid (using the fr unit)
`<line-name>` – an arbitrary name of your choosing
- 

* Properties for the Children
(Grid Items)
- `grid-column-start`  `grid-column-end`  `grid-row-start` `grid-row-end`

values 
`<line>` – can be a number to refer to a numbered grid line, or a name to refer to a named grid line
`span <number>` - the item will span across the provided number of grid tracks
`span <name>` – the item will span across until it hits the next line with the provided name
`auto` – indicates auto-placement, an automatic span, or a default span of one

> [referancfe](https://css-tricks.com/snippets/css/complete-guide-grid/#introduction)