# Stealing NYC Planning Labs' Website

This repo houses a fork of the NYC Planning Labs Jekyll blog/website, for experimentation, and possible adoption as the McKinely Park Development Council Website.

### Jekyll Foundation

This package is based on [Jekyll Foundation](https://github.com/core77/jekyll-foundation/), which lets you quickstart your Jekyll (v3) project with Zurb Foundation for Sites (v6, sass).

[Getting started](https://github.com/core77/jekyll-foundation/wiki/Getting-started)

## Installation

Run each of the following steps to get the site up and running.

1. `git clone git@github.com:tonyatoms/MPDC_web.git`
2. `cd MPDC_web`
3. `bundle install`
4. `bundle exec jekyll serve`

To dramatically reduce the build time, there are two commands that you can run instead of `./serve`:

* `./serve-fast`: This will eliminate all of the blog posts and the search index, but generates all other pages
* `./serve-blog`: This will eliminate all but the latest three blog posts, but keeps the rest of the site intact.

You should be able to see the site at: http://127.0.0.1:4000/site/

