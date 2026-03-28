---
title: "Projects and Ongoing Interests"
permalink: /projects/
---

This page brings together a mix of things I’m building, exploring, and returning to over time. Some are technical projects, some are tied to hobbies and personal interests, and some sit somewhere in between. A few are small experiments; others, like BackBy, are growing into more polished projects with a clearer public shape.

## Projects

These range from practical software ideas to small technical experiments in automation, app development, and tools shaped by real-world use.

{% assign sorted_projects = site.projects | sort: "order" %}
{% for project in sorted_projects %}
- [{{ project.title }}]({{ project.url | relative_url }}): {{ project.excerpt | default: project.description | strip_html }}
{% endfor %}

## Interests

- [Bicycles]({{ '/interests/bicycles/' | relative_url }}): My bikes, setups, and small details I care about.
- [Charity Work]({{ '/interests/charity-work/' | relative_url }}): Organizations and causes I've supported through volunteer or fundraising work.
- [Cycling Routes]({{ '/interests/cycling-routes/' | relative_url }}): Routes, ride ideas, and places worth returning to.
- [Games I'm Playing]({{ '/interests/games/' | relative_url }}): Notes on the games I'm currently spending time with.
