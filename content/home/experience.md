---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

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
  - title: Computing Scholar Graduate Intern
    company: Lawrence Livermore National Laboratories
    company_url: 'https://www.llnl.gov/'
    company_logo: llnl-logo
    location: Livermore, California
    date_start: '2023-05-15'
    date_end: '2023-08-18'
    description: |2-
      * Develop Autoscaling mechanism for ML and HPC Workflows and Cloud Environments (AWS, GCP)
      * Enable Autoscaling into HPC frameworks such as Flux Framework with Cloud
      * Enable HPC and Cloud Computing convergence (Deploying lightweight kubernetes instances with Flux in nested mood)
      * Develop tools to automate the deployment and elasticity of HPC Apps and the cloud
      * Tools and Technologies: Python, AWS API, BOTO3, Terraform, Bash

  - title: Graduate Student Researcher
    company: The University of Texas at Arlington
    company_url: 'https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse'
    company_logo: uta_logo
    location: Texas
    date_start: '2019-09-01'
    date_end: ''
    description: |2-
      * Optimize resource usage of microservice applications in the cloud computing 
      * Develop Resource Manager on top of kubernetes for microservices  
      * Identify root cause of the resource bottlenecks of microservices  
      * Develop Reinforcement Learning Agents to improve task completion time in mobile computation offloading
      
  - title: Software Engineer
    company: Goava Sales Intelligence AB
    company_url: 'https://www.goava.com/en/'
    company_logo: goava-g
    location: Dhaka, Bangladesh
    date_start: '2018-01-01'
    date_end: '2018-07-31'
    description: |2-
      * Accelerated development phase and improved business of the company by introducing APIs for providing personalized recommendations, custom filtering, and targeted companies for B2B

  - title: Software Engineer
    company: IPVision Soft Ltd
    company_url: ''
    company_logo: ''
    location: Dhaka, Bangladesh
    date_start: '2016-09-01'
    date_end: '2017-12-31'
    description: |2-
      * Reduced cloud computing cost by 83% compared with Amazon AWS by deploying a private cluster with 99% uptime
      * Improved the efficiency of a cluster deployment of 50 Node by 75% using automation scripts in Python

  - title: Jr. Software Engineer
    company: Workspace Infotech Ltd
    company_url: 'https://www.workspaceit.com/service/'
    company_logo: ''
    location: Dhaka, Bangladesh
    date_start: '2015-07-01'
    date_end: '2016-08-31'
    description: Designed and built complete applications including backend and front end systems for mobile applications and websites
  

design:
  columns: '2'
---
