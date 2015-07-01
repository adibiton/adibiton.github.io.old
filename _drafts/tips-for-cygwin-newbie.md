---
layout: 
title: tips for cygwin newbie
categories: []
tags: []
published: True

---

I started a new "hobby" - using cygwin. To whom not familiar with it, it is a Unix-like envirment and cli for windows.
I'm working hard tweaking it (it's pain in the ass sometime...) and after hours spending around it I would like share few of my findings:

 - git (actually gitconfig) - the global configuration file of git for window machines (usually under %HOME%) can be found under ~/.gitconfig  - in case you don't find the file you can run the following:
  `git config --global --edit`
Therefore using git under cygwin requires from you to copy the content of gitconfig from your windows machine.
