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
