+++
title = "Seer: Leveraging Big Data to Navigate the Increasing Complexity of Cloud Debugging"
date = 2018-07-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Meghna Pancholi", "Dailun Cheng", "Siyuan Hu", "Yuan He", "Christina Delimitrou"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "USENIX Conference on Hot Topics in Cloud Computing"
publication_short = "[USENIX HotCloud'18](https://www.usenix.org/conference/hotcloud18)"

# Abstract.
abstract = "Performance unpredictability in cloud services leads to poor user experience, degraded availability, and has revenue ramifications. Detecting performance degradation a posteriori helps the system take corrective action, but does not avoid the QoS violations. Detecting QoS violations after the fact is even more detrimental when a service consists of hundreds of thousands of loosely-coupled microservices, since performance hiccups can quickly propagate across the dependency graph of microservices. In this work we focus on anticipating QoS violations in cloud settings to mitigate performance unpredictability to begin with. We propose Seer, a cloud runtime that leverages the massive amount of tracing data cloud systems collect over time and a set of practical learning techniques to signal upcoming QoS violations, as well as identify the microservice(s) causing them. Once an imminent QoS violation is detected Seer uses machine-level hardware events to determine the cause of the QoS violation, and adjusts the resource allocations to prevent it. In local clusters with 10 40-core servers and 200-instance clusters on GCE running diverse cloud microservices, we show that Seer correctly anticipates QoS violations 91% of the time, and attributes the violation to the correct microservice in 89% of cases. Finally, Seer detects QoS violations early enough for a corrective action to almost always be applied successfully."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "2018.hotcloud.seer.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "2018.hotcloud.seer.slides.pdf"
url_video = ""
url_poster = ""
url_source = ""
url_cite = "cite.bib"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
