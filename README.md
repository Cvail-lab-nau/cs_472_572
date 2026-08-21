---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CS 472/572 Unsupervised Learning
---

<div class="hero" markdown="1">

# CS 472/572: Unsupervised Learning
{: .hero-title }

Northern Arizona University &middot; School of Informatics, Computing, and Cyber Systems &middot; Spring 2026
{: .hero-tagline }

Welcome! This course introduces advanced topics in machine learning with a focus on unsupervised and
self-supervised learning. Students will explore clustering, dimensionality reduction, change-point detection,
and modern representation learning approaches.
{: .hero-lede }

[Read the full course description &rarr;]({{ site.baseurl }}/about/){: .btn .btn-primary .hero-cta }

</div>

## Quick links

<div class="quick-links-grid">
  <a class="quick-link-card accent-indigo" href="{{ site.baseurl }}/about/">
    <span class="quick-link-icon" aria-hidden="true">&#128218;</span>
    <span class="quick-link-title">About</span>
    <span class="quick-link-desc">Course purpose, unsupervised learning primer, and learning outcomes</span>
  </a>
  <a class="quick-link-card accent-teal" href="{{ site.baseurl }}/schedule/">
    <span class="quick-link-icon" aria-hidden="true">&#128197;</span>
    <span class="quick-link-title">Schedule</span>
    <span class="quick-link-desc">The weekly meeting and office-hours schedule</span>
  </a>
  <a class="quick-link-card accent-amber" href="{{ site.baseurl }}/course-content/">
    <span class="quick-link-icon" aria-hidden="true">&#128209;</span>
    <span class="quick-link-title">Course Content</span>
    <span class="quick-link-desc">Weekly topics and course materials</span>
  </a>
  <a class="quick-link-card accent-teal" href="{{ site.baseurl }}/staff/">
    <span class="quick-link-icon" aria-hidden="true">&#128100;</span>
    <span class="quick-link-title">Staff</span>
    <span class="quick-link-desc">Instructor contact information and office hours</span>
  </a>
  <a class="quick-link-card accent-indigo" href="{{ site.baseurl }}/important-information/">
    <span class="quick-link-icon" aria-hidden="true">&#128204;</span>
    <span class="quick-link-title">Important Information</span>
    <span class="quick-link-desc">Presentation formats, final project guidance, and other policies</span>
  </a>
  <a class="quick-link-card accent-amber" href="{{ site.baseurl }}/announcements/">
    <span class="quick-link-icon" aria-hidden="true">&#128227;</span>
    <span class="quick-link-title">Announcements</span>
    <span class="quick-link-desc">The latest course announcements</span>
  </a>
</div>

## Latest announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements limit:3 %}
{{ announcement }}
{% endfor %}

[See all announcements &rarr;]({{ site.baseurl }}/announcements/)
