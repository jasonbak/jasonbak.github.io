## Overview
I have been wanting to build and design my own website from scratch for some time now. Having full control over a personal photography and blog page was the initial draw to make this website. After a few paper prototypes and mid-fidelity mock-ups of the website, it turned into a way for me to realize and learn fundamentals of UI/UX fundamentals. I started coding and pivoted my design multiple times. My initial designs were cluttered and riddled with superfluous details. My iteration process was focused on making the UI as minimal as possible while conveying the same amount of information.

With [Jekyll] [jekyll], I developed seven page layouts: homepage, default, media-slideshow, note, notes-list, project, and projects-list. I set up the configuration files so that given a page with a certain set of variables, all data would be translated in HTML using the Liquid templating language. By passing in the right [YAML Front Matter] [yaml] variables into each of the pages and configuration file, Jekyll did most of the work for page creation and navigation. Given most variable content can be added and deleted using non-HTML files, the base HTML/CSS code will never have to be touched other than for the purpose of a redesign, which is useful for my [blog](/notes.html) and [project](/projects.html) posts.

I used a jQuery plug-in called [fotoroma] [fotoroma] for my [DOGE](/doge.html) page. Originally, I used fotorama for my photography page as well. I now use an easy-to-use [visual portfolio generator] [photogenerator] created by the talented [Andy Zhang] [andy]. I would highly recommend this if you need a way to showcase your photos!

I used [fontawesome.io] [fontawesome.io] for the aesthetic icons you see throughout the website.

## Copyright and License

Copyright 2013-2016 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-bare/blob/gh-pages/LICENSE) license.
