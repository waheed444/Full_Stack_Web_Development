# CSS Positioning :
CSS positioning is used to control the layout of elements on a webpage. It allows you to position elements relative to other elements, the document, or a container.

---

## **1. Types of CSS Position:**

The `position` property defines how an element is positioned in a document. The values of the `position` property are:

- **static** (default)
- **relative**
- **absolute**
- **fixed**
- **sticky**

Each value has unique behavior, which is described in detail below.

---

## **2. Position Values**

### **2.1 Static Positioning**
- **Description**: This is the default value. Elements are positioned in the normal document flow.
- **Syntax**:
  ```css
  position: static;
  ```
  **Behavior**: top, right, bottom, and left properties do not apply.
Elements follow the natural flow of the document.
### Example:

```html
<div style="position: static;">This is a static element.</div>
```
### **2.2 Relative Positioning**
- Description: The element is positioned relative to its normal position.
- Syntax:
```css
position: relative;
top: 10px; /* Moves the element 10px down */
left: 20px; /* Moves the element 20px to the right */
```
**Behavior**:
The element still occupies space in the normal document flow.
The top, right, bottom, and left properties move the element relative to its original position.
Example:

```html
<div style="position: relative; top: 10px; left: 20px;">
  This is a relatively positioned element.
</div>
```
### **2.3 Absolute Positioning**
- Description: The element is positioned relative to the nearest positioned ancestor (relative, absolute, fixed, or sticky), or the document if no ancestor is positioned.
- Syntax:
```css
position: absolute;
top: 0; 
left: 0;
```
**Behavior:**
The element is removed from the normal document flow.
It does not affect sibling elements.
Positioned relative to the nearest ancestor with a position value other than static.
### Example:
```html
<div style="position: relative;">
  <div style="position: absolute; top: 0; left: 0;">
    This is an absolutely positioned element.
  </div>
</div>
```
### 2.4 Fixed Positioning
- Description: The element is positioned relative to the viewport (browser window) and does not move when scrolling.
- Syntax:
```css
position: fixed;
top: 10px;
right: 20px;
```
**Behavior:**
The element is removed from the normal document flow.
It stays fixed at a specific position on the screen, even when the page is scrolled.
### Example:
```html
<div style="position: fixed; top: 10px; right: 20px;">This is a fixed positioned element.
</div>
```
### 2.5 Sticky Positioning
- Description: The element toggles between relative and fixed positioning, depending on the user's scroll position.
- Syntax:
```css
position: sticky;
top: 0; /* Sticks to the top of the container */
```
**Behavior:**
The element acts as relative until it reaches a specified scroll position.
Then, it "sticks" in place (like fixed) until its parent container scrolls out of view.
### Example:
```html
<div style="position: sticky; top: 0;">
  This is a sticky positioned element.
</div>
```