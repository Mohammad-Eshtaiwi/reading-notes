# Lists

- \<ol> : used to create ordered list.
- \<ul> : used to create unordered list
- \<li> : used it within \<ol> or \<ul> to add items to the list

**_we can add a nested list by adding new \<ul> tag to our \<li>_**

- \<dl> : used to create a list of a definitions
- \<dt>: used to add a new term to our \<dl>
- \<dd> : used to add a definitions to our \<dl>

# Boxes

Every box have width and height and effected by the padding and the border properties unless you add a box-sizing to your box then they will not affet on the box size.

padding and margin are short had properties which can defined as top right bottom left so it is like a the clock.

the border property is short hand for border of the coler the type of it and the size of it. We can define a border riduis to give our box some edged corner or make our box like a circle

visibility can hide our element if we set it to hidden but out elemnt will still take a space in our site flow

# Control Flow

if (condition){

    some code

} else if (condition){

    some code

}else{

    some code

}

So if the first condition passed the else if will not work, then if else will work if the fisrt condition didn't pass and so on.

Those considered ad falsey:

- var highScore = false;
- var highScore = 0;
- var highScore = "";
- var highScore = 1O/"string;
- var highScore;

Those considered ad truth:

- var highScore = true;
- var highScore = 1;
- var highScore = "hi";
- var highScore = "false";
- var highScore = "0";

Short circuit: Logical operators are processed left to right.They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or false).

# loops

for the basics of loops please check this link [loops basics](https://mohammad-eshtaiwi.github.io/reading-notes/Operators-and-Loops)

- break keyword used to force your loop from excuting
- continue keyword used to force your loop to restart
