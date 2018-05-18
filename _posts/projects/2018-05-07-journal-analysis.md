---
title: Projects
project-title: Analysis of my personal journal
abstract: I have been consistently journaling since the start of high school senior year (Sept 2014), producing around 283,000 words (or 350 pages) of unfiltered thoughts. This is a unique source of personal data which can be used to reveal trends in my life. We were particularly interested in identifying trends that promote happier writing, which may be correlated to a happier life!
recognitions: none
recognitions-2: none
recognitions-3: none
recognitions-4: none
recognitions-5: none
technologies: Python | NLTK | textgenrnn | TextBlob | Stanford CoreNLP 
collaborators: Wan Shen Lim
time-active: May 2018 @ Pittsburgh, PA
photo-path: /assets/img/projects/list_journal-analysis.png
status: completed
permalink: /projects/journal-analysis
layout: project
---

I've been consistently journaling since the start of my high school senior year (Sept 2014), producing around 283,000 words (or 350 pages) of unfiltered thoughts.

This is a unique source of personal data which we can use to reveal trends in my life. Wan and I were particularly interested in identifying trends that promote happier writing, which may be correlated to a happier life!

There is a non-trivial amount of processing to be done on the journals as I have journals for different years in different file types and formats. I have a single .docx file for 2014, 2015, and 2016; a single .tex file for 2017; and my 2018 entries have all been in Dropbox Paper. Each of these different file formats have a different scheme of formatting journal entries. Wan and I needed to consider a data structure to make analysis possible across varying time frames, i.e., weeks, months, years. At the same time, our data format needs to be compatible with various natural language processing libraries.

We experimented with TextBlob, NLTK's VADER, and Stanford's CoreNLP sentiment analyzers. We tested all three on a random sample of our journal entries, and found that VADER was the best at accurately reflecting our protagonist's sentiments.

We also used RNNs and LSTMs via textgenrnn to generate Jason-like entries.

This was a neat project to work on as I was able to reflect on my last few years and recall events with an added layer of rough data analysis. 

Lately, I’ve been incorporating meta-data about my days into each daily entry. Currently, this isn’t much data to warrant analysis, but in the future I’d like to perform similar analysis on this meta-data.

* <i class="fa fa-book" aria-hidden="true"></i> [Jupyter notebook] [Jupyter]
* <i class="fab fa-youtube"></i> [Video] [YouTube]
* <i class="fab fa-github" aria-hidden="true"></i> [GitHub repository] [GitHub]

[Jupyter]: https://github.com/jasonbak/Personal-journal-analysis/blob/master/journal_analysis.ipynb
[YouTube]: https://www.youtube.com/watch?v=7V4cIrVxhA8
[GitHub]: https://github.com/jasonbak/Personal-journal-analysis