---
published: true
title: Intsall spesific version of laravel
layout: post
---
when i write this article the latest version of Laravel Framework is 5.2.*, but i want to install version 5.1.*.

How i can install spesific version of laravel?
Install specific version of laravel is very easy, i can do this with code below.

    composer create-project laravel/laravel forlder-name laravel-version --prefer-dist

example:

    composer create-project laravel/laravel myApp 5.1.* --prefer-dist