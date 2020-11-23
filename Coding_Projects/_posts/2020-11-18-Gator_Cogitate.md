---
layout: sub1
title: Gator Cogitate
description: Python program that retrieves and analyzes statistics of a GitHub Repository.
created: In-class spring 2019
dateShort: 2020-11-06
tag: 99% Complete
type: post
mainpage: True # Whether it should appear on my homepage
mediumDescription: Written during a Software engineering class in 2020 by the entire class, this project is a free and open source tool written in Python. It is designed to evaluate the level of contributions for members of a GitHub repository. GatorCogitate generates a score for members based on a variety of metrics.
---
<h3> Github: </h3> [(link)](https://github.com/GatorCogitate/cogitate_tool)<br>
Written during a Software engineering class in 2019 by the entire class, this
project is a free and open source tool written in Python. It is designed to
evaluate the level of contributions for members of a GitHub repository.
GatorCogitate generates a score for members based on a variety of metrics.
The user interacts with GatorCogitate through the CLI (Command Line
Interface)

  The main portion of my work on this project was for the CLI that
  GatorCogitate uses. The CLI uses argparse to take in arguments from the
  command line. There are four required arguments, the rest have default values
  and can be added if the user wishes to.

  The four required ones are:
  <ol>
    <li>link to the target github repository</li>
    <li>github user token -to allow PyGitHub to access repo data</li>
    <li>The repository's name including root directory if in an organization</li>
    <li>Whether to merge extra usernames -different usernames may get logged if users commit on multiple different wifi/lan connections</li>
</ol>
