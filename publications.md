---
layout: default
title: Publications
permalink: /publications/
---

# Publications

*For a complete list of my publications, please check out my [Google Scholar]({{ site.github.tm_google_scholar }}).*

{% assign pubs_by_year = site.data.publications | group_by: "year" | sort: "name" | reverse %}
{% for year_group in pubs_by_year %}
## {{ year_group.name }}

{% for pub in year_group.items %}{% include pub.html %}{% endfor %}
{% endfor %}

## Some Notes

<div class="pub">
<div class="pub-title"><a href="https://drive.google.com/file/d/1y4hQ03PmEr2AW5VTsts7JJQoSPZywLaW/view?usp=sharing">Improving Zero-Shot Reasoning Using Dynamic Non-Verbal Tokens</a></div>
<div class="pub-authors"><strong>Tanya Marwah</strong>, Zhili Feng, Lester Mackey, Nicolo Fusi, David Alvarez-Melis</div>
</div>
