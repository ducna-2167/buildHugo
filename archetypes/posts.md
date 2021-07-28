---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
author: Anh Duc Nguyen
categories:
- Personal
- Thoughts
tags:
- software
- html
year: "{{ dateFormat "2006" .Date }}"
month: "{{ dateFormat "2006/01" .Date }}"
---

This is my first post so it may not be so amazing

<!--more-->