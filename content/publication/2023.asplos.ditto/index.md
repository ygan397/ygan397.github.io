---
title: "Ditto: End-to-End Application Cloning for Networked Cloud Services"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mingyu Liang
  - Yueying Li
  - Carlos Torres
  - Abhishek Dhanotia
  - Mahesh Ketkar
  - Christina Delimitrou

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-01-30T00:00:00Z"
doi: "10.1145/3575693.3575751"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ACM ASPLOS'23*

abstract: "The lack of representative, publicly-available cloud services has been a recurring problem in the architecture and systems communities. While open-source benchmarks exist, they do not capture the full complexity of cloud services. Application cloning is a promising way to address this, however, prior work is limited to CPU-/cache-centric, single-node services, operating at user level. We present Ditto, an automated framework for cloning end-to-end cloud applications, both monolithic and microservices, which captures I/O and network activity, as well as kernel operations, in addition to application logic. Ditto takes a hierarchical approach to application cloning, starting with capturing the dependency graph across distributed services, to recreating each tier's control/data flow, and finally generating system calls and assembly that mimics the individual applications. Ditto does not reveal the logic of the original application, facilitating publicly sharing clones of production services with hardware vendors, cloud providers, and the research community. We show that across a diverse set of single- and multi-tier applications, Ditto accurately captures their CPU and memory characteristics as well as their high-level performance metrics, is portable across platforms, and facilitates a wide range of system studies."

# Summary. An optional shortened abstract.
summary: Ditto is an automated framework that addresses the lack of representative cloud service benchmarks by creating accurate, privacy-preserving clones of complex, end-to-end cloud applications, capturing everything from application logic and I/O to kernel operations for realistic system studies.

tags:
  - Cloud Computing
  - Computer Architecture
  - Microservices

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "./3575693.3575751.pdf"
url_code: "https://github.com/Mingyu-Liang/Ditto"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

award: Selected in IEEE Micro's Top Picks special issue of "most significant papers in computer architecture based on novelty and long-term impact" for 2023.

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
