---
layout: home
title: CS 472/572 Unsupervised Learning
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CS 472/572 Unsupervised Learning
---

# CS 472/572: Unsupervised Learning

Course website for **CS 472/572: Unsupervised Learning**, Northern Arizona University, Spring 2026.
Instructor: Dr. Khondker Fariha Hossain.

This course introduces advanced topics in machine learning with a focus on unsupervised and self-supervised
methods, including clustering, dimensionality reduction, and modern representation learning approaches.

- [About](about.md) &mdash; course policies, grading, and texts.
- [Calendar](calendar.md) &mdash; weekly topics and materials.
- [Schedule](schedule.md) &mdash; lecture and office-hours times.
- [Staff](staff.md) &mdash; instructor contact information.
- [Announcements](announcements.md) &mdash; course announcements feed.

---

## Repository layout

This site is built with the [Just the Class](https://github.com/kevinlin1/just-the-class) Jekyll template,
which extends [Just the Docs](https://github.com/just-the-docs/just-the-docs), and is published via GitHub
Pages at <https://cvail-lab-nau.github.io/cs_472_572/>.

- `_config.yml` &mdash; site-wide settings (title, URL, theme).
- `about.md`, `staff.md`, `schedule.md`, `calendar.md`, `announcements.md` &mdash; top-level pages.
- `_staffers/` &mdash; instructor/TA profiles, rendered on the Staff page.
- `_modules/` &mdash; weekly topics, rendered on the Calendar page.
- `_schedules/` &mdash; weekly lecture/office-hours grid, rendered on the Schedule page.
- `_announcements/` &mdash; course announcements feed.
- `Spring_2026/` &mdash; lecture slides, notes, and assignment materials linked from the calendar.

> **Note:** `Spring_2026/Midterm/` contains actual exam and solution files that are excluded from git via
> `.gitignore` since this repository is public. Do not remove that exclusion.

## Local development

This site requires no special Jekyll plugins and runs on GitHub Pages' standard Jekyll compiler.

```
bundle install
bundle exec jekyll serve
```

See GitHub's guide on [testing GitHub Pages sites locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
for more details.
