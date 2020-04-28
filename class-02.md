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

* A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a **statement**. Statements should end with a semi-colon `;`.
* JavaScript is case sensitive.
* Some statements are surrounded by curly braces `{}`, these are known as **code blocks**.
* You should write comments to make your code more readable. Multi-line comments start with `/*` and end with `*/`. Single-line comments are anything that follows `//`.
* A **variable** is where script can temporarily store bits of information it needs to do its job.
* JavaScript distinguishes between **numbers** (0-9), **strings** (text), and Boolean values (true or false).
* Before you can use a variable you need to announce that you want to use it. You must **declare** the variable by creating it and giving it a name.
* Once you have created a variable, you can tell it what information you would like it to store for you. This is called **assigning a value**.
* `=` is an **assignment operator**, it says that you are going to assign a value to a variable.
* If a variable name is written in more than one word it is typically written in **camelCase**. This means the first word is all in lowercase and any subsequent words have their first letter capitalized.
* Example of a declaration and assigning a value:
```
var quantity; 
quantity = 3;
```
* Six rules to follow when giving a variable a name:
  1. The name must begin with a letter, dollar sign ($), or and underscore (_), NOT A NUMBER.
  1. The name can contain letters, numbers, dollar sign or an underscore. You must not use a dash (-) or a period (.) in a variable name.
  1. You cannot use keywords or reserved words.
  1. All variables are case sensitive, so score and Score would be two different names. It is bad practices to create two variables that have the same name using different cases.
  1. Use a name that describes the information the variable stores.
  1. If your variable name is made up of more than one word, use a capital letter for the first letter of every word AFTER the first word. Ex.) firstName

* An **array** is a special type of variable used when you are working with a list or set of values that are related to each other. Each item in an array is automatically given a number called a **index**, this can be used to access specific items in an array.
* Expressions evaluate into a single value. Expressions rely on operators to calculate a value.

## JS Chapter 4 Decisions and Loops

* Evaluation of a condition: In order to make a decision, your code checks the current status of the script. This is commonly done by comparing two values using a comparison operator which returns a value of true or false.
* Conditional Statements are based on a concept of if/then/else; *if* a condition is met, *then* your code executes one or more statements, *else* your code does something else (or just skips this step)
* Comparison Operators:
  * `==`: Is equal to
  * `!=`: Is not equal to
  * `===`: Strict equal to
  * `!==`: Strict not equal to
  * `>`: Greater than
  * `<`: Less than
  * `>=`: Greater than or equal to
  * `<=`: Less than or equal to
* In any condition, there is usually one operator and two operands. The **operands** are placed on each side of the operator, they can be values or variables.
  * The operand does not have to be a single value or variable name. An operand can be an expression (because each expression evaluates into a single value)
* Logical Operators (allow you to compare the results of more than one comparison operator)
  * `&&`: Logical And (Tests more than one condition)
  * `||`: Logical Or (Tests at least one condition)
  * `!`: Logical Not (Takes a single Boolean value and inverts it).
  * Logical operators are evaluated left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition.
* **if** statements evaluate (or checks) a condition. If the condition evaluates to true, any statements in the subsequent code blocks are executed. If the condition evaluates to false, the statements in that code block are not run.
* **if...else** statements check a condition. If it resolves to be true the first code block is executed. IF the condition resolve to false the second code block is run instead.

## The Seven Rules of a Great Git Commit Message
1. Separate subject from body with a blank line
1. Limit the subject line to 50 characters
1. Capitalize the subject line
1. Do not end the subject line with a period
1. Use the imperative mood in the subject line
1. Wrap the body at 72 characters
1. Use the body to explain what and why vs. how

