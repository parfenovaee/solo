---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Version control. Git"
subtitle: ""
summary: ""
authors: [Parfenova Elizaveta]
tags: []
categories: []
date: 2022-05-06T19:55:31+03:00
lastmod: 2022-05-06T19:55:31+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit: [**Unsplash**](featured.jpg)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---


---
**Introduction**.

This post will introduce you to the term "version control system". You'll learn about git, how it works, and what you need to do to get started.

**Contents**.

1. What is a version control system
2. Where version control systems are used
What git is and how it works
4. Working with Git
5. A critique of git

**What is a version control system?

A version control system (also defined as "version control system", from Version Control System, VCS or Revision Control System) is software to facilitate working with changing information. Version control system allows you to store several versions of the same document, to return to earlier versions if necessary, to find out who made this or that change and many other things.

**Where are version control systems used?

Such systems are most commonly used in software development to store the source code of the program being developed. However, they can also be successfully applied in other areas where large numbers of continuously changing electronic documents are handled. In particular, version control systems are used in Computer Aided Design Systems, usually as part of Product Data Management (PDM) systems. Version control is used in Software Configuration Management Tools.

**What is git and how does it work?

Git is the absolute leader in popularity among modern version control systems. It is a developed project with active support and open source. The git system was originally developed in 2005 by Linus Torvalds - the creator of the Linux operating system kernel. Git is used for version control in a huge number of software development projects, both commercial and open source. The system is used by many professional software developers. It works perfectly on different operating systems and can be used with many integrated development environments (IDEs).
Version control allows you to see changes at any stage of development and go back to any point.  But that's not quite the case. Changes are saved as commits. In Russian, it's a commit. You make an initial commit to save the initial state of the project, and then for each change. This works like a snapshot of the state.

In addition, git allows you to send data to a remote server. Not only the finished version is sent, but all of the snapshots are sent, so anyone on the team can see the history of changes. Each snapshot should have a comment, so it's easier to work with git and make it easier to understand.

Development in git is focused on providing high performance, security and flexibility of the distributed system.

**Working with git**

Getting started with git requires a few steps.  First, you'll need to create a GitHub account.  Next, set up and configure any features and options you may need via a terminal. The next step is to create a remote repository (or clone it) and connect the system to it. Basically, git is ready to go. You can move the files you need locally (on the system) to the correct directories and write commands that coordinate the local repository. The commands are: - git add .  - save changes to the current directory; -git commut - explain changes; - git push - send to the central repository. There is one other command that is better to run before the previous three. This is the git pull command, which loads changes made by someone else (or from another system). 

**Summary**.

Git has often been criticized for being difficult to learn because some terms may be unfamiliar to newcomers and others may have different meanings. This being said, git is a very powerful system and offers many great features. It will take some time to learn, but the skills learned will help team members work much faster.
