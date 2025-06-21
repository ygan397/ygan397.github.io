---
title: "Towards Foundation Database Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Johannes Wehrstein
  - Carsten Binnig
  - Fatma Özcan
  - Shobha Vasudevan
  - admin
  - Yawen Wang

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: "2025-01-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of Conference on Innovative Data Systems Research*
publication_short: In *CIDR 2025*

abstract: "Recently, machine learning models have been utilized to realize many database tasks in academia and industry. To solve such internal tasks of database systems, the state-of-the-art is one-off models that need to be trained individually per task and even per dataset, which causes extremely high training overheads. In this paper, we argue that a new learning paradigm is needed that moves away from such one-off models towards generalizable models that can be used with only minimal overhead for an unseen dataset on a wide spectrum of tasks. While recently, several advances towards more generalizable models have been made, still no model exists that can generalize across both datasets and tasks. As such, we propose a new direction which we call foundation models for databases which is pre-trained in both task-agnostic and dataset-agnostic manner which makes it possible to use the model with low overhead to solve a wide spectrum of downstream tasks on unseen datasets. In this vision paper, we propose an architecture for such a foundation database model, describe a promising feasibility study with a first prototype of such a model, and discuss the research roadmap to address the open challenges."

# Summary. An optional shortened abstract.
summary: This paper introduces the concept of "foundation models for databases," a new paradigm advocating for pre-trained, general-purpose models that can be adapted to various tasks and datasets with minimal overhead, moving away from the current inefficient one-off model approach.

tags:
  - ML for Systems

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "./p31-wehrstein.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

award: Best paper award in CIRD 2025

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
