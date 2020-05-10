## Willkommen auf meiner Webseite

Aktuell plane ich, hier über Fotografie zu bloggen.

### Blog Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
