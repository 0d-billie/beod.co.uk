---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 16th July 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://en.wikipedia.org/wiki/Utopia_Avenue">Utopia Avenue</a> by David Mitchell</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=BtytYWhg2mc">The Acolyte</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://thelastdinnerparty.bandcamp.com/album/prelude-to-ecstasy"> Prelude to Ecstasy</a> by The Last Dinner Party</li>
		<li><strong><em>learning:</em></strong> to carve out time for myself</li>
		<li><strong><em>writing:</em></strong> a theme for myself; poetry; letters; blogs</li>
		<li><strong><em>playing:</em></strong> <a href="https://www.youtube.com/watch?v=uHGShqcAHlQ">The Legend of Zelda: Tears of the Kingdom</a>; chess; Dungeons & Dragons</li>
		</ul>
	</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	I am DM'ing a fully homebrewed D&D campaign for a wonderful group of people, although we're in scheduling hell for a few weeks while the busy summer months pass. It's the most expansive and sandboxed campaign I've ever written, and at times it feels like the track is going down just before the train rolls over it, but it's tremendous fun.
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	In other games I am still enjoying my chess, and recently got up to just shy of a 1500 rapid rating on lichess before going on quite a dramatic losing streak. My list of board games to buy/try continues to grow, even as my opportunities to play them wane.
</p>
<p style="margin-top: 0.15em">
	I am temporarily living in the company of a real piano again, and it has been a true joy to play and compose on the instrument again. When my purchase completes and I'm settled, it'll be time to start looking at how best to fit an upright into my life.
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
