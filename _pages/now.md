---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 1st October 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://www.saltpublishing.com/products/the-moon-is-trending-9781784632878">The Moon is Trending</a> by Clare Fisher</li>
		<li><strong><em>watching:</em></strong> House MD</li>
		<li><strong><em>listening:</em></strong> to <a href="https://en.wikipedia.org/wiki/The_Silmarillion">The Silmarillion</a> by J.R.R. Tolkien, read by Andy Serkis</li>
		<li><strong><em>learning:</em></strong> the solo from <a href="https://youtu.be/NxFE5YOErcg?feature=shared&t=87">Cosmic</a> by Avenged Sevenfold</li>
		<li><strong><em>writing:</em></strong> backstory for my D&D campaign; the bones of a conlang; guitar solos for a long-in-the-works composition</li>
		<li><strong><em>playing:</em></strong> <a href="https://www.youtube.com/watch?v=I-ra1bksSzs">Prince of Persia: The Lost Crown</a>; Dungeons & Dragons </li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
		As we hurtle towards the end of another year, I'm always struck by how quickly I fill my time up after the summer holidays. I am playing gigs 3/4 weekends this October, and already the rest of the first two weeks are rife with plans. It's nice to be busy in a way, but I am no stranger to burnout. So I am trying to be more deliberate about blocking out time that is not going to be used for anything else, and permits me just to sit quietly and not do a huge amount of social exertion, which always seems to take a much greater-than-normal toll once the nights begin to draw in.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.1em; text-indent: 4ch;">
	I think I want to try doing NaNoWriMo again when next month rolls around (possibly together with M, if she can be persuaded to give it a go). I enjoy writing a lot, but the muscles definitely need loosening and warming up, so I'm planning to spend this month (loosely linked with <a href="https://tildes.net/~creative.timasomo/1j5m/timasomo_2024_roll_call">TiMaSoMo</a>) limbering up my writing chops for a more concerted effort in November. I'll be writing a bit more history for my D&D campaign setting, as well as characters, factions, and concepts that I need to flesh out some more, and I've got a conlang that I want to work on a little.
</p>
<p style="margin-top: 0.05em; margin-bottom: 0.75em; text-indent: 4ch;">
	Beyond the realms of fiction, I need to spend some time completing my "musings on coming out" posts, and I have in mind a series of shorter posts about valuable lessons I try to live by. Hopefully, there'll be more to see here before very long.
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
		The flat purchase is still ongoing, there is sadly nothing new which I can report since last time. The extension of the leasehold remains ongoing, and I'm starting to lose hope that I'll actually get to move into this place. A not-very-small part of me is now wondering if I should start entertaining other possible places to live, though I'm feeling pessimistic that I'll just end up in this same limbo regardless. Circumstances beyond the purchase of my flat are also conspiring to make things a little more complicated and possibly less prudent to buy my own home. Certainly the temptation to begin renting a small studio or one-bed flat is growing greater, though it's much harder to justify from an economic perspective now.
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
