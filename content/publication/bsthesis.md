 +++
title = "Towards Shared Memory Consistency Models for GPUS"
date = 2013-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "Adviser: G. Gopalakrishnan"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication_short = "BS Thesis, *University of Utah*"

# Abstract and optional shortened version.
abstract = "With the widespread use of GPUs, it is important to ensure that programmers have a clear understanding of their shared memory consistency model i.e. what values can be read when issued concurrently with writes. While memory consistency has been studied for CPUs, GPUs present very different memory and concurrency systems and have not been well studied. We propose a collection of litmus tests that shed light on interesting visibility and ordering properties. These include classical shared memory consistency model properties, such as coherence and write atomicity, as well as GPU specific properties e.g. memory visibility differences between intra and inter block threads. The results of the litmus tests are determined by feedback from industry experts, the limited documentation available and properties common to all modern multi-core systems. Some of the behaviors remain unresolved. Using the results of the litmus tests, we establish a formal state transition model using intuitive data structures and operations. We implement our model in the Murphi modeling language and verify the initial litmus tests. As a preliminary study, we restrict our model to loads and stores across global and shared memory along with two of the memory fences given in the NVIDIA PTX, thread fence and thread fence block. Finally, we show real world examples of code that make assumptions about the GPU shared memory consistency model that are inconsistent with our proposed model."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "files/bsthesis.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++
