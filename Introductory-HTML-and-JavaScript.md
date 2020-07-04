# How The web Works

When you enter a domain name in your browser you will send a request to the DNS which will lookup for your domain name and send back an IP address that will let your browser connect to the webserver that hosts the requested domain and finally send you the website.

# HTML & Tags & Elements

- HTML only defines the structure or the skeleton and your content which can be text, image, audio, and video
- every tag that will have content will have a tag and closing tag for example \<p> \</p> on the other hand if it has no content within it doesn't have the closing tag and some tags have attributes to give the element more information.

# main tags

\<html>
<br>
\<head>
<br>
\<title>This is the Title of the Page\</title>
<br>
\</head>
<br>
\<body>
<br>
\<h1>This is the Body of the Page\</h1>
<br>
\<p>Anything within the body of a web page is
displayed in the main browser window.\</p>
<br>
\</body>
<br>
\</html>

- \<body>: all tags that display content shall be inside it
- \<head>: here you define your site information and embed files.
- \<title> this will add a title at the tab.
- \<!-- --> comments: use it to give an idea about what the current section or part of code is about and can be used for document and make your code more informative for the others
- \<div>: used to group related content and give it special features

* ID Attribute and Classes: they used to give your elements an identity but the id shall be unique and every element shall have only one id.

# Block & Inline

the block elements like h1 div p will always start a new line and will be affected by padding, width, margin. But the inline elements are the opposite and example of them are span, b, and i tags

# JS

By script, we mean a small piece of code that performs a task. So the computer can't do a task without following it step by step.
<br><br>
try to design a procure using steps or flowchart to help you write your code.
<br><br>
Objects are represented real-world things and each object have:

- Properties: to describe the characteristics of your object.
- Events: So the object gets triggered at some events like a click.
- methods: used to interact with the object and describe what it can do.

# How Browser Sees A Web Page

- receive the source files.
- create a model for each HTML file and sub-models called nodes.
- use the rendering engine to show the page and if there are not CSS file will apply default styles. **_Every browser has its default styles_**

# The Mix Of HTML CSS JS

Every part have a pourpse and must separate each one from the other. And the JS code it is better to make several files.
<br>
to add JS we use \<script>\</script> and write the code between them or \<script src="/path">\</script> and add the path to the JS code.
![object example](./images/object-example.png)

## **_useful links:_**

- [Structure-web-pages-with-HTML](https://mohammad-eshtaiwi.github.io/reading-notes/Structure-web-pages-with-HTML)
- [Programming-with-JavaScript](https://mohammad-eshtaiwi.github.io/reading-notes/Programming-with-JavaScript)

* [Operators-and-Loops](https://mohammad-eshtaiwi.github.io/reading-notes/Operators-and-Loops)
