## Notes

1.
2.
3. `title` element gives search engines extra information about the page
4. To tell browsers how to encode characters on your page, set the `charset` to `utf-8`. `utf-8` is a universal character set that includes almost every character from all human languages.
5. Viewport Basic `<meta name="viewport" content="width=device-width, initial-scale=1.0">` : khusus untuk optimisasi mobile
6. `<link rel="stylesheet" href="styles.css">` : khusus untuk link ke css
7. 
8.
9. `<div class="container">`
10. `<div class="marker">`
11. 
12. Notice that your marker doesn't seem to have any color. The background color was actually applied, but since the marker div element is empty, it doesn't have any width or height by default.
13. `margin` property to auto. This sets `margin-top`, `margin-right`, `margin-bottom`, and `margin-left` all to auto.
14. `margin: 10px auto;`
15. 
16. `<div class="marker one">`
17. YOU CAN DO THIS index.html : `<div class="marker one">` | styles.css : `.marker { margin: 10px auto; }` `.one { background-color: red; }`
18. `.container { background-color: rgb(0, 0, 0) }` : RGB is function, A function is a piece of code that can take an input and perform a specific action.
19. `background-color: rgb(255, 0, 0);`
20. 
21. 
22.
23.
24.
25. `padding: 10px 0px;` : 10px place is for top & bottom and 0px place is for right & left
26.
27. `background-color: rgb(255, 255, 255);`
28. Secondary colors are the colors you get when you combine primary colors. `rgb(255, 255, 0)` : Yellow
29. `rgb(0, 255, 255)` : Cyan
30. `rgb(255, 0, 255)` : Magenta
31. Tertiary colors are created by combining a primary with a nearby secondary color. `rgb(255, 127, 0)` : Orange
32. `rgb(0, 255, 127)` : Spring Green
33. `rgb(127, 0, 255)` : Violet
34. `rgb(127, 255, 0)` : Chartreuse Green
35. `rgb(0, 127, 255)` : Azure
36. `rgb(255, 0, 127)` : Rose, If two complementary colors are combined, they produce gray. But when they are placed side-by-side, these colors produce strong visual contrast and appear brighter.
37. Notice that the red and cyan colors are very bright right next to each other. This contrast can be distracting if it's overused on a website, and can make text hard to read if it's placed on a complementary-colored background. It's better practice to choose one color as the dominant color, and use its complementary color as an accent to bring attention to certain content on the page.
38. 
39. 
40. 
41. 
42.
43.
44.
45.
46. hexdecimal / hex values colors : #00 (RED) AA (BLUE) FF (GREEN) , #00AAFFF , 00 = 0;0% , FF = 255;100%, 
47. 
48. `hsl(240, 100%, 50%)` : HSL color model, or HUE (0-360, Color), SATURATION (0-100%, Gray), and LIGHTNESS (0-100%, White-Black)
49. 
50. GRADIENT time `linear-gradient(gradientDirection, color1, color2, ...);` , `background: linear-gradient(90deg);`
51.
52. `background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0));`
53. Or you can add to 3 `background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0), rgb(0,0,255));`
54. COLOR-STOPS `linear-gradient(90deg, red 90%, black);` , So Red will dominate 90% over Black
55.
56.
57.
58.
59. Perfect Red Marker `background: linear-gradient(180deg, rgb(122, 74, 14) 0%, rgb(245, 62, 113) 50%, rgb(162, 27, 27) 100%);`
60. `background: linear-gradient(180deg, #55680D, #71F53E, #116C31);`
61.
62.
63.
64.
65. Remove the gradientDirection and color-stops to simplify it `background: linear-gradient( rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));` 
66. HSL AREA : 
67.
68.
69.
70.
71.
72. `.sleeve { width: 110px; height: 25px; }`
73. OPACITY describes how opaque, or non-transparent, something is. `opacity: 0.5;` from 0% which is transparent & 100% is opaque
74. ALPHA CHANNEL 
75. USE RGBA instead RGB, It's better : `rgba(255, 255, 255, 0.5);` 
76. 
77.
78.  the default `display` property for `div` elements is `block`
79. -IMPORTANT
80.
81.
82.
83.
84.
85.
86.
87.
88.
89.
90.
91.
92.
93.
94.
