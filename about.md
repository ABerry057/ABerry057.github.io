---
layout: page
title: About
permalink: /about/
---

![Red Square]({{ site.baseurl }}/images/flavor/red_square_1801_alekseyev.jpg)

# Welcome to the *Faces of Russia*!

This project uses an Latent Dirichlet allocation (LDA) topic modeling technique for distant reading on a novel corpus of English-language texts about Russia from the 19<super>th</super> and 20<super>th</super> centuries. The corpus documents are modeled as compositions of the resulting topics and are be indexed by year to make visible any changes in frequency over the time period. The findings are presented here on a dedicated website in the style of [*Mining the Dispatch*](https://dsl.richmond.edu/dispatch/), created by Richard K. Nelson at the University of Richmond.

### The Process

1. Gather English-language texts from the 19<super>th</super> and 20<super>th</super> centuries that mention Russia*.These texts are in the public domain and are made publicly available by Project Gutenberg. In addition to the text content, the text's author and publication date are recorded.
2. Use a series of Python scripts to clean and organize the texts in a format suitable for [MALLET](http://mallet.cs.umass.edu/), the Machine Learning for Language Toolkit developed at the University of Massachusetts Amherst.
3. Using MALLET, perform LDA-based topic modeling on the corpus for eight topics, noting the
generated topics for coherence and then assigning a label to the topic that best describes the topic.
4. Organize and publish the results of the modeling on this website to explain topic
modeling as a tool for distant reading and also highlight the most interesting
topics and how these change over time (see below).
5. Maintain the corpus, cleaning, organisation, modeling, and visualization scripts and assosciated documentation in a [public repository on GitHub](https://github.com/ABerry057/facesOfRussia).

### Notes

\* For this project, for a text to be "about Russia", that text must be returned by the Project Gutenberg search function and then manually screened for relevance.

### Contact me

[alexander_berry@brown.edu](mailto:alexander_berry@brown.edu)