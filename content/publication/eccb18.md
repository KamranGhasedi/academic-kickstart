+++
title = "Conditional Generative Adversarial Network for Gene Expression Inference"
date = 2018-06-27T09:54:13-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K. Ghasedi Dizaji, X. Wang, H. Huang"]

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
publication = "17th European Conference on Computational Biology (ECCB)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "The rapid progress of gene expression profiling has facilitated the prosperity of recent biological studies in various fields, where gene expression data characterizes various cell conditions and regulatory mechanisms under different experimental circumstances. Despite the widespread application of gene expression profiling and advances in high-throughput technologies, profiling in genome-wide level is still expensive and difficult. Previous studies found that high correlation exists in the expression pattern of different genes, such that a small subset of genes can be informative to approximately describe the entire transcriptome. In the Library of Integrated Network-based Cell-Signature (LINCS) program, a set of ∼1000 landmark genes have been identified that contain ∼80% information of the whole genome and can be used to predict the expression of remaining genes. For a cost-effective profiling strategy, traditional methods measure the profiles of landmark genes and then infer the expression of other target genes via linear models. However, linear models do not have the capacity to capture the non-linear associations in gene regulatory networks. As a flexible model with high representative power, deep learning models provide an alternate to interpret the complex relation among genes. In this paper, we propose a deep learning architecture for the inference of target gene expression profiles. We construct a novel conditional generative adversarial network by incorporating both the adversarial and `1-norm loss terms in our model. Unlike the smooth and blurry predictions resulted by mean squared error objective, the coupled adversarial and l1-norm loss function leads to more accurate and sharp predictions. We validate our method under two different settings and find consistent and significant improvements over all the comparing methods."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
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
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
