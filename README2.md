# The anatomy of a CSS selector
![CSS](https://images.unsplash.com/photo-1669023414162-5bb06bbff0ec?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

**CSS selectors are used to "find" (or select) the HTML elements you want to style.**

We can divide CSS selectors into five categories:

* _Simple selectors_ (select elements based on name, id, class).
* _Combinator selectors_ (select elements based on a specific relationship between them).
* _Pseudo-class selectors_ (select elements based on a certain state).
* _Pseudo-elements selectors_ (select and style a part of an element).
* _Attribute selectors_ (select elements based on an attribute or attribute value).

> This page will explain the most basic CSS selectors.

**The CSS class Selector**

The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.
*Example*
In this example all HTML elements with class="center" will be red and center-aligned: 

```javascrpit
.center {
  text-align: center;
  color: red;
}
```
**The CSS id Selector**
The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

*Example*
The CSS rule below will be applied to the HTML element with id="para1": 
```javascrpit
#para1 {
  text-align: center;
  color: red;
}
```

**The CSS Universal Selector**
The universal selector (*) selects all HTML elements on the page.
*Example*
The CSS rule below will affect every HTML element on the page: 

```javascript
* {
  text-align: center;
  color: blue;
}
```
**The CSS Grouping Selector**
The grouping selector selects all the HTML elements with the same style definitions.

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

```javascipt
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```
>It will be better to group the selectors, to minimize the code.
To group selectors, separate each selector with a comma.

*Example*
In this example we have grouped the selectors from the code above: 

```javascipt
h1, h2, p {
  text-align: center;
  color: red;
}
```

For more information about anatomy of CSS selector , check out the refrence. 

This is [refrence](https://www.w3schools.com/CSS/css_selectors.asp).
