---
layout: default
title: title here
---

Looking for a tech meetup in South Jersey?  
Here are a few you might be interested in:

* **South Jersey Python and Web Development** - Hammonton, NJ
* **Cape May Technology Meetup** - Cape May Court House, NJ
* **Full Stack Javascript** - Cherry Hill, NJ 

Here is some of our recent activity:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Contact

Have a question or want to submit new content to this page?
Email albert.crowley@tcg.com or [submit a pull request](https://github.com/sjtechmeetup/sjtechmeetup.github.io).
