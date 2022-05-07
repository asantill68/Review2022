# Review2022

On-Line Tutorial exercises
These are the online tutorials I will be following:
https://learn.shayhowe.com/
Lesson01:
HTML, Tags, CSS, CSS Reset, Selectors (element, class, id)

Lesson02:  
semantics - element gives content on the page meaning and structure;
div and span 's do not hold any semantic value; they are containgers for CSS
div is a block while span is more for inline content
block Elements start a new line
inLine Elements do not
text-based Elements: H1 to H6, p, strong, bold b, emphasis em and italics i elements
structure based elements (block): header, nav, article, section, aside and footer
header outlines the heading of a segment or page and is not to be used as an h element
nav is for navigation links on a page to other pages or sections of the website
article is to identify a section of independent, self-contained content
section identify a thematic grouping of content
aside holds content, such as sidebars, inserts or brief explanations, that is related to adjacent content
footer closing/end of page
links are added using the anchor a element using the href attribute
relative links are within the same page
absolute links are external
linking to an email see lesson02/index.html
open link in new window use the target attribute value = \_blank

lesson03
CSS (cascading style sheets):
list of selectors:values is the cascade
selecor values are rendered from top to bottom
i.e. whatever color bkg is selected last for the same selector will overwrite other values
selector specificity: ID > Class > Type; use (1, 0, 0) to calculate preference
selectors can be combined i.e. .class p to combine the class and p element
selectors can also be .class p.class2 using two classes and a p element
multi-classes are also an option
common CS property values
format: selector {keyword: values}
color: name black; hex values #000000; RGB rgb(0, 0, 0); HSL hsl(0, 0%, 0%)
lenghth (width): absolute values (px, 1/96"); relative values (percentages, %; em, based on fontsize)

lesson04
box model
elements are displayed as block, inline or inline-block
element values can be altered via css
inline elements will not accetp width and height properties
block and inline-block will accept width and height properties
oddity with margin property is that the top and bottom is not accepted with inline elements
vertical margins are accepted with block elements
padding is within the element's borders
margin values margin: 20px (all); margin: 20px 10px (top/bottom and left/right); margin: 10px 20px 0px 5px (top, right, bottom, left)
boder: width style color i.e. border: 6px solid red
border radius
box-sizing content-box padding-box border-box

lesson05
Positioning Content
floats, left right
clear both

lesson06
Typography
Typface is music; Font is the mpg/cd
color: #555;
font-family: "Helvetica Neue", Helvetica, Ariel, sans-serif; (two-word font should be in " ")
font-size: 14px;
font-style: italic; also normal, oblique and inherit
font-vaiant: small-caps;
font-weight: bold; bolder, lighter, (also 100 - 900 with 400 being normal)
line-height: 22px; usually set to 1.5 the font-size or 150%;
line-height: 22px; and height: 22px; vertically centers text within an element
shorthand lists; font: font-style, font-vaiant, font-weight, font-size, line-height, font-family
example; font: italic small-caps bold 14px/22px "Helvetica Neue", Helvetica, Ariel, sans-serif;
pseudo-class of hover is used in the a element a:hover
Text Properties
text-align: center; left, right, justify
text-decoration: underline; oveline, line-through
text-indent: 20kpx; +/- values accepted
text-shadow: 3px 6px 2px rgba(0, 0, 0, .3)
box-shadow works similar but for elements
text-transform: none; capitalize, uppercase, lowercase
Letter Spacing: -0.5em; +/- values accepted; use relative values em, %
word-spacing: 0.25em; see above
Add fonts using googlefonts.com
cite elemnet used for creative works
q element is used for quotes
blockquote element for large quotes

lesson07
Backgrounds & Gradients
background-color: #b2b2b2;
use back up by setting two background-color: #b2b2b3; background-color: rbga(0, 0, 0, .3);
browser reads second value last and applies it
background-image: url("alert.png");
background-repeat: no-repeat; repeat, repeat-x, repeat-y
background-position: 20px 10 px; horizontal and vertical offset
shorthand: background: #b2b2b2 url("alert.png") 20px 10px no-repeat or
backgound-color, -image, -position, -repeat
gradiant background in linear and radial forms
a backup color is set followed by a linear-gradiant composed of two colors
background: red; background: linear-gradiant(red, green)
use direction: to botom right; or 90deg;
background: red; background: radial-gradian(red, yellow)
