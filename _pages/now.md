---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 1st November 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://www.saltpublishing.com/products/the-moon-is-trending-9781784632878">The Moon is Trending</a> by Clare Fisher; <a href="https://gayprideshop.co.uk/products/the-queer-parent-everything-you-need-to-know-from-gay-to-ze-book">The Queer Parent: Everything You Need to Know From Gay to Ze</a> by Lotte Jeffs and Stu Oakley</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/@primitivetechnology9550">Primitive Technology</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://en.wikipedia.org/wiki/Blood_Harmony_(album)">Blood Harmony</a> by Larkin Poe</li>
		<li><strong><em>learning:</em></strong> the solo from <a href="https://youtu.be/NxFE5YOErcg?feature=shared&t=87">Cosmic</a> by Avenged Sevenfold</li>
		<li><strong><em>writing:</em></strong> my NaNoWriMo project for 2024; backstory for my D&D campaign</li>
		<li><strong><em>playing:</em></strong> <a href="https://www.youtube.com/watch?v=I-ra1bksSzs">Prince of Persia: The Lost Crown</a>; Dungeons & Dragons </li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
	November already! I suppose it's true what they say about time moving more quickly as you age. This time around it's a less busy month, though I'm sure I'll find ways and means of filling it up. I've been trying to counteract the effects that the shorter, colder days have upon my mental health by taking up running, starting with the couch-to-5k programme. It's been enjoyable so far, and there's something quite satisfying about getting out into a chilly evening and starting to run. You don't feel the cold by the end of the run, and the endorphin rush is quite something. Hopefully by Christmas, I'll be a confident 5000m runner.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
	I'm attempting <a href="https://nanowrimo.org/participants/eibhei">NaNoWriMo</a>, as I mentioned in my previous update. I've outlined and planned a little more this time than ever I have before, which I'm hoping will be the foundation I needed to get me over the 50,000 word finish line. The other thing I'll need is time dedicated to the act of writing every day. I'm not sure that I can promise myself that, but I certainly want to try. There may be stolen minutes at work, or over lunch. Who knows. The goal is 50,000. I don't have to tell you exactly how late I stayed up (or how often) to achieve it.
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
	The process of buying a home has been one of endless frustrations, and there is still no end to the waiting. I am weighing whether or not to continue with the purchase at all. B and I have been talking about timelines for moving in together, and it's looking increasingly like I wouldn't have the place for nearly long enough to feel the benefit of appreciation before we began cohabiting if we stick to the vague timeline that we're thinking about. Perhaps it's time to admit defeat and regroup.
</p>

<h1>Ongoing Projects</h1>
<div class="ProjectContainer" style="padding-top: 0.5em">

	<div class="gallery">


  {% for project in site.projects %}

  {% if project.redirect %}
  <div class="projectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="projectTile">
          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

	</div>

</div>
