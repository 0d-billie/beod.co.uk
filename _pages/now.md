---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 2nd September 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://en.wikipedia.org/wiki/Mistborn:_The_Hero_of_Ages">Mistborn: The Hero of Ages</a> by Brandon Sanderson</li>
		<li><strong><em>watching:</em></strong> House MD</li>
		<li><strong><em>listening:</em></strong> to <a href="https://www.youtube.com/watch?v=vvvvZeK4Ecs&list=PLxA687tYuMWhOiau-ePBBnRUZMfW5J-Vk">Life is But A Dream</a> by Avenged Sevenfold</li>
		<li><strong><em>learning:</em></strong> the solo from <a href="https://youtu.be/NxFE5YOErcg?feature=shared&t=87">Cosmic</a> on the above album</li>
		<li><strong><em>writing:</em></strong> a musical theme for myself; poetry; letters; blogs</li>
		<li><strong><em>playing:</em></strong> Dungeons & Dragons</li>
		</ul>
	</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
    The house-purchasing process proceeds at its usual glacial pace. The draft deed of variance for my leasehold extension is with my solicitors now, so the main hold-up appears to have been removed and I can make some actual progress towards buying a place. That said, the process still remains a complete black box mystery, and while the string is definitely shorter, the answer to "how long until you have the place" continues to be "how long is a piece of string?"
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	I'm getting better at putting down the tracks for each D&D session as they occur. I need to spend some time in uffish thought to figure out what the consequences of the previous session are, and how best to continue this wildly branching narrative. A set-up I thought would take 1-2 sessions per in-game day has actually taken 5 sessions to get to the late evening of one day, with the possibility of more shenanigans before the characters sleep. The lesson in underestimating the amount of screwing around players like to do has been well and truly learned.
</p>
<p style="margin-top: 0.15em">
    August was typically busy, and I'm trying to get back into my usual routines now after festivals, gigs, holidays, and time spent with Bee. I always find September to be a bit of a slog, so I'm keeping a close watch on my mental health to see if I fall into any familiar, negative patterns.
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
