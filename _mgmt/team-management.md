---
title: Team Management
permalink: /mgmt/team
toc: true
toc_sticky: true
---

<!-- This page is a WIP -->

For now this page is just a collection of useful resources.

## Practices

- [Writing Strategies](/writing-strategies): I found it useful and scalable to write Strategies for your teams, to support them to address specific challenges.

## Related Posts

{% for post in site.categories['Team Management'] %}- {{ post.date | date: "%B %e, %Y" }} - <a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a>
{% endfor %}