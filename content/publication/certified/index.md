---
title: "Certifiably Optimal Monocular Hand-Eye Calibration (MFI'20)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Emmett Wise
- Matthew Giamou
- Soroush Khoubyarian
- admin
- Jonathan Kelly

date: "2020-10-26T00:00:01Z"
doi: "10.1109/MFI49285.2020.9235219"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-26T00:00:01Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication:  In 2020 IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems (MFI)
publication_short: In MFI 2020

abstract: Correct fusion of data from two sensors requires an accurate estimate of their relative pose, which can be determined through the process of extrinsic calibration. When the sensors are capable of producing their own egomotion estimates (i.e., measurements of their trajectories through an environment), the `hand-eye' formulation of extrinsic calibration can be employed. In this paper, we extend our recent work on a convex optimization approach for hand-eye calibration to the case where one of the sensors cannot observe the scale of its translational motion (e.g., a monocular camera observing an unmapped environment). We prove that our technique is able to provide a certifiably globally optimal solution to both the known- and unknown-scale variants of hand-eye calibration, provided that the measurement noise is bounded. Herein, we focus on the theoretical aspects of the problem, show the tightness and stability of our convex relaxation, and demonstrate the optimality and speed of our algorithm through experiments with synthetic data.

tags: [Convex Optimization, Sensor Calibration]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: IEEE
  url: https://ieeexplore.ieee.org/abstract/document/9235219

url_pdf: 'https://arxiv.org/pdf/2005.08298'
url_code: 'https://github.com/utiasSTARS/certifiable-calibration'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/BdjGBvuaqVo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
# - example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
