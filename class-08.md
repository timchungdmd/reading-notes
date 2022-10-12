# CSS Layout

## Flexbox
Flexbox is designed for one-dimensional content. Explain what this means.
- One dimensioanl content means items are layed out i one direction. 

Explain the difference between the main axis and cross axis.
- Main axis is the one set by your flex-direction property. Cross axis is the one that runs in perpendicular direction to the main axis.

How can using certain properties of flexbox negatively impact accessibility?
- Any properties that can reorder the visual display away from how things are ordered in the HTML document can negatively impact accessibility. Recordering only happens for the visaul order, not the logical/HTML order, hence screen reader read out will not be in the same order as visual order.

What are some advantages of using flexbox over float?
- Positioning child elements is easier with flexbox, flexbox is responsive and mobile friendly, flex container's margine do not collapse with the margins of its content, it's easy to change visual order without making changese to  HTML.

How does this topic connect with your long term goals?
- Flexbox is a crucial element to UI/UX of any web development. It is more predictable than using float and positioning properties. It's also compatible with various display sizes, which will provide more uniform user experience across different platforms.


# References
- [Learn CSS - Layout](https://web.dev/learn/css/layout/)
- [Flexbox vs. Grid](https://medium.com/@byron.skoutaris/flexbox-vs-grid-36d36ae0096e)
- [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Layout](https://web.dev/learn/css/layout/)
- [Why would you use flexbox instead of floats](https://www.geeksforgeeks.org/why-would-you-use-flexbox-instead-of-floats/#:~:text=These%20are%20the%20following%20reasons%20to%20use%20flexbox%20over%20floats.&text=Flexbox%20is%20responsive%20and%20mobile,even%20making%20changes%20in%20HTML.)
