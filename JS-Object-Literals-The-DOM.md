# objects

Objects are a group of variables(properties) and functions(method) that describe a real-world entity.

## example of objects

let human = {
age : 20, name : "someone" , talk: ()=> console.log("I can talk wooow")
}

(human.name) this is how to call a property from an object

this is how to create a constructor for an object

function love(howMuch){

// some properties

this.howMuch:howMush

//some methods

this.moreLove = function () {

return this.howMuch++

}
}

# DOM

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

- when your page loaded your browser create a DOM tree
- every element have attributee or text node or both of them

querySelector( 1css selector ')
Uses CSS selector syntax that would select one or more elements.
This method returns only the first of the matching elements.

querySelectorAll ( "CSS selector")
Uses CSS selector syntax to select one or more elements and return all of those that match.

- when use querySelectorAll it return nodeList which is a collection.
- when dealing with nodeList it is better to use the loop over item() method cause loops are faster.
- Traversing methods are read-only you cant change and content through it.
- to change the content of the element we use textContent, innterHtml.

# Understanding The Problem Domain Is The Hardest Part Of Programming

- Writing the code is the easiest thing in the software creation process what is hard it understanding the problem or the requirements of the project that you are working on.
- you can your problem easier by cutting it into small pieces.
- Also, you can sit with your customer and discuss your project to make a better understanding of it
