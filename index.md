---
layout: page
title: الرئيسية
tagline:
---
{% include JB/setup %}
 <div class="posts">
    {% for post in site.posts %}
      <div class="post py3">
        <a href="{{ post.url | prepend: site.baseurl }}" class="post-link"><h3 class="h1 post-title">{{ post.title }}</h3></a>
		 <p class="post-meta">{{ post.date | date_to_string }}</p>
         <p class="post-summary">
          {% if post.summary %}
            {{ post.summary }}
          {% else %}
            {{ post.excerpt }}
          {% endif %}
        </p>
		<br/>
      </div>
    {% endfor %}
  </div>
