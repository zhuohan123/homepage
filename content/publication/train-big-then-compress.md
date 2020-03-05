+++
abstract = """Since hardware resources are limited, the objective of training deep learning models is typically to maximize accuracy subject to the time and memory constraints of training and inference. We study the impact of model size in this setting, focusing on Transformer models for NLP tasks that are limited by compute: self-supervised pretraining and high-resource machine translation. We first show that even though smaller Transformer models execute faster per iteration, wider and deeper models converge in significantly fewer steps. Moreover, this acceleration in convergence typically outpaces the additional computational overhead of using larger models. Therefore, the most compute-efficient training strategy is to counterintuitively train extremely large models but stop after a small number of iterations.

This leads to an apparent trade-off between the training efficiency of large Transformer models and the inference efficiency of small Transformer models. However, we show that large models are more robust to compression techniques such as quantization and pruning than small models. Consequently, one can get the best of both worlds: heavily compressed, large models achieve higher accuracy than lightly compressed, small models.
"""
abstract_short = ""
authors = ['**Zhuohan Li**\*', 'Eric Wallace\*', 'Sheng Shen\*', 'Kevin Lin\*', 'Kurt Keutzer', 'Dan Klein', 'Joseph E. Gonzalez (*Equal contribution)']
date = "2020-03-01"
image_preview = ""
math = true
publication_types = ["4"]
publication = "*Preprint* (arXiv 2002.11794)"
publication_short = "*Preprint* (arXiv 2002.11794)"
selected = true
title = "Train Large, Then Compress: Rethinking Model Size for Efficient Training and Inference of Transformers"
# url_code = "https://github.com/Edward-Sun/structured-nart"
# url_dataset = "#"
url_pdf = "https://arxiv.org/pdf/2002.11794.pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/g2-lstm-icml18-slides.pdf"
# url_video = "https://vimeo.com/287802865"

[[url_custom]]
name = "arXiv"
url = "https://arxiv.org/abs/2002.11794"

[[url_custom]]
name = "Blog Post"
url = "https://bair.berkeley.edu/blog/2020/03/05/compress/"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
