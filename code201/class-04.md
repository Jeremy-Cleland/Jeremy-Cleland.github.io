# Class 04 Reading Notes

- [Class 04 Reading Notes](#class-04-reading-notes)
  - [Learn HTML](#learn-html)
    - [Important HTML Links](#important-html-links)
      - [HTML Questions](#html-questions)
  - [Learn CSS](#learn-css)
    - [Important CSS Links](#important-css-links)
    - [CSS Questions](#css-questions)
  - [Learn JS](#learn-js)
    - [Important JS Links](#important-js-links)
    - [JS Questions](#js-questions)
  - [Miscellaneous](#miscellaneous)
    - [Important Miscellaneous Links](#important-miscellaneous-links)
    - [Misc Questions](#misc-questions)
  - [Things I want to know more about](#things-i-want-to-know-more-about)

## Learn HTML

### Important HTML Links

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

#### HTML Questions

Q: To create a basic link, we wrap text or other content inside what element?

  `<a href="https://www.clelandco.com/">Cleland Co.</a>.`

Q: The `<href>` attribute contains what information?

Q: What are some ways we can ensure links on our pages are accessible to all readers?

- Use keywords in the link target text

- use descriptive link text

## Learn CSS

### Important CSS Links

[CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

[CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

### CSS Questions

Q: What is meant by “normal flow”?

- The normal flow is the default layout for CSS elements if you haven't changed their layout

Q: What are a few differences between `block-level` and `inline` elements?

- `Block-Level`: Block-level element occupies the entire horizontal space of its parent element[^2]

- `inline`: inline elements are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content.[^2]

- Content model

- Generally, block-level elements may contain inline elements and (sometimes) other block-level elements. Inherent in this structural distinction is the idea that block elements create "larger" structures than inline elements.[^2]

Q: `Static` positioning is the default for every HTML element.

Q: Name a few advantages to absolute positioning on an element.

- Elements that are relatively positioned remain in the normal flow of the document. In contrast, an absolutely positioned element is taken out of the flow; thus, other elements are positioned as if it did not exist.

Q: What is a key difference between fixed positioning and absolute positioning?

- Fixed positioning is similar to absolute positioning, with the exception that the element's containing block is the initial containing block established by the viewport, unless any ancestor has transform, perspective, or filter property set to something other than none [^1]

## Learn JS

### Important JS Links

[Functions – Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

### JS Questions

Q: Describe the difference between a function declaration and a function invocation.

- Function declaration: You must define the function and include the code you want to run inside it.

- Function invocation: After the function declaration, all that's left is running it or invoke it. You must call it by its name and include paramaters if needed, followed by parentheses

Q: What is the difference between a parameter and an argument?

- Function parameters are the names listed in the function's definition.

- Function arguments are the real values passed to the function.

- Parameters are initialized to the values of the arguments supplied.

## Miscellaneous

### Important Miscellaneous Links

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

### Misc Questions

Q: Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

 Paired programming has many advatages.

- Collaboration with the proper teammate would drive cleaner code with a better understanding.

- Increased ability to research problem sets and come together on a solution as a team.

## Things I want to know more about

Different Sources besides MDN Web Docs (Books.. etc)

[^1] [Fixed positioning](<https://developer.mozilla.org/en-US/docs/Web/CSS/position#fixed_positioning>)
[^2] [Block-level vs. inline](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements#block-level_vs._inline)
[^3] [Fixed positioning](<https://developer.mozilla.org/en-US/docs/Web/CSS/position#fixed_positioning>)
