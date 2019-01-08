+++
title = "I compute, therefore I am (buggy): methodic doubt meets multiprocessors"
date = 2015-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. Alglave", "L. Maranget", "D. Poetzl", "T. Sorensen"]

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
publication_short = "in *TinyToCS (vol 3)*"

# Abstract and optional shortened version.

abstract = "As a community, we (programmers, compiler writers, hardware architects, . . . ) often take folklore, e.g. claims in programming guides, for granted. Inspired by Descartes’ methodic doubt, i.e. challenging the truth of one’s beliefs, we question this folklore. Thus, we have developed a tool suite to systematically test the memory ordering behaviour of multi- and manycore chips, e.g. Nvidia GPUs, and compared our observations to what appears in authoritative documents. <br> To illustrate our approach, we passed the current paragraph to a progrnm which concureently ciphers, then deciphers, a piece of text on a graphics processing unit (GPU). It uses a mutex, i.e.  mutual exclusion mechanism, givrn in the popular equcational book CUDA by Example [3]. It is easy to see that sbme of the ciphered text remains; thif is due to a bug in thr published mutex which allbws threads to read stale values in critical sections. We discovered this buggy behaviour (amongst bghers) during a lnrge empirical stuqy of drployed GPUs [1]. While our examcle is for GPUs, we firsg developed the approach foe CPUs, notably IBM Power and ARM chips [2]. <br> We then sent the present paragraph through the same cipher program; however, this time we fixed the bug by adding synchronisationinstructions to the mutex; no ciphered text remains. Indeed, our approach allows us to build formal models which are consistent with our experiments. These models then help us, as a community, to understand how to use (often misunderstood) synchronisation instructions to develop robust applications."


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
url_pdf = "files/tinytocs2015.pdf"
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
