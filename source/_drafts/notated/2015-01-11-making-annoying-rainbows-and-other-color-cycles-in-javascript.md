---
title: Making annoying rainbows and other color cycles in Javascript
url: http://krazydad.com/tutorials/makecolors.php
teaser: |
  It's nerdy in all the ways I like, touching on color theory and basic programming, and illustrated with visual examples of the output.
---

Jim Bumgardner has a nice little tutorial on writing code to cycle through colors. It's a good read to be sure, but I also wanted to link to it because of how I got to it.

First I was revisiting Frank Chimero's transcript of his talk [What Screens Want](http://frankchimero.com/talks/what-screens-want/transcript/)[^whatscreenswant], which simultaneously thinking about changes I might make to a site I'm working on right now.

In the talk, Frank talks about how designing for screens can be like designing for what he calls "flux":

> So what does all of this mean? I think the grain of screens has been there since the beginning. It’s not tied to an aesthetic. Screens don’t care what the horses look like. They just want them to move. They want the horses to change.
>
> Designing for screens is managing that change. To put a finer head on it, the grain of screens is something I call *flux*—
>
> Flux is the *capacity* for change.
>
> Yes, this could be animation, because that’s what I’ve been talking about up until now, but I think it’s a lot more, too. Flux is a generous definition. It encompasses many of the things we take for granted in the digital realm: structural changes, like customization, responsiveness, and variability.

The site which serves as the transcript for the talk, acts as a showcase for this very idea in a rather subtle way: certain portions of the text have a muted background color which, if you pay close attention to it, is changing slowly over time. I didn't notice this the first time I read through the essay, which I think adds another level of interest to the effect.

This time though, I decided to peak under the hood to get a better idea of what exactly was going on, when I came across a file named [`fade.js`](http://frankchimero.com/talks/what-screens-want/transcript/fade.js), which begins:

```js
// This JS code comes from Charlie Loyd [ @vruba ], who wrote a wonderful little
// missive here: http://basecase.org/2012/11/diadem/
// He's given me permission to pilfer his codes. Thank you, Charlie.

// BEGIN COLOR-SCHNAZZIE-IFIER.

// Hi. This is not really production-quality code, just something I
// patched together for an experimental essay. But if you have
// questions, I'd be happy to answer them.
```

Further down, another interesting comment:

```js
// This is an adaptation of the rainbow function described at
// http://basecase.org/env/on-rainbows (K is for @skimbrel, my
// buddy who had the central insight that sines work for this).
// We lighten and desaturate it a little.
```

Charlie Lloyd's 'missive' is called [Perhaps it is broken, the cover of your diadem […], darkness collar […]?](http://basecase.org/2012/11/diadem/), and indeed looks interesting, but I will have to give it a read later. The background for that essay has a similar slow-morphing color as Chimero's.

In his post [On rainbows](http://basecase.org/env/on-rainbows), linked to in the second comment, Lloyd provides further interesting context:

> (Halfway through writing this I double-checked that the techniques it shows were actually new – and, trying different search terms, found that [Jim Bumgardner](https://twitter.com/#!/jbum), a Processing expert, had already [explained them perfectly well](http://www.krazydad.com/makecolors.php). With his encouragement I’m publishing this anyway.)

And that's what led me to the piece I decided to link to above.

I absolutely love reading stuff like this. It's nerdy in all the ways I like, touching on color theory and basic programming, and illustrated with visual examples of the output.[^bostockshuffle] And when I came across Bumgardner's post, I got all excited about this story of how I came across it, and how the web I love is still out there: the one with all the thoughtful independent moving parts, the one where people are free to write what they want and make it available to anyone, where people leave breadcrumbs back to where their ideas come from.

But along the way, I got to thinking what was kicking around my head: that this was evidence of "the web I love" -- as I was calling it in my head. And I don't know why but that thought as it accumulated invited another darker thought, one about comfort and familiarity and safety. And it occurred to me that this idea of mine, of "the web I love" had more to do with comfort and familiarity and safety that I might have let on to myself at first. What did it mean that these writers were all white and male like me? I don't want to presume anything about anyone, and I certainly don't want to claim that these thoughts haven't occurred to any of them, but it strikes me that we all fit a certain kind of profile, with earlier access to more of the tools of computing and the internet, and more leisure time at an earlier age which we could use to pursue our interests, and a physiological makeup that was always culturally considered compatible with obsessive study and possibly some quirky asocial tendencies.

I have more thinking to do on all of this, which I'll leave for another day. But my trail of surfing ultimately led me to the [Parable of the Polygons](http://ncase.me/polygons/)[^hartandcase], which I had never seen before and is simply awesome. Which got me relatively safely back to my good feelings about the web that I love. Give it a read-through, and I think you'll see what I mean.


[^whatscreenswant]: It's a great read, highly recommended.

[^bostockshuffle]: Perhaps my favorite example of this type of post is Mike Bostock's explanation of the [Fisher-Yates Shuffle](http://bost.ocks.org/mike/shuffle/). Then again, there's always Bret Victor's [Learnable Programming](http://worrydream.com/LearnableProgramming/) diatribe.

[^hartandcase]: I had never heard of Nicky Case, but I absolutely love [the work of Vi Hart](http://www.khanacademy.org/math/recreational-math/vi-hart).