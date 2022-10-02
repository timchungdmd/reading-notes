

How does HTML work?
- HTML asks permission to receive website data from DNS server. Once its approved by the DNS server, the server will send the data in bits and pieces. The line that's connecting both are called TCP/IP. Once all the data is received by the client'c computer it get reassmebled into its original form

How does HTML, CSS and JS files get parsed?
- HTML is first requested and received. Browser will then request any CSS files and JS files that are linked by the HTML file. The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

How can I find images for my website?
- Use google search, but in order reduce the likelihood of copyright violatio, use Google's license filter and select only creative common licenses

How do you create a String vs a Number in JavaScript?
- To signify that the value is a string, enclose it in single quote marks. Number type is written without the single quote marks

What is a Variable and why are they important in JavaScript?
- Variable is a container that stores value, and it is decalred by starting with the <b>let<\b> keyword. Variable is important because it enables programs to be dynamic by allowing its values to change dynamically

What is an HTML attribute?
- Attributes contain extra information about the element that won't appear in the content

Describe the Anatomy of an HTMl element.
- Each element starts with an opening tag, followed by the content, and then a closing tag

What is the Difference between \<article> and \<section> element tags?
- The \<section> tag defines a section in a document. The \<article> tag specifies independent, self-contained content.

What Elements does a “typical” website include?
- Every HTML starts with \<\!DOCTYPE html>. Next is \<html> which wraps all the content. Next element is \<head> container for everything you want to include on the HTML page, that isn't the content the page will show to viewers. Next element is the \<meta> element. This element represents metadata that cannot be represented by other HTML meta-related elements. Next is the \<title> element, which containtsthe title that appears in the browser tab. Last is The \<body> element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else

How does metadata influence Search Engine Optimization?
- Meta elements containt name and content attributes. Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines

How is the \<meta> HTML tag used when specifying metadata?
- Meta elements can specify website's character encoding, add an author and description, add custom icons, and it can specify proprietary features for that webiste

What is the first step to designing a Website?
- Start with project ideation: What am I trying to accomplish, how will a website help me reach my goals, what needs to be done and in what order to reach my goal? Structure these steps before even exploring technical aspect

What is the most important question to answer when designing a Website?
- What exactly do I want to accomplish?

Why should you use an \<h1> element over a \<span> element to display a top level heading?
- \<h1> element is a semantic element, which plays the role of top level heading of the website. It also has a default style of large font size to make it look like a heading. \<span> element with multiple attributess can render the content its wrapping to look like a heading, but it lacks the semantic value. 

Describe 2 things that require JavaScript in the Browser?
- Dynamically updating website and server side programming

How can you add JavaScript to an HTML document?
- Internal js can written between script element. External js can be written as a separate file and linked via src attribute in script element.