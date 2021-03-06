---
title: Projects
project-title: Analysis of my personal journal
abstract: I've been consistently journaling since the start of my high school senior year (Sept 2014), producing around 337,000 words (or 320 pages of single-spaced 12 font) of unfiltered thoughts. This is a unique source of personal data that I used to reveal trends in my life that promote happier writing, which may be correlated with a happier life!
recognitions: none
recognitions-2: none
recognitions-3: none
recognitions-4: none
recognitions-5: none
technologies: Python | NLTK | textgenrnn | TextBlob | Stanford CoreNLP 
collaborators: Wan Shen Lim
time-active: May 2018 @ Carnegie Mellon University
photo-path: /assets/img/projects/list_journal-analysis.png
status: completed
permalink: /projects/journal-analysis
layout: project
---

I've been consistently journaling since the start of my high school senior year (Sept 2014), producing around 337,000 words (or 320 pages of single-spaced 12 font) of unfiltered thoughts. 

This is a unique source of personal data which we can use to reveal trends in my life. Wan and I were particularly interested in identifying trends that promote happier writing, which may be correlated with a happier life!

There is a non-trivial amount of processing to be done on the journals as I have journals for different years in different file types and formats. I have a single .docx file for 2014, 2015, and 2016; a single .tex file for 2017; and my 2018 entries have all been in Dropbox Paper. Each of these different file formats have a different scheme of formatting journal entries. Wan and I needed to consider a data structure to make analysis possible across varying time frames, i.e., weeks, months, years. At the same time, our data format needs to be compatible with various natural language processing libraries.

We experimented with TextBlob, NLTK's VADER, and Stanford's CoreNLP sentiment analyzers. We tested all three on a random sample of my journal entries and found that VADER was the best at accurately reflecting my sentiment.

We also used RNNs and LSTMs via textgenrnn to generate Jason-like entries.

Lately, I’ve been incorporating meta-data about my days into each daily entry. Currently, this isn’t much data to warrant analysis, but in the future I’d like to perform similar analysis on this meta-data.

* <i class="fas fa-pencil-alt" aria-hidden="true"></i> [Key lessons](/notes/personal-journal-analysis)
* <i class="fa fa-book" aria-hidden="true"></i> [Jupyter notebook] [Jupyter]
* <i class="fab fa-youtube"></i> [Video] [YouTube]
* <i class="fab fa-github" aria-hidden="true"></i> [GitHub repository] [GitHub]

[Jupyter]: https://github.com/jasonbak/Personal-journal-analysis/blob/master/journal_analysis.ipynb
[YouTube]: https://www.youtube.com/watch?v=7V4cIrVxhA8
[GitHub]: https://github.com/jasonbak/Personal-journal-analysis