# Text
Text is any character or words put together.
There are many *tags* to use when placing text in HTML.

### `<h1>, <h2>, <h3> ...`
The *heading* tags displays the text wrapped in it in different sizes and hierarchy of importance, starting from the h1 tag where the text is at largest and most important, and ending with h6 tags where the text is smallest and of least importance.

### The `<p>` tag
The `<p>` tag allows us to write paragraphs in the HTML document. Each `<p>` tag created will appear on a new line.

### Line Breaks & Horizontal Rules
The `<br>` tag is used to force the html to start on a new line. The `<hr>` tag is used to create a horizontal line on the webpage.<hr>

### Strong and Emphasis
The `<strong>` tag allows us to create a bold style on the word or sentence that is wrapped with `<strong></strong>`. For example, <strong>This text is BOLD</strong>.

The `<em>` tag allows us to create an emphasis on a certain word or sentence, where it will be italicized.
For example, <em>this sentence is emphasized</em>.

# CSS
CSS refers to Cascading Style Sheet, which allows us to style the webpage. We can add borders, change the color of the text and much more. The CSS indicates that you must write the *selector* first, then opening and closing curly braces `{}`, inside the curly braces you will write the declaration. For example,
`p{
    color: red;
}`

This will change the text color of the paragraphs to red.

### 3 different ways to integrate CSS

1. External CSS - The `<link rel="stylesheet" href="path to CSS file"></link>` tag can be used to link the HTML document to an external CSS file, where each selector is combined with a declaration inside curly braces to style that element.

2. Inline CSS - in each of the opeining tags we write `style="color:red;"` to specify that this tag will use red as its text color.

3. Internal CSS - we place `<style>css selectors and declarations</style>` in the `<head>` tag at the begining of the HTML document.

# Javascript
**JavaScript** is a programming language used to add interactivity to your website and make it more dynamic. It can take inputs and display outputs and can be triggered with events such a mouse click or a scroll.

A *script* is a series of instructions that a computer can follow to achieve a certain goal. It can be compared to a recipe that is followed to make a certain dish.

### Comments
`//` is used to make a single-line comment.
`/* */` is used to make multiple-line comment.

A variable stores a piece of information for later use.

You can declare a variable by using:
1. let "variable name"
2. const "variable name"
3. var "variable name"

But it is not recommended to use the 'var' keyword.

### Variables
Variables can take numeric data type, such as 1 or 0.75, A string data type such as 'Hi, Osama', and a boolean type such as true or false.

The variable can begin with a dollar sign ($) or an underscore (_), but can't start with a number.

Variables are case-sensitive, where score is different than Score.

If a variable is made from multiple words, we use way called camel case, where eachWordBeigns with a capital letter except for the first word.