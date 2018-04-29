+++
title = "Deep clustering via joint convolutional autoencoder embedding and relative entropy minimization"
date = 2017-10-01T23:02:51-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K. Ghasedi Dizaji", "A. Herandi", "C. Deng", "W. Cai", "H. Huang"]

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
publication = "IEEE International Conference on Computer Vision (ICCV)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "In this paper, we propose a new clustering model, called DEeP Embedded RegularIzed ClusTering (DEPICT), which efficiently maps data into a discriminative embedding subspace and precisely predicts cluster assignments. DEPICT generally consists of a multinomial logistic regression function stacked on top of a multi-layer convolutional autoencoder. We define a clustering objective function using relative entropy (KL divergence) minimization, regularized by a prior for the frequency of cluster assignments. An alternating strategy is then derived to optimize the objective by updating parameters and estimating cluster assignments. Furthermore, we employ the reconstruction loss functions in our autoencoder, as a data-dependent regularization term, to prevent the deep embedding function from overfitting. In order to benefit from end-to-end optimization and eliminate the necessity for layer-wise pretraining, we introduce a joint learning framework to minimize the unified clustering and reconstruction loss functions together and train all network layers simultaneously. Experimental results indicate the superiority and faster running time of DEPICT in real-world clustering tasks, where no labeled data is available for hyper-parameter tuning."
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
url_pdf = "http://openaccess.thecvf.com/content_ICCV_2017/papers/Dizaji_Deep_Clustering_via_ICCV_2017_paper.pdf"
url_preprint = ""
url_code = "https://github.com/herandy/DEPICT"
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
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
