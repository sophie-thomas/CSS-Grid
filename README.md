# CSS Grid by Sophie Thomas
A simple, responsive grid system using CSS Grid and Scss.

I have developed a simple, responsive grid system using CSS Grid properties that you can integrate into your projects. By default, the grid is set to 12 columns, but you can easily tweak this by adjusting the $grid-columns variable.

Scss was used to ensure my code base could be kept organised and be maintained easily. This was achieved through defining variables and mixins, nesting selectors, performing calculations, and applying flow control rules.

When using this grid:

- Treat both .grid-container and .grid-container-fluid as rows.

- To work out the offset number, begin at the start of the row each time. When determining the offset number for columns beyond the first, add the span and offset numbers on the columns that precede the one you are currently offsetting.

- The columns can be adjusted for smaller screens by defining different column spans and offsets for each breakpoint. Add either xl-, lg-, md-, or sm- before span- and/or offset- to adjust how the columns are positioned.

- Text alignment can also be adjusted for smaller screens using the defined breakpoints. Add either xl-, lg-, md-, or sm- before either align-left, align-right, or align-center to adjust the text alignment.

Codepen: https://codepen.io/fromsophie/pen/rNbbPWR

Previous versions:
CSS Grid: V1 - Column spans and offsets are adjusted automatically for smaller screens using @media queries at defined breakpoints rather than being able to manually define them. Codepen: https://codepen.io/fromsophie/pen/BaEvxyZ