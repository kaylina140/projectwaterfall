
## Welcome to Project Waterfall
A student research project as a part of EECS 499 at the University of Michigan, Project Waterfall sets out build a storytelling AI for video games.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
