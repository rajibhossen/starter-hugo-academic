---
title: "Market Mechanism-Based User-in-the-Loop Scalable Power Oversubscription for HPC Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- kishwar_ahmed
- mohammad_islam


date: "2023-02-26T00:00:00Z"
doi: "10.1109/HPCA56546.2023.10071006"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 29th IEEE International Symposium on High-Performance Computer Architecture ([IEEE HPCA 2023](https://ieeexplore.ieee.org/abstract/document/10071006))
publication_short: The 29th IEEE International Symposium on High-Performance Computer Architecture ([IEEE HPCA 2023](https://ieeexplore.ieee.org/abstract/document/10071006))

abstract: Significant power consumption is one of the major challenges for current and future high-performance computing (HPC) systems. All the while, HPC systems generally remain power underutilized, making them a great candidate for applying power oversubscription to reclaim unused capacity. However, an oversubscribed HPC system may occasionally get overloaded. In this paper, we propose MPR (Market-based Power Reduction), a scalable market-based approach where users actively participate in reducing the HPC system's power consumption to mitigate overloads. In MPR, HPC users bid to supply, in exchange for incentives, the resource reduction required for handling the overloads. Using several real-world trace-based simulations, we extensively evaluate MPR and show that, by participating in MPR, users always receive more rewards than the cost of performance loss. At the same time, the HPC manager enjoys orders of magnitude more resource gain than her incentive payoff to the users. We also demonstrate the real-world effectiveness of MPR on a prototype system.

# Summary. An optional shortened abstract.
summary:  In this paper, we propose MPR (Market-based Power Reduction), a scalable market-based approach where users actively participate in reducing the HPC system's power consumption to mitigate overloads. In MPR, HPC users bid to supply, in exchange for incentives, the resource reduction required for handling the overloads.

tags: ['HPC', 'Resource Management', 'Measurement', 'Power Management']

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
url_slides: 'https://rajib-hossen.com/slides/ahmed_hpca_23.pdf' 
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