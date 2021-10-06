---
position: enter position name
location: enter business location
start: enter start month and year
end: enter end month and year (or 'Present')
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "Write a description here"
---
