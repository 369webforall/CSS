# CSS Introduction

CSS is the language we use to style a Web page.

# YouTube Link

[YouTube Video](https://www.youtube.com/playlist?list=PLus8o0f0SRoNb_aPrph6ekaKb4kpDSlD7)

# What is CSS?

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

# CSS Syntax

![css syntax](./images/css-selector-example-1.gif)

# CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

## The CSS id Selector
 
 - The id selector uses the id attribute of an HTML element to select a specific element.

 - The id of an element is unique within a page, so the id selector is used to select one unique element!

 - To select an element with a specific id, write a hash (#) character, followed by the id of the element.

 ```
#para1 {
  text-align: center;
  color: red;
}

 ```

## The CSS class Selector

- The class selector selects HTML elements with a specific class attribute.

- To select elements with a specific class, write a period (.) character, followed by the class name.

```
.center {
  text-align: center;
  color: red;
}


```

# The CSS Universal Selector
- The universal selector (*) selects all HTML elements on the page.

```
* {
  text-align: center;
  color: blue;
}

```

# The CSS Grouping Selector

- The grouping selector selects all the HTML elements with the same style definitions.

- Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

```
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

```

h1, h2, p {
  text-align: center;
  color: red;
}
 
```

# CSS Rule Example

![CSS Rule](./images/css-rule.jpg)



# CSS Colors

- Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

## CSS Background Color / CSS Text Color / CSS Border Color

```
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>


<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>


```

## CSS Color Values

- In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values:

```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>


```

# CSS Backgrounds

- In these chapters, you will learn about the following CSS background properties:

- background-color
- background-image
- background-repeat
- background-attachment
- background-position
- background (shorthand property)

### background-color

- Sets the background color of an element

`Example:`

`Here, the <h1>, <p>, and <div> elements will have different background colors:` 

```
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}
```

### background-image

- The background-image property specifies an image to use as the background of an element.

- By default, the image is repeated so it covers the entire element.

body {
  background-image: url("paper.gif");
}

### background-repeat

### background-attachment

### background-position

### background (shorthand property)

[Background](https://www.w3schools.com/css/css_background_repeat.asp)


# CSS Box Model

![Box model](./images/box-model.png)

![Box Model](./images/box-model2.jpg)

![Compare Box Model](./images/compare_models.png)

## Width and Height of an Element

```
Important: When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

The total width of an element should be calculated like this:

Total element width = width + left padding + right padding + left border + right border + left margin + right margin

The total height of an element should be calculated like this:

Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
```

# CSS Borders

[CSS Borders](https://www.w3schools.com/css/css_border.asp)


# CSS Margins

[CSS Margins](https://www.w3schools.com/css/css_margin.asp)

# CSS Padding

[CSS padding](https://www.w3schools.com/css/css_padding.asp)

# CSS Height, Width and Max-width

[CSS Height, Width and Max-width](https://www.w3schools.com/css/css_dimension.asp)

# CSS Text

[CSS Text](https://www.w3schools.com/css/css_text.asp)

# CSS Fonts

[CSS Fonts](https://www.w3schools.com/css/css_font.asp)

# CSS Icons

[CSS Icons](https://www.w3schools.com/css/css_icons.asp)

[Font Awesome 5 Introduction](https://www.w3schools.com/icons/fontawesome5_intro.asp)


## Ionicons 

[Ionicons](https://ionic.io/ionicons)

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/ionicons/6.0.3/index.cjs.min.js" integrity="sha512-XA50v2jCBeXCjj3csHdYV4HLvACatDSmuN+qGW2CALMbjz4jqGpzf2Fi2WYbbcfex7n44oj1KUNpSWqg9BblhQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

```
# CSS Links

- With CSS, links can be styled in many different ways.

[CSS Links](https://www.w3schools.com/css/css_link.asp)

# CSS Lists

- HTML Lists and CSS List Properties

[CSS Lists](https://www.w3schools.com/css/css_list.asp)

# CSS Flex Box

[Flex-Box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

# CSS Grid

[CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

# CSS position Property


# HTML and CSS Projects.

## Project - 1

[Personal-portfolio](https://personal-portfolio.freecodecamp.rocks/)

## Project - 2

[tribute-page](https://tribute-page.freecodecamp.rocks/)

## Project - 3

[product-landing-page](https://product-landing-page.freecodecamp.rocks/)

## Project - 4

[mytunes](https://jolly-kalam-23776e.netlify.app/mytunes/)

## Project - 5

[resturant-page](https://jolly-kalam-23776e.netlify.app/restaurantwebsite/)

## Project - 6

[photographysite](https://jolly-kalam-23776e.netlify.app/photographysite/#images)


## More project 

[frontendmentor](https://www.frontendmentor.io/challenges?sort=difficulty|asc&types=free)


## Resoureces

 * [HTML Dog Tag List](http://www.htmldog.com/reference/htmltags/)
 * [W3Schools Tag List](http://www.w3schools.com/tags/default.asp)
 * [Quackit HTML Tag List](http://www.quackit.com/html/tags/)


