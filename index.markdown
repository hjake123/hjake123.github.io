---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: "Home"
permalink: /
---

Welcome! I'm **hyperlynx**, and this is is my homepage. It's mostly a link board right now, but I plan to start hosting some short stories and other projects here as well.

## Links

[Reactive Mod Homepage](https://www.curseforge.com/minecraft/mc-mods/reactive)

[Reactive Mod Wiki](https://github.com/hjake123/reactive/wiki)

[Github](https://github.com/hjake123)

## Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('devhyperlynx', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Support me',
    'floating-chat.donateButton.background-color': '#794bc4',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>