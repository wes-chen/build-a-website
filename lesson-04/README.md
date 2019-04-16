<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>

# CSS Basics

## What is CSS?

CSS stands for Cascading Style Sheets. It describes how HTML elements are to be displayed, and after we create the skeleton for our website using HTML, we write CSS code to make it beautiful. 

Without good CSS code the website may look weird.

<img src="./css-sucks-webdevelopment-in-a-nutshell-43196018.png"/>

 So now let's go through examples and dive into CSS!

## CSS: Basics
### Style elements
Just like html code, like `<h1>title</h1>`, our CSS code is also contained inside a opening tag and a closing tag.

`<style> ...any CSS code you want to write </style>`

Typically, we put our `<style>...</style>` element inside of the `<head></head>` element. By convention, we put anything we want to display like text, paragraphs, and images in the `<body></body>` tag, and we put `<style></style>` in the `<head></head>` element. 

<img src="top.png"/>

But, what does the code inside the `<style>` tags actually mean? So let's talk about the basic syntax of the CSS.

### Syntax
CSS code comprises some basic parts: the selector, the property name, and the value. Let's look at a diagram of it.
<img src="syntax.png"/>
Each part has a different meaning:
<ul>
<li>`p`: This is the <strong>selector</strong> we talked about just now. It means that, we are selecting all the elements with tag `p`. In addition to selecting by the name of the tag, we can also select by id or class, which is covered later in this lesson.</li> 
</ul>
