## Notes

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.
11. `<style>` : placed in `head`
12. Starting CSS here, HTML that can contains CSS in `<style>` element, it's called type selector
```css
element {
 property: value;
}

BECOMES:
h1 {
 text-allign: center;
 }
```
13. Not sure but this works too if you want just one line `p {text-align: center;}`
14. `h1, h2, p {text-align: center;}`
15. Rewrite style in `style.css`
16. CSS style in HTML could be removed
17. `<link rel="stylesheet" href="styles.css">` rel : defines the relationship between a linked resource and the current document, stylesheet : imports an external resource
18. `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` there should be `name` attribute and `content` attribute within meta element, viewport : gives hints about the size of the initial size of the viewport, `content` attribute contains the value for `name` attribute,
19. `body {background-color: brown;}` just look at docs syntax please
20. burlywood
21. `<div>` has no use except is fucking useful for CSS with its `class` attribute, mainly for design layout purposes 
22. `div {width: 300px;}` : px is pixels
23. `/* comment here */`
24. = 19
25. `div {width: 80%;}`
26. `margin-left: auto;` and `margin-right: auto;` to center
27. `.class {styles}`
28. `<div =class="menu">`
29. 
30. `<article>` :  contain a flavor and price of each coffee you currently offer
31. `<article>` : commonly contain multiple elements that have related information
32. 5 <article> with 2 nested <p> on it
33. `<p class="flavor">` : in order not stacked both flavor and price, should be left and right
34. `.flavor {text-align: left;}`
35. `<p class="price">3.00</p>`
36. `.price {text-align: right;}`
37. p elements are block-level elements
38. `.item p {display: inline-block;}` : maksudnya ditunjukkan untuk p didalam element yang mempunyai atribut `class="item"`
39. `width: 50%;` : teknik mengakalkan
40. `width: 49%;` : make it less than 50% so they won't broken (shift to down)
41. `<p class="flavor">French Vanilla</p><p class="price">3.00</p>` : simply move the price `p` element to be on the same line and make sure there is no space between them
42. Now it's work if you change width 49% to width 50% since both <p> are on the same line without space (not sure why)
43. Self-explanatory
44. Self-explanatory
45. Self-explanatory
46. 75% dan 25% Supaya mobile compatible
47. 2 Sections in 1 Main
48. =
49. 
50.
51.
52. `.flavor, .dessert { text-align: left; width: 75%; }`
53.
54. `padding-left: 20px; padding-right: 20px;`
55. `padding-top: 20px; padding-bottom: 20px;`
56. All of those 4 padding could be simplified with just 1 property which is `padding: 20px;`
57. `max-width: 500px;`
58. `font-family: sans-serif;`
59. `h1, h2 { font-family: Impact; }`
60. `font-family: Impact, serif;` : fallback value, only used in instances where the initial is not found/available 
61. `.established { font-style: italic; }`
62. 
63. `h1 { font-size: 40px; } h2 { font-size: 30px; }`
64. `<footer>`
65. `<p><a href="https://www.freecodecamp.org">Visit our website</p>`
66. 
67. `<hr>` : divider
68. `hr { height: 3px; }`
69. 
70. `border-color: brown;` : note : Each side of an element can have a different color or they can all be the same.
71. The default value of a property named border-width is 1px for all edges
72.
73. `padding: 20px;`
74. `margin-top: 5px; margin-bottom: 5px;`
75. `font-size: 18px;`
76. `.bottom-line { margin-top: 25px; }`
77. `<hr class="bottom-line">`
78. `/* FOOTER */` : don't forget to put this comment at the end of `style.css`, will easy you to identify
79. `footer { font-size: 14px; }`
80. `a { color: black; }`
81. PSEUDO-SELECTOR `a:visited { color: grey; }` : when the link has actually been visited
82. `a:hover { color: brown; }` : when the mouse hovers over them
83. `a:active { color: white; }` : when the link is actually being clicked 
84. 
85.
86.
87.
88.
89.
90.
91.
92.
