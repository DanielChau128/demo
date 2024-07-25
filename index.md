---
title: Home
---

# Mama's Favourites!

{% include figure.html img="istockphoto-1350259361-612x612.jpg" alt="intro image here" caption="Food" width="75%" %}

We are a family-run business serving only the best Italian and Mediterranean dishes in Birmingham

Established over 20 years ago by our saviour of food, Head Chef Michael beckett, we bring a relaxed atmosphere to ensure you can immerse yourself in our food.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [Github](https://github.com/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
