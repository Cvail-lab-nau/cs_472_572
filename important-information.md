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
[Course Content]({{ site.baseurl }}/course-content/).

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Getting Help

- Office hours are posted on the [Staff]({{ site.baseurl }}/staff/) page. If you need to meet outside those
  times, email the instructor to schedule an appointment.
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

## Participation in the Quizzes

Participation in quizzes and in-class activities makes up 10% of your total grade.

- There is no fixed or announced schedule for these activities &mdash; they may take place on any class day,
  without advance notice.
- Activities may include short in-class coding/scoring exercises, or in-class work focused on solving problems,
  analysis, or discussion.
- Grading is not based on how well or how efficiently you complete the activity &mdash; it is based on whether
  you were present and actively participated.
- Each activity is graded on a binary basis: 1 if you were present and submitted the activity, 0 if you were
  not.
- Most activities require an in-class submission, which serves as the record of your participation.
- If circumstances require completing an activity outside of class instead of in person, this will be
  accommodated on a case-by-case basis.

<p style="color:#c0392b;"><strong>If you miss a class and therefore miss a participation activity, per
department policy, a resulting zero cannot be changed without documented evidence. Simply telling me you were
unwell, without a medical note or equivalent documentation, is not sufficient on its own. Acceptable evidence
(non medicals) includes, for example, an email you sent me notifying me of your absence and the reason for it.
Mistakes in grading are possible, if you believe you received a zero in error, you'll need to be able to show
evidence (such as an email) that you sent, or that you had a valid, documented reason for missing that specific
class.</strong></p>

<p style="color:#c0392b;"><strong>This policy applies specifically to class days on which a participation
activity was assigned.</strong></p>

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

### Expected Depth of Content

The SOTA Paper Presentation asks each group to develop and demonstrate a deep technical understanding of a
research paper in the field, rather than producing a surface-level summary.

The rubric above covers grading criteria for the presentation itself, but does not fully capture the expected
depth of content. Presentations should go beyond a basic slide summary and should include:

- **In-depth methodology** &mdash; explain not just what the paper does, but how and why its methods work; walk
  through the core technique rather than restating the abstract
- **Relevant equations** &mdash; include the key equations from the paper (or equivalent notation) to
  substantiate your explanation of the methodology, not prose alone
- **Novelty** &mdash; clearly articulate what is new or different about this paper's contribution compared to
  prior work
- **Problem statement** &mdash; state the specific problem or limitation the paper addresses
- **Proposed solution** &mdash; explain how the paper's approach solves that problem
- **Datasets** &mdash; describe the dataset(s) used for evaluation
- **Results and graphs** &mdash; present the paper's key results, including its figures/graphs, and explain what
  they show
- **Your own analysis** &mdash; provide your own critical assessment of the methodology, results, and
  presentation, including any limitations you identify; this should go beyond restating the authors' claims

**Presentation style:** Presenters are expected to be interactive and engaged with the audience, not reading
directly from slides or notes. You should understand the paper deeply enough to explain it in your own words
and respond to questions &mdash; this is a demonstration of understanding, not a recitation.

**Detailed rubric (used for peer & instructor evaluation):**

Each criterion is scored 0&ndash;5 using the scale below, then totaled.

| # | Criterion | What to look for |
|:--|:----------|:------------------|
| 1 | Problem fit | Why clustering (unsupervised) is appropriate: task & context clear |
| 2 | Novelty | What's new vs. k-means/GMM/spectral/DBSCAN/HDBSCAN/hierarchical: key idea stated |
| 3 | Method clarity | Steps precise; similarity/distance choice justified; key params (k, &epsilon;/MinPts, linkage, graph k/&sigma;) explained; complexity noted |
| 4 | Setup | Datasets (synthetic + real) reasonable; baselines strong; metrics (ARI/NMI/AMI, silhouette, purity) appropriate |
| 5 | Results insight | Correct metric reading; clear visuals (dendrograms/embeddings); takeaways beyond numbers |
| 6 | SOTA comparison | Fair head-to-head; when/why it wins or fails (density variation, high-dim, scalability) |
| 7 | Limits & failure modes | Assumptions, sensitivity (params, noise, chaining, graph bias), when not to use |
| 8 | Reproducibility & ethics | Code/data & hyperparams; runtime/memory; notes on bias/privacy for unsupervised grouping |
| 9 | Slide clarity | Clean pipeline diagram; readable plots/legends; proper citations; logical flow |

**Scoring scale:**

| Score | Description |
|:------|:-------------|
| 5 | Excellent: complete, clear, insightful, and technically correct |
| 4 | Strong: minor gaps or small clarity issues |
| 3 | Adequate: covers basics; some unclear/shallow parts |
| 2 | Weak: important gaps; unclear or partially incorrect |
| 1 | Poor: major gaps/misunderstandings |
| 0 | Missing/not attempted |

Full rubric document: [Presentation Rubric]({{ site.baseurl }}/Fall_2026/Files/CS%20472_572_%20Paper%20presentation%20Rubric_%20UnderGrad.docx)

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
