🟧 HTML FULL COURSE

«Goal: Master HTML and be able to build the structure of real-world websites from scratch.»

---

📚 TABLE OF CONTENTS

1. What is HTML?
2. Basic HTML Structure
3. HTML Elements
4. HTML Attributes
5. Headings
6. Paragraphs
7. Text Formatting
8. Comments
9. Links
10. Images
11. Lists
12. Tables
13. Forms
14. Input Types
15. Labels
16. Buttons
17. Select and Textarea
18. Div and Span
19. Semantic HTML
20. Audio
21. Video
22. Iframes
23. HTML Entities
24. File Paths
25. Meta Tags
26. SEO Basics
27. Accessibility
28. Form Validation
29. HTML Best Practices
30. Connecting HTML to CSS
31. Connecting HTML to JavaScript
32. Website Folder Structure
33. HTML Projects
34. Final Assessment

---

🟦 1. WHAT IS HTML?

HTML stands for:

HyperText Markup Language

HTML is the standard markup language used to create the structure and content of webpages.

HTML is not a programming language. It is a markup language.

HTML tells the browser what different pieces of content are.

Examples:

- Headings
- Paragraphs
- Images
- Links
- Buttons
- Forms
- Tables
- Lists
- Videos

---

🟦 2. BASIC HTML STRUCTURE

A basic HTML document looks like this:

<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>My Website</title>

</head>

<body>

    <h1>Hello World</h1>

</body>

</html>

Important parts

"<!DOCTYPE html>"

Tells the browser that the document uses modern HTML.

"<html>"

The root element of the webpage.

"<head>"

Contains information about the webpage that is generally not displayed as page content.

"<body>"

Contains the visible content of the webpage.

"<title>"

Defines the title shown in the browser tab.

---

🟦 3. HTML ELEMENTS

An HTML element usually consists of:

Opening tag
     ↓
<p>Hello World</p>
             ↑
        Closing tag

Example:

<p>Hello World</p>

Some elements do not have closing tags. These are called void elements.

Examples:

<img>
<br>
<hr>
<input>
<meta>
<link>

---

🟦 4. HTML ATTRIBUTES

Attributes provide additional information about an HTML element.

Example:

<a href="https://example.com">Visit Website</a>

"href" is an attribute.

Another example:

<img
    src="photo.jpg"
    alt="A photo"
>

Here:

src → Image location
alt → Alternative text

---

🟩 5. HEADINGS

HTML has six heading levels:

<h1>Main Heading</h1>

<h2>Section Heading</h2>

<h3>Subsection</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>

"<h1>" is the highest-level heading.

Use headings to create a logical structure for your content.

---

🟩 6. PARAGRAPHS

Use "<p>" for paragraphs.

<p>
    This is a paragraph of text.
</p>

Multiple paragraphs:

<p>First paragraph.</p>

<p>Second paragraph.</p>

---

🟩 7. TEXT FORMATTING

Strong importance

<strong>Important text</strong>

Emphasis

<em>Emphasized text</em>

Bold presentation

<b>Bold text</b>

Italic presentation

<i>Italic text</i>

Underline

<u>Underlined text</u>

Highlight

<mark>Highlighted text</mark>

Small text

<small>Small text</small>

Subscript

H<sub>2</sub>O

Superscript

x<sup>2</sup>

---

🟩 8. COMMENTS

Comments are notes inside your code that are not displayed on the webpage.

<!-- This is a comment -->

Comments are useful for explaining sections of code.

---

🟦 9. LINKS

Use the "<a>" element to create links.

<a href="https://example.com">
    Visit Website
</a>

Open a link in a new tab:

<a
    href="https://example.com"
    target="_blank"
>
    Visit Website
</a>

Internal link

<a href="about.html">
    About Us
</a>

---

🟦 10. IMAGES

Use "<img>" to display images.

<img
    src="photo.jpg"
    alt="Description of the photo"
>

Important attributes:

src → Image location
alt → Alternative text

Example:

<img
    src="images/profile.jpg"
    alt="Profile photograph"
    width="300"
>

---

🟩 11. LISTS

Unordered list

Creates a…

<ul>

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>

</ul>

Ordered list

Creates a numbered list.

<ol>

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>

</ol>

Description list

<dl>

    <dt>HTML</dt>
    <dd>Structures webpages.</dd>

    <dt>CSS</dt>
    <dd>Styles webpages.</dd>

</dl>

---

🟦 12. TABLES

Tables display information in rows and columns.

Example:

<table>

    <tr>

        <th>Name</th>
        <th>Age</th>

    </tr>

    <tr>

        <td>John</td>
        <td>20</td>

    </tr>

</table>

Important table elements

<table>     → Table
<tr>        → Table row
<th>        → Table heading
<td>        → Table data
<caption>   → Table title
<thead>     → Table header section
<tbody>     → Table body
<tfoot>     → Table footer section

---

🟧 13. FORMS

Forms collect information from users.

Example:

<form>

    <label for="name">
        Name:
    </label>

    <input
        type="text"
        id="name"
        name="name"
    >

    <button type="submit">
        Submit
    </button>

</form>

Forms are commonly used for:

- Registration
- Login
- Contact forms
- Search
- Applications
- Payments

---

🟧 14. INPUT TYPES

Common input types include:

<input type="text">

<input type="password">

<input type="email">

<input type="number">

<input type="tel">

<input type="date">

<input type="time">

<input type="file">

<input type="checkbox">

<input type="radio">

<input type="color">

<input type="range">

<input type="search">

<input type="url">

---

🟧 15. LABELS

Labels describe form controls.

<label for="email">
    Email:
</label>

<input
    type="email"
    id="email"
>

The "for" attribute connects the label to the input's "id".

---

🟧 16. BUTTONS

Basic button:

<button>
    Click Me
</button>

Form buttons:

<button type="submit">
    Submit
</button>

<button type="reset">
    Reset
</button>

<button type="button">
    Normal Button
</button>

---

🟧 17. SELECT AND TEXTAREA

Select

Creates a dropdown list.

<label for="language">
    Choose a language:
</label>

<select id="language">

    <option>JavaScript</option>
    <option>Python</option>
    <option>Java</option>

</select>

Textarea

Allows users to enter multiple lines of text.

<textarea
    rows="5"
    cols="30"
    placeholder="Write your message..."
></textarea>

---

🟨 18. DIV AND SPAN

"<div>"

A generic block-level container used to group content.

<div>

    <h2>About Me</h2>

    <p>
        I am learning web development.
    </p>

</div>

"<span>"

An inline container.

<p>
    I am learning
    <span>JavaScript</span>.
</p>

---

🟩 19. SEMANTIC HTML

Semantic elements describe the purpose of their content.

Common semantic elements:

<header></header>

<nav></nav>

<main></main>

<section></section>

<article></article>

<aside></aside>

<footer></footer>

Example:

<header>

    <h1>My Website</h1>

</header>

<nav>

    <a href="index.html">Home</a>
    <a href="about.html">About</a>

</nav>

<main>

    <section>

        <h2>About Me</h2>

        <p>
        …
           Welcome to my website.
        </p>

    </section>

</main>

<footer>

    <p>Copyright 2026</p>

</footer>

Semantic HTML helps with:

- Structure
- Accessibility
- Maintainability
- Search-engine understanding

---

🟦 20. AUDIO

Use "<audio>" to add audio.

<audio controls>

    <source
        src="music.mp3"
        type="audio/mpeg"
    >

</audio>

The "controls" attribute displays the audio controls.

---

🟦 21. VIDEO

Use "<video>" to add video.

<video
    controls
    width="500"
>

    <source
        src="video.mp4"
        type="video/mp4"
    >

</video>

---

🟦 22. IFRAMES

An iframe can embed supported external content.

<iframe
    src="https://example.com"
    width="600"
    height="400"
></iframe>

---

🟨 23. HTML ENTITIES

HTML entities allow special characters to be represented in HTML.

&amp;   → &
&lt;    → <
&gt;    → >
&nbsp;  → Space
&quot;  → "

Example:

<p>
    Tom &amp; Jerry
</p>

---

🟨 24. FILE PATHS

File in the same folder

<img src="photo.jpg">

File inside a folder

<img src="images/photo.jpg">

Go up one folder

<img src="../photo.jpg">

Link to another HTML page

<a href="about.html">
    About
</a>

---

🟦 25. META TAGS

Meta information is placed inside "<head>".

Character encoding

<meta charset="UTF-8">

Responsive design

<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>

Description

<meta
    name="description"
    content="My personal website"
>

---

🟩 26. SEO BASICS

SEO means:

Search Engine Optimization

HTML helps search engines understand your webpage.

Use a meaningful title:

<title>
    John's Web Development Portfolio
</title>

Use a description:

<meta
    name="description"
    content="John's web development portfolio and projects."
>

Use meaningful headings:

<h1>
    My Web Development Portfolio
</h1>

<h2>
    My Projects
</h2>

---

🟩 27. ACCESSIBILITY

Accessibility means making websites usable by as many people as possible, including people who use assistive technologies.

Important practices:

- Use semantic HTML
- Use meaningful headings
- Add useful "alt" text to meaningful images
- Use labels with form inputs
- Use descriptive links
- Use understandable buttons

Example:

<img
    src="student.jpg"
    alt="Student studying JavaScript"
>

---

🟧 28. FORM VALIDATION

HTML provides built-in form validation.

Example:

<input
    type="email"
    required
>

Useful validation attributes:

required
min
max
minlength
maxlength
pattern

Example:

<input
    type="text"
    required
    minlength="3"
    maxlength="30"
    placeholder="Enter your name"
>

---

🟥 29. HTML BEST PRACTICES

Use proper indentation

Good:

<body>

    <h1>Hello</h1>

    <p>
        Welcome to my website.
    </p>

</body>

Use meaningful names

Good:

<div class="profile-card">

Avoid unclear names:

<div class="x">

Use semantic HTML

Prefer:

<header>
<nav>
<main>
<section>
<article>
<footer>

when they correctly describe the content.

Use useful alt text

<img
    src="profile.jpg"
    alt="John's profile photo"
>

---

🟦 30. CONNECTING…

An external CSS file can be connected using:

<link
    rel="stylesheet"
    href="style.css"
>

Example project:

website/
│
├── index.html
└── style.css

---

🟪 31. CONNECTING HTML TO JAVASCRIPT

JavaScript can be connected using:

<script src="script.js"></script>

Example:

<!DOCTYPE html>
<html lang="en">

<head>

    <title>My JavaScript Website</title>

</head>

<body>

    <h1 id="title">
        Hello
    </h1>

    <script src="script.js"></script>

</body>

</html>

JavaScript:

let title = document.getElementById("title");

title.textContent = "Hello JavaScript!";

---

📁 32. WEBSITE FOLDER STRUCTURE

A basic website can be organized like this:

my-website/
│
├── index.html
│
├── about.html
│
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── images/
    └── profile.jpg

---

🏗️ 33. HTML PROJECTS

Project 1 — Personal Profile

Practice:

- Headings
- Paragraphs
- Images
- Links
- Lists

---

Project 2 — Registration Form

Practice:

- Forms
- Inputs
- Labels
- Select
- Textarea
- Buttons
- Validation

---

Project 3 — Personal Portfolio

Practice:

- Semantic HTML
- Navigation
- Sections
- Projects
- Contact form

---

Project 4 — Product Page

Practice:

- Images
- Links
- Lists
- Tables
- Forms

---

Project 5 — Multi-page Website

Practice:

- Multiple HTML files
- Navigation
- File paths
- Images
- Semantic structure

---

Project 6 — Full Website

Combine:

HTML
+
CSS
+
JavaScript

---

🏆 34. FINAL HTML CHECKLIST

Before completing HTML, I should be able to:

- [ ] Create an HTML document from scratch
- [ ] Understand "<!DOCTYPE html>"
- [ ] Understand "<html>", "<head>" and "<body>"
- [ ] Use headings
- [ ] Create paragraphs
- [ ] Format text
- [ ] Create links
- [ ] Add images
- [ ] Create lists
- [ ] Create tables
- [ ] Create forms
- [ ] Use input types
- [ ] Use labels
- [ ] Create buttons
- [ ] Use select
- [ ] Use textarea
- [ ] Understand attributes
- [ ] Use "div" and "span"
- [ ] Use semantic HTML
- [ ] Add audio
- [ ] Add video
- [ ] Understand iframes
- [ ] Understand HTML entities
- [ ] Understand file paths
- [ ] Use meta tags
- [ ] Understand basic SEO
- [ ] Understand accessibility
- [ ] Use form validation
- [ ] Connect HTML to CSS
- [ ] Connect HTML to JavaScript
- [ ] Organize a website project
- [ ] Build a multi-page website

---

📈 MY HTML PROGRESS

- [ ] HTML Introduction
- [ ] Document Structure
- [ ] Elements
- [ ] Attributes
- [ ] Headings
- [ ] Paragraphs
- [ ] Text Formatting
- [ ] Comments
- [ ] Links
- [ ] Images
- [ ] Lists
- [ ] Tables
- [ ] Forms
- [ ] Input Types
- [ ] Labels
- [ ] Buttons
- [ ] Select
- [ ] Textarea
- [ ] Div
- [ ] Span
- [ ] Semantic HTML
- [ ] Audio
- [ ] Video
- [ ] Iframes
- [ ] HTML Entities
- [ ] File Paths
- [ ] Meta Tags
- [ ] SEO
- [ ] Accessibility
- [ ] Form Validation
- [ ] Best Practices
- [ ] CSS Connection
- [ ] JavaScript Connection
- [ ] Projects
- [ ] Final Assessment

---

🎓 MY HTML RULE

I will not only memorize tags.

I will understand:

WHAT the tag does → WHY it is used → HOW to use it → WHEN to use it.

My goal is to be able to build HTML structures from my own knowledge.