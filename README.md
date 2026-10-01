
day 6
CSS Basics — Selectors, Box Model
What CSS is
CSS (Cascading Style Sheets) controls how HTML looks — colors, spacing, fonts, layout. HTML = structure, CSS = presentation. Without CSS, every page is just plain text and default browser styling.
Three ways to add CSS
<!-- 1. Inline -->
<p style="color: red;">Text</p>

<!-- 2. Internal -->
<head>
  <style>
    p { color: red; }
  </style>
</head>

<!-- 3. External (preferred) -->
<head>
  <link rel="stylesheet" href="style.css">
</head>
​
External is standard practice — keeps HTML and styling separate, reusable across multiple pages.
Basic CSS syntax
selector {
  property: value;
}
​
p {
  color: blue;
  font-size: 16px;
}
​
Selector = what to target. Property:value pairs inside {} = what to change. Every line ends with ;.
Selectors
Element selector — targets all elements of that type:
p {
  color: gray;
}
​
Class selector — targets elements with a specific class, reusable across multiple elements:
<p class="highlight">Text</p>
​
# day-6
css basic-selectors,box model
