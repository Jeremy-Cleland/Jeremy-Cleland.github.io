# Class 11: Audio, Video, Images

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

## Video and Audio Content Questions

- Q: Explain how the ability to use video and audio on the web has evolved since the early 2000s.

  - A:

- Q: Describe using the src and controls attributes in the `<video>` element.

  - A: In the same way as for the `<img>` element, the `src` (source) attribute contains a path to the video you want to embed. It works in the same way. ^[1]



- Q: Why is it important to have fallback content inside the `<video>` element?

  - A: The fallback element is essential for browsers that dont support the `<video>` element. The fallback can be anything from a link to the video.

- Q: Write a concise story where `<audio>` and `<video>` are characters.

  - A: The video element shows videos well while the audio element plays a given song, podcast, or whatever else. The audio element takes up[ less space than a video player, as there is no visual component — you need to display controls to play the audio. Other differences from HTML video are as follows:

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## CSS GRID Questions

- Q: How does Grid layout differ from Flex?

  - A: flex is one-dimensional while grid is two-dimensional.


- Q: Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

  - A:
  - Grid Container:  The element on which `display: grid` is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

  - Grid Item: The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

  - Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

  - Grid Cell: The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. Here’s the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.

  - Grid Track: The space between two adjacent grid lines. You can think of them as the columns or rows of the grid. Here’s the grid track between the second and third-row grid lines.


[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

## Responsive Images Questions

- Q: Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

  - A: Page Speed.

- Q: Define the following `<img>` attributes `srcset` and sizes. Write an example of how they are used.
 
  - A: `srcset` defines the set of images we will allow the browser to choose between, and what size each image is.

- Q: How is srcset more helpful for responsive images than CSS or JavaScript?
A: srcset defines the set of images we will allow the browser to choose between and what size each image is. The attribute sizes define a set of media conditions (e.g., screen widths) and indicate what image size would be best to choose when certain media conditions are true. These coupled together allow for the browser to select the best photo for the screen size. 


## Bookmark and Review

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)


[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)


### Code 201

- [Class 01 Reading Notes](/code201/class-01.md)
- [Class 02 Reading Notes](/code201/class-02.md)
- [Class 03 Reading Notes](/code201/class-03.md)
- [Class 4 Reading Notes](/code201/class-04.md)
- [Class 5 Reading Notes](/code201/class-05.md)
- [Class 6 Reading Notes](/code201/class-06.md)
- [Class 7 Reading Notes](/code201/class-07.md)
- [Class 8 Reading Notes](/code201/class-08.md)
- [Class 9 Reading Notes](/code201/class-09.md)
- [Class 10 Reading Notes](/code201/class-10.md)
- [Class 11 Reading Notes](/code201/class-11.md)
- [Class 12 Reading Notes](/code201/class-12.md)
- [Class 13 Reading Notes](/code201/class-13.md)
- [Class 14 Reading Notes](/code201/class-14.md)
- [Class 15 Reading Notes](/code201/class-15.md)

## Sources

^[1](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video#attr-src)
