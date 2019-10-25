# Hoffman2 User Guide (experimantal)

Travis CI: [![Build Status](https://travis-ci.com/schuang/hoffman2-user-guide.svg?branch=master)](https://travis-ci.com/schuang/hoffman2-user-guide)

Gitlab Pipeline: [![pipeline status](https://gitlab.com/huangsc/hoffman2-user-guide/badges/master/pipeline.svg)](https://gitlab.com/huangsc/hoffman2-user-guide/commits/master)

## How to update the contents

- The ./source directory contains all of the source files:
  - configuration file for Sphinx
  - All .rst (restructuredText) files are the texts for the pages, organized by chapters

See [Sphinx's documentation](http://www.sphinx-doc.org/en/master/) for details

## Continuous integration

- Use continuous integration to rebuild the web pages when there is a change.
- When a commit enters the master branch, rebuilding is automatically triggered. Usually it takes a few minutes to complete.
- CI is supported by Travis CI (travis.yml) and Gitlab pipeline (gitlab-ci.yml).
- The CI build status is displayed by the rectangular badges on the top of this file.



