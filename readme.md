<script src="jquery.js"></script>

# jQuery Selectors and Events

## Learning Objectives
- Identify whether a desired functionality can be accomplished with CSS or with Javascript.
- Use jQuery to manipulate elements on a webpage.
- Use events to add interactivity to a webpage.

## Framing

The intent of this class is to understand what Javascript is capable of, and what it can do that CSS cannot.

## What is jQuery?

*jQuery is Javascript.*

It's a bunch of Javascript someone wrote for you so you don't have to.

It's as if someone wrote a whole bunch of CSS classes for you to save you time working on your webpage.

jQuery's slogan is "write less; do more".

### What's a library?

A bunch of code someone wrote for you that you can use in your code is considered a **library**.

Some notable other libraries are Bootstrap CSS, Underscore JS, and D3 JS.

Just as jQuery is pure Javascript, Bootstrap is pure CSS. If you look at the source code for Bootstrap, it is 100% CSS just like you've written yourself. There's no "magic".

### Minification

[This is jQuery.](jquery.js)

[This is also jQuery.](jquery.min.js)

They are the exact same code. One has been "minified".

- Why would you minify code?

## What can you do with jQuery?

### Documentation Dive

#### Questions

- What are 3 interesting-looking jQuery functions you found?
- What do you put inside `$(" ... ")`?

#### Look at:

- [Attributes](http://api.jquery.com/category/attributes/)
- [CSS](http://api.jquery.com/category/css/)
- [Dimensions](http://api.jquery.com/category/dimensions/)
- [Effects](http://api.jquery.com/category/effects/)
- [Events](http://api.jquery.com/category/events/)
- [Manipulation](http://api.jquery.com/category/manipulation/)
- [Offset](http://api.jquery.com/category/offset/)

### Selecting elements

We're going to use jQuery to manipulate elements.

jQuery selectors are just like CSS selectors. The only difference is you "wrap them in cash":

#### CSS

```css
ul > li.message:not(:first-child){
  color: red;
}
```

#### jQuery

```js
$("ul > li.message:not(:first-child)").css("color", "red")
```

### You Do: Getters and setters

Several functions, like `.css()`, `.html()`, and `.text()` do different things depending on whether you put 1, 2, 3, or more things inside them. What's the difference?

```js
$("something").css()
$("something").css("color")
$("something").css("color", "red")
```

```js
$("something").html()
$("something").html("<h1>Hello</h1>")
$("something").html("<h1>Hello</h1>", "<h1>World</h1>")
```

```js
$("something").text()
$("something").text("<h1>Hello</h1>")
$("something").text("<h1>Hello</h1>", "<h1>World</h1>")
```

## What's an event?



## Putting them together

```js

```

### Lights Out

### Tic Tac Toe

## References

