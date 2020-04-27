# Introductory HTML and Java Script Notes

## HTML Chapter 1: Structure

* HTML pages are text documents.
* HTML code is made up of characters that live inside brackets like these: `<>`, these are called HTML **elements**. 
* **Elements** are made up of two __tags__, an opening and a closing tag. The closing tag has and extra forward slash like this: `</>` HTML tags tell the browser about the information that sits between the opening and closing tags, such as if it is a heading, or the body of the page. The opening tag dentoes the start of a piece of content, the closing tag denotes the end.
* **Attributes** provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts:
    * The attribute **name** indicates what kind of information you are supplying about the elements content. It should be written in lowercase.
    * The attribute **value** is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values.

* An example of an attribute is below.

``` <p lang="en-us">Paragraph in English</p>```

* The name of the attribute is `lang` which represents the language used on the page. The value of that language is `en-us` or the English language used in the United States.

### Examples of elements:
* `<body></body>`: Everything within this element is what is shown inside the main browser window.
* `<head></head>`: This contains information about the page, the **title** element is typically found here.
* `<title></title>`: The contents of this element are either shown in the top of the browser, above where you usually type the URL of the page you want to visit, or on the tab of that page.
* `<p></p>`: Paragraph
* `<ul></ul>`: Unordered List
* `<ol></ol>`: Ordered List
* `<h1></h1>`: Level 1 Header
* `<nav></nav>`: Navigation

## HTML Chapter 8: Extra Markup
* Because there are several versions of HTML, each web page should begin with a DOCTYPE declaration on top to tell what type it is.
* If you want to add a comment in the code that isn't visible in the user's browser use: `<!--comment goes here-->`
* The **id attribute** is used to uniquely identify an elemnt from other elements on the page. Its value should start with a letter or an underscore. The **id attribute** is known as a global attribute because it can be used on any element.
* The **class attribute** gives a way to identify several elements as being different from the other elements on the page. Its value should describe the class it belongs to.
* **Block Elements** are elements that will always appear to start on a new line in the browser window. Examples of block elements are: `<h1>`(level 1 header), `<p>`(paragraph),`<ul>`(unordered list), and `<li>`(list item).
* **Inline Elements** are elements that always appear to continue on the same line as their neighboring elements. Examples of inline elements are: `<a>`(hyperlink), `<b>`(bold text), `<em>`(emphasis or italics), `<img>`(image).
* The `<div>` element allows you to group a set of elements together in one block-level box. You might create a `<div>` tag to contain all the elements for the header of your site like th logo and navigation bar. 
* The `<span>` element acts like the inline equivalent of the `<div>` element. It is used to either.
    1. Contain a section of text where ther is no other suitable element to differentiate it from its surrounding text.
    1. Contain a number of inline elements.
    * You will usually see that a class or id attribute is used with `<span>` elements to explain the purpose of the `<span>` element or so CSS styles can be applied to elements that have specific values for these attributes. 
* The `<iframe>` is like a little window that has been cut into your page, and in that window you can see another page. The term iframe is an abbreviation for "inline frame". An example of use of iframes is to embed a Google mMap into a page.
* The `<meta>` element lives inside the `<head>` element and contains information about that webpage. It is not visible on the page but allows you to supply all kinds of information about your webpage.
* **Escape Characters** are used to include special characters in your pages that are usually reserved for HTML. such as angled brackets and copyright symbols. 
 
 ## HTML Chapter 17: HTML5 Layout 

* The `<div>` element is used to group together related elements on the page.
* The class or id attributes indicate the role of the `<div>` element in the structure of the page.

### HTML5 Layout Elements:

* The `<header>` and `<footer>` elements can be used for:
    * The main header or footer that appears at the top or bottom of every page on the site.
    * A header or footer for an individual `<article>` or `<section>` within the page.
* The `<nav>` element is used to contain the major navigational blocks on the site such as the primary site navigation. 
* The `<article>` element acts as a container for any section of a page that could stand alone.
* The `<aside>` element has two purposes depending on whether it is inside an `<article>` element or not.
    * When the `<aside>` element is used inside a `<article>` element. it should contain info that is related to the article but not essential to its overall meaning. Ex.) a pullquote or glossary.
    * When the `<aside>` element is used outside of an `<article>`, it acts as a container for content that is related to the entire page. Ex.) links to other sections of the site or a search box.
* The `<section>` element groups related content together.
* The `<hgroup>` element groups together a set of one or more `<h1>` through `<h6>` elements so they are treated as a single heading.
* The `<figure>` element is used to contain any content that is referenced in the main flow of an article (not just images.) Examples of usage are images, videos, graphs, diagrams, code samples, and text that supports the main body of an article.
    * THe `<figure>` element should also contain a `<figcaption>` element which provides a text description for the content in the figure element.

## HTML Chapter 18: Process and Design 

When creating a website you must conisder a few things:
* Who is this website for?
* Why will people be visiting your website?
    * What are the underlying motivations of visitors?
    * What are the specific goals of the visitors?
* What are your visitors trying to achieve?
* What information do your visitors need?
* How often will people visit your site?

After deciding what needs to appear on your website, you need to organize the information into sections or pages. This can be done using a **site map**.

* A **site map** is a diagram of the pages that will be used to structure the site. This shows how the pages will be grouped. 
* A **site map** usually begins with a homepage, and the other pages are compartmentalized into sections that are linked to the homepage.

* A **wireframe** is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of information and how much space it might require.

### Design

* Webpages contain a lot of content that need to be organized and prioritized.

* **Visual Hierarchy** refers to the order in which your eyes percieve what they see. It is created by adding **visual contrast** between items being displayed, the items with higher contrast are recognized and processed first. Visual hierarchy helps to get the visitor's attention on the important stuff using size, color, and style.
* Images create a high visual contrast and often attract the eye first.

* **Grouping** related pieces of information together can make a design easier to comprehend.

* **Navigation** helps people find where they want to go on your site and how your site works.

## JS Chapter 1: The ABC of Programming.

### Script
* A **script** is a series of instructions that a computer can follow to achieve a goal. Scripts are like recipes, by following the steps in a recipe, cooks can make a dish that has never been made before.
* A browser may use different parts of the script depending on how the user interacts with the webpage.
* Scripts can run different sections of the code in response to the situation around them.

* To write a script, you first need to state your goal and then the list of tasks that need to be completed in order to achieve it. To break it down you want to:
    1. **Define the goal**. What task do you want to achieve? This is like a puzzle for the computer to solve.
    1. **Design the script** by splitting the goal into a series of tasks that are going to be involved in solving this puzzle. You can write this down like a recipe, with all the individual steps that the computer needs to perform in order to complete each individual task laid out in a step-by-step order.
    1. **Code each step**, each of the steps need to be written in a programming language that the computer undserstands, such as JavaScript.
* To understand JavaScript better you need to become familiar with the **vocabulary** (the words that the computer understands), and the **syntax** (how you put those words together to create instructions computers can follow).
* You also need to learn how a computer achieves different types of goals using a **programmatic** approach to problem solving. Computers solve problems programatically, this means they follow series of instructions one after another.
### Objects and Properties
* In computer programming, each physical thing in the world can be represented as an **object**. Objects can have:
    * Properties, or the characteristics of the object.
    * Events are the computers way of saying "Hey, this happened!"
    * Methods, or the things people need to do with the object. They can retrieve or update the value's of the object's properties.
* Web browsers use HTML markup to create a model of the webpage. Each element creates its own node, which si a type of object.
* To make web pages interactive you write code that uses the browser's model of the web page.
### Writing Script
* Web pages are comprised of HTML, CSS, and JavaScript working together. It is best to keep these in their own separate files. JavaScript files are like HTML and CSS files, but have the `.js` extension.
* The HTML `<script>` element is used in HTML pages to tell the browser to load the JavaScript file.
* When looking at the source code, you will see that the JavaScript does not change the HTML because the script works with the model that the browser has created.
