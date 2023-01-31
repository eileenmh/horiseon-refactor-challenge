# Horiseon Refactor Challenge

## Description

For this week's UNC Bootcamp challenge, we were asked to refactor a marketing agency's website to make it more accessible.

We were provided with the following acceptance criteria:
```GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
The main changes I made were: 
- using semantic elements in place of div elements;
-  consolidating the CSS by reducing the specificity of the selectors and in some cases combining rules;
- and improving the order and layout of the HTML & CSS files, for easier code viewing.


# Mock Up
The following image shows the web application's appearance and functionality:

![image](./assets/images/01-html-css-git-homework-demo.jpg)

## Roadmap
Some things that can be worked on in the future:
- The layout is designed for "desktop." The elements could be made responsive to be optimized for any screen size.
- The intrinsic sizes of the images are much larger than how they're actually loading on the web page. They could be reduced to a smaller size to improve web loading.
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) could be used to practice DRY code.

---

## Credits
- Starter code provided by [UNC Coding Bootcamp](https://bootcamp.unc.edu/coding/)
- Code refactoring completed by Eileen Harvey ([@eileenmh](https://github.com/eileenmh))