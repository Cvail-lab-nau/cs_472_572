---
layout: page
title: Important Information
description: General course policies and procedures that apply throughout the semester.
---

# Important Information
{:.no_toc}

General reference information that applies throughout the semester &mdash; how presentations are formatted and
graded, what the final project requires at each milestone, and other recurring policies. For grading weights,
texts, and university policies, see [About]({{ site.baseurl }}/about/); for what's due and when, see the
[Calendar]({{ site.baseurl }}/calendar/).

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Getting Help

- Office hours are posted on the [Staff]({{ site.baseurl }}/staff/) page. If you need to meet outside those
  times, email the instructor to schedule an appointment.
- Ahead of major exams, an additional review session is typically offered (often over Zoom) &mdash; watch for
  an announcement with the date, time, and link.
- If you're finding the material difficult or feeling overwhelmed, come to office hours or email to set up a
  meeting. The pace of new material generally eases in the back half of the semester.

## Preparing Before the Course Starts

A short set of videos is enough to get you ready for the material. Recommended order:

1. **Python for absolute beginners** &mdash; [video](https://youtu.be/K5KVEU3aaeQ) &mdash; useful by Week 2
2. **Python libraries refresher** &mdash; useful by Week 2
   - [NumPy](https://www.youtube.com/watch?v=QUT1VHiLmmI)
   - [Pandas](https://www.youtube.com/watch?v=2uvysYbKdjM)
   - [Scikit-learn](https://www.youtube.com/watch?v=0B5eIE_1vpU&t=188s)
3. **Math for ML** (linear algebra & statistics refresher) &mdash; [video](https://www.youtube.com/watch?v=uZeDTwWcnuY) &mdash; useful by Week 4
4. **Neural networks from scratch** &mdash; only needed once representation-learning topics begin after the
   midterm
   - [Playlist](https://youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3)
   - [Video](https://youtu.be/V_xro1bcAuA)

You don't need to use these exact videos &mdash; any comparable resource covering the same concepts is fine, as
long as you're comfortable with the material by the time it's needed.

## Midterm Exam Format

The midterm is given in person during regular class time and covers the clustering and dimensionality-reduction
material up to that point in the semester:

- Clustering I &mdash; K-means & spectral methods
- Clustering II &mdash; GMMs & the EM algorithm
- Hierarchical & density-based clustering
- PCA analysis

The exam includes both conceptual/theoretical questions and hand-simulation problems that require working
through small, illustrative examples step by step. A study handout outlining the scope of questions is posted
in the Midterm module ahead of time.

## SOTA Paper Presentations

Presentations are done in **pairs**, run **10 minutes total per group** (about 8 minutes presenting, the rest
for Q&A), and are held across two class sessions per round. There are two rounds during the semester.

**Grading (15 marks per round):**

| Component | Marks | Weight |
|:----------|:------|:-------|
| Attendance (both presentation days) | 2 | 13.3% |
| Peer evaluation | 5 | 33.3% |
| Instructor evaluation | 8 | 53.3% |

If you need to change your assigned paper, email the instructor for approval.

## Final Project

### Choosing a Topic

- The project must focus on **unsupervised machine learning**.
- Start with a **literature review**: search existing work and clearly identify your topic and direction.
- Check the availability of the core components you'll need (dataset, algorithm implementations, etc.) before
  committing to a topic.
- You're welcome to extend a capstone project or other existing project into an unsupervised-learning context.

### Overview Presentation

Worth 5 of the 40 points allocated to the Final Project. You must be present on both presentation days &mdash;
1 point is deducted per day missed without an approved absence arranged in advance. Your slides should address:

1. **Project title**
2. **Existing work** &mdash; prior code and/or papers you're building on
3. **Your novelty** &mdash; the specific idea or contribution you plan to pursue, and why
4. **Plan** &mdash; a clear path from where you are now to a finished project (a flowchart is recommended)
5. **Contribution** &mdash; how work is divided between team members
6. **Feasibility check** &mdash; can this be finished in the time available?
7. **Datasets** &mdash; what you'll use and why it's appropriate

This is an initial estimate and can be updated as the project evolves; the most important part is showing
you've found enough existing work to build on.

### Update Presentation

Worth 5 of the 40 points allocated to the Final Project. Your presentation should demonstrate concrete
progress and incorporation of prior feedback:

- **Problem & direction** &mdash; restate your problem setup with confidence
- **Progress evidence** &mdash; sample data, preliminary results, or other concrete artifacts (even if small or
  incomplete)
- **Implementation updates** &mdash; what's built so far, and what you've learned
- **Timeline** &mdash; what's done, and a forward-looking plan to the final deadline
- **Clarity** &mdash; a clear, specific, structured plan rather than vague descriptions

### Final Submission Checklist

- Slides uploaded, containing your GitHub Pages website link and GitHub repository link
- Folder named `Group<Number>_<YourFullName>_<YourProjectTitle>`
- Paper included (mandatory for graduate students)
- Code, README, `requirements.txt`/`environment.yml`, and run instructions included
- All required data pointers/paths and results/figures included
- Submitted as a folder or zip, with every teammate submitting the same file individually

Because this is end-of-semester grading, there's generally no back-and-forth to fix submission issues after the
deadline &mdash; make sure links open and code runs before you submit. Late/incorrect submissions that require
follow-up may incur a point penalty. If the grader doesn't have Canvas access, materials may also need to be
shared via a Drive folder as a backup &mdash; watch for instructions closer to the deadline.

### Grading Rubric

**Total: 30 points**

| Criterion | What's evaluated | Points |
|:----------|:------------------|:-------|
| Technical implementation & correctness | Working pipeline; sound modeling/engineering; readable, modular code | 10 |
| Experimental design & evaluation | Baselines; appropriate metrics; ablations/sensitivity; error/limitation analysis; evidence-based conclusions | 5 |
| Contribution / insight | A clearly stated "new bit" (method/system/study); justified design decisions | 5 |
| Reproducibility & documentation *(excluding GitHub)* | Run instructions; config/seeds; data paths; organized results & figure-generation scripts | 3 |
| Deliverable quality | Undergrad: website/app clarity & usability, or a concise report. Grad: paper-style write-up | 5 |
| GitHub repository | Public/shared repo with a proper README, `requirements.txt`/`environment.yml`, clean structure, and a LICENSE (mandatory for graduate students) | 2 |

Undergraduate deliverables may be a website/app (preferred) or a report; graduate deliverables must be a
paper-style write-up (a website/demo is optional). Partial credit is awarded when criteria are partially met.

### Building a GitHub Pages Site

If your deliverable includes a project website, GitHub Pages is a free way to host it:

- [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [How to Create a Free Website Using GitHub Pages (video)](https://youtu.be/o5g-lUuFgpg)
- [Example project page templates](https://github.com/topics/project-template)

## Course Evaluation Bonus

You can earn 1 bonus point by completing the [course evaluation](https://nau.edu/course_evals) near the end of
the semester. Take a screenshot of the confirmation page (showing your name and that you submitted it, but
**not** your actual responses &mdash; feedback is anonymous) and upload it to the corresponding bonus
assignment on Canvas.
