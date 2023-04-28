---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Swift: Reducing the Effects of Latency in Online Video Scrubbing'
subtitle: ''
summary: ''
authors:
- Justin Matejka
- Tovi Grossman
- George Fitzmaurice
tags:
- online streaming
- video
- video navigation
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
publishDate: '2023-02-14T19:24:47.382456Z'
publication_types:
- '1'
abstract: We first conduct a study using abstracted video content to measure the effects
  of latency on video scrubbing performance and find that even very small amounts
  of latency can significantly degrade navigation performance. Based on these results,
  we present Swift, a technique that supports real-time scrubbing of online videos
  by overlaying a small, low resolution copy of the video during video scrubbing,
  and snapping back to the high resolution video when the scrubbing is completed or
  paused. A second study compares the Swift technique to traditional online video
  players on a collection of realistic live motion videos and content-specific search
  tasks which finds the Swift technique reducing completion times by as much as 72%
  even with a relatively low latency of 500ms. Lastly, we demonstrate that the Swift
  technique can be easily implemented using modern HTML5 web standards.
publication: '*Proceedings of the SIGCHI Conference on Human Factors in Computing
  Systems*'
doi: 10.1145/2207676.2207766
links:
- name: URL
  url: https://doi.org/10.1145/2207676.2207766
---
