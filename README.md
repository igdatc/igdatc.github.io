# igdatc.github.io

A website for the people of IGDATC by the people of IGDATC.

located at [https://igdatc.github.io/](https://igdatc.github.io/)

## Helpful Links
* [Github Pages](https://pages.github.com/)
* [Github Pages Metadata](https://help.github.com/en/articles/repository-metadata-on-github-pages)
* [Jekyll](https://jekyllrb.com/docs/)
* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Copy as Markdown](https://github.com/yorkxin/copy-as-markdown)

## Getting started
* There are detailed instructions at the Jekyll link above, but if you are on a mac and already familiar with .git, you may be able to just check out this repo, and run `bundle exec jekyll serve` from the Terminal inside the resulting directory.
* See the github "Issues" for a list of things to work on, or create a new issue!

## redirect_from

We use [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from) for redirections as necessary.
`redirect_to` is the preferred method for redirection. Adding this to the header creates a 301 redirection and the pages do not get generated. This is preferred over deleting old pages because it perserves the route.