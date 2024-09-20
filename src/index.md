---
layout: base
eleventyNavigation:
    key: "Forum Home"
    order: 10
---


The 2014 DLF Forum was in Atlanta, GA, October 27-29 at the <a target="_blank" href="http://www.gatechhotel.com/">Georgia Tech Hotel & Conference Center</a>.

Participation was open to all who are interested in contributing to and playing an active part in the successful future of digital libraries, museum and archives services, and collections. The Forum featured presentations and panels, workshops, research updates, working sessions, demos, and more.

<a href="{{ '/program/' | url }}" class="btn btn-primary btn-large">Program & Schedule</a>

Use the hashtag <a target="_blank" href="https://twitter.com/search?q=%23dlfforum">#dlfforum</a> to tweet about the DLF Forum!


<h3 class="mt-5 pb-4 mb-4 border-bottom">2014 Blog Posts</h3>

{% for post in collections.posts %}
<article class="blog-post border-bottom">
<h2 class="blog-post-title"><a href="{{ post.data.url }}">{{ post.data.title }}</a></h2>
<p class="blog-post-meta">{{ post.data.date | readableDate }} in <a href="https://www.diglib.org/category/forum/">Forum</a></p>
<p>{{ post.data.blurb }}...</p>
<p>
<a href="{{ post.data.url }}" class="btn btn-outline-primary">Read More</a>
</p>
</article>
{% endfor %}

<div class="my-5 py-5">
<a target="_blank" href="https://www.diglib.org/category/forum/" class="btn btn-primary">Read More Forum Posts</a>
</div>