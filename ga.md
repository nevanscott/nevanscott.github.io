---
title: General Assembly
---

At GA, I started out teaching a 10-week part-time course on [front-end web development](https://generalassemb.ly/education/front-end-web-development) whose curriculum I subsequently helped [overhaul](#fewd-overhaul). As I continued to run the class, I built up an accompanying course website over time, starting out with something very [rudimentary](http://nevanscott.com/fewd13/), then [rolling](http://nevanscott.com/fewd19/), [rolling](http://nevanscott.com/fewd29/), [rolling](http://fewd49.nevan.org). Now I teach an immersive course in user experience design, which has been as demanding as it has been rewarding.


FEWD Overhaul
-------------

I developed several exercises and [projects](#fewd-projects) that I'm particularly proud during this process, including a [box model](http://codepen.io/nevan/pen/vtorn) exercise, a way to explore the basics of [classes and ids](http://codepen.io/nevan/pen/JnfEd), a simple and visual way to approach [page layouts](http://codepen.io/nevan/pen/nHIEo), an introduction to [nested selectors](http://codepen.io/nevan/pen/gFAfh), an old-school game of [rock, paper, scissors](http://codepen.io/nevan/pen/zChrG), and a basic [cash register](http://codepen.io/nevan/pen/uBkEr). I also developed a series of refactored color scheme switchers which I've found are very effective for progressively introducing more sophisticated approaches to refactoring JS--first in [pure JS](http://codepen.io/nevan/pen/kBItz), then using a [body class](http://codepen.io/nevan/pen/pnLje) to remove CSS from the JS, next doing the same thing [with jQuery](http://codepen.io/nevan/pen/dmklG), and finally making the code more flexible by using [the "this" keyword](http://codepen.io/nevan/pen/sHpbj).

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="vtorn" title="The Box Model" %}
  </div>
  <figcaption markdown="1">
  The [box model](http://codepen.io/nevan/pen/vtorn) exercise introduces basic properties like `padding`, `border`, and `margin`.
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="JnfEd" title="Classes and IDs" %}
  </div>
  <figcaption markdown="1">
  [Classes and IDs](http://codepen.io/nevan/pen/JnfEd) are useful for differentiating content beyond what is possible with built-in HTML elements.
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="nHIEo" title="Page Layout" %}
  </div>
  <figcaption markdown="1">
  [Page Layout](http://codepen.io/nevan/pen/nHIEo) introduces the basics of composing pages using `float`.
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="gFAfh" title="Nested Selectors" %}
  </div>
  <figcaption markdown="1">
  As pages become more intricate, we may need [nested selectors](http://codepen.io/nevan/pen/gFAfh) to style elements under specific circumstances.
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="zChrG" title="Rock, Paper, Scissors" %}
  </div>
  <figcaption markdown="1">
  [Rock, Paper, Scissors](http://codepen.io/nevan/pen/zChrG) turned out to be more challenging for students than I initially imagined. I did enjoy putting together this weird retro style for the game though.
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    {% include codepen.html slug="uBkEr" title="Cash Register" %}
  </div>
  <figcaption markdown="1">
  [Cash Register](http://codepen.io/nevan/pen/uBkEr) is a great challenge project for students who are ready to stretch their JS skills a bit.
  </figcaption>
</figure>



FEWD Projects
-------------

I made a simple [About Me](http://fewd49.nevan.org/projects/wendy_bite/) website, which utilizes only a very basic set of HTML elements (no ids or classes), and very lightly introduces the concept of floats. This is followed by a [single-column blog](http://fewd49.nevan.org/projects/fashion_blog_alpha/), which I use to introduce a greater range of HTML elements, along with nested CSS. That has a [2-column redesign](http://fewd49.nevan.org/projects/fashion_blog/) which students transition to, using floats for page layout and for the navigation. It's fascinating to me that it is doable now, but students who take the class actually learn to code layouts to be fluid right out of the gate. From here, they are ready to tackle the more complex layouts in [Startup Matchmaker](http://fewd49.nevan.org/projects/startup_matchmaker/), which I give them with extra pages which have not been "designed", as an exercise for them to imagine and create those pages based on the style established on the given pages.

<figure class="screenshot">
  <div class="browser">
    <img src="/img/about.png"
      srcset="/img/about.png 1024w, /img/about_m.png 640w"
      alt="About Page Screenshot">
  </div>
  <figcaption markdown="1">
  The [About Me](http://fewd49.nevan.org/projects/wendy_bite/) project gives students the opportunity to build a 2-page website using only basic HTML elements and a minimal set of CSS.

  <h2>Introduces</h2>

  * Basic HTML tags
  * HTML page "skeleton"
  * Semantic HTML sections
  * Starter CSS properties
  * CSS Element selectors
  * CSS Descendant selectors
  * CSS `:hover` pseudo-class
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    <img src="/img/fashion1.png"
      srcset="/img/fashion1.png 1024w, /img/fashion1_m.png 640w"
      alt="Single-column Fashion Blog Screenshot">
  </div>
  <figcaption markdown="1">
  [Sartre’s List](http://fewd49.nevan.org/projects/fashion_blog_alpha/) pushes students further with more nested HTML and more sophisticated CSS.

  <h2>Introduces</h2>

  * Nav layout using `float`
  * More practice with the basics
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    <img src="/img/fashion2.png"
      srcset="/img/fashion2.png 1024w, /img/fashion2_m.png 640w"
      alt="Two-column Fashion Blog Screenshot">
  </div>
  <figcaption markdown="1">
  The [Redesign of Sartre’s List](http://fewd49.nevan.org/projects/fashion_blog/) requires students to produce a 2-column layout, and also offers subtle nudges to begin exploring CSS transitions.

  <h2>Introduces</h2>

  * Page layout using `float`
  * Nested CSS selectors
  </figcaption>
</figure>

<figure class="screenshot">
  <div class="browser">
    <img src="/img/startup.png"
      srcset="/img/startup.png 1024w, /img/startup_m.png 640w"
      alt="Startup Matchmaker Screenshot">
  </div>
  <figcaption markdown="1">
  [Startup Matchmaker](http://fewd49.nevan.org/projects/startup_matchmaker/) gives students room to explore more sophisticated layouts, as well as opportunities to think about design systems.

  <h2>Introduces</h2>

  * Background images
  * CSS class selectors
  </figcaption>
</figure>



*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets
*[JS]: JavaScript
*[UXDI]: User Experience Design Immersive
*[FEWD]: Front-End Web Development
*[UX]: User Experience
