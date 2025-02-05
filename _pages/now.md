---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 5th February 2025.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://www.theguardian.com/books/article/2024/sep/08/want-sexual-fantasies-edited-by-gillian-anderson-review-intriguing-survey-of-desire">Want: Sexual Fantasies</a> by Anonymous, edited by Gillian Anderson</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=_UXKlYvLGJY">Severance, Season 2</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://en.wikipedia.org/wiki/Rite_Here_Rite_Now">Rite Here Right Now</a> by Ghost</li>
		<li><strong><em>learning:</em></strong> the songs from Ey Up Maiden's 2025 setlist</li>
		<li><strong><em>writing:</em></strong> D&D campaign background</li>
		<li><strong><em>playing:</em></strong> at being an adult</li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
		My Year of Clearing the Decks is off to a fairly good start. My girlfriend and I have been steadily reorgansing the house following my move-in, and while there is much plenty to do, we have also made a huge amount of progress already. January being what it is, it has been harder to <em>clear</em> my personal decks, but I am learning to be comfortable when they are not clear, and still taking time to enjoy myself and relax instead of fretting over the state of my to-do list. This is a struggle for me, but I am learning to let go a little more, and it's doing me good, I think.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
		February sees the return of band practices with Ey Up Maiden, and I have been working on learning the new (to us) material ahead of time. I have been consistently grateful for this aspect of being in a covers band: we all just need to learn the stuff ourselves and then turn up to make sure we're all playing together. It makes rehearsals a doddle. Having taken a few weeks off from guitar playing, I can feel a bit of rust that will need oiling away. And the itch for original music is growing again. Quite what form that will take, I don't yet know.
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
		I have a few creative ideas in the works still, although I'm struggling to dedicate time to the act of writing much of anything. The downtime that I've been enjoying the past few weeks has meant that my mind has been more prone to wander, and to come up with new ideas. It's always difficult to know what to pick to begin with. Everything I want to do has a significant amount of activation energy and I'm struggling to consistently get over the hump at the moment. That said, as the days grow longer and warmer, it's getting easier and easier. Continue to watch this space!</p>

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
