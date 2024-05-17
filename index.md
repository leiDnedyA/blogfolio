---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

My name is Ayden Diel, and I'm a CS undergrad student and freelance fullstack dev.

I started tinkering with computers when I was a kid, and never stopped. Right now I'm
working towards my CS undergrad degree, but on top of that 
- I'm a freelancer
- I run the UMass Boston CS Club 
- I do research
- [I build cool stuff!](https://www.qrpigeon.pics/)

Stuff I like: 
- Linux
- Neovim / Vim



### Check out some of my posts!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
