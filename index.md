# link to portfolio
<ul>
<li>
<a href="https://github.com/bim2016/Portfolio/">Portfolio</a>
</li>
</ul>

# draft blog post
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>