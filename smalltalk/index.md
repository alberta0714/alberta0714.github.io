---
layout: html
---
<div>
		<ul class="artical-list">
        {% for post in site.categories.smalltalk %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
                {{ post.description }}
            </li>
        {% endfor %}
        </ul>
</div>