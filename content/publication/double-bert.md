+++
abstract = "Unsupervised pre-training is commonly used in natural language processing: a deep neural network trained with proper unsupervised prediction tasks are shown to be effective in many downstream tasks. Because it is easy to create a large monolingual dataset by collecting data from the Web, we can train high-capacity models. Therefore, training efficiency becomes a critical issue even when using high-performance hardware. In this paper, we explore an efficient training method for the state-of-the-art bidirectional Transformer (BERT) model. By visualizing the self-attention distributions of different layers at different positions in a well-trained BERT model, we find that in most layers, the self-attention distribution will concentrate locally around its position and the start-of-sentence token. Motivated by this, we propose the stacking algorithm to transfer knowledge from a shallow model to a deep model; then we apply stacking progressively to accelerate BERT training. Experiments showed that the models trained by our training strategy achieve similar performance to models trained from scratch, but our algorithm is much faster."
abstract_short = ""
authors = ["Linyuan Gong", "Di He", "**Zhuohan Li**", "Tao Qin", "Liwei Wang", "Tie-Yan Liu"]
date = "2019-05-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*Thirty-sixth International Conference on Machine Learning (ICML 2019)*"
publication_short = "*ICML 2019*"
selected = true
title = "Efficient Training of BERT by Progressively Stacking"
url_code = "https://github.com/gonglinyuan/StackingBERT"
# url_dataset = "#"
url_pdf = "pdf/double-bert-icml19.pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/g2-lstm-icml18-slides.pdf"
# url_video = "https://vimeo.com/287802865"

# [[url_custom]]
# name = "arXiv"
# url = "https://arxiv.org/abs/1806.02988"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
