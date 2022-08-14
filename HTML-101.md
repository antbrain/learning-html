# Learning HTML, One Link at a Time

#### Contents

- [HTML Document Anatomy](#html-document-anatomy)
- [Semantic Elements in HTML](#semantic-elements-html)
- [HTML Style Guides](#html-style-guides)
- [Meeting WCAG2 (Web Content Accessibility Guidelines)](#wcag-guidelines)

## HTML Document Anatomy

An HTML document is made up of the following elements:
- **<!DOCTYPE html>** : Needed to allow for functionality of a website.
- **<html></html>** : Wraps all content on page. Sometimes known as "root element".
- **<head></head>** : Container for HTML metadata, not visible to website visitors.
- **<meta charset="utf-8">** : Sets the character set to UTF-8, which includes characters from a majority of human written languages (can also use <meta author / content / property / name> for other metadata types)
- **<title></title>** : Sets title of page that appears in browser tab when page is loaded / bookmarked.
- **<body></body>** : Contains all content on page, including text, images, videos, games, playable, audio, etc.

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <title>have we gone insane?</title>
  </head>
  <body>
    <p>MAYBE</p>
  </body>
</html>
```

## Semantic Elements in HTML

- **<article>** : Defines independent, self-contained content
- **<aside>** : Defines content aside from the page content
- **<details>** : Defines additional details that the user can view or hide
- **<figcaption>** : Defines a caption for a <figure> element
- **<figure>** : Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
- **<footer>** : Defines a footer for a document or section
- **<header>** : Specifies a header for a document or section
- **<main>**: Specifies the main content of a document
- **<mark>**: Defines marked/highlighted text
- **<nav>** : Defines navigation links
- **<section>** : Defines a section in a document
- **<summary>** : Defines a visible heading for a <details> element
- **<time>** : Defines a date/time

## HTML Style Guides
- [How to Use the HTML5 Sectioning Elements](https://blog.teamtreehouse.com/use-html5-sectioning-elements) : Proivdes context into HTML5's elements that give elevated semantic meaning to the page.
- [markodenic's Awesome HTML Tips](https://github.com/markodenic/awesome-html-css-js-tips/blob/master/HTML.md)
- [w3 School's HTML Tag List](https://www.w3schools.com/tags/default.asp)
- [mdn web docs_ HTML Guides](https://developer.mozilla.org/en-US/docs/Learn/HTML)

## Meeting WCAG2 (Web Content Accessibility Guidelines)
- [How to Meet WCAG2 (Quick Reference)](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=128%2C313#language-of-page)
- [WebAIM's WCAG2's Checklist](https://webaim.org/standards/wcag/checklist)