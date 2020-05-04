# JS Object Literals, The DOM

## JS Chapter 3: Object Literals

* Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object variables and functions take on new names.
* In an object, variables become **properties**. Properties tell us about an object.
* In an object, functions are known as **methods**. Methods represent the task associated with the object.
* A **key** is the name and value of the properties and methods.

## JS Chapter5: Document Object Model

* The **Document Object Model**  specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

* When a browser loads a web page it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using a **DOM Tree**. The DOM is called an object model because the DOM tree (the model) is made up of objects.

* Dom Trees have four different types of nodes: Document Node, Element Node, Attribute Node, and Text Node.

* Accessing and updating the DOM tree involves two steps:
  1. Locate the node that represents the element you want to work with.
  1. Use its text content, child elements, and attributes.

* Methods that find elements in the DOM tree are called DOM queries. When you need to work with an element more than once, you should use a variable to store the result of this query.

* DOM queries may return one element, or they may return a NodeList which is a collection of nodes.

* Methods that return a single element node:
  1. `getElementById('id')`
  1. `querySelector('css selector')`

* Methods that return one or more elements (AS A NODELIST):
  1. `getElementsByClassName('class')`
  1. `getElementsByTagName('tagName')`
  1. `querySelectorAll('css selector')`

* From an element node, you can access and update its content using properties such as `textContent` and `innerHTML` or using DOM manipulation techniques.

* An element node can contain multiple text nodes and child elements that are siblings of each other.

* Browsers offer tools for viewing the DOM tree.