[![CircleCI](https://dl.circleci.com/status-badge/img/gh/sandro-elsweijer/padme-am-website/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/sandro-elsweijer/padme-am-website/tree/main)

# Website for ADAPTEX

Website and announcements for the ADAPTEX project.

Based on [Pelican](http://blog.getpelican.com/) and a modifed Polar theme by [CodePassenger](http://www.codepassenger.com/).

## Local Installation

* Clone ADAPTEX-website

  git@github.com:DLR-AMR/adaptex-website.git
  ```
  or
  ```
  https://github.com/DLR-AMR/adaptex-website.git
  ```
* Change to 
  ```
  adaptex-website/
  ```

* Install pelican, fabric3 and some other dependencies

  ```
  pip install -r requirements.txt
  ```

## Build 

* Run 
  ```
  pelican -s pelicanconf.py
  ```

  to generate the site locally in `output`.

  For a publication-ready version run

  ```
  pelican -s publishconf.py
  ```

  The generated site will be in `published`.


## Writing Content

Use either [Markdown](http://daringfireball.net/projects/markdown/) or HTML for new articles, as described in [Writing content](http://docs.getpelican.com/en/3.6.3/content.html).

Add new articles to `content`.

### Metadata

The required meta data for ADAPTEX announcements are:
TODO


