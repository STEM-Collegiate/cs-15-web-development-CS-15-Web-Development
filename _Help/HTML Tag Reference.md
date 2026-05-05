## HTML Structure Tags

These tags define the overall structure of an HTML document and tell the browser how to interpret the page.

---

### `<!DOCTYPE html>`

Declares the document as HTML5 so the browser knows how to correctly render the page.

* Tells the browser what version of HTML is being used

```html
<!DOCTYPE HTML>
```
[Additional info - \<!DOCTYPE HTML>](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)

---

### `<html>`

Wraps all content on the page and acts as the root of the document.



```html
<html>
</html>
```

[Additional info - \<html>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/html)

---

## Metadata

Metadata provides information about the webpage that is not directly displayed to users.

---

### `<head>`

Contains metadata such as title, links, and scripts.

* Holds non-visible information about the page

```html
<head>
</head>
```

[Additional info - \<head>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/head)

---

### `<title>`

Sets the text shown in the browser tab.

* Appears in the tab, not on the page itself

```html
<title>My Website</title>
```

[Additional info - \<title>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/title)

---

### `<meta>`

Provides additional information like character encoding or viewport settings.

* Helps with compatibility and responsiveness

```html
<meta charset="UTF-8">
```

[Additional info - \<meta>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/meta)

---

### `<link>`

Connects external files like CSS to the HTML document.

* Used to apply styling from another file

```html
<link rel="stylesheet" href="styles.css">
```

[Additional info - \<link>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/link)

---

### `<script>`

Links or includes JavaScript code.

* Adds interactivity and behavior to the page

```html
<script src="script.js"></script>
```

[Additional info - \<script>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/script)

---

## Content

These tags define what users actually see on the webpage.

---

### `<body>`

Contains all visible content like text, images, and links.

* Everything displayed on the page goes here

```html
<body>
</body>
```

[Additional info - \<body>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/body)

---

### `<a>`

"Anchor" tags are used for creating hyperlinks between web pages.

* It must include an `href` property representing the URL to the linked page.
* URLs can be relative (for local files) or absolute (for external files / webpages).


External URL:

```html
<a href="https://www.google.com/">Google</a>
```

Relative URL:

```html
<a href="index.html">Home</a>
```

[Additional info - \<a>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/a)

---

### Text Tags

These tags are used to display written content on a webpage.

---

#### `<p>`

Defines a paragraph of text.

* Used for blocks of readable text

```html
<p>This is a paragraph.</p>
```

[Additional info - \<p>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/p)

---

#### `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`

Define headings, with `<h1>` being the largest and most important.

* Used to organize content by importance

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

[Additional info - \<h1>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/Heading_Elements)

---

### Lists

Lists group related items together.

---

#### `<ul>`

Creates an unordered (bulleted) list.

* Used when order does not matter

```html
<ul>
</ul>
```

[Additional info - \<ul>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/ul)

---

#### `<ol>`

Creates an ordered (numbered) list.

* Used when order matters

```html
<ol>
</ol>
```

[Additional info - \<ol>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/ol)

---

#### `<li>`

Defines an item inside a list.

* Must be inside `<ul>` or `<ol>`

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

[Additional info - \<li>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/li)

---

## Images

Images are used to display visuals on a webpage.

---

### `<img>`

Embeds an image into the page.

* `src` specifies the file path
* `alt` provides fallback text

```html
<img src="images/photo.png" alt="Description">
```

[Additional info - \<img>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img)

## Semantic Tags

Semantic tags clearly describe the purpose of the content they contain, improving readability, accessibility, and organization.

---

### `<header>`

Defines the top section of a page, often containing titles, logos, or navigation.

```html
<header>
    <h1>My Website</h1>
</header>
```

[Additional info - \<header>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/header)

---

### `<main>`

Represents the main content of the webpage.

```html
<main>
    <p>This is the main content of the page.</p>
</main>
```

[Additional info - \<main>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/main)

---

### `<footer>`

Defines the bottom section of a page, often containing copyright or contact information.

```html
<footer>
    <p>© 2026 My Website</p>
</footer>
```

[Additional info - \<footer>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/footer)

---

### `<section>`

Groups related content together into a logical section.

```html
<section>
    <h2>About Us</h2>
    <p>We build websites.</p>
</section>
```

[Additional info - \<section>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/section)

---

### `<article>`

Represents a standalone piece of content that could exist independently.

```html
<article>
    <h2>News Article</h2>
    <p>This is a news story.</p>
</article>
```

[Additional info - \<article>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/article)

---

### `<nav>`

Contains navigation links for moving around the website.

```html
<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
</nav>
```

[Additional info - \<nav>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/nav)

---

## General Purpose Tags

These tags are used when semantic tags are not appropriate or when more flexible grouping is needed.

---

### `<div>`

A block-level container used to group larger sections of content for styling or layout.

```html
<div>
    <p>This content is grouped together.</p>
</div>
```

[Additional info - \<div>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/div)

---

### `<span>`

An inline container used to group small pieces of text for styling.

```html
<p>This is a <span>highlighted</span> word.</p>
```

[Additional info - \<span>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/span)

---

### `<table>`

Used to display data in rows and columns, but should not be used for page layout.

```html
<table>
    <tr>
        <td>Row 1</td>
        <td>Data</td>
    </tr>
</table>
```

[Additional info - \<table>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/table)

## Content

These tags are used to embed media or create interactive elements on a webpage.

### `<video>`

Embeds a video player on the webpage.

* `src`: Path to the video file. *Note: You actually need a video source for this to work saved in your folders somewhere.*
* `controls`: Adds play, pause, and volume controls

```html
<video src="video.mp4" controls></video>
```

[Additional info - \<video>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/video)

---

### `<audio>`

Embeds an audio player on the webpage.

* `src`: Path to the audio file. *Note: You actually need an audio source for this to work saved in your folders somewhere.*
* `controls`: Adds playback controls

```html
<audio src="audio.mp3" controls></audio>
```

[Additional info - \<audio>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/audio)

---

### `<iframe>`

Embeds another webpage or external content inside the current page.

* `src`: URL of the embedded content
* `width` / `height`: Size of the frame

```html
<iframe src="https://example.com" width="300" height="200"></iframe>
```

[Additional info - \<iframe>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/iframe)

---

### `<canvas>`

Creates a drawing area for graphics using JavaScript.

* `width` / `height`: Size of the drawing area

```html
<canvas width="300" height="200"></canvas>
```

[Additional info - \<canvas>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/canvas)

---

### `<svg>`

Defines scalable vector graphics directly in HTML.

* `width` / `height`: Size of the graphic

```html
<svg width="100" height="100">
    <circle cx="50" cy="50" r="40"></circle>
</svg>
```

[Additional info - \<svg>](https://developer.mozilla.org/en-US/docs/Web/SVG/Guides/SVG_in_HTML)

---

### `<summary>` and `<details>`

Creates a collapsible section that users can expand or hide.

* `<summary>`: The visible title users click
* `<details>`: Wraps the hidden content

```html
<details>
    <summary>Click to expand</summary>
    <p>Hidden content here</p>
</details>
```

[Additional info - \<summary>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/summary)

[Additional info - \<details>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/details)

---

## Text Decoration

These tags add meaning or emphasis to text.

### `<strong>`

Indicates important text (usually bold).

```html
<p>This is <strong>important</strong> text.</p>
```

[Additional info - \<strong>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/strong)

---

### `<em>`

Emphasizes text (usually italic).

```html
<p>This is <em>emphasized</em> text.</p>
```

[Additional info - \<em>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/em)

---

### `<mark>`

Highlights text.

```html
<p>This is <mark>highlighted</mark> text.</p>
```

[Additional info - \<mark>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/mark)

---
### `<del>` and `<ins>`

Show deleted and inserted text.

```html
<p>This is <del>old</del> <ins>new</ins> text.</p>
```

[Additional info - \<del>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/del)

[Additional info - \<ins>](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/ins)