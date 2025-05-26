+++
title = "Seer: Leveraging Big Data to Navigate the Complexity of Performance Debugging in Cloud Microservices"
date = 2019-04-15

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Yanqi Zhang", "Kelvin Hu", "Yuan He", "Meghna Pancholi", "Dailun Cheng", "Christina Delimitrou"]

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
publication = "ACM International Conference on Architectural Support for Programming Languages and Operating Systems "
publication_short = "[ACM ASPLOS'19](https://asplos-conference.org/2019/)"

# Abstract.
abstract = "Performance unpredictability is a major roadblock towards cloud adoption, and has performance, cost, and revenue ramifications. Predictable performance is even more critical as cloud services transition from monolithic designs to microservices. Detecting QoS violations after they occur in systems with microservices results in long recovery times, as hotspots propagate and amplify across dependent services. We present Seer, an online cloud performance debugging system that leverages deep learning and the massive amount of tracing data cloud systems collect to learn spatial and temporal patterns that translate to QoS violations. Seer combines lightweight distributed RPC-level tracing, with detailed low-level hardware monitoring to signal an upcoming QoS violation, and diagnose the source of unpredictable performance. Once an imminent QoS violation is detected, Seer notifies the cluster manager to take action to avoid performance degradation altogether. We evaluate Seer both in local clusters, and in large-scale deployments of end-to-end applications built with microservices with hundreds of users. We show that Seer correctly anticipates QoS violations 91% of the time, and avoids the QoS violation to begin with in 84% of cases. Finally, we show that Seer can identify applicationlevel design bugs, and provide insights on how to better architect microservices to achieve predictable performance."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1145/3297858.3304004"

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
url_pdf = "2019.asplos.seer.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "2019.asplos.seer.slides.pdf"
url_video = "https://youtu.be/Mf_C2xCpBdc"
url_poster = ""
url_source = ""
url_cite = "cite.bib"

award = "Invited to SIGOPS Operating Systems Review."

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
