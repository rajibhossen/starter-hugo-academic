---
title: Microesrvice Resource Autoscaler
summary: A resource manager on top of kubernetes that automatically finds optimum resources for deployed application without human intervention. Upon doing that, the resource manager does not violate SLO and does not need offline datasets for training. The algorithm is simple yet effective in real world scenario.

tags:
- Resource Autoscaler
- Microesrvice
- Kubernetes
date: "2022-01-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The block diagram of our system
  focal_point: Smart

links:
url_code: "https://github.com/rajibhossen/microservice-autoscaling"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

A resource manager on top of kubernetes that automatically finds optimum resources for deployed application without human intervention. Upon doing that, the resource manager does not violate SLO and does not need offline datasets for training. The algorithm is simple yet effective in real world scenario.

Results: Saves 33% more resources than state-of-the-art rule based autoscaling
Technology used: Python, Kubernetes, Prometheus, Jaeger, Machine Learning.