+++
title = "Performance evaluation of OpenCL standard support (and beyond)"
date = 2019-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "S. Pai", "A. F. Donaldson"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication_short = "<b> Best Paper Award </b> in *IWOCL*"

# Abstract and optional shortened version.
abstract = "One of the benefits to programming of OpenCL is platform portability. That is, an OpenCL program that follows the OpenCL specification should, in principle, execute reliably on any platform that supports OpenCL. To assess the current state of OpenCL portability, we provide an experience report examining two sets of open source benchmarks that we attempted to execute across a variety of GPU platforms, via OpenCL. We report on the portability issues we encountered, where applications would execute successfully on one platform but fail on another. We classify issues into three groups: (1) framework bugs, where the vendorprovided OpenCL framework fails; (2) specification limitations, where the OpenCL specification is unclear and where different GPU platforms exhibit different behaviours; and (3) programming bugs, where non-portability arises due to the program exercising behaviours that are incorrect or undefined according to the OpenCL specification. The issueswe encountered slowed the development process associated with our sets of applications, but we view the issues as providing exciting motivation for future testing and verification efforts to improve the state of OpenCL portability; we conclude with a discussion of these."


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
url_pdf = "files/iwocl2019.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "files/iwocl_slides2019.pdf"
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
