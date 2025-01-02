---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 2nd January 2025.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://gayprideshop.co.uk/products/the-queer-parent-everything-you-need-to-know-from-gay-to-ze-book">The Queer Parent: Everything You Need to Know From Gay to Ze</a> by Lotte Jeffs and Stu Oakley; <a href="https://en.wikipedia.org/wiki/Wind_and_Truth">Wind and Truth</a> by Brandon Sanderson</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=6y0E1pL5wws">Mr Robot</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://en.wikipedia.org/wiki/Rite_Here_Rite_Now">Rite Here Right Now</a> by Ghost</li>
		<li><strong><em>learning:</em></strong> the solo from <a href="https://youtu.be/NxFE5YOErcg?feature=shared&t=87">Cosmic</a> by Avenged Sevenfold</li>
		<li><strong><em>writing:</em></strong> a piece of hard rock/metal for a friend</li>
		<li><strong><em>playing:</em></strong> <a href="https://www.youtube.com/watch?v=MmX7a_e65uU">Prince of Persia: The Lost Crown</a></li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
    As a proponent of <a href="https://www.youtube.com/watch?v=NVGuFdX5guE">CGP Grey's theme system</a>, I spent the last few days of December trying to work out what I want my theme for 2025 to be. The coming year will be the Year of Clearing the Decks (I think I may be stealing one from Grey himself here). This will be a year of reducing my commitment load, identifying systems and routines which are no longer working for me, and trying to create time and energy for the personal projects I would like to work on. I expect to reach the end of 2025 having said "no" a whole bunch more times than usual. 
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
    2024 overall was a really great year. After a rocky start finding myself newly single, and one of my musical projects coming to an end, the year picked up steam again in the spring. I went to three weddings, attended a bunch of concerts, met my girlfriend, played at a bucket list venue, as well as some absolutely incredible shows with Ey Up Maiden, and my transition continued to be working really well for me. December passed in the usual flurry of events, social obligations, sugary foods, and burnout. January is most likely to be quite hibernatory for me, but I look forward to recovering the energy to meet the rest of the year at full steam.
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
    I have some ideas for writing projects I'd like to get out in 2025, as well as some music I'd like to write and release to the general public. I'm under few illusions about the breadth of my audience, but it would be nice to get some original work out there again, even if just to say that I've done it. Tenatively, watch this space.</p>

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
