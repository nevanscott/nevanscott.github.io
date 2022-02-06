---
clients:
  - A Book Apart
  - American Express
  - Cornelsen
  - David Korins
  - Duden
  - Fiji Water
  - General Assembly
  - Mandy Brown
  - Mercedes
  - Midnight Breakfast
  - New York University
  - Northeastern University
  - Rustic Pathways
  - Swiss Red Cross
---

<section class="lede" markdown="1">

<header>
  <strong>Howdy!</strong> I teach user&nbsp;experience and interaction&nbsp;design in&nbsp;Barcelona.
</header>

<div class="rotator" markdown="1">

- I'm learning how to say "design&nbsp;educator" without&nbsp;flinching.
- I use open-minded definitions of *puppet*, *teaching*, and&nbsp;*definition*.
- I aim to put people first and tools&nbsp;second.
- My home is not "smart" and I'd like to keep&nbsp;it that&nbsp;way.

</div>

<script>
(function() {
  const $rotator = document.querySelector('.rotator');
  const $list = $rotator.querySelector('ul');

  $rotator.classList.add('enabled');
  $list.firstElementChild.classList.add('active');

  $list.addEventListener('click', function() {
    const $current = $list.querySelector('.active');
    const $next = $current.nextElementSibling || $list.firstElementChild;

    $current.classList.remove('active');
    $next.classList.add('active');
  });
})();
</script>

</section>


Teaching
--------

I teach a [UX/UI design bootcamp](https://uxui.cat) at Ironhack in Barcelona.

Previously, I've taught at Noble Desktop and at General Assembly, both in New York.


Clients
-------

A selection of clients I've worked with over the years:

<ul class="listing">
  {% for client in page.clients %}
    <li>{{ client }}</li>
  {% endfor %}
</ul>


Writing
-------

I write and share thoughts on what I'm reading around the web at [notated.org](http://notated.org).



*[UX]: User Experience
*[UI]: User Interface
