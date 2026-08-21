---
layout: page
title: About
description: >-
    Course policies and information for CS 472/572 Unsupervised Learning.
has_toc: false
---

# About

## Course Purpose

This course introduces advanced topics in machine learning with a focus on unsupervised and self-supervised methods. Unlike courses that primarily address supervised learning, where algorithms are trained on labeled data, this course emphasizes techniques for discovering structure in unlabeled data. Students will explore clustering, dimensionality reduction, change-point detection, and modern representation learning approaches.

See [Course Information]({{ site.baseurl }}/course-information/) for term, room, and enrollment details, and the [Staff]({{ site.baseurl }}/staff/) page for instructor contact information and office hours.

## What Is Unsupervised Learning?

Most machine learning techniques you may have already encountered are *supervised*: a model learns a mapping from inputs to known outputs (labels) provided by a human, such as classifying an email as spam or predicting a house price. **Unsupervised learning** removes the labels. Given only raw, unlabeled data, the goal is to discover structure, patterns, or a compact representation of that data on its own.

This course groups the major families of unsupervised and self-supervised techniques as follows:

- **Clustering** &mdash; grouping similar data points together (e.g., k-means, spectral clustering, hierarchical clustering, density-based clustering), useful for market segmentation, document organization, and exploratory data analysis.
- **Dimensionality reduction & representation learning** &mdash; compressing high-dimensional data into a smaller set of informative features while preserving its structure (e.g., PCA, autoencoders), useful for visualization, denoising, and as a preprocessing step for other models.
- **Density estimation & anomaly/change-point detection** &mdash; modeling the distribution that generated the data (e.g., Gaussian mixture models fit via the EM algorithm) to flag unusual points or moments where that distribution shifts.
- **Generative modeling** &mdash; learning to produce new samples that resemble the training data (e.g., variational autoencoders, GANs, diffusion models).
- **Self-supervised learning** &mdash; a modern hybrid approach that creates its own "labels" from the structure of the data itself (e.g., predicting a masked word, or recognizing that two augmented views of an image come from the same source), and has become the dominant way large-scale foundation models are pretrained.

Unsupervised methods matter because labeled data is expensive and slow to produce, while unlabeled data is abundant. Being able to discover structure without hand-labeling is often the only practical way to work with the volume of data modern applications generate.

## A Brief History of Unsupervised Learning

Unsupervised techniques predate "machine learning" as a field. **Principal component analysis (PCA)**, still one of the most widely used dimensionality-reduction methods, was first described by Karl Pearson in 1901 and independently reformulated by Harold Hotelling in the 1930s.

Cluster analysis developed alongside PCA through the mid-20th century, before **k-means clustering** took its now-familiar form: Hugo Steinhaus proposed the basic idea in 1956, Stuart Lloyd developed the standard algorithm in 1957 (not published until 1982), and James MacQueen coined the name "k-means" in 1967. Around the same period, statisticians developed hierarchical and density-based clustering methods and the **expectation-maximization (EM) algorithm** (Dempster, Laird & Rubin, 1977) &mdash; a general framework for fitting probabilistic models like Gaussian mixtures when data is only partially observed, and still a core tool taught in this course.

The rise of deep learning brought unsupervised learning into representation learning: **autoencoders** learned compressed representations by reconstructing their own input, and generative modeling took off with **variational autoencoders** (Kingma & Welling, 2013), **generative adversarial networks** (Goodfellow et al., 2014), and, more recently, **diffusion models** &mdash; first proposed by Sohl-Dickstein et al. in 2015 and popularized by the denoising diffusion probabilistic models (DDPM) of Ho, Jain & Abbeel in 2020, which now underlie most state-of-the-art image and video generation systems.

In parallel, **self-supervised learning** emerged as a way to get supervised-style training signal without hand labels, by having a model predict some hidden part of its own input. This idea now underlies most modern foundation models, from word embeddings and large language models in NLP to contrastive and masked-image methods in computer vision &mdash; and is one of the newest topics covered in this course.

## Learning Outcomes

- **Quizzes and Midterm** &mdash; describe and explain foundational concepts in unsupervised and self-supervised learning; analyze problems and select appropriate algorithms; design pseudocode or workflows from models and optimization problems.
- **Weekly Assignments** &mdash; apply unsupervised learning methods to real-world datasets; evaluate algorithms using appropriate metrics and validation techniques.
- **Graduate Student Extensions** &mdash; implement core algorithms from scratch; compare implementations with open-source libraries.
- **Paper Presentations** &mdash; synthesize and critique state-of-the-art research; communicate findings effectively in written and oral formats.
- **Final Project** &mdash; design, implement, and evaluate an unsupervised or self-supervised learning system end-to-end. Graduate students must demonstrate additional novelty or technical depth.
