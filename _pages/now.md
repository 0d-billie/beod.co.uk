---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 12th March 2025.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://www.theguardian.com/books/article/2024/sep/08/want-sexual-fantasies-edited-by-gillian-anderson-review-intriguing-survey-of-desire">Want: Sexual Fantasies</a> by Anonymous, edited by Gillian Anderson</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=_UXKlYvLGJY">Severance, Season 2</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://www.youtube.com/watch?v=mGR2M2mBJXU">Satanized</a> by Ghost</li>
		<li><strong><em>learning:</em></strong> the songs from Ey Up Maiden's 2025 setlist</li>
		<li><strong><em>writing:</em></strong> D&D campaign background</li>
		<li><strong><em>playing:</em></strong> at being an adult</li>
	</ul>
</p>

<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
		The Year of Clearing the Decks continues to go well. B and I have have been continuing to tackle the house and are focusing on some fairly major reorganisations. The kitchen is more or less done, and the lounge is close to as well. We're into the "living out of piles" stage of the process, which fills me with an existential dread, but I am powering through. The work is myterious and important.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.75em; text-indent: 4ch;">
		I have been saving money since last year to switch to an amp-modelling system for my live music needs. I finally pulled the trigger late last month on a whole rig that will save my back some effort, and will hopefully sound just as good. I still need to figure out a few of the peculiarities of the Quad Cortex, but I'm enjoying the process of (re-)sculpting my sounds. As ever, finding time to focus on this is proving a challenge, but I am thoroughly enjoying myself.        
</p>
<p style="margin-top: 0.15em; text-indent: 4ch;">
		I confess I have put extremely little time into the blog post ideas I mentioned in last month's update. Part of the reason for that is that I got bogged down in writing a script that would populate and generate a skeleton of a blog post for me. It's a classic case of the work taking hours to save me seconds, but I really enjoyed dipping back into python and writing something that was actually what I need, and not just something for a coding challenge! My git server is down at the moment (planned maintenance) but I'll post the source code some time this month when it's back up.</p>

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
