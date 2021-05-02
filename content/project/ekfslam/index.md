---
title: Invariant EKF Slam
summary: 
tags:
- robotics
date: "2019-12-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/abhitoronto/Invaraint_EKF_SLAM
url_code: ""
url_pdf: "https://github.com/abhitoronto/Invaraint_EKF_SLAM/blob/master/AER_1513_Project_doc.pdf"
url_slides: ""
url_video: "https://youtu.be/4vqj0PBAAgs"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
Completed as part of a graduate course at the University of Toronto | MATLAB. 

Simultaneous Localization and Mapping (SLAM) has been a highly research problem and the techniques that solve it have undergone huge improvements in the last two decades. One of the most popular technique is the Extended Kalman filtering (EKF) approach, but it suffers from the problem of inconsistency. Out of the many ways developed to solve this problem, the Invariant Kalman filter based approach is quite interesting and offers provable mathematical guarantees. This project implements an Invariant EKF-SLAM method by representing the robot pose as a member of  the special euclidean Lie group. The normalized estimation error square (NEES) metric is also computed which reveals that the given implementation, though works, is over-confident. The inconsistency appears during the process of loop closure and experiments are suggested for further investigation.