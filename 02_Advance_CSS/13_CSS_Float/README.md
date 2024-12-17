# CSS Float Property

The `float` property in CSS is used to position an element to the left or right of its container, allowing text or other inline elements to wrap around it.

---

## **1. Overview of Float**

The `float` property places an element on the left or right side of its container, and content (like text or images) flows around it.

### **Syntax**:
```css
float: value;
```
## 2. Float Property Values

| **Value**   | **Description**                                                                 |
|-------------|---------------------------------------------------------------------------------|
| `none`      | Default value; the element does not float.                                      |
| `left`      | The element floats to the left of its container, and content wraps around it.   |
| `right`     | The element floats to the right of its container, and content wraps around it.  |
| `inherit`   | The element inherits the float value from its parent.                           |

---

## 3. Behavior of Floated Elements

- A floated element is removed from the normal document flow and positioned to the specified side (`left` or `right`) of its container.
- Other content wraps around the floated element.
- The height of the parent container may collapse if it only contains floated elements.

---

## 4. Clearing Floats

When an element is floated, it may affect the layout of subsequent elements. To handle this, you can use the `clear` property.

### **Syntax**:
```css
clear: value;
```