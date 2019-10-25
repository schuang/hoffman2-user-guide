# Hoffman2 User Guide (experimantal)

[![Build Status](https://travis-ci.com/schuang/hoffman2-user-guide.svg?branch=master)](https://travis-ci.com/schuang/hoffman2-user-guide)

[![pipeline status](https://gitlab.com/huangsc/hoffman2-user-guide/badges/master/pipeline.svg)](https://gitlab.com/huangsc/hoffman2-user-guide/commits/master)

## How to update the contents

- The ./source directory contains all of the source files:
  - configuration file for Sphinx
  - All .rst (restructuredText) files are the texts for the pages, organized by chapters
- See Sphinx's manual

## Continguous integration

- Travis CI is used for contiguous integration, i.e. to rebuild the web pages when there is a change.
- When a commit enters the master branch, the rebuilding the web pages is triggered. Usually it takes a few minutes to complete.
- The build status is displayed by the rectangular icons on the top of this page.




