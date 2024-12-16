
# Combining Selections :

## **Grouping Selector**
- Applies the same style to multiple elements by separating selectors with commas.

```css
h1, h2, h3 {
  font-family: Arial, sans-serif;
}
```

---

## **Descendant Selector**
- Targets elements inside a specific parent element.

```css
div p {
  color: red;
}
```

---

## **Child Selector**
- Targets direct child elements of a specified parent.

```css

div > p {
  font-weight: bold;
}
```

---

## **Adjacent Sibling Selector**
- Selects an element that is immediately preceded by a specified sibling.

```css
h1 + p {
  margin-top: 20px;
}
```

---

## **General Sibling Selector**
- Selects all siblings of a specified element.

```css
h1 ~ p {
  font-style: italic;
}
```

---

## **Attribute Selector**
- Targets elements based on their attributes.

```css
/* Element with the 'type' attribute set to 'text' */
input[type="text"] {
  border: 1px solid gray;
}
```

---

## **Pseudo-classes**
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

## **Combinators**
- Combine multiple selectors.
  - **Descendant**: `ancestor descendant`
  - **Child**: `parent > child`
  - **Adjacent Sibling**: `element1 + element2`
  - **General Sibling**: `element1 ~ element2`

---
