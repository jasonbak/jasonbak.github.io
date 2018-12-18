---
title: "&amp;TextEdit"
note-title: ANALYSIS OF MY PERSONAL JOURNAL OF FOUR YEARS
abstract: I've been consistently journaling since the start of my high school senior year (Sept 2014), producing around 337,000 words (or 320 pages of single-spaced 12 font) of unfiltered thoughts. This is a unique source of personal data that I used to reveal trends in my life that promote happier writing, which may be correlated to a happier life!
permalink: /notes/personal-journal-analysis
layout: note
---

I've been journaling since the start of my high school senior year (Sept 2014). The idea of capturing moments I've lived for my future self to relive excites me and the emotional freedom of writing down my thoughts is liberating. 

This consistent mindset for the past four years resulted in an amazingly thorough and equally unique source of data I leveraged to help me to answer a fundamental question I consider daily: **how can I be more happy?**

To this end, I was particularly interested in identifying trends that promote happier writing, which may be correlated to a happier life! 

At the crux of this analysis, I ran a sentiment analyzer at different granularities of journal entry groupings to obtain a sentiment score, which ranges from [-1.0, 1.0]. The higher the sentiment score, the happier the writing!

If you're interested in learning about the methodology, I include a link to a Jupyter Notebook with code and in-depth analysis at the end of this post. 

Otherwise, here are **four of the most interesting questions I sought to answer.**

---

# 1. How has my mood changed over the years?

![yearly sentiment](/assets/img/notes/yearly_sentiment.png){:class="note-photo"}

I've made efforts to incorporate more balance and people in my life since entering college in 2015, which I have felt has enabled me to enjoy life more. Thankfully, 2018 has felt like the best year of my life, so I'm glad this is reflected in my writing.

# 2. How has my mood changed over the months?

![monthly sentiment](/assets/img/notes/monthly_sentiment.png){:class="note-photo"}

This graph fits my memory quite well! Some interesting data points.

- Oct-14, Nov-14: I was incredibly stressed with college applications, preparing for science fairs, and keeping up with school. This was one of the worst periods of my life, which is reflected in the graph. I'm surprised to see sentiment is actually positive!

- Apr-15: My friends and I were delighted with our college acceptances, so we spent a lot of time hanging out and enjoying the time we had left with each other. Further, I found a church I was glad to be a part of. :)

- Jun-15: It was becoming normal to hang out with my friends, and I suppose I didn't appreciate the time we spent together as much as I should have. In retrospect, this time was wonderful because it was the first time I truly felt like I belonged to a group of friends.

- Aug-15: My last month before college. A lot of wholesome talks to wrap up this period of my life made me appreciate this month a lot. Further, college orientation at the end of this month had me incredibly excited for CMU.

- Apr-16 - Sep-16: The most sustained decrease in sentiment in the graph. My plans to study abroad this summer fell through, so I was rather discontent with goofing around back home while most of my friends were having fun at their internships. This gave me a lot of time to think about some girl trouble, which turned me into a sadboi.

- Dec-16 - May-17: This semester, I was making efforts to switch majors out of Chemistry. It started off well because I was excited to finally take actions to get out of a major I didn't enjoy. I had periods of high self-confidence quickly followed by periods of self-doubt over my technical abilities and concern with being behind my peers in coursework. 

- Sep-17 - Oct-17: Missed Chicago and my summer friends. Though, mainly I was concerned with getting another summer internship, being a great TA, and handling my courses. I felt more stable in my major and career at this point, but I chose to ignore a lot of people I cared about to maintain this stability. This made life rather draining--I burned out a bit in Oct-17, which explains the sharp decrease. 

- Dec-17: I was rather proud of what I accomplished that semester. Additionally, I got my dream internship in Seattle and was feeling fulfilled with my relationships with my family and close friends. I recall feeling like everyone around me was in a good mood, but I think that's simply because I was feeling on top of the world!

- Jan-18 - Mar-18: Was simply writing about school for most of this time period. Mar-18 was when I was most engrossed in schoolwork; sentiment dropped a bit since nothing exciting was happening. 

- Apr-18: I started my YouTube channel, which I found quite fulfilling. Further, my best friend visited me at CMU for Spring Carnival, and I was spending more time developing significant relationships at school.

- Jun-18 - Aug-18 An absolutely wonderful summer in Seattle, where I got to experience life in a way I've never done before. Shared so many unique memories with incredible people.

# 3. How is my mood correlated with the month?

![aggregated monthly sentiment](/assets/img/notes/aggregated_monthly_sentiment.png){:class="note-photo"}

This was very neat to see because the results go against my initial hunch that my best months were during the summer and my worst months were in the middle of Fall and Spring semester.

**I'm starting to recognize that this use of sentiment analysis is not necessarily a way for me to understand when the best times of my life were. Rather, it is a way for me to understand when I felt most grateful about my life.**

It was a bit sad to see the low sentiment scores for the summer months as these are the months in which I can spend more time doing the things I love and hanging out with people I care about. Thus, these are the times in which sentiment should be the highest! However, I suppose I feel worried about what work I'm accomplishing due to the lack of constant and almost-immediate feedback school provides during the rest of the year.

Gladly, I performed this analysis in May, so I was able to make efforts to be more appreciative this last summer. Thankfully, when I ran this analysis again with the new summer month entries included in the data set, the sentiment for the summer months were a lot higher than before. :)

# 4. When did I have the most to write about?

- 2015: September 25, October 20, October 29, November 11, November 14, November 21, November 23
- 2016: April 16, August 23
- 2017: July 8

On every single one of these days, I've had fulfilling and enlightening conversations. I use my journal to reflect and flesh out ideas/thoughts I stumbled upon throughout the day. Originally I thought the more time I spend alone, the more time I have to think through ideas--thus more to write about and reflect upon.

**However, I see now that through chatting with people, I have more to reflect upon and more insights to draw from the day. This is quite interesting to me because I make an effort to have time to meditate on my thoughts by myself for most days as I believe this will bolster my self-development.**

Recently, I've realized the importance of finding people whom you can communicate effectively with. Where even if either of you can't fully express your ideas, the other person understands your thought process enough to help you develop your own idea further.

With this analysis, I think it's important for me to take time out of my days to have conversations with these people.

---

Thanks for reading! As promised, here is the [Jupyter notebook with detailed analysis and code I used] [notebook]. Feel free to share any ideas or suggestions for further analysis I can do. My email is jason.j.bak (at) gmail.com

Thanks to [Wan Shen Lim] [wan] for helping structure my analyses and cleaning up my code!

[notebook]: https://github.com/jasonbak/Personal-journal-analysis/blob/master/journal_analysis.ipynb
[wan]: [https://wanshenl.me]