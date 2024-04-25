# CSS Grid by Sophie Thomas
A simple, responsive grid system using CSS Grid and Scss. 

I have developed a simple, responsive grid system using CSS Grid properties that you can integrate into your projects. By default, the grid is set to 12 columns, but you can easily tweak this by adjusting the $grid-columns variable. The columns are adjusted for smaller screens using @media queries at defined breakpoints.

Scss was used to ensure my code base could be kept organised and be maintaned eaisly. This was achieved through defining variables and mixins, nest selectors, performing calcuclations and applying flow control rules.

When using this grid:

- Treat both .grid-container and .grid-container-fluid as rows.

- To work out the offset number, begin at the start of the row each time. When determining the offset number for columns beyond the first, add the span and offset numbers on the columns that precede the one you are currently offsetting.

Codepen: https://codepen.io/fromsophie/pen/BaEvxyZ