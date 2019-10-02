# Introduction & Scripts

You need to learn about the next to program using Javascript:

1- Understand the programming basics
2- Learn the language by learning its vocabulary and the syntax
3- Understand how to apply it at your website, examples will help you to learn more about this

## How to make your webpage interactive?

1- You need at first to access your HTML page, by selecting any element, attribute, or text from it.

2- Not just to add your spices! you can also use Javascript to modify the HTML content

3- Consider your HTML as the ingriendients of your cake and the Javascript is your cooker which will go through programming rules to apply.

## Examples to review

### SlideShows example:
In slideshows we can display images to be shown in a rectangled box and being slide into the right or to the left to show your wanted galleray.

### Forms example:
As the name states it is for collecting data, so Javascript is used to check if the information that is filled if its correct or not.

## 3 Important programming concepts to put in mind:

A-  To know what is exactly is the script and how to create it.
B- How do the computers being applied with the surrounded world.
C. How can we wrtie a script for a webpage.

# JavaScript Variables and Arrays

## Rules
 
there some rules we should consider while using the variables to avoid any errors.[1](http://www.informit.com/articles/article.aspx?p=131025&seqNum=3)

Also something called Arrays is imoportant to conisder.[2](https://www.w3schools.com/js/js_arrays.asp)

# Javascript Functions

You can think of the function as a way to do things that you want to do on and on. So instead why we do not make the computer do it for us! 

## Basic Faunction

Show me then I will learn! 
so let us start with this example to check what is exactly the function is.

### HTML

```
<!DOCTYPE html>
<html>
<head>
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="css/ c03.css" / >
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></ script>
</ body>
</ html>
```

### JAvascript code

```
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};
```

I would recommend to try them out here, come on give it a try ;)
[Go ahead copy them](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default)

