---
layout: post
section-type: post
title: Modifying and Unmodifying a { Personal} Jekyll blog
category: tech
tags: [ 'tutorial' ]
---



There is a difference between staging and modifying. When you use 'git add .', and you end up adding to many files. That means you have staged the files by adding them. Let say, you had not added the files, the file will still show up as 'modified', when you run a git status.
So, don't let that confuse you.
It may not be necessary to run a 'git reset HEAD nameoffile.extension', unless you added it at which point the file wil show up in green as staged instead of red, for un-staged.

You will at some point, if you have not run into making a modification you did not intend to make. And pretty, git will show you that the name of said file is now, 'modified'. I too, asked myself how do I un-modify, said file, aka how to Unstage a staged file.

To un-modify a modified file, you can run ''$ git checkout --nameoffile.extension',  when you 'git status', again the file will no longer show up.
