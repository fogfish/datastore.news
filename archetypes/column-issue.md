---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true
description: ""
tags: ["{{ .File.Dir | path.Dir | path.Base }}"]
issue: 1
---
