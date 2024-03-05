# 01 HTML, CSS, and Git: Code Refactor

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

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

## Project Notes

1. Changed all divs to semantic elements for sections of the site.
2. Added comments to further separate code into sections for future coders.
3. I consolidated code by making universal classes for similarly styled items and kept the original class as an id where applicable. I could've also used a space (in the html class) and gave each div 2 classes but figured id was preferrable.
4. The search-engine-optimization, online-reputation-management and social-media-marketing classes were below the benefits class in the css folder but above them in the HTML. I moved these to what seems like their proper spot and consolidated more classes. Instead of adding classes, I could've used .content div as a selector but chose to use classes.
