+++
title = "GPU schedulers: how fair is fair enough?"
date = 2018-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "H. Evrard", "A. F. Donaldson"]

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
publication_short = "in *CONCUR*"

# Abstract and optional shortened version.
abstract = "Blocking synchronisation idioms, e.g. mutexes and barriers, play an important role in concurrent programming. However, systems with semi-fair schedulers, e.g. graphics processing units (GPUs), are becoming increasingly common. Such schedulers provide varying degrees of fairness, guaranteeing enough to allow some, but not all, blocking idioms. While a number of applications that use blocking idioms do run on today’s GPUs, reasoning about liveness properties of such applications is difficult as documentation is scarce and scattered. <br> In this work, we aim to clarify fairness properties of semi-fair schedulers. To do this, we define a general temporal logic formula, based on weak fairness, parameterised by a predicate that enables fairness per-thread at certain points of an execution. We then define fairness properties for three GPU schedulers: HSA, OpenCL, and occupancy-bound execution. We examine existing GPU applications and show that none of the above schedulers are strong enough to provide the fairness properties required by these applications. It hence appears that existing GPU scheduler descriptions do not entirely capture the fairness properties that are provided on current GPUs. Thus, we present two new schedulers that aim to support existing GPU applications. We analyse the behaviour of common blocking idioms under each scheduler and show that one of our new schedulers allows a more natural implementation of a GPU protocol."


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
url_pdf = "files/concur2018.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "files/concur_slides_2018.pptx"
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
