# CS52 Bootstrap Workshop

![](http://jpcamara.com/wp-content/uploads/2015/02/Bootstrap-Delay.gif)

Welcome to the CS52 workshop session on Bootstrap.  During this workshop, you will learn the basics of using
the Bootstrap framework by using it to create a clean, responsive, and mobile friendly web page.

## Workshop Overview

For this workshop, you will be asked to incorporate many of the components of Bootstrap into a simple website. Your challenge, should you choose to accept it is:

*Take the poorly formatted and un-styled HTML that we have provided for you in this workshop and use Bootstrap to turn it into a masterpiece, without using any CSS.*

In order to complete the challenge, follow these steps:

1. [Fork the repository](#fork)
2. [Set up Bootstrap](#setup)
3. [Create the Navigation Bar](#nav-bar)
4. [Add a Jumbotron](#jumbotron)
5. [Encapsulate Content in a Grid Layout](#grid-layout)

## Fork

To start our workshop, please clone [this](URL HEREfjdklsafjldsfflkdsafjl) repository to your computer. It contains a bare-bones HTML file with content that we will be starting with. Notice how ugly it looks right now?

## Setup

Setting up Bootstrap is simple – all you have to do is link it into the html from a CDN.  For example, you can link in Bootstrap by including the following line in the `<head>` of your HTML:

`<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">`

Also, to ensure proper rendering and touch zooming, add the following `<meta>` tag inside the `<head>`:

`<meta name="viewport" content="width=device-width, initial-scale=1">`

## Navigation Bar

First, we will begin by setting up a simple nav-bar for the site.  Bootstrap provides many
different classes that can be used to customize a nav bar.  To customize the nav bar using Bootstrap,
incorporate Bootstrap classes into the `<nav>` section of the HTML.  


To add a standard nav-bar, use `<nav class="navbar navbar-default">`.

Next, within the nav element, add the `container-fluid` class to the div – this class creates a full width container, spanning the entire width of your viewport.

To make the title of the website a header, add the `navbar-header` class to the "Dartmouth CS Survival Guide" div and `navbar-brand` to the anchor tag. This will give the text a slightly larger size.

To add links to the navbar, simply add to _both_ unordered list tags the classes `nav navbar-nav`.

At this point, it should look miles better already! All just by adding a few simple classes to your HTML. But let's make it a little better.

Often times, you want to align specific parts of the navbar to the left or right. Let's do that here. Add the `navbar-right` class to the unordered list tag containing the "Sign Up" and "Login" items.

To indicate that the Home page is the page we are currently on, add the `active` class to Home's list item element.

Now, let's make this nav-bar responsive. We will make the navigation bar  hidden on small screens and replaced by a button in the top right corner.


As a final touch, add icons to the two right items. Inside these two list item tags, add `<span class="glyphicon glyphicon-user"></span> ` and `<span class="glyphicon glyphicon-log-in"></span> ` (note the spaces), respectively.

And that's it! Note that many variations of this exist, such as `navbar-inverse` instead of `navbar-default` to invert the colors, or `navbar-fixed-top` to pin to the top even when scrolling (try it out).

For more complex Bootstrap navigation bar examples, see the
[W3Schools tutorial](https://www.w3schools.com/bootstrap/bootstrap_navbar.asp).

## Jumbotron

A jumbotron indicates a big box for calling extra attention to some special content or information. To create a jumbotron in Bootstrap, incorporate the Bootstrap `jumbotron` class into the `div class="page header"`.

## Grid Layout

The HTML that we have provided for you is laid out vertically.  Use the Bootstrap preset grid layout to
align the content in an arrangement that is more visually appealing.

## Footer

Placeholder

### What you should have at this point

Four sections, each of which should be nicely formatted and responsive
* Navigation bar
* Jumbotron
* Grid layout
* Footer

Also, you should have added one extra feature on your own from the list provided above.  

__Be creative!__ One of the best parts about Bootstrap is that there are an endless amount of features and classes already built-in, and extra ones are being added with every new version.



### Additional Resources

* https://www.w3schools.com/bootstrap/
* https://scotch.io/bar-talk/bootstrap-3-tips-and-tricks-you-might-not-know
