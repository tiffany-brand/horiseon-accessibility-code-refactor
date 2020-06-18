# horiseon-accessibility-code-refactor

## Refactor of the Horiseon web page to follow accessibility standards and optimize for search engines.

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
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes made

- added a more descriptive title
- added semantic tags (header, nav, section, article, aside, footer)
- changed h3 tags to h2 tags in aside and restyled to make the font smaller
- added alt text for images
- consolidated repetitive css and made selectors more specific
- re-organized css to better match sections in html
- fixed missing id to make menu link work correctly
- commented HTML and CSS for readability and clarity

## Deployed page

Page published at: https://tiffany-brand.github.io/horiseon-accessibility-code-refactor/
