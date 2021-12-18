This is going to be a practice sheet going over some modern CSS concepts.

We're going to learn flexbox, grid, psuedoelements, CSS Frameworks, and more!

I've been studying front-end tech for about 4 months now, this is going to be a review of concepts I've studied before and new one's I havn't hit yet.

That's it!


GRID
<------->
- Made for unique responsive designs 

- Can be used with Flexbox to create layouts

- display: grid; (sets the container into a grid)

- grid-template-column/row: # # #; (Can specify the number of row/columns to display in the grid)

- instead of writing the # # # of columns/rows you want, you can do "repeat(3, #px)"

- minmax(#px #fr) makes element a declared minimum and can declare a max value

- For responsivity, you can add the value "auto-fit" and the CSS is going to automatically fill the space with default # of rows/columns

- grid-column/row: #/# (Can specify where you want the div to layout by specifying the line number)

- NOTE Can use align-items/justify-items similar to flexbox

- Can display:flex to individual div elemets and shift content within them

- Can add grid-column/row gap: #px for some margin between elements