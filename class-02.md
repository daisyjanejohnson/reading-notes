# HTML Text, CSS Introduction and Basic JavaScript Instructions

## HTML Chapter 2 Text

* Headings
  * HTML has six "levels" of headings ranging from `<h1>` which is the largest and is used for main headings to `<h6>` which is the smallest
* Paragraphs
  * To create a paragraph surround the text with `<p></p>' tags.
* Bold and Italics
  * By enclosing words with `<b></b>` you can make words bold.
  * By enclosing words with `<i></i>` you can make words italic.
* Superscript and Subscript
  * The `<sup>`element is used to contain characters that should be superscript like suffixes of dates, or mathematical concepts like raising a number to a power.
  * The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas.
* Line Breaks and Horizontal Rules
  * `<br />` adds a line break inside the middle of a paragraph.
  * `<hr />` creates a break between themes, such as a change of topic in a book.
  * `<strong>` indicates that the content has strong importance. By default most browsers show the contents of this element as bold.
  * `<em>` element indicates emphasis that subtly changes a sentence. By default browsers will show the contents of this element in italics.
* Quotations
  * `<blockquote>` element is used for longer quotes that take up an entire paragraph. `<p>` is inside of this element.
  * `<q>` is used for shorter quotes that sit within a paragraph. Internet Explorer does not recognize this element so many people avoid it.
* If you use an abbreviation or an acronym, then the `<abbr>` element can be used.
* When you are referencing a piece of work such as a book, film or research paper the `<cite>` element can be used to indicate where the citation is from. Browser will render the content of this element in italics.
* The `<dfn>` element is used to indicate the defining instance of a new term.
* The `<address>` element is used to contain contact details for the author of the page.
* The `<ins>` element (usually underlined) can be used to show content that has been inserted into a document while `<del>` (usually has a line through it) can show text that has been deleted from it. The `<s>` element indicates something that is no longer relevant but should not be deleted.

## Introducing CSS

* The key to understanding how CSS is works is to imagine there is an invisible box around every HTML element.
* CSS works by associating rules with HTML elements. These rules govern how the content of specific elements should be displayed. A CSS rule contains two parts: 
  1. **Selector** indicates which element the rule applies to. The same rule can apply to multiple elements if you separate the element names with commas.
  1. **Declaration** indicates how the elements reffered to in the selector should be styled. Declarations are split into two parts (property and value) and are separated by a colon.
    * Properties indicate the aspects of the element you want to change like font, color, or width.
    * Values specify the settings you want to use for the chosen properties. For example if you want to specify a color porperty then the value is the color you want the text to be.
* CSS rules typically appear in another docment although they may appear within a HTML page.

## JS Chapter 2 Basic JavaScript Instructions

* A scriot is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a **statement**. Statements should end with a semi-colon `;`.
* JavaScript is case sensitive.
* Some statements are surrounded by curly braces `{}`, these are known as **code blocks**.
* You should write comments to make your code more readable. Multi-line comments start with `/*` and end with `*/`. Single-line comments are anything that follows `//`.
* A **variable** is where script can temporarily store bits of information it needs to do its job.
* JavaScript distinguishes between **numbers** (0-9), **strings** (text), and Boolean values (true or false).


