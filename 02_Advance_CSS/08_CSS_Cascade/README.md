# CSS Cascade

The **CSS Cascade** refers to the order in which CSS rules are applied to an element when there are conflicting rules. In simpler terms, if multiple CSS rules target the same element, the **cascade** decides which rule takes priority.

## Three Main Principles of CSS Cascade

1. **Order of Appearance**: If two rules have the same specificity (importance), the one that appears last in the CSS will be applied.
2. **Specificity**: Some CSS selectors are more specific than others. For example, an ID selector is more specific than a class selector, so it will override class-based styles.
3. **Importance**: If a rule is marked with `!important`, it will override other rules, regardless of specificity or order.

## Cascade Priority

1. **Inline Styles** (written directly in the HTML element) are the most specific and have the highest priority.
2. **IDs** are more specific than classes and element selectors.
3. **Classes**, **attributes**, and **pseudo-classes** are less specific than IDs.
4. **Element selectors** (like `div`, `h1`, etc.) are the least specific.

## Example of the CSS Cascade

### HTML:
```html
<p class="text">This is a paragraph.</p>
```
### CSS :
```css
/* Rule 1 */
p {
    color: blue;
}

/* Rule 2 */
.text {
    color: green;
}

/* Rule 3 */
#special {
    color: red;
}

/* Rule 4 */
p {
    color: yellow; /* This will override Rule 1 */
}

```

### Explanation:

- Rule 1: All `<p>` elements are given a color: blue;.
- Rule 2: The .text class applies color: green; to elements with that class. Since the paragraph has the class .text, it would normally be green.
- Rule 3: The #special ID would apply color: red; to any element with the ID special. However, since the paragraph doesn't have this ID, this rule doesn't apply here.
- Rule 4: This rule is applied last, so it overrides the previous rules and sets the paragraph color to yellow.

### Result:
The final color of the paragraph will be yellow, because the last matching rule (Rule 4) has the highest priority.