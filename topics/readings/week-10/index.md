---
layout: page
title: "Week 10"
# What topic does this page belong to?
group: readings
# Relative ordering of lessons within a topic
order: 10
#script: /javascripts/mypage.js
#scripts:
#  - /javascripts/one.js
#  - /javascripts/two.js
---


{% include toc.md %}

# Week 10
{:.ui.dividing.header.no_toc}

## Reading

- [Git Command Overview][git-commands]
- [Using Git on GitHub][using-github]

## Lab

This week's homework has two parts. The first part is on Autolab:

- [ColLab](https://autolab.andrew.cmu.edu/courses/15131-f16/assessments/collab)

For the second part of this assignment, you will get practice with forking a
GitHub repo and making a pull request. The repo you will be working with is the
[git-practice] repo that you've seen in lecture a couple times. Do the
following:

- Sign in to your Github account and visit
  <https://github.com/cmugpi/git-practice>.
- Fork the git-practice repo.
- Clone your fork of the git-practice repo.
- On a new branch (named what you want), edit the files of the repo so that you
  fill in an appetizer, main course, and dessert.
- Commit your changes and push them to your fork.
- Make a pull request to cmugpi's git-practice repo. For the title of your pull
  request, put your Andrew ID.

[git-practice]: https://github.com/cmugpi/git-practice
[using-github]: {{ "/topics/git/using-github/"    | prepend: site.baseurl }}
[git-commands]: {{ "/topics/git/git-commands/"    | prepend: site.baseurl }}
