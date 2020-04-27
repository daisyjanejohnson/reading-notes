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

## Chapter 8 Extra Markup
* Because there are several versions of HTML, each web page should begin with a DOCTYPE declaration on top to tell what type it is.
* If you want to add a comment in the code that isn't visible in the user's browser use: `<!--comment goes here-->`
* The **id attribute** is used to uniquely identify an elemnt from other elements on the page. Its value should start with a letter or an underscore. The **id attribute** is known as a global attribute because it can be used on any element.
* The **class attribute** gives a way to identify several elements as being different from the other elements on the page. Its value should describe the class it belongs to.
* **Block Elements** are elements that will always appear to start on a new line in the browser window. Examples of block elements are: `<h1>`(level 1 header), `<p>`(paragraph),`<ul>`(unordered list), and `<li>`(list item).
* **Inline Elements** are elements that always appear to continue on the same line as their neighboring elements. Examples of inline elements are: `<a>`(hyperlink), `<b>`(bold text), `<em>`(emphasis or italics), `<img>`(image).
* The `<div>` element allows you to group a set of elements together in one block-level box. You might create a `<div>` tag to contain all the elements for the header of your site like th logo and navigation bar. 
##