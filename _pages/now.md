---
title:
layout: default
permalink: /now/
published: true
---

This is a <a href="https://nownownow.com/about">now page</a>. It was last updated on 1st August 2024.

<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	<ul>
		<li><strong><em>reading:</em></strong> <a href="https://www.waterstones.com/book/a-natural-history-of-dragons/marie-brennan/9781783292394">A Natural History of Dragons: A Memoir by Lady Trent</a> by Marie Brennan</li>
		<li><strong><em>watching:</em></strong> <a href="https://www.youtube.com/watch?v=xWlmzl2jCNs">Prehistoric Planet</a></li>
		<li><strong><em>listening:</em></strong> to <a href="https://www.youtube.com/watch?v=PpHKdfzNtAw&list=PLUOawz4pB8d2rwAGyseGk1Gmz5APzcKoE">Blood Harmony</a> by Larkin Poe</li>
		<li><strong><em>learning:</em></strong> to solo in a more bluesy style</li>
		<li><strong><em>writing:</em></strong> a musical theme for myself; poetry; letters; blogs</li>
		<li><strong><em>playing:</em></strong> <a href="https://www.youtube.com/watch?v=uHGShqcAHlQ">The Legend of Zelda: Tears of the Kingdom</a>; chess; Dungeons & Dragons</li>
		</ul>
	</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	I am hot off another year attending the Cambridge Folk Festival, and am once again fired up with desire to start a musical project. What it'll be (or even if I will while I'm in such a state of flux) is yet to be determined, though I'm leaning towards something potentially folky, or possibly a bluesy/hard rock kind of situation. Watch this space, I suppose!
</p>
<p style="margin-top: 0.15em; margin-bottom: 0.15em">
	I am DM'ing a fully homebrewed D&D campaign for a wonderful group of people, although we're in scheduling hell for a few weeks while the busy summer months pass. It's the most expansive and sandboxed campaign I've ever written, and at times it feels like the track is going down just before the train rolls over it, but it's tremendous fun.
</p>
<p style="margin-top: 0.15em">
	In other games I am still enjoying my chess, and recently got up to just shy of a 1500 rapid rating on lichess before going on quite a dramatic losing streak. My list of board games to buy/try continues to grow, even as my opportunities to play them wane.
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
