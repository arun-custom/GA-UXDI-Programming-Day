# UXDi Programming Day

## Share Out

- What is programming and why should I care?
- Should I learn programming or should I hire someone else to do it?
- Come up with two ideas and discuss how technology could make them a reality.

## Overview of the Web

- We will talk about the request-response cycle and how this integrates with front and back end technologies.

## Introduction to HTML and CSS

##### HTML and CSS

- HTML and CSS work together to create the front end structure and design.
- Front end frameworks and the grid system.

##### Tags:

- Tags allow you to set up your document's structure.
- Attributes allow you to add additional information to a tag.
- Attributes also allow you to bridge the gap between HTML and CSS.

##### Div:

- Divs are like empty rectangles.
- They help organize content on the page.

```html
<div class="margin-top-20 logo">
	My Text Inside
</div>
```

##### Input:

- Inputs allow users to enter data to be saved to a database.
- They come in different forms to facilitate the specific data entry type.

```html
<input type="text" class="form-control" />
```

##### Select list:

- Select lists allow users to select options from a dropdown menu.

```html
<select>
	<option value="USA">United States</option>
</select>
```

##### Button:

- Buttons are HTML elements that give users the ability to submit the data entered as well as transition to new pages.

```html
<button>My Button</button>
```

## CSS Stylesheets

- CSS stylesheets provide the look and feel of the website.
- There are two main ways of referencing CSS in the HTML so you can apply styles - classes and IDs.
- Consider this HTML:

```html
<div class="header">
	My Header
</div>
```

- Here we have a class attribute that can serve as the bridge between the HTML and CSS code.
- Here is how we would reference this class in the stylesheet:

```css
.header {
	font-size:20px;
	background-color:blue;
}
```

- We could also use IDs to reference the style:

HTML

```html
<div id="header">
	My Header
</div>
```

CSS

```css
#header {
	font-size:20px;
	background-color:blue;
}
```

> **The main difference between classes and IDs is that classes can be used multiple times in the HTML document whereas IDs should only be used once.**

##### Linking CSS with HTML

- In order to run external CSS you need to link it to the HTML. This usually goes in the `head` tag:

```html
<link rel="stylesheet" href="css/style.css" />
```

##### Linking JS with HTML

- JavaScript enables interaction with the page.
- In order to run external JS you need to link it to the HTML. This usually goes before the closing `body` tag:

```html
<script src="js/app.js"></script>
```

## HTML Markup Lab

- [Please refer to the project here](https://github.com/arun-projects/html_form)

## A Little More on CSS

- CSS is a powerful language and has an easy-to-learn syntax.
- CSS can be used to achieve everything from pixel-perfect colors to advanced animations.
- If you want to see a couple examples, check these out:
	- [http://codepen.io/juliangarnier/pen/idhuG](http://codepen.io/juliangarnier/pen/idhuG)
	- [http://www.rleonardi.com/interactive-resume/](http://www.rleonardi.com/interactive-resume/)

## CSS Colors

- There are three main ways to use colors in CSS - semantic, HEX values, and RGB(A) values.

##### Semantic:

```css
div {
	background-color:black;
}
```

##### HEX:

```css
div {
	background-color:#000000;
}
```

##### RGBA:

```css
div {
	background-color:rgba(0,0,0,0.5);
}
```

## CSS Gradients

- CSS gradients were introduced as of CSS3.
- They allow for a gradient of colors to be applied across multiple solid colors.
- These are hard to write via raw CSS, so generators are often used.
- Let's have a look at one [here](http://www.colorzilla.com/gradient-editor/).

## CSS Color Lab

- Create three divs via Codepen with a width, height, and border.
- Style them all differently via classes or ids (your choice) by giving them varying colors using a different method each time.
- Make sure one uses a gradient.

## About Me Lab

- [Please refer to the project here](https://github.com/arun-projects/about_me)