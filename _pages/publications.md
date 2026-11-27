---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% assign pubs = site.publications | sort: "date" | reverse %}

{% assign groups = "journal|Peer-Reviewed Journal Articles,conference|Conference Proceedings" | split: "," %}
{% for g in groups %}
{% assign parts = g | split: "|" %}
<h2>{{ parts[1] }}</h2>
{% for post in pubs %}{% if post.category == parts[0] %}
<div class="list__item">
  <article class="archive__item">
    <h3 class="archive__item-title"><a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a></h3>
    <p>Published in <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}</p>
    <p style="font-size: smaller">{{ post.cite }}</p>
    <p><a href="{{ post.doi }}">Access paper here</a></p>
  </article>
</div>
{% endif %}{% endfor %}
{% endfor %}

<h2>Works Under Review / In Revision</h2>

* *Analyzing Russia–Ukraine War on Twitter using Network Science.* In revision: [Heliyon](https://www.cell.com/heliyon/home) [IF: 3.6, SJR: Q1]
* *Adapting gamification to develop computational thinking in a learning environment.* In revision: Journal of Computers in Education [IF: 4.7, SJR: Q1]
* *LARA-Event: Lexicon-Audited Robust Adaptive Fusion for Event-Centric Opinion Mining.* Under review: [Applied Intelligence](https://link.springer.com/journal/10489) [IF: 3.5, SJR: Q2]
* *Linking Emojis to User Perceptions: SUS Insights with an LLM-Based Hybrid Approach.* In draft: [Behaviour & Information Technology](https://www.tandfonline.com/journals/tbit20) [IF: 4.2, SJR: Q1]
