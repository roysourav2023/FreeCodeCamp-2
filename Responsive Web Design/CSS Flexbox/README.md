# CSS Flexbox

CSS Flexbox (Flexible box) provides an efficient way to distribute items in a container dynamically. It is a layout mode that arranges elements in a predictable way for different screen sizes and browsers

Adding " display: flex " to an element turns it into a flex container.

## Main and Cross Axis

Every flex container has a main axis (horizontal line for rows and vertical line for columns) and a cross axis (vertical line for rows and horizontal line for columns)

" justify-content " is used to align elements along the main axis.

" align-items " is used to align elements along the cross axis.

## flex-shrink

This property allows an item to shrink if the flex container is too small. Items shrink when the width of the parent container is smaller than the combined widths of all the flex items within it.

It takes numbers as values. The higher the number, the more it will shrink compared to the other items in the container.

## flex-grow

This property is the opposite of the " flex-shrink " property.

It controls the size of items when the parent container expands.

## flex-basis

The flex-basis property specifies the initial size of the item before CSS makes adjustments with flex-shrink or flex-grow.

## Order

The order property is used to tell CSS the order of how flex items appear in the flex container.

The property takes numbers as values, and negative numbers can be used.

