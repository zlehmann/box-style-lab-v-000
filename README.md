# Box Style Lab

## Objectives

1. Practice writing and employing a box styling with CSS
2. Explore `border`, `box-shadow`, `background`, and the `linear-gradient()` CSS function


## Introduction

As you have already noticed (as an non-programming end-user of the internet)
the majority of websites out there use boxes to represent content. Sometimes we
see the borders of these boxes, sometimes they have a slight 3D effect, and
sometimes they change color when we hover over them. 

Now, being the web programmer that you are, you know there is good reason for
this! The DOM, via direction from HTML and CSS, defaults to box shapes for the
majority of its elements. As such, there are many ways we can manipulate, add
effects to, and style our HTML boxes.

Using a 'before' and 'after' example, we will transform a page into a column
based presentation. In doing so, we will practice our skills writing re-usable,
rule-based, CSS. 

This lab is a great time to practice editing CSS directly in Chrome Inspector
Tools. This allows us to change properties/values on the fly and see what they
look like on screen before going back and editing the actual CSS file. 


## Instructions

- Examine what we have rendering already by opening `index.html` in the browser
- Create a raised 3D effect for each of our sections using [`box-shadow`][box-shadow] (the green section has already been implemented)
- Provide a solid [`border`][border] for all of our `<img>` tiles
- Provide a [`background`][background] texture for the whole page, using `images/white-wood.jpg`
- Implement an over-the-top, mind-blowing, [`linear-gradient()`][linear-gradient] and [`:hover`][hover] effect for all of our section titles


<div align="center">
  <h4>What We Have</h4>
  <img src="https://curriculum-content.s3.amazonaws.com/fewds-css/box-style-lab-incomplete.png" alt="drawing" width="200px"/>
</div>

In the above example, our images are simply lining up one after another, left to
right, top to bottom. Instead, we want to organize them into columns, within
which they will align vertically.

<div align="center"><br>
  <h4>What We Want</h4>
  <img src="https://curriculum-content.s3.amazonaws.com/fewds-css/box-style-lab-complete.png" alt="drawing" width="200px"/>
</div><br>


#### Help Getting Started

border: 1px solid #aa2222;
box-shadow: -1px 1px #aa2222, -2px 2px #aa2222, -3px 3px #aa2222, -4px 4px #aa2222, -5px 5px #aa2222;
background-color: #dd4444;

box-sizing: border-box;
border: 2px solid #333;

background: url("../images/white-wood.jpg") no-repeat fixed; (our image is not very big so making it 'fixed' allows us to scroll through the content while keeping the foreground fixed). Experiment with how you can change it so the background appears to scroll _with_ the content
background-size: cover;

Implement an over-the-top, mind-blowing, [`linear-gradient()`][linear-gradient] and [`:hover`][hover] effect for all of our section titles

h4.amiable {
  background: linear-gradient(
    to right,
    #118833,
    /* #66ee88 */
    #fff
  );
}









<p data-visibility='hidden'>View <a href='https://learn.co/lessons/box-style-lab' title='Box Style Lab'>Box Style Lab</a> on Learn.co and start learning to code for free.</p>

[linear-gradient]: https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient
[hover]: https://www.w3schools.com/cssref/sel_hover.asp
[box-shadow]: https://www.w3schools.com/cssref/css3_pr_box-shadow.asp
[background]: https://www.w3schools.com/css/css_background.asp
[border]: https://www.w3schools.com/css/css_border.asp
