# CSS Layout

* CSS treats HTML elements like they are each in their own box. This is either a **block-level** box or an **inline** box.
* Block-level boxes start on a new line and act as the main building blocks of any layout.
* Inline boxes flow between surrounding text.
* To control how much space each box takes up you can alter the width ( and sometimes the height) of the boxes.
* To separate boxes use borders, margins, padding, and background colors.
* If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. ex. a `<div>` element holding all of the elements of a header.

* Positioning Schemes:
  1. **Normal Flow**: `position:static` every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. This is the default behavior.
  1. **Relative Positioning**: `position:relative` moves the element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.It does not affect the position of surrounding elements as they stay in normal flow.
  1. **Absolute Positioning**: `position:absolute` This positions the element in relation to its containing element. It is taken out of normal flow, and does not affect the position of any surrounding elements (They act like it isn't there). Absolutely position elements move as users scroll up and down the page.
  1. **Fixed Positioning**: `position:fixed` A form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Do not affect the position of surrounding elements, and do not move when the user scrolls up and down the page. 
  1. **Floating Elements**: Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The float-level element becomes block-level around which other content can flow.
* When you move any element from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.
* The `clear` property allows you to say that no element (within the same containing element) should touch the left or right hands side of a box. It can take the following values:
  * `left`: The left-hand side of the box should not touch any other elements appearing in the same containing element.
  * `right`: The right-hand side of the box should not touch any other elements appearing in the same containing element.
  * `both`: Neither the left nor right-hand sides of the box should not touch any other elements appearing in the same containing element.
  * `none`: elements can touch either side.
* Most developers try and create pages around 960-1000 pixels wide since most users will be able to see designs this wide on their screens.
* **Fixed Width Layouts** do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
* **Liquid Layouts** stretch and contract as the user increases or decrease the size of their browser window. They tend to use percentages.