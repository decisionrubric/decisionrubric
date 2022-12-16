---
title: "Posts"
permalink: /posts/
---

[Posts](#posts) &nbsp; 

Posts are published on an irregular cadence.

{% include base_path %}

<!-- ## <span style="color: #3b5998">Posts </span> -->
<h2 id="posts">
Posts
</h2>
{% for post in site.posts reversed %}
  {% include post-snippet.html %}
{% endfor %}

