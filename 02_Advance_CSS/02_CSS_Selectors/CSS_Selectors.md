
# Types of CSS Selectors

CSS selectors are used to target HTML elements for styling. Below are the main types of CSS selectors:

---

## **1. Universal Selector**
- Selects all elements in the document.

```css
* {
  margin: 0;
  padding: 0;
}
```

---

## **2. Type Selector (Element Selector)**
- Selects all elements of a given type (e.g., all `<p>` or `<h1>` tags).

```css
p {
  font-size: 16px;
}
```

---

## **3. Class Selector**
- Targets elements with a specific class attribute.

```css
.my-class {
  color: blue;
}
```

---

## **4. ID Selector**
- Targets an element with a specific `id` attribute.

```css
#my-id {
  background-color: yellow;
}
```

---

## **5. Grouping Selector**
- Applies the same style to multiple elements by separating selectors with commas.

```css
h1, h2, h3 {
  font-family: Arial, sans-serif;
}
```

---

## **6. Descendant Selector**
- Targets elements inside a specific parent element.

```css
div p {
  color: red;
}
```

---

## **7. Child Selector**
- Targets direct child elements of a specified parent.

```css
div > p {
  font-weight: bold;
}
```

---

## **8. Adjacent Sibling Selector**
- Selects an element that is immediately preceded by a specified sibling.

```css
h1 + p {
  margin-top: 20px;
}
```

---

## **9. General Sibling Selector**
- Selects all siblings of a specified element.

```css
h1 ~ p {
  font-style: italic;
}
```

---

## **10. Attribute Selector**
- Targets elements based on their attributes.

```css
/* Element with the 'type' attribute set to 'text' */
input[type="text"] {
  border: 1px solid gray;
}
```

---

## **11. Pseudo-classes**
- Targets elements based on their state or position.

```css
a:hover {
  text-decoration: underline;
}

li:nth-child(2) {
  color: green;
}
```

---

## **12. Pseudo-elements**
- Targets specific parts of an element.

```css
p::first-line {
  font-weight: bold;
}
```

---

## **13. Combinators**
- Combine multiple selectors.
  - **Descendant**: `ancestor descendant`
  - **Child**: `parent > child`
  - **Adjacent Sibling**: `element1 + element2`
  - **General Sibling**: `element1 ~ element2`

---

## **14. Not Selector**
- Excludes elements that match a specific selector.

```css
p:not(.exclude) {
  color: gray;
}
```

---

## **15. Custom Selectors (CSS Variables in Selectors)**
- With modern CSS, you can also use variables to define dynamic styling rules.

```css
:root {
  --main-color: blue;
}
p {
  color: var(--main-color);
}
```
