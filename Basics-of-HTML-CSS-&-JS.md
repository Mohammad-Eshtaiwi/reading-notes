# Text

Mainly we use \<p> tag to add text but some times we need to add more semantic tags like \<address>, \<blockquote>.

we can have only one \<h1> in our HTML so be SEO friendly.
<br> <br>
if we added more than 1 white space it will be considered one cuz the HTML engine will consider it added to improve the readablity.
<br><br>
\<br> and \<hr> are used to break into a new line but the hr tag adds like a robe between sections.
<br>

# CSS

we use css to add style to our document and in written as :

- inline-style (\<p style:"some css code">)
- in style tag (\<script>some css code\</script>)
- in seperated file and applyed to our document using \<link rel="stylesheet" href="styles.css">
  <br><br>
  best was to use the link approch because by this way we make it eazier to read our code when it get bigger and we can re-use it within other document
  <br><br>
  p
  <br>{
  <br>
  color : red;
  <br>
  }
  <br><br>

* p is the selector
* code written within {}
* color is the property
* red is the value
* every line of CSS we should add ;

some selectors:

- \* called the universal selector
- p -or any tag name- called tag selector
- .class we add . to indicate that we select class and #id to indicate to an id

# Js

![Statment Example](./images/statment.png)

- The green is part is a statement. and the pink indicates that block of code.
  <br><br>
- JS is case sensitive so Document is not a document.
- comments used to make a note about different parts of your code and used to debug your code

* you need to be very informative when writing code so you need to write very clear instructions to your computer.

**var name= "some string"**

- the above statement is used to define a variable and storing string in it.

## some examples of data types

- boolen: can be true or false
- string: "some string"
- number : 123, 1.23
- object: {name: "some name" , age: 20}
- array: [1,"hello world", true]

 <br>

- for more details go to :

[Programming-with-JavaScript](https://mohammad-eshtaiwi.github.io/reading-notes/Programming-with-JavaScript)

switch(expression) {
<br>
case n:
<br>
code block
<br>
break;
<br>
case n:
<br>
code block
<br>
break;
<br>
default:
<br>
default code block
<br>
}

- expression: define the value to test its value

* case n: used to check your expression and if it passes then the code under it will apply and you have to add break or it will do every code under it.
* default: if every case didn't pass then the default code will execute
