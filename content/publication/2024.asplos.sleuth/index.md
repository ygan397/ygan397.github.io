---
title: "Sleuth: A Trace-Based Root Cause Analysis System for Large-Scale Microservices with Graph Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guiyang Liu
  - Xin Zhang 
  - Qi Zhou 
  - Jiesheng Wu 
  - Jiangwei Jiang

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: "2024-02-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ACM ASPLOS'23*

abstract: "Cloud microservices are being scaled up due to the rising demand for new features and the convenience of cloud-native technologies. However, the growing scale of microservices complicates the remote procedure call (RPC) dependency graph, exacerbates the tail-of-scale effect, and makes many of the empirical rules for detecting the root cause of end-to-end performance issues unreliable. Additionally, existing open-source microservice benchmarks are too small to evaluate performance debugging algorithms at a production-scale with hundreds or even thousands of services and RPCs. To address these challenges, we present Sleuth, a trace-based root cause analysis (RCA) system for large-scale microservices using un-supervised graph learning. Sleuth leverages a graph neural network to capture the causal impact of each span in a trace, and trace clustering using a trace distance metric to reduce the amount of traces required for root cause localization. A pre-trained Sleuth model can be transferred to different microservice applications without any retraining or with few-shot fine-tuning. To quantitatively evaluate the performance and scalability of Sleuth, we propose a method to generate microservice benchmarks comparable to a production-scale. The experiments on the existing benchmark suites and synthetic large-scale microservices indicate that Sleuth has significantly outperformed the prior work in detection accuracy, performance, and adaptability on a large-scale deployment."

# Summary. An optional shortened abstract.
summary: Sleuth is a root cause analysis system that uses unsupervised graph learning on trace data to accurately and adaptably identify performance bottlenecks in large-scale microservice applications.

tags:
  - ML for Systems
  - Microservices

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "./3623278.3624758.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
