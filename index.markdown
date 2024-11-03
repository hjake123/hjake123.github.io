---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: "Home"
permalink: /
---

Welcome! I'm **hyperlynx**, and this is is my homepage. It's mostly a link board right now, but I plan to start hosting some short stories and other projects here as well.

## Links

[About Me](/about.markdown)

[Reactive Mod Homepage](https://www.curseforge.com/minecraft/mc-mods/reactive)

[Reactive Mod Discord](https://discord.gg/zHe3wVBmbR)

[Github](https://github.com/hjake123)

[Tumblr](https://hyper-lynx.tumblr.com/)

## Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>