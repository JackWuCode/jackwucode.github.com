---
layout: page
title: Hello World!
tagline: Never stop trying... 
---
{% include JB/setup %}

## Who am I?

My name is Jack Wu, a programmer now working at Ctrip.
I majored in Computer Science at NJU which is a proud in my life.

You can find me at:

@Weibo [2W_continued](http://weibo.com/1921727853/profile)

@Facebook [JackWu](http://www.facebook.com/wei.wu.353250)

@Github [JackWuCode](https://github.com/JackWuCode)
    
## Blogs

I write blogs on github pages, which is a delight for guys like me who can't care less about building a website.

Topics in the posts includes computer knowledge, essays, and reviews. Recording my learning process is main  motivation for updating the blog, sharing knowledge is another one.

Enjoy your trip here.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
