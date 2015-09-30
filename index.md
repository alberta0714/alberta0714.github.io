---
layout: home
---
<div>
        <div class="cate-bar"><span id="cateBar"></span></div>
		
        <ul class="artical-list">
        {% for post in site.categories.index %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
<<<<<<< HEAD
</div>
=======
		###丁丁宝贝，要准备做前端 了！~~ 
    </div>
    <div class="aside">
    </div>
</div>
>>>>>>> 4d2ed2a4d28e105f5ffb7413000d2665cf4075da
