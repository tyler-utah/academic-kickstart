+++
title = "GPU concurrency: weak behaviours and programming assumptions"
date = 2015-09-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. Alglave", "M. Batty", "A. F. Donaldson", "G. Gopalakrishnan", "J. Ketema", "D. Poetzl", "T. Sorensen", "J. Wickerson"]

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
publication_short = "In *ASPLOS*"

# Abstract and optional shortened version.

abstract = "Concurrency is pervasive and perplexing, particularly on graphics processing units (GPUs). Current specifications of languages and hardware are inconclusive; thus programmers often rely on folklore assumptions when writing software. To remedy this state of affairs, we conducted a large empirical study of the concurrent behaviour of deployed GPUs. Armed with litmus tests (i.e. short concurrent programs), we questioned the assumptions in programming guides and vendor documentation about the guarantees provided by hardware. We developed a tool to generate thousands of litmus tests and run them under stressful workloads. We observed a litany of previously elusive weak behaviours, and exposed folklore beliefs about GPU programming—often supported by official tutorials—as false. As a way forward, we propose a model of Nvidia GPU hardware, which correctly models every behaviour witnessed in our experiments. The model is a variant of SPARC Relaxed Memory Order (RMO), structured following the GPU concurrency hierarchy."

abstract_short = ""

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
url_pdf = "files/asplos2015.pdf"           
url_preprint = ""
url_code = ""
url_dataset = "http://multicore.doc.ic.ac.uk/gpu-litmus/"
url_project = ""
url_slides = ""
url_video = ""
url_poster = "files/asplos_poster2015.pdf"
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

Contributions mentioned in this <a href="http://lwn.net/Articles/608550/"> LWN article</a>.

Confirmed and repaired *CUDA by Example* bug (<a href="https://developer.nvidia.com/cuda-example-errata-page">errata</a>)