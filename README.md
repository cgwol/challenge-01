Challnge 01
# 01 HTML, CSS, and Git: Code Refactor

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```


## Changes to index.html
	<div class="header"> is replaced with <header>.
	The <div> containing the navigation links is replaced with <nav>.
	The sections with class names search-engine-optimization, online-reputation-management, and social-media-marketing are given IDs to improve navigation.
	The <div class="benefits"> is replaced with <section class="benefits">.
	The individual benefit sections are wrapped in <article> tags to represent discret sections of content.
	Added alt attributes to the <img> tags, providing descriptive text for each image.
	The closing </div> after <div class="footer"> is replaced with </footer>.

## Changes to Style.css 
  Changed .header to header.
  Changed .header div to header nav.
  Added header nav ul li selector to style the navigation list items.
  Updated the selector for .search-engine-optimization, .online-reputation-management, and social-media-marketing to .content article.
  Added .content article img selector to style the images within the articles.
  Added .content article h2 selector to style the headings within the articles.
  Renamed .benefit-lead, .benefit-brand, and .benefit-cost to .benefits article.
  Updated the selector for .benefit-lead img, .benefit-brand img, and .benefit-cost img to .benefits article img.
  Changed .footer to footer.

# challenge-01
