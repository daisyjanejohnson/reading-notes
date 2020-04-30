# HTML Links, CSS Layout, JS Functions

## HTML Chapter 4 Links
* Links are created using the `a` element. You specify what page you would like to go to using the `href` attribute.
```
<a href="http://www.takesyoutolink.com">WHEREUSERCLICKS</a>
```
* The link text is what users click on to reach a link. The link text should explain where the users will be taken.
* An **absolute** url is when the value of the href is the full web address to a different website.
* A **relative** url is used when you are linking to other pages within the same site.
* On larger websites, you should organize your code by placing pages for each different section of the site into a new folder. Folders on a website are refered to as **directories**.
* **URL** Uniform Resource Locator.
* To create an email link use `mailto:`:
```
<a href="mailto:daisy@example.org">Email Daisy</a>
```
* If you want a link to open in a new window use `target`:
```
<a href="http://www.imbd.com" target="_blank">
```
* You can use the id attribute to target elements within a page that can be linked to.

## HTML Chapter 15 Layout

* CSS treats each HTML element as if it is in its own box. This box will either be a **block-level** box or an **inline** box.
  * **Block-level** elements start on a new line. Ex. `<h1>`,`<p>`,`<ul>`,`<li>`.
  * **Inline** elements flow in between surrounding text. Ex. `<img>`, `<b>`, `<i>`.
* If one block-level element sits inside another block-level element then the outer box is known as the **containing** rt **parent** element. Ex. `<div>`
* CSS has the following **conditioning schemes** that allow you to control the layout of a page:
  1. *Normal Flow*: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. This is the default behavior (unless you tell the browser to do something else).
  1. *Relative Positioning*: This moves an element from the position it would be in normal shift, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be  in normal flow.
  1. *Absolute Positioning*: This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they ignore the space it would have taken up). These elements move as the user scrolls up and down the page.
  1. *Fixed Positioning*: This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element
* **box-offset** properties tell the browser how far from the top or bottom and left or right it should be placed.
* **Floating Elements** allows you to take that element out of normal flow and position it to the far left or right of the containing box.
* When you move any element from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.

## JS Chapter 3 Functions

* **Functions** let you group a series of statements together to perform a specific task. If different parts of the script repeat the same task, you can reuse the function.
* You should always name your function with a name that describes the task it is performing.
* **Calling** the function is when you ask the function to perform its task.
* **Parameters** are pieces of information passed to a function so it can achieve its given task.
* When you write a function and expect it to provide you with an answer, the response is called a **return value**.
* To create a function you must give it a name and then write the statement needed to achieve its task inside the curly braces. This is called a **function declaration**.
- You declare a function by using the `function` keyword.
- You give the function a name (sometimes called an **identifier**) followed by a parentheses.
- The statements that perform the task that sits in the curly braces.
```
function sayHello() {
  document.write('Hello');
}
```
* **arguments** are the values you specify that the function should use in the parenthesis that follows its name. It can be values or variables.

## 6 Reasons for Pair Programming

* The driver is the programmer who is typing and handling the mechanics of coding. The driver manages the text editor, switching files, version control, and writing code.
* Navigator uses their words to guide the driver. They think about the big picture, what comes next, how an algorithm might be converted into code while scanning for typos or bugs.
* Pair Programming results in higher quality code, enhanced technical skills, team communication, and even the enjoyability of coding in the workplace.
* It helps you remained focused on your code.
* You learn from each other and benefit from each other's knowledge.
* It improves social skills, thus having long-term career impacts because you can work well with others.
* It helps you prepare for the interview process as that often involves pair programming between a current employee and an applicant. 
* Many companies utilize pair programming, and being already familiar with the concept makes starting your career easier.