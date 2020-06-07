---
title: Web Books
---

I'm fascinated by the web. It's so big and vast that it's hard to pin down much about it. To me, web books are an expression of what the web can be when it's at its best: access to ideas.

Here are just a few of the web books that I enjoy and share:

[<cite>Resilient Web Design</cite>](https://resilientwebdesign.com) by Jeremy Keith
: Keith covers a bit of the underlying history of the web itself, and makes one of the best cases I know of for taking a progressive approach to building for the web.

[<cite>The Shape of Design</cite>](http://shapeofdesignbook.com) by Frank Chimero
: Chimero writes about the "whys" of design.

[<cite>Practical Typography</cite>](http://practicaltypography.com) by Matthew Butterick
: Butterick's overview is probably the most comprehensive approach to typography available on the web. I find myself recommending [Typography in Ten Minutes](http://practicaltypography.com/typography-in-ten-minutes.html) to anyone interested in improving their typographic skills, and often share Butterick's advice on [Résumés](http://practicaltypography.com/resumes.html).

[<cite>Professional Web Typography</cite>](https://prowebtype.com) by Donny Trương
: Trương's treatment focuses more on typography as it is employed on the web. His section on [Practicing Typography](https://prowebtype.com/practicing-typography/) has some great examples of web-based typesetting.



More Examples
-------------

* [<cite>Beautiful Racket</cite>](http://beautifulracket.com) by Matthew Butterick
* [<cite>Eloquent JavaScript</cite>](http://eloquentjavascript.net) by Marijn Haverbeke
* [<cite>Vietnamese Typography</cite>](https://vietnamesetypography.com) by Donny Trương
* [<cite>Design is History</cite>](http://www.designishistory.com)
* [<cite>How to Design Programs, Second Edition</cite>](http://www.ccs.neu.edu/home/matthias/HtDP2e/) by Matthias Felleisen, Robert Bruce Findler, Matthew Flatt, and Shriram Krishnamurthi



What Makes them Work
--------------------

For anyone out there who might embark upon the publication of a web book, some notes on best practices:

1. **Provide friendly links to content.** Typically, these books allow linking to each chapter separately. Many also provide mechanisms for providing a link to a particular paragraph.

    Jeremy Keith does it best by making highlighted selections linkable, e.g. ["This is not a handbook. It’s more like a history book."](https://resilientwebdesign.com/introduction/#This%20is%20not%20a%20handbook.%20It’s%20more%20like%20a%20history%C2%A0book.) I believe this could be further improved for readability by using a `+` for spaces, as opposed to `%20`.
    
    Haverbeke provides links to individual paragraphs, which are available to users by hovering over a text block. Unfortunately, these URLs are not human-parseable, e.g. ["For open-ended interfaces, such as instructing the computer to perform arbitrary tasks, we’ve had more luck with an approach that makes use of our talent for language: teaching the machine a language."](http://eloquentjavascript.net/00_intro.html#p_8m5Rp23sjC)


2. **Allow users to keep reading by providing a prominent link to the next chapter.** Almost all of the examples above do this well, and make these links very prominent.

    Butterick's approach in [<cite>Practical Typography</cite>](http://practicaltypography.com) provides less prominent links to the previous and next chapters, in a manner reminiscent to most online documentation, [such as for Django](https://docs.djangoproject.com/en/1.11/intro/tutorial01/). The link to the next chapter should be easier to spot and jump to.
    
    Keith [includes a prominent link to the next chapter](https://resilientwebdesign.com/chapter6/), along with a full table of content following it. This is a useful approach, which works particularly well on smaller screen sizes. It could be improved by providing the reader with an indication of which chapter they have just finished in the full table of contents, as well as greater differentiation between the prominent next chapter and the full contents. Chimero does the best job of the latter in [<cite>The Shape of Design</cite>](http://shapeofdesignbook.com/chapters/01-how-and-why/), but could still improve by giving an indication of which chapter is currently being viewed.


3. **Incorporate interactive examples and illustrations.** This can include manipulable diagrams or code playgrounds.
    
    Of the above examples, these are only successfully executed by Haverbeke [in <cite>Eloquent JavaScript</cite>](http://eloquentjavascript.net/03_functions.html#c_YeYw47ylC5). His topic has an advantage, as web browsers natively execute code written in JavaScript. The interface could be improved with greater discoverability. As it stands, a reader must click on the code to discover that it can be edited, and further actions are hidden behind keyboard shortcuts listed only in a hamburger menu. A straightforward toolbar would go a long way, and could be done tastefully without disrupting the flow of reading.
    
    Most writing is published inertly, and invites fairly passive consumption—not as passive as television perhaps, but less active than getting one's hands dirty. This is where the medium of web books has a major advantage that I'd like to be explored more deeply.
    
    At the moment, these remain painfully difficult to build, so it is no wonder there are so few good examples of this on the web. Even Bret Victor's essay on [Learnable Programming](http://worrydream.com/LearnableProgramming/) misses the opportunity to use interactive examples, instead opting for short videos of interaction. This keeps the reader in a similar passive mode and fails to fully engage as actively as it could.
    
    Vi Hart and Nicki Case offer more active examples in their beautifully prepared [Parable of the Polygons](http://ncase.me/polygons/), which functions more as an essay than as a book.
    
    In [<cite>Programming Design Systems</cite>](https://programmingdesignsystems.com), Rune Madsen includes exercises at the end of some chapters, like this one at the end of [Shape: Figure and Ground](https://programmingdesignsystems.com/shape/figure-and-ground/):
    
    > Pick a random adjective from the dictionary, and write a sketch that tries to convey that word by changing the position, size, and rotation of a single rectangle. Do this for a couple of words, and ask friends to guess the word-image combinations.
    
    There is an opportunity here to provide an interactive space right on the page, even if rudimentary.