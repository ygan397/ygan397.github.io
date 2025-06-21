---
title: "EchoLM: Accelerating LLM Serving with Real-time Knowledge Distillation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yifan Yu
  - Lillian Tsai
  - Nikhil Sarda
  - Jiaming Shen
  - Yanqi Zhou
  - Arvind Krishnamurthy
  - Fan Lai
  - Henry M. Levy
  - David Culler

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"

date: "2025-01-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
# publication: In *The Thirteenth International Conference on Learning Representations*
# publication_short: In *ICLR 2025*

abstract: "Large language models (LLMs) have excelled in various applications, yet serving them at scale is challenging due to their substantial resource demands and high latency. Our real-world studies reveal that over 60% of user requests to LLMs have semantically similar counterparts, suggesting the potential for knowledge sharing among requests. However, naively caching and reusing past responses leads to large quality degradation. In this paper, we introduce EchoLM, an in-context caching system that leverages historical requests as examples to guide response generation, enabling selective offloading of requests to more efficient LLMs. However, enabling this real-time knowledge transfer leads to intricate tradeoffs between response quality, latency, and system throughput at scale. For a new request, EchoLM identifies similar, high-utility examples and efficiently prepends them to the input for better response. At scale, EchoLM adaptively routes requests to LLMs of varying capabilities, accounting for response quality and serving loads. EchoLM employs a cost-aware cache replay mechanism to improve example quality and coverage offline, maximizing cache utility and runtime efficiency. Evaluations on millions of open-source requests demonstrate that EchoLM has a throughput improvement of 1.4-5.9x while reducing latency by 28-71% without hurting response quality on average."

# Summary. An optional shortened abstract.
summary: EchoLM is an in-context caching system that improves large language model (LLM) serving efficiency by leveraging semantically similar past requests as examples to guide response generation, resulting in significant throughput gains and latency reduction without compromising quality.

tags:
  - LLM

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "./2501.12689v2.pdf"
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
