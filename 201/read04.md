# Read04

## Links
A link is a hyper-text that moves you from one page to another, or from one section of a page to another.

There is also, an email link; which will open a new mail window with the email address automatically appearing in the "Send to" space.

A link can be initiated in the HTML from the `<a>` tag. The href attribute specifies the destination URL that the user will be taken to when pressing on the link.

## Layout
A layout refers to where every elemnt sits on the page and how the page looks overall.

In **Normal flow**
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside, they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).

In **Relative Positioning**
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.

In **Absolute positioning**
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.

In **Fixed Positioning**
This is a form of absolute
positioning that positions
the element in relation to the
browser window, as opposed
to the containing element.
Elements with fixed positioning
do not affect the position of
surrounding elements and they
do not move when the user
scrolls up or down the page.

In **Floating Elements**
Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box. The floated
element becomes a block-level
element around which other
content can flow.

> This was quoted from Duckett HTML Pages 363 & 364

## Functions
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements).
> This is quoted from Javascript Book, page 88

We can declare a function by typing `function functionName(){code goes here}`

We can then call a function by typing `functionName();`