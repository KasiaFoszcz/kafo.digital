---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
dateTo: {{ .Date }}
draft: true
image: /images/projects/....png
summary: &summary |
  This is summary.
description: *summary
categories: Projects
tags:
  - UX

showInHome: false
homeOrder: 0
testimonial:
  showInHome: true
  author:
    name: John Doe
    url: https://www.linkedin.com/in/john-doe
    role: CEO
    short: John
    company: Doe Co.
  content: |
    This is testimonial content.
---
