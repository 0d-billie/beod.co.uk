---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 2nd December 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong><a href="https://gayprideshop.co.uk/products/the-queer-parent-everything-you-need-to-know-from-gay-to-ze-book">The Queer Parent: Everything You Need to Know From Gay to Ze</a> by Lotte Jeffs and Stu Oakley</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=6y0E1pL5wws">Mr Robot</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://en.wikipedia.org/wiki/Rite_Here_Rite_Now">Rite Here Right Now</a> by Ghost</li>
		<li><strong><em>learning:</em></strong> the solo from <a href="https://youtu.be/NxFE5YOErcg?feature=shared&t=87">Cosmic</a> by Avenged Sevenfold</li>
		<li><strong><em>writing:</em></strong> a piece of hard rock/metal for a friend</li>
		<li><strong><em>playing:</em></strong> Dungeons & Dragons </li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
    Illness befell me, and I was not able to keep up with much of my ambition for November. Running and writing both fell by the wayside, and some days I found myself incapable of little more than lying in bed coughing. I'm on the mend, but still not back to 100% health. I'm doing battle with the NHS to try and refresh a childhood asthma diagnosis and get an inhaler that will actually work when I'm having an attack (oh yes, I'm getting asthma attacks again). November felt like a hard month. December will also be busy, and tiring. We are deep into the midst of short days and dark nights, and I'm ready to clear the decks from my calendar again.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
    I signed up to Bluesky, and I'm actually having a great time. Microblogging never truly hooked me as a format, but it's fun over there. Engagement is high, most people are friendly, and it's generally a place that people are happy to just be silly and have a good time. It's very refreshing. My profile is linked behind the butterfly at the bottom of this page.
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
    The flat purchase did indeed get cancelled, and B and I have set a date for moving in together next year. As our lives become more and more integrated, however, I find myself without as much time in the evenings to focus on my extra little projects and suchlike. I'm trying to be more protective of that time, and to ensure I still get the opportunity to practice playing the guitar, writing stories, prepping D&D games, and so forth. But with a girlfriend and two additional children in my life, time is necessarily shorter. I'm still learning how to carve out dedicated me time that doesn't detract from my work time (I'm writing this between tickets). Watch this space as I inevitably fail to make any meaningful progress on this.
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
