+++
title = "Portable inter-workgroup barrier synchronisation for GPUs"
date = 2016-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "A. F. Donaldson", "M. Batty", "G. Gopalakrishnan", "Z. Rakamaric"]

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
publication_short = "In *OOPSLA*"

# Abstract and optional shortened version.
abstract = "Despite the growing popularity of GPGPU programming, there is not yet a portable and formally-specified barrier that one can use to synchronise across workgroups. Moreover, the occupancy-bound execution model of GPUs breaks assumptions inherent in traditional software execution barriers, exposing them to deadlock. We present an occupancy discovery protocol that dynamically discovers a safe estimate of the occupancy for a given GPU and kernel, allowing for a starvation-free (and hence, deadlock-free) interworkgroup barrier by restricting the number of workgroups according to this estimate. We implement this idea by adapting an existing, previously non-portable, GPU interworkgroup barrier to use OpenCL 2.0 atomic operations, and prove that the barrier meets its natural specification in terms of synchronisation. <br> We assess the portability of our approach over eight GPUs spanning four vendors, comparing the performance of our method against alternative methods. Our key findings include: (1) the recall of our discovery protocol is nearly 100%; (2) runtime comparisons vary substantially across GPUs and applications; and (3) our method provides portable and safe inter-workgroup synchronisation across the applications we study."


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
url_pdf = "files/oopsla2016.pdf"           
url_preprint = ""
url_code = "https://github.com/mc-imperial/gpu_discovery_barrier"
url_dataset = ""
url_project = ""
url_slides = "files/oopsla_slides2016.pptx"
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
