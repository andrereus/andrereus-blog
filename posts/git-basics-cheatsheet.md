---
title: GIT Basics / Cheatsheet
date: 2021-06-16T18:58:05.614Z
summary: Git is a free and open source distributed version control system
  designed to handle everything from small to very large projects with speed and
  efficiency.
---
## What is GIT?

Best short and also official description:

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Benefits / Comparison:

> Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

## Setup

Download and install it from <https://git-scm.com/>

## GIT Commands

### Basic Commands

```
git status // Show the current status
git init // Initialize project folder with GIT
git add // Add changes to the stage
git commit // Commit changes in the stage to the history / log
git log // Show the commit history
```

### GIT Help

```
git help // Help Overview
git help -a // GIT Commands
git help -g // GIT Guides
```

### GIT Branching in visual form

![GIT Branching](/static/img/git-branching.png)

### Branching Commands

```
git branch // Create a branch
git checkout (in future "git switch") // Switch to a branch
git merge // Merge a branch into an other one
```

Playground for GIT Commands: <https://git-school.github.io/visualizing-git/>

## GIT Client

![GIT Client](/static/img/git-client.jpg)

Some good free GIT Clients (GUIs) are:

* <https://git-fork.com/>
* <https://www.sourcetreeapp.com/>

Optional useful Diff Tool: Beyond Compare

## Collaboration

### Collaboration (or cloud backup)

![GIT Collaboration](/static/img/git-collaboration.png)

### Hosting services

* <https://github.com/>
* <https://bitbucket.org/>
* <https://about.gitlab.com/>
* <https://azure.microsoft.com/>

### Collaboration Commands

```
git clone // Download a repository to your PC
git fetch // Download the latest content from the server
git pull // Download the latest content from the server and merge it with your local content
git push // Upload your content to the server
```

## Useful Links

* <https://help.github.com/en/articles/github-glossary>
* <https://github.github.com/training-kit/>
* <http://rogerdudler.github.io/git-guide/>
* <https://www.atlassian.com/git/tutorials/setting-up-a-repository>
* <https://try.github.io/>