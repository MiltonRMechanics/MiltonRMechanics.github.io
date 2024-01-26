.Rproj.user
.Rhistory
.RData
.Ruserdata
rmarkdown-website-template.Rproj
# privefl.github.io

This is my githup repo for creating and hosting my personal website on GitHub. 

I moved from [Jekyll](https://jekyllrb.com/) to [R Markdown](http://rmarkdown.rstudio.com/rmarkdown_websites.html), mostly because I'm an R enthusiast and an RStudio fanatic :').

I now use [Jekyll Now](https://github.com/privefl/blog/tree/gh-pages) for my blog.
name: "YOURNAME" /* CHANGE HERE */
output_dir: "."
navbar:
  title: "YOURNAME" /* CHANGE HERE */
  type: inverse
  left:
    - text: "Home"
      icon: fa-home
      href: index.html
    - text: "About"
      icon: fa-user 
      href: about.html
    - text: "CV"
      icon: fa-file-pdf-o
      href: cv.html
    - text: "Blog"
      icon: fa-rss
      href: https://YOURGITHUB.github.io/blog/ /* CHANGE HERE */
  right:
    - text: "Contact me"
      icon: fa-envelope-o
      href: mailto:YOUREMAIL /* CHANGE HERE */
    - text: "GitHub"
      icon: fa-github
      href: https://github.com/YOURGITHUB /* CHANGE HERE */
output:
  html_document:
    theme: cosmo
    highlight: textmate
    ---
title: "About me"
---

## Header

Say more about you here.
---
title: "CV"
---

<a href="CV.pdf#" class="download" title="Download CV as PDF">Download CV</a>			

## Header

Say more about your CV here.
---
title: "Welcome to my website!"
---

You're up and running!
