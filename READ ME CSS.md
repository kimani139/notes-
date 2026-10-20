---

🟦 1. WHAT IS CSS?

CSS stands for:

Cascading Style Sheets

CSS is used to control the appearance and layout of HTML webpages.

HTML provides the structure.

CSS provides the design.

JavaScript provides behavior and interaction.

Think of a website like a house:

HTML       → Structure
CSS        → Design
JavaScript → Behavior

Example:

HTML:

<h1>Hello World</h1>

CSS:

h1 {
    color: blue;
}

---

🟦 2. CSS SYNTAX

Basic CSS syntax:

selector {
    property: value;
}

Example:

h1 {
    color: blue;
    font-size: 40px;
}

Parts:

h1        → Selector
color     → Property
blue      → Value

---

🟦 3. CONNECTING CSS TO HTML

There are three main ways to add CSS.

1. Inline CSS

<h1 style="color: blue;">
    Hello
</h1>

Useful for quick testing, but generally not preferred for larger projects.

---

2. Internal CSS

<style>

    h1 {
        color: blue;
    }

</style>

Usually placed inside "<head>".

---

3. External CSS ⭐

Create:

style.css

Then connect it:

<link
    rel="stylesheet"
    href="style.css"
>

CSS:

h1 {
    color: blue;
}

External CSS is generally the best approach for real projects.

---

🟩 4. SELECTORS

Selectors tell CSS which HTML elements to style.

Element selector

p {
    color: red;
}

Styles every "<p>" element.

---

Class selector

HTML:

<p class="description">
    Hello
</p>

CSS:

.description {
    color: green;
}

A class starts with:

.

---

ID selector

HTML:

<h1 id="title">
    My Website
</h1>

CSS:

#title {
    color: blue;
}

An ID starts with:

#

---

Universal selector

* {
    margin: 0;
    padding: 0;
}

Selects all elements.

---

Group selector

h1,
h2,
p {
    color: blue;
}

---

🟩 5. COLORS

Color names

h1 {
    color: red;
}

Hexadecimal

h1 {
    color: #ff0000;
}

RGB

h1 {
    color: rgb(255, 0, 0);
}

RGBA

RGBA includes transparency.

h1 {
    color: rgba(255, 0, 0, 0.5);
}

HSL

h1 {
    color: hsl(0, 100%, 50%);
}

---

🟩 6. BACKGROUNDS

Background color

body {
    background-color: lightgray;
}

Background image

body {
    background-image: url("image.jpg");
}

Background size

body {
    background-size: cover;
}

Background position

body {
    background-position: center;
}

Background repeat

body {
    background-repeat: no-repeat;
}

---

🟩 7. TEXT

Text color

p {
    color: black;
}

Text alignment

h1 {
    text-align: center;
}

Possible values:

left
center
right
justify

Text decoration

a {
    text-decoration: none;
}

Text transformation

p {
    text-transform: uppercase;
}

Other values:

uppercase
lowercase
capitalize

Letter spacing

h1 {
    letter-spacing: 2px;
}

Line height

p {
    line-height: 1.6;
}

---

🟩 8. FONTS

Font family

body {
    font-family: Arial, sans-serif;
}

Font size

h1 {
    font-size: 40px;
}

Font weight

p {
    font-weight: bold;
}

Common values:

normal
bold
100
300
400
500
600
700
900

Font style

p {
    font-style: italic;
}

---

🟨 9. CSS UNITS

Pixels

p {
    font-size: 20px;
}

Percentage

div {
    width: 50%;
}

"em"

Relative to the element's font size.

p {
    font-size: 2em;
}

"rem"

Relative to the root element's font …
p {
    font-size: 2rem;
}

Viewport units

div {
    width: 50vw;
    height: 50vh;
}

Important units:

px
%
em
rem
vw
vh

---

🟧 10. CSS BOX MODEL ⭐

Every HTML element can be thought of as a box.

+-----------------------------+
|           Margin            |
|   +---------------------+   |
|   |       Border        |   |
|   |  +---------------+  |   |
|   |  |    Padding    |  |   |
|   |  |  +---------+  |  |   |
|   |  |  | Content |  |  |   |
|   |  |  +---------+  |  |   |
|   |  +---------------+  |   |
|   +---------------------+   |
+-----------------------------+

The four parts are:

Content
Padding
Border
Margin

---

🟧 11. WIDTH AND HEIGHT

.box {
    width: 300px;
    height: 200px;
}

Maximum width:

.box {
    max-width: 600px;
}

Minimum width:

.box {
    min-width: 200px;
}

---

🟧 12. MARGIN

Margin creates space outside an element.

.box {
    margin: 20px;
}

Individual sides:

.box {
    margin-top: 10px;
    margin-rigkht: 20px;
    margin-bottom: 30px;
    margin-left: 40px;
}

Center an element:
 
.box {
    width: 300px;
    margin: 0 auto;
}

---

🟧 13. PADDING

Padding creates space inside an element.

.box {
    padding: 20px;
}

Individual sides:

.box {
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
}

---

🟧 14. BORDERS

.box {
    border: 2px solid black;
}

Individual properties:

.box {
    border-width: 2px;
    border-style: solid;
    border-color: black;
}

Rounded corners:

.box {
    border-radius: 10px;
}

Circle:

.circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

---

🟨 15. DISPLAY

Block

div {
    display: block;
}

Inline

span {
    display: inline;
}

Inline-block

button {
    display: inline-block;
}

None

.hidden {
    display: none;
}

---

🟨 16. POSITION

CSS positioning controls where an element appears.

Static

Default:

.box {
    position: static;
}

Relative

.box {
    position: relative;
    top: 20px;
}

Absolute

.box {
    position: absolute;
    top: 0;
    right: 0;
}

Fixed

.navbar {
    position: fixed;
    top: 0;
}

Sticky

.navbar {
    position: sticky;
    top: 0;
}

---

🟨 17. Z-INDEX

Controls which positioned element appears on top.

.box {
    position: relative;
    z-index: 10;
}

Higher values generally appear above lower values when the elements participate in the same stacking context.

---

🟨 18. OVERFLOW

Controls content that goes outside an element.

.box {
    overflow: hidden;
}

Other values:

visible
hidden
scroll
auto

---

🟨 19. OPACITY

Controls transparency.

.box {
    opacity: 0.5;
}

Values range from:

0   → Completely transparent
1   → Completely visible

---

🟪 20. PSEUDO-CLASSES

Pseudo-classes style an element in a particular state.

Hover

button:hover {
    background-color: blue;
}

Focus

input:focus {
    border-color: blue;
}

First child

li:first-child {
    color: red;
}

Last child

li:last-child {
    color: blue;
}

---

🟪 21. PSEUDO-ELEMENTS

Pseudo-elements style specific parts of an element.

"::before"

…

h1::before {
    content: "★ ";
}

"::after"

h1::after {
    content: " ✓";
}

First letter

p::first-letter {
    font-size: 30px;
}

---

🟪 22. COMBINATORS

Descendant

div p {
    color: red;
}

Selects paragraphs inside a "<div>".

Child

div > p {
    color: blue;
}

Selects direct children.

Adjacent sibling

h1 + p {
    color: green;
}

Selects the paragraph immediately after an "<h1>".

General sibling

h1 ~ p {
    color: purple;
}

---

🟪 23. ATTRIBUTE SELECTORS

HTML:

<input type="text">
<input type="email">

CSS:

input[type="email"] {
    border: 2px solid blue;
}

---

🟦 24. FLEXBOX ⭐⭐⭐

Flexbox is one of the most important CSS layout systems.

Create a flex container:

.container {
    display: flex;
}

---

Flex direction

.container {
    flex-direction: row;
}

or:

.container {
    flex-direction: column;
}

---

Justify content

Controls the main axis.

.container {
    justify-content: center;
}

Common values:

flex-start
center
flex-end
space-between
space-around
space-evenly

---

Align items

Controls the cross axis.

.container {
    align-items: center;
}

---

Gap

.container {
    gap: 20px;
}

---

Flex wrap

.container {
    flex-wrap: wrap;
}

---

Complete example

HTML:

<div class="container">

    <div class="box">1</div>
    <div class="box">2</div>
    <div class="box">3</div>

</div>

CSS:

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.box {
    padding: 30px;
    background-color: lightblue;
}

---

🟦 25. CSS GRID ⭐⭐⭐

Grid is useful for two-dimensional layouts.

Create a grid:

.container {
    display: grid;
}

Define columns:

.container {
    grid-template-columns: 1fr 1fr 1fr;
}

Create gaps:

.container {
    gap: 20px;
}

Example:

.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

---

🟦 26. RESPONSIVE DESIGN ⭐⭐⭐

Responsive design means a website adapts to different screen sizes.

A website should work on:

📱 Phones
📱 Tablets
💻 Laptops
🖥️ Desktops

Use flexible layouts.

Example:

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

---

🟦 27. MEDIA QUERIES ⭐⭐⭐

Media queries allow CSS to change based on screen size.

@media (max-width: 768px) {

    .container {
        flex-direction: column;
    }

}

Example:

.nav {
    display: flex;
    gap: 20px;
}

@media (max-width: 600px) {

    .nav {
        flex-direction: column;
    }

}

---

🟩 28. IMAGES

Responsive image:

img {
    max-width: 100%;
    height: auto;
}

Cover an area:

img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

Contain the complete image:

img {
    object-fit: contain;
}

---

🟩 29. FORMS

Style an input:

input {
    padding: 10px;
    border: 1px solid gray;
    border-radius: 5px;
}

Style a button:

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}

Focus effect:

input:focus {
    outline: none;
    border-color: blue;
}

---

🟪 30. CSS VARIABLES

CSS variables allow you to store reusable values.

:root {

h1::before {
    content: "★ ";
}

"::after"

h1::after {
    content: " ✓";
}

First letter

p::first-letter {
    font-size: 30px;
}

---

🟪 22. COMBINATORS

Descendant

div p {
    color: red;
}

Selects paragraphs inside a "<div>".

Child

div > p {
    color: blue;
}

Selects direct children.

Adjacent sibling

h1 + p {
    color: green;
}

Selects the paragraph immediately after an "<h1>".

General sibling

h1 ~ p {
    color: purple;
}

---

🟪 23. ATTRIBUTE SELECTORS

HTML:

<input type="text">
<input type="email">

CSS:

input[type="email"] {
    border: 2px solid blue;
}

---

🟦 24. FLEXBOX ⭐⭐⭐

Flexbox is one of the most important CSS layout systems.

Create a flex container:

.container {
    display: flex;
}

---

Flex direction

.container {
    flex-direction: row;
}

or:

.container {
    flex-direction: column;
}

---

Justify content

Controls the main axis.

.container {
    justify-content: center;
}

Common values:

flex-start
center
flex-end
space-between
space-around
space-evenly

---

Align items

Controls the cross axis.

.container {
    align-items: center;
}

---

Gap

.container {
    gap: 20px;
}

---

Flex wrap

.container {
    flex-wrap: wrap;
}

---

Complete example

HTML:

<div class="container">

    <div class="box">1</div>
    <div class="box">2</div>
    <div class="box">3</div>

</div>

CSS:

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.box {
    padding: 30px;
    background-color: lightblue;
}

---

🟦 25. CSS GRID ⭐⭐⭐

Grid is useful for two-dimensional layouts.

Create a grid:

.container {
    display: grid;
}

Define columns:

.container {
    grid-template-columns: 1fr 1fr 1fr;
}

Create gaps:

.container {
    gap: 20px;
}

Example:

.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

---

🟦 26. RESPONSIVE DESIGN ⭐⭐⭐

Responsive design means a website adapts to different screen sizes.

A website should work on:

📱 Phones
📱 Tablets
💻 Laptops
🖥️ Desktops

Use flexible layouts.

Example:

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

---

🟦 27. MEDIA QUERIES ⭐⭐⭐

Media queries allow CSS to change based on screen size.

@media (max-width: 768px) {

    .container {
        flex-direction: column;
    }

}

Example:

.nav {
    display: flex;
    gap: 20px;
}

@media (max-width: 600px) {

    .nav {
        flex-direction: column;
    }

}

---

🟩 28. IMAGES

Responsive image:

img {
    max-width: 100%;
    height: auto;
}

Cover an area:

img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

Contain the complete image:

img {
    object-fit: contain;
}

---

🟩 29. FORMS

Style an input:

input {
    padding: 10px;
    border: 1px solid gray;
    border-radius: 5px;
}

Style a button:

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}

Focus effect:

input:focus {
    outline: none;
    border-color: blue;
}

---

🟪 30. CSS VARIABLES

CSS variables allow you to store reusable values.

:root {
  -main-color: blue;
    --spacing: 20px;
}

Use them:

button {
    background-color: var(--main-color);
    padding: var(--spacing);
}

---

🟪 31. TRANSITIONS

Transitions make changes smoother.

button {
    background-color: black;
    transition: 0.3s;
}

button:hover {
    background-color: blue;
}

More specific:

button {
    transition:
        background-color 0.3s ease,
        transform 0.3s ease;
}

---

🟪 32. TRANSFORMS

Move

.box {
    transform: translateX(20px);
}

Rotate

.box {
    transform: rotate(45deg);
}

Scale

.box {
    transform: scale(1.2);
}

---

🟪 33. ANIMATIONS

Create an animation:

@keyframes moveBox {

    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(200px);
    }

}

Use it:

.box {
    animation: moveBox 2s infinite;
}

---

🟨 34. BOX SHADOW

.card {
    box-shadow:
        0 4px 10px rgba(0, 0, 0, 0.2);
}

---

🟨 35. GRADIENTS

Linear gradient

.box {
    background:
        linear-gradient(
            to right,
            blue,
            purple
        );
}

Radial gradient

.box {
    background:
        radial-gradient(
            circle,
            blue,
            purple
        );
}

---

🟨 36. CSS FUNCTIONS

"calc()"

.box {
    width: calc(100% - 40px);
}

"min()"

.box {
    width: min(90%, 1000px);
}

"max()"

.box {
    width: max(300px, 50%);
}

"clamp()"

Useful for responsive sizing.

h1 {
    font-size: clamp(
        2rem,
        5vw,
        4rem
    );
}

---

🟥 37. CSS SPECIFICITY

When multiple CSS rules target the same element, CSS uses specificity and the cascade to determine which declarations apply.

General priority:

Inline styles
     ↓
ID
     ↓
Class / attribute / pseudo-class
     ↓
Element

Example:

p {
    color: red;
}

.text {
    color: blue;
}

#special {
    color: green;
}

If an element has all three selectors, the more specific rule can take precedence.

---

🟥 38. INHERITANCE

Some CSS properties are inherited from parent elements.

Example:

body {
    color: blue;
}

Text inside the body may inherit that color unless another rule overrides it.

---

🟥 39. "!IMPORTANT"

Example:

p {
    color: red !important;
}

"!important" can override normal declarations.

Avoid using it unnecessarily.

---

🟧 40. CSS ORGANIZATION

A larger stylesheet can be organized into sections:

/* Reset */

/* Variables */

/* Global styles */

/* Header */

/* Navigation */

/* Main content */

/* Cards */

/* Forms */

/* Footer */

/* Responsive design */

---

♿ 41. ACCESSIBILITY

Good CSS should help create usable websites.

Important practices:

- Maintain readable text
- Don't rely only on color to communicate information
- Keep keyboard focus visible
- Make buttons and links easy to identify
- Ensure sufficient contrast
- Make layouts usable on different screen sizes

Example:

button:focus {
    outline: 3px solid blue;
}

---

🟩 42. CSS BEST PRACTICES

Use classes for reusable styling

.card {
    padding: 20px;
}

Avoid unnecessary "!important"

Keep CSS organized

Use responsive layouts

Use meaningful class names

Good:

.profile-card
.navbar
.login-form
.product-grid

Avoid:

.red-box
.box1
.x
.test

when the name doesn't describe the element's purpose.

---

🐛 43. DEBUGGING CSS

When CSS doesn't work:

Step 1

Check that CSS is connected:

<link
    rel="stylesheet"
    href="style.css"
>

Step 2

Check the selector.

Step 3

Check spelling.

Step 4

Check the browser Developer Tools.

Step 5

Check whether another rule is overriding your rule.

Step 6

Check the box model.

Step 7

Check your media queries.

---

🏗️ 44. CSS + HTML PROJECTS

Project 1 — Profile Card

Practice:

- Colors
- Fonts
- Padding
- Margin
- Border
- Border-radius
- Box-shadow

---

Project 2 — Login Page

Practice:

- Forms
- Inputs
- Buttons
- Flexbox
- Focus states

---

Project 3 — Navigation Bar

Practice:

- Flexbox
- Links
- Hover effects
- Spacing
- Responsive design

---

Project 4 — Product Cards

Practice:

- Grid
- Images
- Cards
- Buttons
- Responsive layout

---

Project 5 — Portfolio Website

Practice:

HTML
+
CSS
+
Responsive Design

---

Project 6 — Complete Responsive Website

Build a website containing:

Header
Navigation
Hero section
About section
Services
Projects
Contact form
Footer

---

🏆 45. FINAL CSS CHECKLIST

Before completing CSS, I should be able to:

- [ ] Explain what CSS is
- [ ] Write CSS syntax
- [ ] Connect CSS to HTML
- [ ] Use selectors
- [ ] Use classes
- [ ] Use IDs
- [ ] Work with colors
- [ ] Work with backgrounds
- [ ] Style text
- [ ] Use fonts
- [ ] Understand CSS units
- [ ] Understand the box model
- [ ] Use width and height
- [ ] Use margin
- [ ] Use padding
- [ ] Use borders
- [ ] Understand display
- [ ] Use positioning
- [ ] Understand z-index
- [ ] Control overflow
- [ ] Use opacity
- [ ] Use pseudo-classes
- [ ] Use pseudo-elements
- [ ] Use combinators
- [ ] Use attribute selectors
- [ ] Master Flexbox
- [ ] Master CSS Grid
- [ ] Build responsive layouts
- [ ] Use media queries
- [ ] Style images
- [ ] Style forms
- [ ] Use CSS variables
- [ ] Use transitions
- [ ] Use transforms
- [ ] Create animations
- [ ] Use shadows
- [ ] Create gradients
- [ ] Use CSS functions
- [ ] Understand specificity
- [ ] Understand inheritance
- [ ] Debug CSS
- [ ] Build complete responsive websites

---

📈 MY CSS PROGRESS

- [ ] Introduction
- [ ] Syntax
- [ ] Connecting CSS
- [ ] Selectors
- [ ] Colors
- [ ] Backgrounds
- [ ] Text
- [ ] Fonts
- [ ] Units
- [ ] Box Model
- [ ] Width & Height
- [ ] Margin
- [ ] Padding
- [ ] Borders
- [ ] Display
- [ ] Position
- [ ] Z-Index
- [ ] Overflow
- [ ] Opacity
- [ ] Pseudo-Classes
- [ ] Pseudo-Elements
- [ ] Combinators
- [ ] Attribute Selectors
- [ ] Flexbox
- [ ] Grid
- [ ] Responsive Design
- [ ] Media Queries
- [ ] Images
- [ ] Forms
- [ ] CSS Variables
- [ ] Transitions
- [ ] Transforms
- [ ] Animations
- [ ] Shadows
- [ ] Gradients
- [ ] CSS Functions
- [ ] Specificity
- [ ] Inheritance
- [ ] Debugging
- [ ] Projects
- [ ] Final Assessment

---

🎓 MY CSS RULE

I will not just memorize CSS properties.

For every property, I will understand:

WHAT it does → WHY it is used → HOW to use it → WHEN to use it.

My goal is to be able to take an HTML page and turn it into a responsive, professional-looking website using CSS from my own knowledge.
