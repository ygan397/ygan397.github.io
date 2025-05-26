---
title: "Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- yu_gan
- Mingyu Liang
- Sundar Dev
- David Lo
- Christina Delimitrou

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-04-13T00:00:00Z"
doi: "10.1145/3445814.3446700"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems
publication_short: ACM ASPLOS'21

abstract: Cloud applications are increasingly shifting from large monolithic services to complex graphs of loosely-coupled microservices. Despite the advantages of modularity and elasticity microservices offer, they also complicate cluster management and performance debugging, as dependencies between tiers introduce backpressure and cascading QoS violations. Prior work on performance debugging for cloud services either relies on empirical techniques, or uses supervised learning to diagnose the root causes of performance issues, which requires significant application instrumentation, and is difficult to deploy in practice. \nWe present Sage, a machine learning-driven root cause analysis system for interactive cloud microservices that focuses on practicality and scalability. Sage leverages unsupervised ML models to circumvent the overhead of trace labeling, captures the impact of dependencies between microservices to determine the root cause of unpredictable performance online, and applies corrective actions to recover a cloud service’s QoS. In experiments on both dedicated local clusters and large clusters on Google Compute Engine we show that Sage consistently achieves over 93% accuracy in correctly identifying the root cause of QoS violations, and improves performance predictability.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2021.asplos.sage.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '2021.asplos.sage.slides.pdf'
url_source: ''
url_video: 'https://youtu.be/5S1j9ZAEDuk'
url_cite: 'cite.bib'

award: "Selected in IEEE Micro's Top Picks special issue of \"most significant papers in computer architecture based on novelty and long-term impact\" for 2021."

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).