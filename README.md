# r-bookdown

CUNY Data 607 Spring 2018 Project

## Project Outline

Using data from the [fivethirtyeight](http://fivethirtyeight.com/) website, our class will develop tutorials to demonstrate the capabilities of the functions in the [tidyverse package](https://www.tidyverse.org/) using R. These tutorials will be compiled in a book using [bookdown R package](https://cran.rstudio.com/web/packages/bookdown/index.html). The [short book](https://bookdown.org/yihui/bookdown/) introduces how to use bookdown R package in writing books.

1. Each class member is expected to contribute an example tutorial to the final project.  
2. Although each student is expected to prepare a tutorial for a specific function, collaboration on the overall project is encouraged and allowed.
2. The student body as a whole will be responsible for the organization and content of the project, collaborating in an unsupervised manner to self-determine the best presentation of the final product.

## Project Planning

Please check out the "[Projects](https://github.com/cunydata607/r-bookdown/projects)" tab in GitHub and click on the "[tidyverse r-bookdown project](https://github.com/cunydata607/r-bookdown/projects/1)" and **create a new card to let the group know what you are working on**.  

Also please **add items to the [Book_Structure.md file](https://github.com/cunydata607/r-bookdown/blob/master/Book_Structure.md) and add your name next to items you want to workj on**.

**Questions and issues** should be added to the [Issues](https://github.com/cunydata607/r-bookdown/issues) tab.

## Working in Github

Github is a web based graphical interface based off of Git: a command line tool for version control. If you're new to Github, learn more through the links below!

For beginners, start here: [Good explanation of what GitHub is for](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/)

And then here: [Basic GitHub Website Instructions](https://guides.github.com/activities/hello-world/)

Here is a great [Github fork and pull request video tutorial](https://www.youtube.com/watch?v=yr6IzOGoMsQ) that goes through a basic workflow in GitHub.

Another source for beginners: [Happy Git and GitHub for the useR](http://happygitwithr.com/)

Video from GitHub: [GitHub for Beginners](https://resources.github.com/webcasts/GitHub-for-beginners/?utm_source=announcement&utm_medium=email&utm_campaign=gh-for-beginners-follow-up&elqTrackId=5e3f26814be04d1f81c4865816946a24&elq=384f5c0a35964e25a0108bbfbd78b5b3&elqaid=424&elqat=1&elqCampaignId=165)

This tutorial: [Try Git](https://try.github.io/levels/1/challenges/1) gives a good explanation of the steps to contributing to a GitHub repo and hands on experience with using Git in the command prompt. Even if you want to use the GitHub website or GitHub Desktop, it will help you understand what the various terms mean.

If you're already acquainted with the basics, [Github provides tons of training videos on advanced topis on YouTube](https://www.youtube.com/user/GitHubGuides/videos).

## Working with Bookdown Files

The formatting and structure of the book are created in the index.Rmd file. The filename must remain exactly as index.Rmd or it will not be recognized by bookdown as the index file. The index file should contain setup code and a description of the project only.  Each chapter must be in a separate file in the same R Project in order to 'build' the book using bookdown.  I have already created a file for each chapter.  They must be numbered sequentially (or alphabetically) in order to build in the correct order.  

I have also added code to create a biblilogrpahy in the index file that I copied out of a sample bookdown project.  

To create an inline reference use square brackets and \@R- followed by the package name. The package name must also be added to the bibliography code in the index.Rmd file (if it isn't already there).

For example: 
[@R-tidyr]

The reference will show at the bottom of the page and also at the end in the references chapter.

To learn more about how to work with bookdown you can check out this book written by the package author.  
<https://bookdown.org/yihui/bookdown/>

## Kanban Board (Projects)

I have created a Kanban Board project on the "[Projects](https://github.com/cunydata607/r-bookdown/projects)" tab in GitHub named "[tidyverse r-bookdown project](https://github.com/cunydata607/r-bookdown/projects/1)" that I suggest we use to help organize the distribution of tasks and keep track of who is working on what.  There are basic instructions about how to use the project board in the project itself on the left side, so check it out! **Please create a new card to let the group know what you are working on**.  

## Adding Contributions to the Repository

There are basically two ways to contribute to the repository.

1. If you are an admin, you can make changes and commit them directly to the cunydata607/r-bookdown repo. 
2. If you are not an admin, you can fork the repo, make changes to your forked version and submit a pull request that one of the admins will need to approve and merge with the master branch of the cunydata607/r-bookdown repo.  

If you are not fimiliar with how to use GitHub please see the links above for lots of great tutorials and info.  I particularly recommend [this video](https://www.youtube.com/watch?v=yr6IzOGoMsQ) to understand a basic GitHub workflow.

## Slack channel communication

Further communication among class members may also be found at https://data607.slack.com in the #tidyversebook channel.

## Required Packages

Please add any additional packages needed to this list and make sure you have these installed if you want to build the book on your computer.

https://github.com/cunydata607/r-bookdown/blob/master/Required_Packages.md
