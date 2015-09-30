---
layout: home
---
<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li style="text-align:left" class="on"><a href="/"><span>首页</span></a></li>
            <li style="text-align:left"><a href="/tec"><span>技术</span></a></li>
			<li style="text-align:left"><a target="_blank" href="http://beiyuu.com/"><span>beiyuu</span></a> </a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.index %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
