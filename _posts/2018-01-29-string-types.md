---
title: Python tips and tricks - literal vs raw strings
---
When I began writing some basic code, I wanted to reference a particular directory. What I wrote looked a little something like this:

![pic1](/blog/img/pic1.png "string with escape characters")
Pic1

The problem with this is that Python recognises “\” as an escape character. So to solve my issue I had to manually go through and change “\” to “/”. This did solve the issue but was annoying especially as I was copy and pasting directories locations, often with many back slashes.

![pic2](/blog/img/pic2.png "edited literal string")
Pic2

One way to solve my issue would be to change every “\” to “\\”. This tells Python to ignore the single backslash as an escape character. However, again this would mean that I would have to go through and change “\” to “\\”.

I was blindly continuing with the first solution for a month or so until I stumbled across some info on strings. The important thing to know here is that assigning a string value by using single or double quotes creates a string literal. When dealing with literal strings, Python will act on any escape characters that it finds. To tell Python to ignore any escape characters, you can create a raw string. Here’s how the syntax looks. Simply start the string with either a lower or upper case “r”.

![pic3](/blog/img/pic3.png "literal and raw strings")

Using raw strings is very handy when referencing file paths like I was doing. Something to bear in mind however is you cannot end a raw string with “\”. If you do this, Python will think you are trying to escape the “ character wrapping the string. To end a string with “\”, you must use a literal (regular) string. 

There you have it. A really tiny little thing that can save a bit of time when writing your code!

