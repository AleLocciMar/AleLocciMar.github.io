--
layout: home
title: "Meu Blog"
---

Bem-vindo ao meu blog sobre IA e validação de LLMs!

## Últimos posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>
