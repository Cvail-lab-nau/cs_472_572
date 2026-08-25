---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

## Monthly Calendar

The same 16-week schedule laid out by calendar date instead of by week number. Each class day (Tuesday/Thursday)
shows the week number and that week's topic; see [Course Content]({{ site.baseurl }}/course-content/) for full
weekly details and materials.

<div class="month-legend">
  <span class="month-legend-item"><span class="month-legend-swatch is-class"></span>Lecture</span>
  <span class="month-legend-item"><span class="month-legend-swatch is-presentation"></span>Presentation</span>
  <span class="month-legend-item"><span class="month-legend-swatch is-exam"></span>Exam</span>
  <span class="month-legend-item"><span class="month-legend-swatch is-holiday"></span>Holiday / No Class</span>
</div>

**Note:** Thanksgiving Day (Thursday, November 26, 2026) falls within Week 15, which is currently listed as
"Final Project Presentation Day 1/Day 2" in [Course Content]({{ site.baseurl }}/course-content/). Confirm against
NAU's official Fall 2026 academic calendar and adjust the Week 15&ndash;16 presentation schedule if needed.

{% include monthly-calendar.html %}
