---
section: Terminal
nav_order: 7
title: CollectionBuilder Terminal Commands
---

**First time repository created**<br>
`bundle install`<br>
When first cloning or creating a repository, all the gems (libraries), sub-dependencies, and any other necessary dependencies which need to be setup within the development environment. This only needs to be done if the Gemfile changes or when setting up the project within a new environment, such as a new machine.
<br><br>
A Gemfile.lock file is also created, which locks the versions of the installed gems. This guarantees consistency across different environments. 
<br><br>  

**Starting dev server on local computer**<br>
`bundle exec jekyll s` <br>This will start a development server on your local computer. It serves - or makes available - the html, css, javascript that creates the CB website. (Note: this is different from the documentation site, which uses `jekyll s`)
<br><br>  

**Deploying Final Version to Site**<br>
When the version will be built locally and/or self-hosted, see CollectionBuilder Documentation, under [Deploy/Jekyll Build](https://collectionbuilder.github.io/cb-docs/docs/deploy/build/)  
<br>

**Stop Server**<br>
`CTRL + C` <br>
(This is the same for most command line programs.)  
<br>

**Additional documentation**<br>
General information for [Generating the site](https://collectionbuilder.github.io/cb-docs/docs/repository/generate), and a video version within the [CSV Walkthrough documentation](https://collectionbuilder.github.io/cb-docs/docs/walkthroughs/csv-walkthrough/#13-run-the-bundle-exec-jekyll-serve-command-to-generate-your-site-video-version)
<br><br>


{% include alert.html text="**Note**: explanatory text on this page about a command (how it functions, what it does) primarily came from [GitHub Copilot](https://github.com/features/copilot) or [CollectionBuilder documentation](https://collectionbuilder.github.io/cb-docs/)" align="left" color="info" %}

