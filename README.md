
# Introduction to Web Development
 IT Workshop at Biblioteka Wielokulturowa/Multicultural Library

[Facebook event's page](https://facebook.com/events/1603644207183061/)

## The Dawn of HTML

Our journey starts with HTML , at CERN in 1989. By 1990-91, the world's first website went live, and exist at [https://info.cern.ch/hypertext/WWW/TheProject.html](https://info.cern.ch/hypertext/WWW/TheProject.html).  In 1994, the W3C was founded to develop and maintain web standards. Later, in 2004, the WHATWG was formed by major players like Apple, Google, Microsoft, Mozilla to maintain HTML as a "Living Standard" (sometimes informally called HTML5). Since 2019, the W3C announced that WHATWG would be the sole publisher of the HTML. This collaboration ensures that HTML remains robust.

Ref: https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/The_web_standards_model
https://en.wikipedia.org/wiki/WHATWG

Two example of HTML & CSS (no JavaScript!) websites:

-   **[Richard Stallman](https://stallman.org/)** 
-   **[Prof. Donald E. Knuth](https://www-cs-faculty.stanford.edu/~knuth/)**

## HTML TAGS
The base block of building HTML is a tag which has a starting and ending and what is in between them are the content and as a whole we call it an element.
```html
<h1>Two apples are falling from the sky 🍎🍏</h1>
```

## Attribute
Attributes are proving more information about the element and they won't be visible to the end user.

```html
<html  lang="en"></html>
<p class="warning-text">My lovely cats are flying to New York next week 😸✈️</p>
<a href="https://duck.com" target="_blank">Visit Duck Duck Go Search Engine 🦆</a>
<button type="button">Click Me!</button>
```

## Nesting Elements
In HTML, elements can be nested and in all HTML documents you can find nested HTML elements.
```html
<p class="warning-text">
	My <strong>lovely</strong> cats are flying to New York next week 😸✈️
</p>
```
## Void Elements
A void element cannot have any child nodes:
```html
<meta  charset="UTF-8">
<img src="images/my-squirrel.png" alt="My squirrel at home">
<br>
<hr>
```

## Let's Start Coding HTML
Now I'm going to tell you a story about a student whose got his classmate's notebook by mistake and must return it to him until next morning. I'm going to use many different HTML tags to tell this story. You can find the final code here in this repository at `index.html`. OK, let's start it.