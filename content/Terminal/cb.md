---
section_id: Terminal
nav_order: 7
title: CollectionBuilder Terminal Commands
---

**First time repository created**
`bundle install`
When first cloning or creating a repository, all the gems (libraries), sub-dependencies, and any other necessary dependencies which need to be setup within the development environment. This only needs to be done if the Gemfile changes or when setting up the project within a new environment, such as a new machine.
<br>
A Gemfile.lock file is also created, which locks the versions of the installed gems. This guarantees consistency across different environments. 
  

**Starting dev server on local computer**
`bundle exec jekyll s` This will start a development server on your local computer. It serves - or makes available - the html, css, javascript that creates the CB website. (Note: this is different from the documentation site, which uses "jekyll s")
<br>  

**Deploying Final Version to Site**
See CollectionBuilder Documentation, under [Deploy/Jekyll Build](https://collectionbuilder.github.io/cb-docs/docs/deploy/build/)  
<br>

**Stop Server** 
`CTRL + C` 
(This is the same for most command line programs)  

**Additional documentation**
General information for [Generating the site](https://collectionbuilder.github.io/cb-docs/docs/repository/generate)
[Video within CSV Walkthrough documentation](https://collectionbuilder.github.io/cb-docs/docs/walkthroughs/csv-walkthrough/#13-run-the-bundle-exec-jekyll-serve-command-to-generate-your-site-video-version)

