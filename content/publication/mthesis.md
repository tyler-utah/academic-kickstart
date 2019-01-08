 +++
title = "Testing and Exposing Weak GPU Memory Models"
date = 2014-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Sorensen", "Adviser: G. Gopalakrishnan and Z. Rakamaric"]

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
publication_short = "MS Thesis, *University of Utah*"

# Abstract and optional shortened version.
abstract = "Graphics Processing Units (GPUs) are highly parallel shared memory microprocessors, and as such, they are prone to the same concurrency considerations as their traditional multicore CPU counterparts. In this thesis, we consider shared memory consistency, i.e. what values can be read when issued concurrently with writes on current GPU hardware. While memory consistency has been relatively well studied for CPUs, GPUs present substantially different concurrency systems with an explicit thread and memory hierarchy. Because documentation on GPU memory models is limited, it remains unclear what behaviors are allowed by current GPU implementations. <br><br>To this end, this work focuses on testing shared memory consistency behavior on NVIDIA GPUs. We present a format for describing GPU memory consistency tests (dubbed GPU litmus tests) which includes the placement of testing threads into the GPU thread hierarchy (e.g. cooperative thread arrays, warps) and memory locations into GPU memory regions (e.g. shared, global). We then present a framework for running GPU litmus tests under system stress designed to trigger weak memory model behaviors, that is, executions that do not correspond to an interleaving of the instructions of the concurrent program. We discuss GPU specific incantations (i.e. heuristics) which we found to be crucial for observing weak memory model executions; these include bank conflicts and custom GPU memory stressing functions. <br> <br> We then report the results of running GPU litmus tests in this framework and show that we observe a controversial relaxed coherence behavior on older NVIDIA chips. We present several examples of published GPU applications which may exhibit unintended behavior due to the lack of fence synchronization; one such example is a spin-lock published in the popular CUDA by Example book. We then test several families of tests and compare our results to a proposed operational GPU memory model and show that the model is unsound (i.e. disallows behaviors that we observe on hardware). Our techniques are implemented in a modified version of a memory model testing tool named litmus."


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
url_pdf = "files/msthesis.pdf"
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
Confirmed and repaired *CUDA by Example* bug (<a href="https://developer.nvidia.com/cuda-example-errata-page">errata</a>)