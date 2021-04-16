---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Research Student - Robotics and AI
    company: University of Toronto Robotics Institute
    company_url: 'https://robotics.utoronto.ca/'
    company_logo: 
    location: Toronto
    date_start: '2019-09-01'
    date_end: ''
    description: |2-
        I am working as a researcher at STARS lab under the supervision of Dr. Jonathan Kelly. For my current project, I am working on a learning-based algorithm to perceive in-hand object slip using inexpensive [barometric tactile sensors](https://ieeexplore.ieee.org/document/6877681). A [publication](https://arxiv.org/abs/2103.13460) on this topic, submitted to [IROS 2021](https://www.iros2021.org/), is currently under review. During the course of my masters, I have received the [NSERC Canadian Graduate Scholarship](https://www.nserc-crsng.gc.ca/students-etudiants/pg-cs/cgsm-bescm_eng.asp) and the [Vector Scholarship in AI](https://vectorinstitute.ai/scholarship/).
        
  - title: Software Engineer - Autonomous Driving
    company: Nvidia Inc.
    company_url: 'https://developer.nvidia.com/drive'
    company_logo: 
    location: New Jersey
    date_start: '2018-01-10'
    date_end: '2018-08-15'
    description:  |2-
      Worked in a team of 25 machine learning engineers, led by Dr. Urs Muller, creating an end-to-end autonomous driving solution. (Linux, C++, Git, Bash)
      * Contributed to the re-architecture of Nvidia’s Driving Simulation application in order to enable simulation on the GPU cluster and standardize the benchmark testing of DriveNets across the company
      * Developed a prototype of a model-predictive vehicle controller in C++ that runs on the DRIVE Xavier platform
      * Contributed to Nvidia DriveWorks SDK which meant overcoming extensive quality checks designed for MISRA compliance

       
  - title: Systems Engineer - DRIVE platform
    company: Nvidia Inc.
    company_url: 'https://developer.nvidia.com/drive'
    company_logo: 
    location: Seatle
    date_start: '2017-05-01'
    date_end: '2017-08-30'
    description:  |2-
      Worked on Nvidia's DRIVE hardware stack, aiming to revolutionize the Automotive computing industry (C++, bash, python)
      * Contributed to the Embedded PDK for the DRIVE automotive hardware products, that now serve giants like Tesla and Audi.
      * Re-implemented the Tegra flashing software for the DRIVE computing platforms to meet strict Automotive standards and to gain MISRA compliance.
      * Architected the incremental Tegra flashing functionality, reducing the average OS flash time to half.

design:
  columns: '1'
---
