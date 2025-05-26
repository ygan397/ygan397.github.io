+++
title = "The Architectural Implications of Cloud Microservices"
date = 2018-07-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["yu_gan", "Christina Delimitrou"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "IEEE Computer Architecture Letters"
publication_short = "[IEEE CAL](https://www.computer.org/csdl/journal/ca)"

# Abstract.
abstract = "Cloud services have recently undergone a shift from monolithic applications to microservices, with hundreds or thousands of loosely-coupled microservices comprising the end-to-end application. Microservices present both opportunities and challenges when optimizing for quality of service (QoS) and cloud utilization. In this paper we explore the implications cloud microservices have on system bottlenecks, and datacenter server design. We first present and characterize an end-to-end application built using tens of popular open-source microservices that implements a movie renting and streaming service, and is modular and extensible. We then use the end-to-end service to study the scalability and performance bottlenecks of microservices, and highlight implications they have on the design of datacenter hardware. Specifically, we revisit the long-standing debate of brawny versus wimpy cores in the context of microservices, we quantify the I-cache pressure they introduce, and measure the time spent in computation versus communication between microservices over RPCs. As more cloud applications switch to this new programming model, it is increasingly important to revisit the assumptions we have previously used to build and manage cloud systems."

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

award = "Selected as Best of CAL for 2018. \\\n Received the Best Paper Award from the IEEE CS Publications Board for CAL 2018." 

# Links (optional).
url_pdf = "2018.cal.deathstarbench.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/7_iQfLtMcfI"
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
