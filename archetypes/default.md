---
title: "{{ replace .Name "-" " " }}"
name: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: "page"
layout: "default"
draft: true
---
