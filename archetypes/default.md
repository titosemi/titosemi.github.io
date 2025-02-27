---
title: '{{ replace (replace .Name "-" " ") "_" " " | humanize | title }}'
date: '{{ .Date }}'
draft: true
--- 
