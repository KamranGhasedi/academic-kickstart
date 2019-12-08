+++
title = "Balanced Self-Paced Learning for Generative Adversarial Clustering Network"
date =  2019-05-01T20:35:43-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K. Ghasedi Dizaji, X. Wang, , C. Deng, H. Huang"]

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
publication = "IEEE Conference on Computer Vision and Pattern Recognition (CVPR)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Clustering is an important problem in various machine learning applications, but still a challenging task when dealing with complex real data. The existing clustering algorithms utilize either shallow models with insufficient capacity for capturing the non-linear nature of data, or deep models with large number of parameters prone to overfitting. In this paper, we propose a deep Generative Adversarial Clustering Network (ClusterGAN), which tackles the problems of training of deep clustering models in unsupervised manner. ClusterGAN consists of three networks, a discriminator, a generator and a clusterer (i.e. a clustering network). We employ an adversarial game between these three players to synthesize realistic samples given discriminative latent variables via the generator, and learn the inverse mapping of the real samples to the discriminative embedding space via the clusterer. Moreover, we utilize a conditional entropy minimization loss to increase/decrease the similarity of intra/inter cluster samples. Since the ground-truth similarities are unknown in clustering task, we propose a novel balanced self-paced learning algorithm to gradually include samples into training from easy to difficult, while considering the diversity of selected samples from all clusters. Therefore, our method makes it possible to efficiently train clusterers with large depth by leveraging the proposed adversarial game and balanced self-paced learning algorithm. According our experiments, ClusterGAN achieves competitive results compared to the state-of-the-art clustering and hashing models on several datasets."
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
url_pdf = "http://openaccess.thecvf.com/content_CVPR_2019/papers/Ghasedi_Balanced_Self-Paced_Learning_for_Generative_Adversarial_Clustering_Network_CVPR_2019_paper.pdf"
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
