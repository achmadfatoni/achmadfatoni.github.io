---
published: true
title: Git ignore global
layout: post
---
# Declare the global .gitignore file
    git config --global core.excludesfile ~/.gitignore_global
    
    # Create the file
    touch .gitignore_global
    
    # write ignore file
    vim .gitignore_global