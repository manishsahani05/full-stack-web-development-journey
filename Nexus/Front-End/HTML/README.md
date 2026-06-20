# HTML

## What is HTML?

HTML (HyperText Markup Language) is the standard markup language used to create and structure 
web pages.

# Introduction to HTML and Web Development

## HTML (HyperText Markup Language)

### What is HTML?
HTML is the standard markup language used to create and organize the content of web pages. It defines the structure of a webpage using different tags and elements. Unlike programming languages, HTML focuses on presenting and arranging content.

### Basic HTML Structure
Every HTML document follows a standard structure that mainly consists of:

- `<html>` : Root element of the webpage
- `<head>` : Contains metadata and page information
- `<body>` : Contains the visible content displayed in the browser

### HTML Elements and Tags

HTML uses tags to define different parts of a webpage.

- Opening Tag: `<tagname>`
- Content: Information placed between opening and closing tags
- Closing Tag: `</tagname>`

#### Common Self-Closing Tags

- `<img>` – Displays images
- `<br>` – Inserts a line break
- `<hr>` – Creates a horizontal line

---

## Web Browsers

### What is a Web Browser?
A web browser is a software application that reads and displays HTML documents, allowing users to access websites on the internet.

### Popular Browsers

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

### How Browsers Work
Browsers interpret HTML code, build the Document Object Model (DOM), and render the webpage on the screen for users to interact with.

## HTML Document Structure

HTML documents follow a hierarchical structure that begins with the <!DOCTYPE html> declaration.

A basic HTML page contains:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```
This structure helps browsers understand and display the webpage correctly.

## HTML vs CSS vs JavaScript

- HTML: Creates the structure of a web page.
- CSS: Styles and designs the web page.
- JavaScript: Adds interactivity and functionality.

- # 2. Types of HTML Elements

HTML elements are the building blocks of a web page. They help structure content, display text, create forms, add media, and make websites interactive.

---

## Structure Elements

Structure elements define the basic layout of an HTML document.

| Tag | Description |
|------|------------|
| `<!DOCTYPE html>` | Declares the HTML version |
| `<html>` | Root element of the webpage |
| `<head>` | Contains metadata |
| `<body>` | Contains visible content |
| `<title>` | Sets the browser tab title |

### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    Hello World
</body>
</html>
```

---

## Semantic Elements

Semantic elements describe the meaning of content and improve SEO and accessibility.

| Tag | Description |
|------|------------|
| `<header>` | Introductory content |
| `<nav>` | Navigation links |
| `<main>` | Main content |
| `<section>` | Content section |
| `<article>` | Independent content |
| `<aside>` | Sidebar content |
| `<footer>` | Footer information |

### Benefits

- Better SEO
- Better Accessibility
- Easy Maintenance
- Improved Readability

---

## Text Elements

Text elements are used to display and organize text content.

| Tag | Description |
|------|------------|
| `<h1>` to `<h6>` | Headings |
| `<p>` | Paragraph |
| `<span>` | Inline container |
| `<div>` | Block-level container |

### Example

```html
<h1>HTML Notes</h1>

<p>This is a paragraph.</p>

<span>Inline Text</span>

<div>Block Element</div>
```

---

## List Elements

Lists are used to organize related items.

### Unordered List

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### Ordered List

```html
<ol>
    <li>Step One</li>
    <li>Step Two</li>
    <li>Step Three</li>
</ol>
```

### Description List

```html
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>

    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
</dl>
```

### List Tags

| Tag | Description |
|------|------------|
| `<ul>` | Unordered List |
| `<ol>` | Ordered List |
| `<li>` | List Item |
| `<dl>` | Description List |
| `<dt>` | Description Term |
| `<dd>` | Description Definition |

---

## Media Elements

Media elements are used to embed multimedia content.

| Tag | Description |
|------|------------|
| `<img>` | Display images |
| `<audio>` | Play audio |
| `<video>` | Play video |
| `<source>` | Define media source |

### Image Example

```html
<img src="image.jpg" alt="Sample Image">
```

### Audio Example

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
```

### Video Example

```html
<video controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

---

## Text Formatting and Emphasis

Formatting tags help make text more meaningful and attractive.

| Tag | Description |
|------|------------|
| `<strong>` | Bold text |
| `<em>` | Italic text |
| `<mark>` | Highlight text |
| `<small>` | Smaller text |
| `<del>` | Deleted text |
| `<ins>` | Inserted text |
| `<sub>` | Subscript text |
| `<sup>` | Superscript text |

### Example

```html
<strong>Important Text</strong>

<em>Italic Text</em>

<mark>Highlighted Text</mark>

H<sub>2</sub>O

x<sup>2</sup>
```

---

## Links and Navigation

The `<a>` tag is used to create hyperlinks.

### Example

```html
<a href="https://example.com">Visit Website</a>
```

### Common href Values

| Type | Example |
|------|---------|
| Absolute URL | `https://example.com` |
| Relative URL | `./page.html` |
| Parent Directory | `../folder/page.html` |
| Anchor Link | `#section-id` |
| Email Link | `mailto:email@example.com` |
| Phone Link | `tel:+1234567890` |

---

## Forms and Input Elements

Forms are used to collect user information.

### Form Tags

| Tag | Description |
|------|------------|
| `<form>` | Creates a form |
| `<input>` | Input field |
| `<textarea>` | Multi-line text input |
| `<select>` | Dropdown menu |
| `<option>` | Dropdown option |
| `<optgroup>` | Group of options |
| `<button>` | Clickable button |
| `<label>` | Label for form fields |
| `<fieldset>` | Groups related controls |
| `<legend>` | Caption for fieldset |
| `<datalist>` | Autocomplete suggestions |

### Example

```html
<form>
    <label>Name:</label>
    <input type="text">

    <button type="submit">
        Submit
    </button>
</form>
```

## Common Input Types

| Input Type | Description |
|------------|------------|
| text | Single-line text input |
| email | Email input |
| password | Password field |
| number | Numeric input |
| range | Slider input |
| date | Date picker |
| time | Time picker |
| datetime-local | Date and time picker |
| color | Color picker |
| checkbox | Multiple selection |
| radio | Single selection |
| file | File upload |
| hidden | Hidden field |
| search | Search field |
| tel | Telephone input |
| url | Website URL input |
| submit | Submit button |
| reset | Reset button |
| button | Generic button |

---

## Table Elements

Tables display data in rows and columns.

| Tag | Description |
|------|------------|
| `<table>` | Creates a table |
| `<thead>` | Table header |
| `<tbody>` | Table body |
| `<tfoot>` | Table footer |
| `<tr>` | Table row |
| `<th>` | Header cell |
| `<td>` | Data cell |
| `<caption>` | Table title |
| `<colgroup>` | Column group |
| `<col>` | Column settings |

### Example

```html
<table border="1">
    <caption>Student Data</caption>

    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Manish</td>
        <td>20</td>
    </tr>
</table>
```

---

## Multimedia Elements

Advanced multimedia tags:

| Tag | Purpose |
|------|---------|
| `<picture>` | Responsive images |
| `<track>` | Video subtitles |
| `<embed>` | External content |
| `<object>` | External resources |
| `<iframe>` | Embed another webpage |

---

## Interactive Elements

Interactive elements improve user experience.

| Tag | Description |
|------|------------|
| `<details>` | Expandable content |
| `<summary>` | Title of details |
| `<dialog>` | Dialog box |
| `<menu>` | Menu options |
| `<menuitem>` | Menu command (Deprecated) |

### Example

```html
<details>
    <summary>Click Here</summary>
    <p>Hidden Content</p>
</details>
```

---

## Grouping and Container Elements

Container elements help organize content and apply styling.

| Tag | Description |
|------|------------|
| `<div>` | Block-level container |
| `<span>` | Inline container |
| `<main>` | Main content |
| `<section>` | Content section |
| `<article>` | Independent content |
| `<aside>` | Related content |
| `<header>` | Introductory content |
| `<footer>` | Footer information |
| `<nav>` | Navigation links |
| `<address>` | Contact information |

### Why Use Containers?

- Organize content efficiently
- Apply CSS styling easily
- Improve code readability
- Create responsive layouts

---

## Summary

HTML elements are divided into different categories such as Structure Elements, Semantic Elements, Text Elements, Lists, Media, Forms, Tables, Interactive Elements, and Containers. Understanding these elements is essential because they form the foundation of every web page and help create accessible, SEO-friendly, and well-structured websites.


# 3. HTML Attributes

## Introduction

HTML Attributes are special properties that provide additional information about HTML elements and control their behavior, appearance, and functionality. Attributes are always written inside the opening tag of an element and usually consist of a name-value pair.

### Syntax

```html
<tagname attribute="value">Content</tagname>
```

### Example

```html
<a href="https://www.google.com">Visit Google</a>
```

In this example:

- `href` is the attribute.
- `https://www.google.com` is the attribute value.
- The attribute tells the browser where the link should navigate.

---

## Why Attributes are Important?

Attributes play a crucial role in HTML because they:

- Provide additional information about elements.
- Control the behavior of HTML tags.
- Improve accessibility.
- Help with styling and scripting.
- Enable communication between HTML, CSS, and JavaScript.

Without attributes, many HTML elements would lose their functionality.

---

# Types of HTML Attributes

HTML attributes can be categorized into different groups based on their purpose.

---

## 1. Global Attributes

Global attributes can be applied to almost every HTML element.

| Attribute | Description |
|------------|------------|
| `id` | Unique identifier for an element |
| `class` | Used to group elements for CSS and JavaScript |
| `style` | Applies inline CSS styles |
| `title` | Displays tooltip text on hover |
| `lang` | Specifies the language of content |
| `data-*` | Stores custom data |

### Example

```html
<p id="intro" class="text" title="Introduction">
    Welcome to HTML
</p>
```

### Explanation

- `id` uniquely identifies an element.
- `class` allows multiple elements to share styles.
- `title` displays a tooltip when the mouse hovers over the element.

---

## 2. Link Attributes

Link attributes are mainly used with the `<a>` tag.

| Attribute | Description |
|------------|------------|
| `href` | Specifies destination URL |
| `target` | Specifies where to open the link |
| `rel` | Defines relationship between linked pages |

### Example

```html
<a href="https://github.com" target="_blank">
    Visit GitHub
</a>
```

### Explanation

- `href` defines the destination.
- `target="_blank"` opens the page in a new tab.

---

## 3. Image Attributes

Image attributes help display and optimize images.

| Attribute | Description |
|------------|------------|
| `src` | Image source |
| `alt` | Alternative text |
| `width` | Width of image |
| `height` | Height of image |
| `srcset` | Responsive image sources |

### Example

```html
<img
    src="nature.jpg"
    alt="Beautiful Nature"
    width="500"
    height="300">
```

### Importance of Alt Attribute

The `alt` attribute:

- Improves accessibility.
- Helps screen readers.
- Displays text when image fails to load.
- Improves SEO.

---

## 4. Form Attributes

Form attributes help collect and process user data.

| Attribute | Description |
|------------|------------|
| `action` | URL where data is submitted |
| `method` | Submission method (GET/POST) |
| `name` | Name of input field |
| `value` | Default value |
| `placeholder` | Hint text |
| `required` | Makes field mandatory |
| `disabled` | Disables user interaction |

### Example

```html
<form action="/submit" method="POST">

    <input
        type="text"
        name="username"
        placeholder="Enter Username"
        required>

    <button type="submit">
        Submit
    </button>

</form>
```

---

## 5. Table Attributes

Table attributes control table structure.

| Attribute | Description |
|------------|------------|
| `colspan` | Span multiple columns |
| `rowspan` | Span multiple rows |
| `scope` | Defines header relationship |

### Example

```html
<table border="1">

<tr>
    <th colspan="2">
        Student Details
    </th>
</tr>

<tr>
    <td>Manish</td>
    <td>20</td>
</tr>

</table>
```

---

# Important Notes About Attributes

## Boolean Attributes

Boolean attributes do not require a value.

Examples:

```html
<input type="text" required>

<input type="checkbox" checked>

<button disabled>
    Submit
</button>
```

Common Boolean Attributes:

- required
- checked
- disabled
- readonly
- autoplay
- selected

---

## Case Sensitivity

Although HTML attributes are generally case-insensitive, lowercase is strongly recommended.

✔ Recommended

```html
<input type="text">
```

✖ Avoid

```html
<INPUT TYPE="TEXT">
```

---

## Quotes Around Attribute Values

Always use quotes around attribute values.

✔ Correct

```html
<input type="text" placeholder="Enter Name">
```

✖ Incorrect

```html
<input type=text>
```

---

# Best Practices

- Use meaningful id and class names.
- Always add alt text to images.
- Use semantic HTML whenever possible.
- Keep attribute names lowercase.
- Avoid excessive inline styles.
- Validate HTML regularly.
- Write clean and readable code.

---

## Summary

HTML Attributes provide additional information and functionality to HTML elements. They are essential for creating interactive, accessible, and well-structured web pages. Understanding attributes is important because they help control element behavior, improve user experience, and make websites more professional and maintainable.

# 4. HTML Document Structure and Best Practices

## Introduction

A well-structured HTML document is the foundation of every website. Proper document structure improves readability, maintainability, accessibility, SEO (Search Engine Optimization), and performance. Following best practices ensures that websites work correctly across different browsers and devices.

---

# Basic HTML Document Structure

Every HTML5 document should start with the following template:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Page content goes here -->
</body>
</html>
```

---

## Understanding Each Part

### `<!DOCTYPE html>`

Declares that the document uses HTML5.

```html
<!DOCTYPE html>
```

Without this declaration, browsers may render pages in compatibility mode.

### `<html>`

The root element of an HTML document.

```html
<html lang="en">
```

The `lang` attribute specifies the language of the webpage.

### `<head>`

Contains metadata and information about the webpage that is not displayed directly.

Examples:

- Meta Tags
- CSS Files
- JavaScript Files
- Page Title

### `<body>`

Contains all visible content displayed in the browser.

Examples:

- Headings
- Paragraphs
- Images
- Forms
- Tables
- Videos

---

# Meta Tags

Meta tags provide information about the webpage to browsers and search engines.

## Character Encoding

```html
<meta charset="UTF-8">
```

### Purpose

- Supports multiple languages.
- Displays special characters correctly.
- Prevents encoding issues.

**Always place this tag near the top of the `<head>` section.**

---

## Viewport Meta Tag

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Purpose

- Makes websites responsive.
- Adjusts layout according to device width.
- Essential for mobile-friendly design.

---

## Description Meta Tag

```html
<meta name="description" content="Learn HTML with examples and notes">
```

### Purpose

- Provides page description.
- Appears in search engine results.
- Improves SEO.

---

## Keywords Meta Tag

```html
<meta name="keywords" content="HTML, CSS, JavaScript">
```

### Purpose

- Describes page keywords.
- Less important for modern SEO but still supported.

---

## Author Meta Tag

```html
<meta name="author" content="Author Name">
```

### Purpose

Identifies the creator of the webpage.

---

# Semantic HTML Structure

Semantic elements describe the purpose of content rather than just its appearance.

```html
<body>

<header>
    <nav>
        Navigation Links
    </nav>
</header>

<main>

    <section>

        <article>
            Main Content
        </article>

        <aside>
            Sidebar Content
        </aside>

    </section>

</main>

<footer>
    Footer Information
</footer>

</body>
```

---

## Benefits of Semantic HTML

- Better SEO
- Improved Accessibility
- Cleaner Code
- Easier Maintenance
- Better Developer Experience

---

# Accessibility Best Practices

Accessibility ensures that websites are usable by everyone, including people with disabilities.

## Use Meaningful Alt Text

```html
<img src="logo.png" alt="Company Logo">
```

### Benefits

- Helps visually impaired users.
- Improves SEO.
- Displays text if images fail to load.

---

## Maintain Proper Heading Hierarchy

Correct:

```html
<h1>Main Heading</h1>
<h2>Section Heading</h2>
<h3>Subsection Heading</h3>
```

Incorrect:

```html
<h1>Main Heading</h1>
<h4>Subsection Heading</h4>
```

---

## Use Labels for Forms

```html
<label for="email">Email Address</label>
<input type="email" id="email">
```

Benefits:

- Better accessibility
- Better user experience
- Larger clickable area

---

## Use ARIA Attributes

```html
<button aria-label="Close Menu">
    X
</button>
```

ARIA improves accessibility when semantic HTML is not enough.

---

## Ensure Keyboard Accessibility

Users should be able to navigate websites using:

- Tab
- Enter
- Space
- Arrow Keys

---

# Performance Best Practices

Performance directly affects user experience and SEO.

## Optimize Images

| Format | Use Case |
|---------|----------|
| JPEG | Photographs |
| PNG | Transparent Graphics |
| SVG | Icons & Logos |
| WebP | Modern Optimized Images |

---

## Minimize HTTP Requests

Reduce the number of files loaded by browsers.

Methods:

- Combine CSS files
- Combine JavaScript files
- Use image sprites

---

## Lazy Loading

```html
<img
    src="image.jpg"
    loading="lazy"
    alt="Sample Image">
```

### Benefits

- Faster page load
- Better performance
- Reduced bandwidth usage

---

## Preload Critical Resources

```html
<link rel="preload" href="styles.css" as="style">
```

---

# SEO Best Practices

SEO helps websites rank higher in search engines.

## Use Descriptive Title Tags

```html
<title>Complete HTML Notes for Beginners</title>
```

Recommended length:

- 50–60 characters

---

## Write Effective Meta Descriptions

```html
<meta
name="description"
content="Learn HTML from basic to advanced with examples.">
```

Recommended length:

- 150–160 characters

---

## Maintain Proper Heading Structure

```html
<h1>Main Topic</h1>
<h2>Sub Topic</h2>
<h3>Details</h3>
```

Only one `<h1>` should be used per page.

---

## Internal Linking

```html
<a href="/contact.html">
    Contact Us
</a>
```

---

## Use Clean URLs

### Good

```text
example.com/html-notes
```

### Bad

```text
example.com/page?id=12345
```

---

## Use Descriptive Alt Text

```html
<img
src="laptop.jpg"
alt="Student learning HTML on a laptop">
```

---

# Development Best Practices

| Best Practice | Description |
|---------------|------------|
| Semantic HTML | Use meaningful HTML elements |
| Valid HTML | Follow W3C standards |
| Accessibility | Make content accessible to everyone |
| Performance | Optimize loading speed |
| SEO | Improve search visibility |
| Maintainability | Keep code organized |
| Mobile-First | Design for small screens first |
| Security | Use HTTPS and validate inputs |

---

# Additional Notes

## Validation

Always validate HTML using the W3C Markup Validator.

Benefits:

- Detects errors
- Improves compatibility
- Follows standards

---

## Progressive Enhancement

Build websites in layers:

1. HTML → Structure
2. CSS → Styling
3. JavaScript → Functionality

---

## Mobile-First Design

Design for mobile devices first and then scale for larger screens.

Benefits:

- Better responsiveness
- Better user experience
- Faster loading

---

# Summary

HTML document structure is the backbone of every website. A properly structured document improves accessibility, maintainability, SEO, and performance. By following modern HTML best practices such as semantic markup, responsive design, accessibility guidelines, and performance optimization techniques, developers can build professional, scalable, and user-friendly websites.

# 5. HTML5 Features and APIs

## Introduction

HTML5 is the latest major version of HTML that introduced many new features, elements, attributes, and APIs to make web development more powerful and efficient. HTML5 reduces the need for external plugins and provides built-in support for multimedia, graphics, storage, geolocation, and form validation.

### Advantages of HTML5

- Better multimedia support
- Improved form handling
- Enhanced accessibility
- Better SEO
- Mobile-friendly development
- Faster and cleaner code
- Support for modern web applications

---

# HTML5 Form Features

One of the biggest improvements in HTML5 is enhanced form handling and built-in validation.

---

## New Input Types

HTML5 introduced several new input types.

| Input Type | Description |
|------------|------------|
| `email` | Validates email addresses |
| `url` | Accepts website URLs |
| `tel` | Accepts telephone numbers |
| `number` | Numeric input field |
| `range` | Slider control |
| `date` | Date picker |
| `time` | Time picker |
| `datetime-local` | Date and time picker |
| `month` | Month selector |
| `week` | Week selector |
| `color` | Color picker |
| `search` | Search input |

---

## Example

```html
<form>

    <label>Email:</label>
    <input type="email" required>

    <br><br>

    <label>Website:</label>
    <input type="url">

    <br><br>

    <label>Birth Date:</label>
    <input type="date">

    <br><br>

    <input type="submit">

</form>
```

---

# HTML5 Validation Attributes

HTML5 provides built-in validation without JavaScript.

---

## Required Attribute

Makes a field mandatory.

```html
<input type="text" required>
```

---

## Pattern Attribute

Validates user input using regular expressions.

```html
<input
type="text"
pattern="[A-Za-z]{3,}">
```

---

## Min and Max Attributes

Defines minimum and maximum values.

```html
<input
type="number"
min="1"
max="100">
```

---

## Step Attribute

Defines valid intervals.

```html
<input
type="number"
step="5">
```

---

# Form Validation States

HTML5 provides CSS pseudo-classes for validation.

| Pseudo Class | Description |
|--------------|------------|
| `:valid` | Valid input field |
| `:invalid` | Invalid input field |
| `:required` | Required field |
| `:optional` | Optional field |

---

## Example

```css
input:valid {
    border: 2px solid green;
}

input:invalid {
    border: 2px solid red;
}
```

---

# HTML5 Semantic Elements

HTML5 introduced semantic elements that clearly describe content.

## Common Semantic Elements

| Element | Purpose |
|----------|---------|
| `<header>` | Header section |
| `<nav>` | Navigation links |
| `<main>` | Main content |
| `<section>` | Content section |
| `<article>` | Independent content |
| `<aside>` | Sidebar content |
| `<footer>` | Footer section |

---

## Example

```html
<header>
    <h1>My Website</h1>
</header>

<nav>
    Navigation Links
</nav>

<main>

    <section>

        <article>
            Article Content
        </article>

    </section>

</main>

<footer>
    Copyright 2025
</footer>
```

---

# Benefits of Semantic Elements

## Better SEO

Search engines can understand page structure more effectively.

## Better Accessibility

Screen readers can navigate webpages more easily.

## Improved Readability

Code becomes easier to understand and maintain.

## Future-Proof Development

Semantic code is more scalable and maintainable.

---

# HTML5 Multimedia Features

HTML5 allows embedding multimedia without third-party plugins.

---

## Audio Element

```html
<audio controls>

    <source
        src="audio.mp3"
        type="audio/mpeg">

</audio>
```

### Features

- Play audio directly
- Multiple audio formats
- No external plugins required

---

## Video Element

```html
<video
    width="600"
    controls>

    <source
        src="video.mp4"
        type="video/mp4">

</video>
```

### Features

- Built-in video player
- Subtitles support
- Multiple video formats

---

# HTML5 APIs

HTML5 introduced powerful APIs that allow developers to create modern web applications.

---

# 1. Local Storage API

Local Storage allows data to be stored inside the browser.

### Features

- Data persists even after browser restart
- Stores key-value pairs
- More storage than cookies

---

## Store Data

```javascript
localStorage.setItem(
    "username",
    "Manish"
);
```

---

## Retrieve Data

```javascript
let name =
localStorage.getItem(
    "username"
);
```

---

## Remove Data

```javascript
localStorage.removeItem(
    "username"
);
```

---

# 2. Session Storage API

Session Storage stores data only during the current browser session.

### Example

```javascript
sessionStorage.setItem(
    "theme",
    "dark"
);
```

### Difference

| Local Storage | Session Storage |
|--------------|----------------|
| Permanent | Temporary |
| Survives restart | Cleared after tab close |

---

# 3. Geolocation API

Allows websites to access user location.

---

## Example

```javascript
navigator.geolocation.getCurrentPosition(
    function(position) {

        console.log(
            position.coords.latitude
        );

        console.log(
            position.coords.longitude
        );

    }
);
```

---

## Uses

- Maps
- Location tracking
- Delivery applications
- Ride-sharing services

---

# 4. Canvas API

Canvas allows drawing graphics using JavaScript.

---

## Example

```html
<canvas
id="myCanvas"
width="300"
height="150">
</canvas>
```

```javascript
const canvas =
document.getElementById(
    "myCanvas"
);

const ctx =
canvas.getContext("2d");

ctx.fillRect(
    50,
    50,
    100,
    100
);
```

---

## Uses

- Games
- Charts
- Drawing applications
- Animations

---

# 5. Web Workers API

Web Workers allow JavaScript to run in the background.

### Benefits

- Improves performance
- Prevents UI freezing
- Executes heavy tasks separately

---

## Example

```javascript
const worker =
new Worker("worker.js");
```

---

# 6. History API

Allows manipulation of browser history without reloading pages.

### Example

```javascript
history.pushState(
    {},
    "",
    "/about"
);
```

### Uses

- Single Page Applications (SPA)
- Modern routing systems

---

# 7. File API

Allows web applications to access files selected by users.

---

## Example

```html
<input
type="file"
id="fileInput">
```

```javascript
const file =
document.getElementById(
    "fileInput"
).files[0];
```

---

## Uses

- Image uploads
- Document uploads
- File preview systems

---

# 8. Drag and Drop API

Provides native drag-and-drop functionality.

---

## Example

```html
<div draggable="true">
    Drag Me
</div>
```

### Uses

- Task management apps
- Kanban boards
- File upload interfaces

---

# Additional HTML5 Features

## Placeholder Attribute

```html
<input
type="text"
placeholder="Enter Name">
```

Displays hint text inside an input field.

---

## Autofocus Attribute

```html
<input
type="text"
autofocus>
```

Automatically focuses on the field when the page loads.

---

## Autocomplete Attribute

```html
<input
type="email"
autocomplete="on">
```

Provides automatic suggestions based on previous inputs.

---

# Summary

HTML5 introduced many powerful features that significantly improved web development. These include semantic elements, multimedia support, advanced form controls, built-in validation, and modern APIs such as Local Storage, Geolocation, Canvas, Web Workers, History API, File API, and Drag-and-Drop. Together, these features help developers build fast, interactive, responsive, and modern web applications without relying heavily on external plugins or libraries.
