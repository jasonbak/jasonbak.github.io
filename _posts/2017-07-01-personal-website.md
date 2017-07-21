---
title: Projects
project-title: Personal website written from scratch
abstract: This website serves mainly as a professional portfolio for potential employers and a photography portfolio to potential clients. I include a blog using Jekyll in hopes it will provide some positive change in their lives. I outline most of the technologies and libraries used to build this website for guidance to others who would like to learn about them for their own purposes.
recognitions: none
recognitions-2: none
recognitions-3: none
recognitions-4: none
recognitions-5: none
technologies: Jekyll | HTML/CSS | JavaScript
collaborators: none
time-active: Jul 2017 @ Chicago, Illinois
photo-path: /assets/img/projects/list_personal-website.jpeg
status: in-progress
permalink: /projects/personal-website
layout: project
---

I have been wanting to build and design my own website from scratch for some time now. Having full control over a personal photography and blog page was the initial draw to make this website. After a few paper prototypes and mid-fidelity mock-ups of the website, it turned into a way for me to realize and learn fundamentals of UI/UX fundamentals. I started coding and pivoted my design multiple times. My initial designs were cluttered and riddled with superfluous details. My iteration process was focused on making the UI as minimal as possible while conveying the same amount of information.

With [Jekyll] [jekyll], I developed seven page layouts: homepage, default, media-slideshow, note, notes-list, project, and projects-list. I set up the configuration files so that given a page with a certain set of variables, all data would be translated in HTML using the Liquid templating language. By passing in the right Front Matter variables into each of the pages and configuration file, Jekyll did most of the work for page creation and navigation. Given most variable content can be added and deleted using non-HTML files, the base HTML/CSS code will never have to be touched other than for the purpose of redesign, which is was useful for my [blog](/notes.html) and [project](/projects.html) posts.

I used a jQuery plug-in called [fotoroma] [fotoroma] for my [photography](/photography.html) and [DOGE](/doge.html) pages. I'm currently thinking of ways to drastically improve the photography page.

* [Mid-fi mock-up v1](/doc/bak_jason_website_v1.pdf)
* [Mid-fi mock-up v2](/doc/bak_jason_website_v2.pdf)

[fotoroma]: http://fotorama.io/
[jekyll]: https://jekyllrb.com