+++
abstract = """Model parallelism has become a necessity for training modern large-scale deep language models. In this work, we identify a new and orthogonal dimension from existing model parallel approaches: it is possible to perform pipeline parallelism within a single training sequence for Transformer-based language models thanks to its autoregressive property. This enables a more fine-grained pipeline compared with previous work. With this key idea, we design TeraPipe, a high-performance token-level pipeline parallel algorithm for synchronous model-parallel training of Transformer-based language models. We develop a novel dynamic programming-based algorithm to calculate the optimal pipelining execution scheme given a specific model and cluster configuration. We show that TeraPipe can speed up the training by 5.0x for the largest GPT-3 model with 175 billion parameters on an AWS cluster with 48 p3.16xlarge instances compared with state-of-the-art model-parallel methods.
"""
abstract_short = ""
authors = ['**Zhuohan Li**', 'Siyuan Zhuang', 'Shiyuan Guo', 'Danyang Zhuo', 'Hao Zhang', 'Dawn Song', 'Ion Stoica']
date = "2021-05-08"
image_preview = ""
math = true
publication_types = ["4"]
publication = "*ICML 2021*"
publication_short = "*ICML 2021*"
selected = true
title = "TeraPipe: Token-Level Pipeline Parallelism for Training Large-Scale Language Models"
url_code = "https://github.com/zhuohan123/terapipe"
# url_dataset = "#"
url_pdf = "https://arxiv.org/pdf/2102.07988.pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/g2-lstm-icml18-slides.pdf"
# url_video = "https://vimeo.com/287802865"

[[url_custom]]
name = "arXiv"
url = "https://arxiv.org/abs/2102.07988"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
