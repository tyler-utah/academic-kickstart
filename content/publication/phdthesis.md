 +++
title = "Device-wide Barrier Synchronisation on Graphics Processing Units"
date = 2018-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "Adviser: A. F. Donaldson"]

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
publication_short = "PhD Thesis, *Imperial College London*"

# Abstract and optional shortened version.
abstract = "GPUs are parallel devices that are able to run thousands of independent threads concurrently. Traditional GPU programs are data-parallel, requiring little to no communication, i.e. synchronisation, between threads. However, classical  concurrency in the context of CPUs often exploits synchronisation  idioms that are not supported on GPUs. By studying such idioms on  GPUs, with an aim to facilitate them in a portable way, we can  enable a wider space of GPU applications.<br> <br>   While the breadth of this thesis extends to many aspects of GPU   systems, the common thread throughout is the *global barrier*:   an execution barrier that synchronises all threads executing a GPU   application. The idea of such a barrier might seem straightforward,   however this investigation reveals many challenges and insights. In   particular, this thesis includes the following studies: <br> <br>   *Execution models*: while a general gobal barrier can     deadlock due to starvation on GPUs, we show that the scheduling     guarantees of current GPUs can be used to dynamically create an     execution environment that allows for a safe, and portable global     barrier across a subset of the threads.<br><br>   *Application optimisations*: we examine a set GPU     optimisations, including one optimisation enabled by our global     barrier, targeted for graph applications.  We show that these     optimisations can provided substantial performance improvements,     e.g., the barrier optimisation achieves up to a 14x and     16x speedup on AMD and Intel GPUs, respectively.  We     investigate the performance portability of these optimisations, as     their utility varies across input, application, and     architecture. <br><br>   *Multitasking*: because many GPUs don't support     preemption, long running GPU compute applications (e.g.,     applications that use the global barrier) may block other GPU     functions, including graphics. We propose a simple cooperative     multitasking scheme that allows graphics tasks to meet their     deadlines with reasonable overheads. "


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
url_pdf = "files/phdthesis.pdf"
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
