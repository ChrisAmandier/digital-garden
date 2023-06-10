---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to my digital garden! 🍄👻🛸



<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
 <strong> This is the digital garden of Chris Amandier.</strong> I'm a paranormal researcher, writer, artist, and the host of <a href="https://www.buriedsecretspodcast.com">Buried Secrets Podcast</a>. I write about <a class="internal-link" href="/paranormal">paranormal</a> and <a class="internal-link" href="/occult">occult</a> weirdness, <a class="internal-link" href="/paranormal">paranormal</a> and <a class="internal-link" href="/history">history</a>, <a class="internal-link" href="/tech">tech</a>, <a class="internal-link" href="/creativity">creativity</a>, and <a class="internal-link" href="/nostalgia">nostalgia</a>.
</p>

<p>
</p>

## Browse <a class="internal-link" href="/topic">topics</a>
<a class="internal-link" href="/paranormal">paranormal</a> - <a class="internal-link" href="/tech">tech</a> - <a class="internal-link" href="/creativity">creativity</a> - <a class="internal-link" href="/ghost">ghost</a> - <a class="internal-link" href="/nostalgia">nostalgia</a> - <a class="internal-link" href="/occult">occult</a> - <a class="internal-link" href="/liminality">liminality</a> - <a class="internal-link" href="/ufo">ufo</a> - <a class="internal-link" href="/folklore">folklore</a> - <a class="internal-link" href="/fae">fae</a> - <a class="internal-link" href="/digital-gardens">digital gardens</a> - <a class="internal-link" href="/zettlekasten">zettlekasten</a> - <a class="internal-link" href="/urban-legend">urban legend</a> - <a class="internal-link" href="/history">history</a>

## About this garden
If you want my more refined (though still ever-evolving) thoughts, check out my <a href="https://www.buriedsecretspodcast.com/listen/">podcast</a> or <a href="https://www.buriedsecretspodcast.com/tag/blog/">blog</a>. These are my notes. They're written for me, first and foremost, but I've decided to share them with the public to 1) force myself to take better, more rigorous notes and revisit them often, and 2) share what I'm learning about with fellow researchers.

✔️ If you decide to reference any of my research, please be sure to link back to me.

✍️ Since these notes are written for myself first and other audiences second, you can expect to find plenty of broken links to unshared notes, bits that may make sense to no one but myself, typos, and other mistakes.

🧠 That's all as it should be—I'm here to learn in public, and I'm always refining my thoughts and ideas.

✉️ If you have thoughts or feedback, feel free to write to me at buriedsecretspodcast@gmail.com.



## Recently updated notes

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 15 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<p>Here are all the notes in this garden, along with their links, visualized as a graph.</p>

{% include notes_graph.html %}

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
