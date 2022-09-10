---
title: Business Intelligence Application
summary: Business to Business Application APIs to provide recommendations, custom filtering, and detail information of potential businesses.

tags:
- Business Intelligence
- Data Analysis
- Machine Learning
date: "2018-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The System features
  focal_point: Smart

links:
url_code: ""
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

At first, we built a data processing pipeline where we automatically collect raw data from crawler team, then indexed the data using ElasticSearch and store them in S3 Database. To serve web requests, and mobile client, we developed APIs that queries from ES and used machine learning to recommend potential customers, provided custom metrics, and insights from unprocessed large informations.

Technology used: Python, REST API, ElasticSearch, Machine Learning.