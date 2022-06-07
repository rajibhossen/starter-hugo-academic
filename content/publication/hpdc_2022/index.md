---
title: "Towards Efficient Microservices Management Through Opportunistic Resource Reduction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- mohammad_islam
- Kishwar Ahmed


date: "2022-06-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 31st International Symposium on High-Performance Parallel and Distributed Computing ([ACM HPDC 2022](https://www.hpdc.org/2022/))
publication_short: The 31st International Symposium on High-Performance Parallel and Distributed Computing ([ACM HPDC 2022](https://www.hpdc.org/2022/))

abstract: Cloud applications are increasingly moving away from monolithic
services to agile microservices-based deployments. However, effi-
cient resource management for microservices poses a significant
hurdle due to the sheer number of loosely coupled and interacting
components. The interdependencies between various microservices
make existing cloud resource autoscaling techniques ineffective.
Meanwhile, machine learning (ML) based approaches that try to cap-
ture the complex relationships in microservices require extensive
training data and cause intentional SLO violations. Moreover, these
ML-heavy approaches are slow in adapting to dynamically chang-
ing microservice operating environments. In this paper, we propose
PEMA (Practical Efficient Microservice Autoscaling), a lightweight
microservice resource manager that finds efficient resource alloca-
tion through opportunistic resource reduction. PEMA’s lightweight
design enables novel workload-aware and adaptive resource man-
agement. Using three prototype microservice implementations, we
show that PEMA can find efficient resource allocation and save up
to 33% resource compared to the commercial rule-based resource
allocations

# Summary. An optional shortened abstract.
summary:  In this paper, we propose
PEMA (Practical Efficient Microservice Autoscaling), a lightweight
microservice resource manager that finds efficient resource alloca-
tion through opportunistic resource reduction. PEMA’s lightweight
design enables novel workload-aware and adaptive resource man-
agement.

tags: ['Microservices', 'Resource Management', 'Cloud Computing', 'Kubernetes', 'Service-Level-Objective']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---