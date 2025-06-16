---
title: "An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud and Edge Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yanqi Zhang
  - Dailun Cheng
  - Ankitha Shetty
  - Priyal Rathi
  - Nayantara Katarki
  - Ariana Bruno
  - Justin Hu
  - Brian Ritchken
  - Brendon Jackson
  - Kelvin Hu
  - Meghna Pancholi
  - Yuan He
  - Brett Clancy
  - Chris Colen
  - Fukang Wen
  - Catherine Leung
  - Siyuan Wang
  - Leon Zaruvinsky
  - Mateo Espinosa
  - Rick Lin
  - Zhongling Liu
  - Jake Padilla
  - Christina Delimitrou

# Author notes (optional)
author_notes: []

date: "2019-04-15T00:00:00Z"
doi: "10.1145/3297858.3304013"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In *ACM International Conference on Architectural Support for Programming Languages and Operating Systems*"
publication_short: "In *[ACM ASPLOS'19](https://asplos-conference.org/2019/)*"

abstract: "Cloud services have recently started undergoing a major shift from monolithic applications, to graphs of hundreds of loosely-coupled microservices. Microservices fundamentally change a lot of assumptions current cloud systems are designed with, and present both opportunities and challenges when optimizing for quality of service (QoS) and utilization. In this paper we explore the implications microservices have across the cloud system stack. We first present DeathStarBench, a novel, open-source benchmark suite built with microservices that is representative of large end-to-end services, modular and extensible. DeathStarBench includes a social network, a media service, an e-commerce site, a banking system, and IoT applications for coordination control of UAV swarms. We then use DeathStarBench to study the architectural characteristics of microservices, their implications in networking and operating systems, their challenges with respect to cluster management, and their trade-offs in terms of application design and programming frameworks. Finally, we explore the tail at scale effects of microservices in real deployments with hundreds of users, and highlight the increased pressure they put on performance predictability."

# Summary. An optional shortened abstract.
summary: "DeathStarBench is an open-source benchmark suite built with microservices that is representative of large end-to-end services. We use DeathStarBench to study the architectural characteristics of microservices, their implications in networking and operating systems, their challenges with respect to cluster management, and their trade-offs in terms of application design and programming frameworks."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: "IEEE Micro's Top Picks 2019"
#   url: ""

url_pdf: "2019.asplos.deathstarbench.pdf"
url_code: "https://github.com/delimitrou/DeathStarBench"
url_dataset: ""
url_poster: ""
url_project: "http://microservices.ece.cornell.edu/"
url_slides: "2019.asplos.deathstarbench.slides.pdf"
url_source: ""
url_video: "https://youtu.be/7_iQfLtMcfI"

award: Selected in IEEE Micro's Top Picks special issue of "most significant papers in computer architecture based on novelty and long-term impact" for 2019.

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

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
slides: ""
---