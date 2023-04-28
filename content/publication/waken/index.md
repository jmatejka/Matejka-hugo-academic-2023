---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Waken: Reverse Engineering Usage Information and Interface Structure from
  Software Videos'
subtitle: ''
summary: ''
authors:
- Nikola Banovic
- Tovi Grossman
- Justin Matejka
- George Fitzmaurice
tags:
- pixel-based reverse engineering
- tutorials
- videos
categories: []
date: '2012-01-01'
lastmod: 2023-02-14T14:24:47-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-14T19:24:47.130539Z'
publication_types:
- '1'
abstract: We present Waken, an application-independent system that recognizes UI components
  and activities from screen captured videos, without any prior knowledge of that
  application. Waken can identify the cursors, icons, menus, and tooltips that an
  application contains, and when those items are used. Waken uses frame differencing
  to identify occurrences of behaviors that are common across graphical user interfaces.
  Candidate templates are built, and then other occurrences of those templates are
  identified using a multi-phase algorithm. An evaluation demonstrates that the system
  can successfully reconstruct many aspects of a UI without any prior application-dependant
  knowledge. To showcase the design opportunities that are introduced by having this
  additional meta-data, we present the Waken Video Player, which allows users to directly
  interact with UI components that are displayed in the video.
publication: '*Proceedings of the 25th Annual ACM Symposium on User Interface Software
  and Technology*'
doi: 10.1145/2380116.2380129
links:
- name: URL
  url: https://doi.org/10.1145/2380116.2380129
---
