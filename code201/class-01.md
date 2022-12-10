
# Getting Started

- [Getting Started](#getting-started)
  - [Getting Started](#getting-started-1)
    - [Important Links](#important-links)
    - [My Notes](#my-notes)
    - [Questions](#questions)
  - [Introduction to HTML](#introduction-to-html)
    - [Important Links](#important-links-1)
    - [Questions](#questions-1)
  - [Miscellaneous](#miscellaneous)
    - [Important Links](#important-links-2)
    - [Questions](#questions-2)
  - [Things I want to know more about](#things-i-want-to-know-more-about)

Module 1 dives into the introduction of web development. This first class covers the big picture of how the Web works and is vital to understand these basic principles

## [Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

### Important Links

[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Website Design](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

### My Notes

- Clients: End user-connected devices.
- Servers: Computers that store the website.
- Internet Connection: Allows us to send and receive data.
- TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that control how data is transmitted across the Web.
- DNS: Domain Name System acts as an address book for websites. The browser uses to find the website's IP address so it can retrieve the website.
- HTTP: Hypertext Transfer Protocol, a language for clients and servers. The foundation of any data exchange on the Web is a client-server protocol.
- Component files:
  - Code Files: HTML, JS, CSS
  - Assets: Images, PDF… etc

Address Entered in Browser by End-User

1. The browser goes to the DNS server to locate the website IP address
2. The browser sends an HTTP request to the server to request a copy of the website
3. If the server approves the request: Sever will send a "200 OK" message along with website files
4. The browser parses files to render websites.

### Questions

**Compose a short poem describing how HTTP sends data between computers.**

If the URL contains a domain name, the browser connects to the

Domain Name Server

The browser retrieves the corresponding IP address for the

Web Server

The browser connects to the web server and sends an HTTP request, and says

Sever

If the web server has the website, the server sends a 200 ok message and

Server

The browser gets the page and closes the connection, does a little parsing, and requests more from

Web Server

**Describe how HTML, CSS, and JS files are "parsed" in the browser.**

The browser sends requests to the server for HTML files, and within the HTML files, there are link to CSS stylesheets and script HTML elements that embed executable JavaScript code.

Order in Which Files are Parsed

1. HTML is parsed first.
2. If any link script elements are presents, it will request them and then parse them both.**
3. The browser generates an in-memory DOM tree and CSSOM tree and compiles and executes the parsed JavaScript.
4. The browser builds the DOM tree and applies CSSOM styles, and executes the JavaScript.

**How can you find images to add to a Website?**

There are many sources, but it is essential to use images that are Creative Commons licensed, your own, or you purchase a license for its use

**How do you create a String vs a Number in JavaScript?**

```js
// To create a Sting in JS enclose it in single quote marks.

let myName = 'Jeremy';

// To create a Number in JS don't enclose it in quote marks.

let myAge = 32;

```

**What is a Variable, and why are they important in JavaScript?**

Variables are containers that store the value. A Variable is a named container for a particular set of bits of data, such as primitives and objects.

## [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

### Important Links

[Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Medadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

### Questions

**What is an HTML attribute?**

HTML attributes contain additional information about a given element and won't appear in the content. This could be the height and width of an image or an Alt tag.

An Attribute should have

- A space between it and the element name.
- The attribute name is followed by an equal sign.
- An attribute value that is wrapped with opening and closing quote marks.

**Describe the Anatomy of an HTML element.**

An HTML element contains:

The opening tag: Contains the name of the element wrapped in opening and closing angle brackets. The opening tag is where the element begins.

The content: Content of the element. (h1, paragraph text.. etc.)

The closing tag: Similar to the opening tag but contains a forward slash before the element name, indicating the end of the element.

**What is the difference between article and section element tags?**

An article element should be used if the contents are a stand-alone piece, such as a blog post. This could also be a product card, widget, or product review.

A Section doesn't represent a stand-alone piece but as a part. The overall content is typically represented with a heading.

**What Elements does a "typical" website include?**

Semantic Tags

- **header**
- **navigation bar**
- **main content**
- **Main content subsections: article, section, and div elements**
- **sidebar**
- **footer**

Along with those, you have all the individual HTML elements, such as paragraphs, links, headings.

**How does metadata influence Search Engine Optimization?**

Metadata is vital for Search Engine Optimization. The title tag and meta description are significant and are what the end user typically sees when searching on Google. The description should be within 160 characters and relevant to the article while also grasping the searcher's attention. The viewport should also be specified, and a failure to add one could lead to a poor mobile experience. You can also provide social meta tags and meta robots. Meta charset sets the encoding of a webpage, and a failure to do so can lead to a page looking broken and ultimately resulting in a high bounce rate. Also, which language the article is in is important, so Google serves a website for a search query in a given language.

**How is the meta HTML tag used when specifying metadata?**

The meta HTML element represents metadata that cannot be represented by other HTML meta-related elements, like base, link, script, style, or title. Many meta elements include name and content attributes.

## Miscellaneous

### Important Links

[How to start to design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

[What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

### Questions

**What is the first step to designing a Website?**

Project ideation is the first step. It's a set of questions to determine the purpose, goals, and steps needed to be done to meet your goals.

**What is the most important question to answer when designing a Website?**

The most important question is, what do you want to accomplish?

**Why should you use an h1 element over an span element to display a top-level heading?**

HTML should be coded to represent its data but not styling. CSS is for how it should look and is the purpose and responsibility of CSS.

**What are the benefits of using semantic tags in our HTML?**

Writing semantic markup will increase visibility by providing search engines with important keywords. For example, an h1 heading is very important for Google and indicates what the following section is about, but if an h3 ( that said best places to live) were to be used first, followed by an h1 that says (worst places to live), then it would appear that the blog post is about the worst places to live. A user would load the page and notice that the first heading isn't about the best places but instead the worst and would likely leave.

**Describe 2 things that require JavaScript in the browser.**

Dynamically changing the content, scroll effects, pop up chat boxes and much much more.

**How can you add JavaScript to an HTML document?**

You add JavaScript internally inside the HTML document with the script element. The other way is by creating a javascript file and adding the following code inside the HTML document

```HTML

<script src="script.js" ></script>

```

## Things I want to know more about

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
