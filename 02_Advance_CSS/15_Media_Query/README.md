# CSS Media Queries

## 1. What is a Media Query?

A **Media Query** in CSS is a technique used to apply different styles to a web page based on the device's characteristics, such as screen width, height, resolution, or orientation. It enables developers to create responsive designs that adapt to various devices and screen sizes.

---

## 2. Importance of Media Queries

- **Responsiveness**: Media queries allow web pages to be adaptable and mobile-friendly by altering the layout depending on the screen size or device characteristics.
- **User Experience**: They ensure that content is displayed optimally on all devices, providing a seamless browsing experience.
- **Device Targeting**: Media queries enable developers to apply specific styles to desktops, tablets, mobile devices, and even print layouts.
- **Performance**: With media queries, developers can load lighter or more appropriate stylesheets for different devices, improving page load times.

---

## 3. Media Query Syntax

The general syntax of a media query in CSS is as follows:

```css
@media media-type and (condition) {
  /* CSS rules */
}
```
---
### Breakdown:
- @media: The keyword to define a media query.
- media-type: Specifies the type of media (e.g., screen, print).
- condition: A condition that must be met for the styles to be applied, such as max-width, min-width, orientation, etc.
---
### Syntax Example:
```css
@media screen and (max-width: 768px) {
  /* Styles for devices with a max width of 768px */
}
```
---
## Media Query Features:

| **Feature**       | **Description**                                      |
|-------------------|------------------------------------------------------|
| `width`           | Defines the width of the viewport.                   |
| `height`          | Defines the height of the viewport.                  |
| `device-width`    | Defines the width of the device screen.              |
| `device-height`   | Defines the height of the device screen.             |
| `orientation`     | Defines the orientation of the device (portrait or landscape). |
| `resolution`      | Defines the resolution of the output device.         |
---
