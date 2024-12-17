# CSS Display Properties

The `display` property in CSS determines how an element is rendered and how it behaves in the document layout.

---

## **List of Display Properties**

1. **`none`**  
   Hides the element completely; it does not occupy space in the layout.

2. **`block`**  
   Makes the element a block-level element, starting on a new line and taking the full width available.

3. **`inline`**  
   Makes the element an inline-level element, taking up only as much width as necessary without starting a new line.

4. **`inline-block`**  
   Behaves like `inline` but allows setting width and height.

5. **`flex`**  
   Turns the element into a flex container, enabling flexbox layout for its children.

6. **`inline-flex`**  
   Behaves like `inline` but acts as a flex container for its children.

7. **`grid`**  
   Turns the element into a grid container, enabling grid layout for its children.

8. **`inline-grid`**  
   Behaves like `inline` but acts as a grid container for its children.

9. **`table`**  
   Makes the element behave like an HTML `<table>` element.

10. **`table-row`**  
    Makes the element behave like a table row.

11. **`table-cell`**  
    Makes the element behave like a table cell.

12. **`list-item`**  
    Makes the element behave like a list item with a marker.

---

## **Summary**
- The `display` property controls the layout behavior of an element.
- Use `block`, `inline`, and `inline-block` for simple layouts.
- Use `flex` and `grid` for advanced, modern layouts.
- Use `none` to hide elements completely.

---



| **Display Value** |         **Behavior**                                                  |
|-------------------|----------------------------------------------------------|
| `none`           | Hides the element; it does not occupy any space.         |
| `block`          | Starts on a new line and takes up the full width.        |
| `inline`         | Takes up only as much width as necessary; no line break. |
| `inline-block`   | Behaves like `inline` but allows width and height.       |
| `flex`           | Turns the container into a flexbox layout.               |
| `inline-flex`    | Behaves like `inline`, but with flexbox properties.      |
| `grid`           | Turns the container into a grid layout.                  |
| `inline-grid`    | Behaves like `inline`, but with grid layout properties.  |
| `table`          | Behaves like an HTML table element.                      |
| `table-row`      | Behaves like a table row element.                        |
| `table-cell`     | Behaves like a table cell element.                       |
| `list-item`      | Behaves like a list item with a marker.                  |
| `inherit`        | Inherits the `display` value from its parent element.    |
| `initial`        | Resets the `display` property to its default value.      |
| `unset`          | Reverts to `inherit` or the default value.               |

---

