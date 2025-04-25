# d3-playground

## Concepts

- **.select()** – grab a DOM element
- **.append()** – add a new element like circle, rect
- **.attr()** – set attributes like position, color, size
- **.style()** – set CSS style
- **.data() + .enter()** – bind data to elements

## Two Methods to Create and Manage Elements

1. **Direct DOM Creation and Manipulation**
   - Use `.append` manually for each element
   - Better for quick prototyping, one-off elements
   - Not ideal for representing models and interactivity

2. **Data-Driven Binding**
   - Bind a visual interface to an existing data set
   - Easy to update and redraw, scales well
   - Great for simulation and interactivity

## Approach

- Represent each element as an object in a data array (or custom data structure down the line)
- Draw based on the data types
- Make it interactive
-- dragging elements
-- clicking elements
-- hovering elements
- Easily update layout, colors, labels
- Add export feature

## What's Done?

- Rough model visualization using hardcoded model data

## What's Next?

- Understand how models are initialized/saved in AWE
- Parse that information to easily create visual model for SimBioUI
- Rather than specifically assigning (x, y) coordinates to each element, create a dynamic environment with automatic layout and positioning (d3.forceSimulation())
