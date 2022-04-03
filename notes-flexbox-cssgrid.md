# Flexbox Notes and Overview

- a set of related CSS properties for building 1-dimensional layouts
- allow browser automatically divide empty spaces inside a container element between child elements and
- automatically align items to one another inside a parent container
- solves common problems such as vertical centering and creatign equal-height colums
- replacing floats

## Flexbox Terminology

- flex container
- flex items
- main axis
- cross axis

### Flex Container Properties

```css
- gap: 0 | < length >
    🎲 to create space b/w items, without using margin
- justify-content: flex-start; | < flex-end  > | <center> | <space-between> | <space-around> | <space-evenly>
    🎲 to align items alon main axis (horizontally, by default)
- align-items: stretch; | <flex-start> | <flex-end> | <center> | <baseline>
    🎲 to align items along cross axis (vertically, by default)
- flex-direction: row | row-reverse | column | column-reverse
    🎲 to define which is the main axis
- flex-wrap: nowrap | wrap | wrap-reverse
    🎲 to allow items to wrap into new line if they are too large
- align-content: stretch | felx-start | flex-end | center | space-between | space-around
    🎲 only applies when there are multiple lines(flex-wrap: wrap)
```

### Flex Items

```css
- align-self: auto | stretch | flex-start | flex-end | center | baseline
    🎲 to overwrite align-items for individual flex items
- flex-grow: 0 | <integer>
    🎲 to allow an element to grow (o means no, +1 means yes)
- flex-shrink: 1 | <integer>
    🎲 to allow an element to shrink (0 means no, 1+ means yes)
- flex-basis: auto | <length>
    🎲 to define an item's width, instead of the width property
- flex: 0 1 auto | <int> <int> <len>
    🎲 recommended shorthand for flex-grow, -shrink, -basis
- order: 0 | <integer>
    🎲 controls order of items. -1 makes items first, 1 makes it last
```

### Flex Container

### Flex Items
