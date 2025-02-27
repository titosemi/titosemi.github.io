---
title: '{{ substr (replace (replace .Name "-" " ") "_" " ") 9 | humanize | title }}'
slug: '{{ substr (replace (replace .Name "-" " ") "_" " ") 9 | urlize }}'
date: '{{ .Date }}'
draft: true
toc: true
comments: true
socialShare: true
cover:
  src: /florian-klauer-mk7D-4UCfmg-unsplash.jpg
  caption: Photo by [Florian Klauer](https://unsplash.com/@florianklauer)
tags:
---
