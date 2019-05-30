+++
title = "Joint Generative-Discriminative Aggregation Model for Multi-Option Crowd Labels"
date = 2018-02-02T00:34:36-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K. Ghasedi Dizaji", "Y. Yang", "H. Huang"]

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
publication = "ACM International Conference on Web Search and Data Mining (WSDM)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Although some crowdsourcing aggregation models have been introduced to aggregate noisy crowd labels, these models mostly consider single-option (i.e. discrete) crowd labels as the input variables, and are not compatible with multi-option (i.e. non-deterministic) crowd data. In this paper, we propose a novel joint generative-discriminative aggregation model, which is able to efficiently deal with both single-option and multi-option crowd labels. Considering the confidence of workers for each option as the input data, we first introduce a new discriminative aggregation model, called Constrained Weighted Majority Voting (CWMVL1), which improves the performance of majority voting method. CWMVL1 considers flexible reliability parameters for crowd workers, employs L1-norm loss function to deal with noisy crowd data, and includes optimization constraints to have probabilistic outputs. We prove that our object is convex, and derive an efficient optimization algorithm. Moreover, we integrate the discriminative CWMVL1 model with a generative model, resulting in a powerful joint aggregation model. Combination of these sub-models is obtained in a probabilistic framework rather than a heuristic way. For our joint model, we derive an efficient optimization algorithm, which alternates between updating the parameters and estimating the potential true labels. Experimental results indicate that the proposed aggregation models achieve superior or competitive results in comparison with the state-of-the-art models on single-option and multi-option crowd datasets, while having faster convergence rates and more reliable predictions."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://dl.acm.org/citation.cfm?id=3159672"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "pdf/wsdm18_slides.pdf"
url_video = ""
url_poster = "pdf/wsdm18_poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
