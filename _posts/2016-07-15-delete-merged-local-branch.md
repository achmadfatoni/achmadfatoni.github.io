---
published: true
title: Delete all merged git branch
layout: post
---
git branch --merged | grep -v "\*" | grep -v master | grep -v dev | xargs -n 1 git branch -d