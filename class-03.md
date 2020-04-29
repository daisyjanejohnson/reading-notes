# HTML Lists, CSS Boxes, JS Control Flow

## HTML Chapter 3 Lists

* Three different types of lists:
  1. **Ordered Lists** are lists where each item in the list is numbered.
  1. **Unordered Lists** are lists that begin with bullet points.
  1. **Definition Lists** are made up of a set of terms along with the definitions for each of those terms.
* `<ol>` = ordered list
* `<li></li>` = list item
* `<ul>` = unordered list
* `<dl>` = definition list
  * `<dt>` = used to contain the term being defined
  * `<dd>` = used to contain the definition
* **Nested Lists** are lists within lists that are indented further.

## HTML Chapter 13 Boxes

* Box Dimensions are set using width and height.
* **min-width** is the smallest size a box can be displayed when the browser is narrow.
* **max-width** is the largest size a box can be displayed when the browser window is wide.
* The **overflow** property tells the browser what to do if the content contained within the box is larger than the box. It can have one of two values:
  1. **hidden** = this property simply hides away any content that does not fit in the box.
  1. **scroll** = this property adds a scrollbar to the box so that users can scroll to see the missing content.
* Every box has three available properties that can be adjusted to control its appearance:
 1. Border separates the edge of one box from another.
  * `border-width` is used to control the width of a border. The value of this property can be either given in pixels or using thin, medium, or thick. You can control the individual size of borders using one of the following values: `border: top-width`, `border-right-width`, `border-bottom-width`, `border-left-width`.
  * `border-style` can be solid, dotted, dashed, double, groove, ridge, inset, outset, or hidden/none.
  *`border-color` is the color of the border.
 1. Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
 1. Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of the content.
* **White Space** is the space between items on a page.
* the `text-align` property is inherited by child elements.

## JS Chapter 4 Decisions and Loops

* A switch statement starts with a variable called the switch value. Each case indicated a possible value for this variable and the code that should run if the variable matches that value.
  * At the end of each case is the **break** keyword. It tells the JS interpreter that is has finished with this switch statement.
- There is no need to provide an else option (just use if statement)
* The **Default Option** is run if none of the cases match.
* **Type Coercion** is when JS converts data types behind the scenes to complete an operation.
* Every value is JS can be treated as if it were true or false due to type coercion.
* **Unary Operator** returns a result with just one operand. Here you can see if the statement is checking for the presence of the element.
* Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again if it still returns true, the code block will run again. It repeats until the condition returns false. There are three common types of loops:
  1. For: Runs code a specific number of times. Condition is usually a counter that tells the number of times the loop runs.
  2. While: if you don't know how many times a code should run. The condition can be something other than a counter. It will loop until true.
  3. Do While: The do..while loop is similar to the while loop with one key difference. It will always run the statements inside the curly braces at least once, even if the condition evaluates to false.
