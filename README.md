---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CS 472/572 Unsupervised Learning
---

# CS 472/572: Unsupervised Learning
{: .fs-9 }

Northern Arizona University &middot; School of Informatics, Computing, and Cyber Systems &middot; Spring 2026
{: .fs-5 .text-grey-dk-000 }

Welcome! This course introduces advanced topics in machine learning with a focus on unsupervised and
self-supervised learning. Students will explore clustering, dimensionality reduction, change-point detection,
and modern representation learning approaches. See [About]({{ site.baseurl }}/about/) for the full course
purpose, learning outcomes, and policies.
{: .fs-5 }

## Quick links

- [About]({{ site.baseurl }}/about/) &mdash; course information, purpose, learning outcomes, texts, and policies
- [Schedule]({{ site.baseurl }}/schedule/) &mdash; the weekly meeting and office-hours schedule
- [Calendar]({{ site.baseurl }}/calendar/) &mdash; weekly topics and course materials
- [Staff]({{ site.baseurl }}/staff/) &mdash; instructor contact information and office hours
- [Announcements]({{ site.baseurl }}/announcements/) &mdash; the latest course announcements

## Latest announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements limit:3 %}
{{ announcement }}
{% endfor %}

[See all announcements &rarr;]({{ site.baseurl }}/announcements/)
