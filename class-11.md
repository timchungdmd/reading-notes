# Video and Audio Content

Explain how the ability to use video and audio on the web has evolved since the early 2000s.
- First mass adopted online video and audio were  based on Flash and Silverlight technologies. Both softwares had security and accessibility issues, and are no obsolete, in favor of native HTML solutions 'video' and 'audio' elements and the availability of Javascript APIs for controlling them. 

Describe the use of the src and controls attributes in the \<video> element.
- 'SRC' contains a path to the video we want to embed, 'Control' attribute includes broswer's own control interface, or we can build our own interface using the appropriate Javascript API. At a  minimum, the interface must include a way to start and stop the media and to adjust the volume.

Why is it important to have fallback content inside the \<video> element?
- Paragraph inside the 'video' tag is called fallback content. Fallback content is important because it will be displayed if the browser accesssing the page doesn't support the 'video' element, allowing us to provide a fallback for older browsers.

Write a very short story where \<audio> and \<video> are characters.
- audio and video are essentially the same, just a little different. Both have various codecs that encode audio or video data, and there are multiple containers that package these encoded date define structure of those said data.

# A Complete Guide To Grid

How does Grid layout differ from Flex?
- Flexbox is one dimensional flow, but grib layout is a two dimenstional grid based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. 

Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid container: The element on which display grid is applied. It's the direct parent of all the grid items.
- Grid line: The dividing lines that make up the structure of the grid. They can be either vertical or horizontal and reside on either side of a row or column.

- Grid item: Direct descendent of grid container. Item elements are grid items, but sub-item isn't.

- Grid cell: the space between two adjacent row and two adjacent column grid lines. It's a single unit of the grid.

- Grid track: The space between two adjacent grid line.It is equivalent of columns or rows of the grid.

- Grid area: The total space surrounded by four grid line. A grid area may be composed of any number of grid cells.

# Responsive Images

Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
- Avoid wasting bandwidth, it can adapt to different screen sizes and different resolutions.

Define the following \<img> attributes srcset and sizes. Write an example of how they are used.
- Srcset define the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.(example: 'file name' 'image's intrinsic size')
- Size attribute defines a set of media conditions and indicates what image size would be best to choose, 
when certain media conditions are true.(exampe: 'media condition' 'width of the slot the image will fill')

\<srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"
  sizes="(max-width: 600px) 480px,
         800px"/>

How is srcset more helpful for responsive images than CSS or JavaScript?
- Syntax is easier, it does a better job than HTML CSS explicit media attributes. Also it has the opportunity to be much better in the future with browser settings and browser improvements. Srcset lets the browser do the work of figuring out which image is best. 

# References
- [Video and Audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content#video_and_audio_on_the_web)
- [Complete guide to grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [From object to iframes; other embedding technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
- [Responsive Images: If you're just changing resolutions, use srcset](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/)
