

## How to gh_pages + xaringan slides

- Create a repo with xaringan slide and the following files:
    + xaringan_example.rmd, your xaringan slide
    + index.md, for the homepage of github page, see the index.md for an example.
- In rstudio, knit the xaringan slides.
- Push everything to github
- Setup github pages
    + Settings - Github Pages- source: master branch 
    + Optional: choose a jekyll theme)

Done, the slides can be viewed online at https://{account}.github.io/{repo_name}/{xaringan_slide_filename}
