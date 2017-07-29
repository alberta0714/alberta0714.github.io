---
layout: html
---
<div>
        <div class="cate-bar"><span id="cateBar"></span></div>
		
        <ul class="artical-list">
		{% for cate in site.categories %}
			<li>[{{cate[0]}}]</li>
			{% for post in cata[0] %}
				{{ post }}
			{% endfor %}
		{% endfor %}
		</ul>
		
		<ul class="artical-list">
        {% for post in site.categories.tec %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
                {{ post.description }}
            </li>
        {% endfor %}
        </ul>
		<ul class="artical-list">
        {% for post in site.categories.smalltalk %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
                {{ post.description }}
            </li>
        {% endfor %}
        </ul>
</div>