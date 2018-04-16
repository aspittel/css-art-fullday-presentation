# Learning CSS Through Creating Art - Full Day Edition!

## Learning Objectives

* Discuss CSS art and look at how to make it.
* Use a design software to create our art.
* Use CSS selectors and attributes to create CSS art.
* Use CSS grid to create grids in CSS.
* Implement CSS animations using keyframes and transitions.

## What you will create

* A piece of CSS art that uses colors, shapes, and positioning.
* A piece of CSS art using CSS grid.
* An animation built in CSS.

## Intros

Let's go around and say:
* Your name
* Where you are from
* Your background in coding (no background is totally fine!)
* Your guilty pleasure

## What is CSS and HTML?

### CSS
* CSS is used to declare styling on webpages. Pretty much every website uses it!
* Styles are applied in a cascading manner -- the most specific styles will override the less specific ones!
* CSS stands for Cascading Style Sheets.

### HTML 

HTML defines the structure and content of our website. HTML tags have different meanings. For example a *p* tag defines a paragraph. We will attach our CSS code to HTML tags using selectors.

## Example CSS Art

See the slides! All of these are built using pure CSS and HTML (no JavaScript!)

## Intro to CSS

### CSS Syntax

![](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

### HTML Syntax

![](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)
![](https://mdn.mozillademos.org/files/9345/grumpy-cat-attribute-small.png)

### Selectors

When we use CSS, we are selecting content from our HTML code and adding styling to it. We apply CSS code at varying levels of specificity. We will use:

* Elements - to select all HTML tags of a certain type. Selected with the tag's name.
* IDs - to get one element with a specific ID. Selected with a <b>`#`</b> and the name of the ID.
* Classes - to get all elements with a class. Selected with a <b>`.`</b> and the name of the class.

### Divs

Today, we will be using an HTML tag called a div. These tags are special -- they just specify a grouping of elements or a space to style -- they don't have any default behaviors other than having a new line after them.

### Positioning

Elements are positioned using the top, bottom, left, and right properties. These properties don't work until the position property is set! There are a few different options for positioning, but we will use two today: absolute and relative.

<b>Absolute positioning</b>: We can position our divs on the page relative to their parent elements using absolute positioning! The "sibling" absolutely positioned divs ignore each other, so they can overlap. We will be using absolute positioning for most of our art!

<b>Relative positioning</b>: We can position our divs on the page relative to that div's default position using relative positioning. Remember, divs by default will stack on top of one another!

[Demo](https://codepen.io/aspittel/pen/BYxvOX?editors=1100")


### Shapes

As we just saw, we can easily create squares with css, just by setting the width, height, and background-color attributes. To make that square into a circle, just add a border-radius of 50%! That will round the corners of the shape perfectly. Triangles, and other shapes get a little bit more tricky: I use [Clippy](https://bennettfeely.com/clippy/) and to visually edit those shapes using clip paths!

[Demo](https://codepen.io/aspittel/pen/zRLvaQ?editors=0100)


## Code Along - First Project

![](./images/house.png)

[Completed House](https://codepen.io/aspittel/pen/jZKpdQ?editors=1100)

## Design Software

We are going to download a design software so that you can sketch out your CSS art before creating it.

Download [Gravit](https://designer.io/)


## Activity: Make your own art

Build a piece of CSS art! Use a design software to outline what your artwork will look like.

Some Ideas:

* An animal
* A landscape
* A self-portrait
* A pretty pattern

## CSS Grid

CSS grid is a pretty new technology -- it just rolled out this year! It allows you to make grid-based layouts with rows and columns, which makes positioning much easier!

We will start with a grid container that contains grid items within it. We will also specify rows (horizontal) and columns (vertical) that our items will fit within.

## Activity: Mondrian with CSS Grid

Practice CSS Grid! Choose one of Piet Mondrian's artworks and recreate it using CSS grid.

## CSS Animations

We can also animate our web pages using CSS! No JavaScript needed. There are two main ways we can add animations to our sites: transitions and keyframes. If you want to do something simple upon a user interaction, transitions are great. If you want to do something more complex or time based, you will want to use keyframes.

[Transitions Demo](https://codepen.io/aspittel/pen/rdXBWZ)
[Keyframes Demo](https://codepen.io/aspittel/pen/mxNbzO)

## Activity: Adding Animations



## Next Steps

<li><a href="https://dev.to/aspittel/learning-css-through-creating-art-9i7">My article on the topic!</a></li>
<li><a href="http://creativecoding.club/">Creative Coding Club</a></li>
<li><a href="https://medium.com/coding-artist/a-beginners-guide-to-pure-css-images-ef9a5d069dd2">A Beginner’s Guide to Pure CSS Images</a></li>
<li><a href="http://www.bypeople.com/50-impressive-css-drawings/">50 Great CSS Images</a></li>
<li><a href="http://coffeecraftcode.com/2017/12/27/breaking-down-css-art/">Breaking Down CSS Art</a></li>


## Bonus: SCSS

SCSS is a CSS pre-processor. It is a different way to write CSS that adds a bunch of cool features, like loops, mixins, variables, 
[Demo](https://codepen.io/aspittel/pen/oqKvVb)
