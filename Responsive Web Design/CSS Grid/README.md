# CSS Grid

The CSS Grid offers a grid-based layout system making it easier to design web pages without having to use floats and positioning.

Adding " display: grid " to an element turns it into a grid container.

## Grid Lines

The hypothetical horizontal and vertical lines that create the grid are referred to as lines. 

These lines are numbered starting with 1 at the top left corner of the grid and move right for columns and down for rows, counting upward.

An item can be placed on the grid using these lines with the help of grid-row, grid-column and grid-area properties.

## auto-fill v/s auto-fit

These keywords tell the browser to handle the column sizing and element wrapping, so that the elements will wrap into rows when the width is not large enough to fit them in.

Up to a certain point, both auto-fill and auto-fit show identical results.

After this point, auto-fill creates new columns to add to the rows and displays them even if there is no content that could occupy those columns. 

auto-fit also creates new columns but those columns don't occupy any space, instead that space is used to expand the filled in columns to fit the empty row space.