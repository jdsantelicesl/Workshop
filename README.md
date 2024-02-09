# Front End Workshop 1

This repository contains html, css, and javascript examples. Please see each section for further guidance

Please watch the following on the CS50s lecture before continuing:
- HTML 0:51-1:27
- CSS 1:45-2:00
- JavaScript 2:03-2:28
<br><br>
[Video Link](https://www.youtube.com/live/alnzFK-4xMY?si=_lQ8kbOYxCpurVsh&t=3102)
<br> <br>
These intervals go over the necessary content for our purposes. In order to truly grasp front end development I encourage you to watch the entire video.

## HTML

Html is a markup language, not a programming language. The idea behind html is to "wrap" text in tags in order to display it in a certain way. You can also include images, videos, and links with special tags.

For our purposes we will use the following tags:

- `<body> Content goes here </body>`: All of the content of an html page must reside within this tag.
- `<p> Content goes here </p>`: Used for a paragraph of text (aka normal text). You can alternatively write normal text in any other tag that does not have formatting.
- `<div> Content goes here </div>`: A div is a container, nothing else. It is probably the most popular html tag as it can be used for anything (versatile).
- `<h1> Content goes here </h1>`: Used for headings. You can also use h2, h3, and so on for progressively smaller headings. 
- `<img src="image source goes here" >`: Used to insert images. The source can either be online or local. 
- `<a href="link goes here"> Text goes here </a>`: Used to insert a link in a line of text. 

## CSS

CSS is a language that allows us to add styles to html tags. This includes color, shape, font, size, alignment, etc. CSS works by listing a tag and setting specific properties within a set of curly brackets (see example). Html components can be given a class or an id. Id is special for that tag, while classes can be shared by many tags. When listing properties for an id in css, you must start the name of the id with a `#`. When using classes, you must start the class name with a period `.`.

To set a property, list property name, : , property, and ;. Ex: `text-align: center;`.

Some popular CSS properties:
- `text-align`: aligns text to left, center, or right of container. 
- `background-color`: sets background color.
- `color`: sets color of text.
- `font-size`: sets font size.
- `font-family`: chooses a font to use for that tag.

## JavaScript

Unlike the previous two, JavaScript is actually a programming language. This means that it handles logic. Getting started with JavaScript will be more difficult than HTML or CSS. In this document we will compare JavaScript to C++ in order to help you understand it better. 

JavaScript uses semicolons (;) after every line just like C++, however, the program may run without them (runs better with semicolons). Declaring variables in JS does not require the programmer to specify type. Constant variables are declared with const, nonconstants are declared with let. Ex: `const TAXRATE = .01;` and `let state = "loading"`. 

## Summary 

This repository contains examples to reinforce concepts learned in CS50s video lectures. Please refer to the video for more information.

When getting started with a new language, I recommend using a cheatsheet in order to have all commands available and avoid syntax errors. I also like to use Chat GPT for assistance with error handling and explaining program logic. 