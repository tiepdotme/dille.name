---
id: 939
title: Organizing PostScript Pages
date: 2007-11-30T07:51:07+00:00
author: Nicholas Dille
layout: post
permalink: /blog/2007/11/30/organizing-postscript-pages/
categories:
  - Nerd of the Old Days
tags:
  - LaTeX
  - PostScript
---
The following command creates a new PostScript document containing `n` pages per page:<!--more-->

`psnup -l -<n> <file>.ps <file>.<n>.ps`