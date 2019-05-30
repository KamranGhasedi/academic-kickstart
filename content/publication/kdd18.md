+++
title = "Semi-Supervised Generative Adversarial Network for Gene Expression Inference"
date = 2018-05-07T10:07:05-04:00
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
publication = "The 24th SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Gene expression profiling provides comprehensive characterization of cellular states under different experimental conditions, thus contributes to the prosperity of many fields of biomedical research. Although the rapid development of gene expression profiling has been observed, genome-wide profiling of large libraries is still expensive and difficult. Due to the fact that there are significant correlations between gene expression patterns, previous studies introduced regression models for predicting the target gene expressions from the landmark gene profiles. These models formulate the gene expression inference in a completely supervised manner, which require a large labeled dataset (i.e paired landmark and target gene expressions). However, collecting the whole gene expressions is much more expensive than the landmark genes. In order to address this issue and take advantage of cheap unlabeled data (i.e. landmark genes), we propose a novel semi-supervised deep generative model for target gene expression inference. Our model is based on the generative adversarial network (GAN) to approximate the joint distribution of landmark and target genes, and an inference network to learn the conditional distribution of target genes given the landmark genes. We employ the reliable generated data by our GAN model as the extra training pairs to improve the training of our inference model, and utilize the trustworthy predictions of the inference network to enhance the adversarial training of our GAN network. We evaluate our model on the prediction of two types of gene expression data and identify obvious advantage over the counterparts."
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
