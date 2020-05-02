# HTML Images, CSS Color, and Text

## HTML Chapter 5: Images

 * Images set the tone for a site.
 * **Stock Images** are images you can pay to use.
 * `<img>`: The image element is used to add images to your website. It must carry the `<src>` (tells the browser where it can find the file) and `<alt>` (provides a text description of the image which describes the image if you cannot see it) attributes. You can also use the `<title>` attribute to provide additional information about the image.
 * You will often see the `<img>` element use two attributes to specify its size; `<height>` and `<width>`. 
 * Websites mainly used images in the .jpeg, .gif, or .png format. If you choose the wrong format the image may have trouble loading and not be the best quality.
 * Photographs are best saved as jpegs; illustrations or logos that use flat colors are better saved as gifs.
 * You should save images at the same width and height it will appear on the website. 
 * **Adobe Photoshop** is a good tool to use to edit images.

 ## CSS Chapter 11: Color

 * the `color` property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
  1. **RGB** values express colors in terms of how much red, green, and blue are used to make it up. Ex.) `rgb(100,100,90).
  2. **HEX CODES** are six-digit codes that represent the amount of red, green, and blue in a color preceded by a pound or a hash `#` sign. Ex.) `#ee3e80`
  3. **COLOR NAMES**: There are 147 predefined color names that are recognized by browsers. Ex.) DarkCyan.

* `background-color` sets the color of the background for the part of the page you are styling.
* Hue is near to the colloquial idea of color.
* Saturation refers to the amount of gray in a color. At max saturation, there would be no gray and at min saturation, it would be all gray.
* Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color and at min, the color would be all black.
* It is important to ensure there is enough contrast between any text and the background color, otherwise, it will be unreadable.
* Opacity is the condition of lacking transparency or translucence.
* CSS3 introduced an extra value for RGB colors to indicate opacity, this is RGBA.
* HSL stands for hue, saturation and lightness.
* CSS3 allows you to specify colors as HSL values, with an optional opacity value, this is HSLA. 

## CSS Chapter 12: Text

* Typeface Terminology
  - Serif: the extra details on the ends of the main strokes of the letters.
  - Sans-serif: straight ends to letters.
  - Monospace: Every letter in a monospace font is the same width.
  - Weight: light, medium, bold, black.
  - Style: Normal, italic, oblique.
  - Stretch: Condensed, regular, extended.
* **font-weight** allows you to create bold text.
* **font-style** allows you to create italic text.
* **text-transform** is used to change the case of text. (`uppercase`, `lowercase`, `capitalize`)
* **text-decoration** includes: `underline`, `overline`, `line-through`, and `blink`.
* **kerning** is the term typographers use for the space between each letter. This can be controlled using `letter-spacing`.
* **text-align** allows you to control the alignment of text.
* **text-indent` allows you to indent the first line of text within an element. 
* **text-shadow** is used to create a drop shadow, which is a dark version of the word behind it and slightly offset.
* `:link` allows you to set styles for links that have not yet been visited. `:visited` is for the links that have been clicked on.
* `:hover` is applied when a user hovers over an element with a mouse.
* `:active` is applied when an element is being activated by a user, like when a button is being pressed or link being clicked.
* `:focus` is applied when an element has focus. Any element that you can interact with such as a link you can click can have focus.
* There is a limited choice of fonts that you can assume most people have installed.
* if you want to use a wider range of typefaces there are options, but you need to have a license to use them.
