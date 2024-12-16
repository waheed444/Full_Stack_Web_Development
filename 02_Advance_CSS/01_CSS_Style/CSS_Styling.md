# Types of CSS Styling with Examples

CSS styling can be applied in several ways in HTML documents. Below are the main types of CSS styling with examples.

## 1. Inline CSS
Inline CSS is applied directly within an HTML element using the `style` attribute.

```html
<p style="color: red; font-size: 16px;">This is an inline styled paragraph.</p>
```
## 2. Internal CSS
Internal CSS is defined within the `style` tag in the `head` section of the HTML document.

```HTML
<head>
  <style>
    p {
      color: blue;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <p>This is an internal styled paragraph.</p>
</body>

```

## 3. External CSS
External CSS is defined in a separate .css file and linked to the HTML document using the `link` tag.

```html
<!-- HTML file -->
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <p>This is an external styled paragraph.</p>
</body>

```

```CSS
/* styles.css */
p {
  color: green;
  font-size: 20px;
}

```