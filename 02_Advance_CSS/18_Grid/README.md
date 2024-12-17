# CSS Grid

## 1. What is CSS Grid?

CSS Grid is a two-dimensional layout system for the web. It allows you to create complex layouts by defining rows and columns, and placing elements into these rows and columns. Unlike Flexbox, which is a one-dimensional layout system, CSS Grid can handle both horizontal and vertical layouts simultaneously.

---

## 2. `display: grid`

- The `display: grid` property is used to define a container as a grid container, making its children grid items.
- When a container is set to `display: grid`, it becomes a grid container and the children (direct descendants) automatically become grid items.
- This enables the use of grid-related properties such as `grid-template-rows`, `grid-template-columns`, and others to control the layout.

---

## 3. Grid Sizing

Grid sizing refers to defining the size of the rows and columns in a grid layout. 

### Key Properties for Grid Sizing:
- **`grid-template-rows`**: Defines the number and size of rows in the grid.
- **`grid-template-columns`**: Defines the number and size of columns in the grid.
- **`grid-auto-rows`**: Specifies the size of rows that are automatically created when content overflows the predefined grid structure.
- **`grid-auto-columns`**: Specifies the size of columns that are automatically created when content overflows the predefined grid structure.
- **`grid-gap` or `gap`**: Specifies the space between rows and columns.

Grid sizing can use different units, including `px`, `%`, `fr` (fractional units), and `auto`.

---

## 4. Grid Placement

Grid placement refers to how items are placed in the grid, both in terms of where they start and how many grid cells they span.

### Key Properties for Grid Placement:
- **`grid-column-start`**: Defines where the item will start in terms of columns.
- **`grid-column-end`**: Defines where the item will end in terms of columns.
- **`grid-row-start`**: Defines where the item will start in terms of rows.
- **`grid-row-end`**: Defines where the item will end in terms of rows.
- **`grid-column`**: A shorthand for setting both `grid-column-start` and `grid-column-end`.
- **`grid-row`**: A shorthand for setting both `grid-row-start` and `grid-row-end`.

The combination of these properties gives full control over the placement and span of grid items.

---

## 5. Summary

CSS Grid is a powerful layout tool that offers precise control over both rows and columns in a two-dimensional space. Using properties like `display: grid`, `grid-sizing`, and `grid-placement`, developers can create complex and responsive layouts with ease.

---
## Comparison of `display grid`, `grid sizing`, and `grid placement`

| **Feature**            | **Description**                                                                                                                                                   |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **`display: grid`**     | Defines the container as a grid and activates grid layout for its children (grid items). It makes the container a grid container.                                |
| **`grid sizing`**       | Refers to defining the number of columns and rows and their respective sizes. Uses properties like `grid-template-columns`, `grid-template-rows`, `gap`, etc.     |
| **`grid placement`**    | Refers to placing grid items into specific positions in the grid. Uses properties like `grid-column`, `grid-row`, `grid-column-start`, `grid-row-start`, etc.    |

---

## Properties

| **Property**                | **`display: grid`**                                    | **`grid sizing`**                                       | **`grid placement`**                                      |
|-----------------------------|--------------------------------------------------------|---------------------------------------------------------|-----------------------------------------------------------|
| **Definition**               | Activates grid layout on the container                | Defines the structure and size of rows and columns      | Places grid items within the grid container               |
| **Key Properties**           | `display: grid`                                       | `grid-template-columns`, `grid-template-rows`, `gap`     | `grid-column`, `grid-row`, `grid-column-start`, `grid-row-start` |
| **Purpose**                  | Establishes the grid container                        | Defines the grid's structure (rows, columns, gaps)      | Controls where and how grid items are placed              |
| **Behavior**                 | Converts the container into a grid                    | Sets the layout dimensions (static or flexible)         | Determines the position and span of grid items            |

---

## Summary

- **`display: grid`**: Defines the container as a grid and allows the use of grid layout.
- **`grid sizing`**: Determines the number of rows and columns, as well as their sizes and the gaps between them.
- **`grid placement`**: Determines where the grid items should be placed and how many rows or columns they should span.

---
