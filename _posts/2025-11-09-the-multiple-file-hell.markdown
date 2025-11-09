---
layout: post
author: juanestebanagudelo
title: The Multiple File Hell
date: 2025-11-09 12:38:37
categories: blog, data
---

# The Multiple File Hell

## Why this post?

I have worked with multiple companies that manage from mid- to high data volumes and one of the most common issues I have seen is too many unexpert data engineers writing thousands of low size datafiles. It happens from financial institutions to logistics one.

Sometimes is hard to get a good assumption of how many files should my dataset be splitted. It depends of the format, the way the data is partitioned and the application. Unfortunately sometimes the engineer don't take care of this or even it doesn't matter.

