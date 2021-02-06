# A review of HTML & CSS & JS
* How People Access the Web:
- *Browsers* :People access websites using software called a web browser
example: Firefox, Internet Explorer, Safari,Chrome, and Opera.
- *Web Servers* :When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website.
- *Screen readers* : are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.
- *Devices* :People are accessing websites on an increasing range of devices including desktop computers,laptops, tablets, and mobile phones. It is important to remember that various devices have different screen sizes and some have faster connections to the web than others.
* How Websites Are Created:
All websites use HTML and CSS, but content management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.

## HTML Describes the Structure of Pages :
- HTML Uses Elements to Describe the Structure of Pages
- The HTML code : is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.
example :`<h1>that tag for make heading </h1>`,`<p>this tag for paragragh </p>`
- Tags act like containers. They tell you something about the information that lies between their opening and closing tags
- Attributes Tell us More About Elements :
Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
example :`<p lang="en-us">Paragraph in English</p>` ,lang is an attribute for` <p>` tag  , and `en-us` is a value for this attribute.
`<body>` Everything inside this element is shown inside the main browser window.
`<head>` Before the `<body>` element you will often see a `<head>` element.
This contains information about the page (rather than information that is shown within the main part of the browser window). You will usually find a `<title>` element inside the `<head>` element.

## Extra Markup :
* Since the web was first created, there have been several different versions of HTML:
- HTML4 Released 1997
- XHTML 1.0 Released 2000
- HTML5 Released 2000
 ###  tags HTML :
 * *DOCTYPES* 
 Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included). example:
 - HTML5 : `<!DOCTYPE html>` 
 - HTML 4: `<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`
 - Transitional XHTML 1.0 :`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/ xhtml1-transitional.dtd">`
 * *Comments in HTML :* `<!-- -->` 
 If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters: `<!-- comment goes here -->`
* *ID Attribute* 
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). `<p id="pullquote">`
It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).that used with CSS 
* *Class Attribute* 
is a way to identify several elements as being different from the other elements on the page.
The class attribute on any element can share the same value.
* *Block Elements*
Some elements will always appear to start on a new line in the browser window. These are known as block level elements.
example of block elements are `<h1>`, `<p>`, `<ul>`, and `<li>`.
* *Inline Elements*
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
Examples of inline elements are `<a>`, `<b>`, `<em>`, and `<img>`.
* *Grouping Text & Elements In a Block*
* *`<div>`* The <div> element allows you to group a set of elements together in one block-level box.
* *Grouping Text & Elements Inline*
* *`<span>`* The `<span>` element acts like an inline equivalent of the `<div>` element. It is used to either:
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
2. Contain a number of inline elements.
* *IFrames*
An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
- An iframe is created using the`<iframe>` element. There are a few attributes that you will need to know to use it: src,height,width,scrolling,frameborder and seamless.
* *Information About Your Pages*
* *`<meta>`*
The `<meta>` element lives inside the `<head>` element and contains information about that web page.
this attribute that are commonly used are: description,keywords,robots,author,pragma and expires.
* *Escape Characters*
- There are some characters that are used in and reserved by HTML code.`<`,`>` ,`&`,`"`,`¢`,`£` ,`¥`,`¤`, `©`,`®`,`™`,`‘`,`'`,`“` ,`”` ,`#`.

# HTML5 Layout :
* *Traditional HTML Layouts*
For a long time, web page authors used `<div>` elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar).
 Authors used class or id attributes to indicate the role of the `<div>` element in the structure of the page.
 * *New Html5 Layout Elements*
 HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them.
 They are still subject to change, but that has not stopped many web page authors using them already.
 1. *Headers & Footers* `<header>`and `<footer>`
 2. *Navigation* `<nav>`
 3. *Articles* `<article>`
 4. *Asides* `<aside>`
 5. *Sections*` <section>`
 6. *Heading Groups* `<hgroup>`
 7. *Figures* `<figure>`and `<figcaption>`
 8. *Sectioning El ements*`<div>`
 9. *Linking Around Block-Level Elements* `<a>`

 # Process & Design
 * It's important to understand w XX ho your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
 * Site maps allow you to plan the structure of a site.
 * Wireframes allow you to organize the information that will need to go on each page.
 * Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
 * You can differentiate between pieces of information using size, color, and style.
 * You can use grouping and similarity to help simplify the information you present.

 # itroduction into  javaScript :
 * javaScript :
 is is a programming language that allows you to make web pages more interactive by accessing and modifing the content and markup used in a web page while it being viewed in the browser.
 * Before you learn how to read and write the JavaScript language itself, you need to become familiar with some key concepts in computer programming. They will be covered in three sections:
1. What is a script and how do i create one ?
2. How do computers fit in with the world around them?
3. How do I write a script for a web page? 

1. What is a script and how do i create one ?
**A script** is a series of instructions that a computer can follow to achieve a goal.
scripts can run different sections of the code in response to the situation around them.
a script is just a series of short instructions, each of which is performed in order to solve the problem in hand.
* Each time the script runs, it might only use a subset of all the instructions.
* Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
* To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
2.  How do computers fit in with the world around them ?
* computers create models of the world using data.
* the models use objects to represent physical things .
objects can have : proprties that tell us about the object , 
methods that preform tasks using the properties of that objects,
events which are triggered when a user interacts with the computer.
* programmers can write code to say"when this event occurs run that code ".
* web browsers use html markup to create a model of the web page . each element creates its own node ( which is kind of object).
* to make web pages interactive , you write code that uses the browser's model of the web page .

3.  How do I write a script for a web page ? 
* It is best to keep JavaScript code in its own JavaScriptfile.
 JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.
 * The HTML` <script>` element is used in HTML pages to tell the browser to load the JavaScript file (rather like the `<link>` element can be used to load a CSS file).
 * If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.
 