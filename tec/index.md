---
layout: home
---
<div>
        <div class="cate-bar"><span id="cateBar"></span></div>
		
        <ul class="artical-list">
        {% for post in site.categories.tec %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
</div>