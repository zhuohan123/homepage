+++
abstract = """Autoregressive sequence models achieve state-of-the-art performance in domains like machine translation. However, due to the autoregressive factorization nature, these models suffer from heavy latency during inference. Recently, non-autoregressive sequence models were proposed to speed up the inference time. However, these models assume that the decoding process of each token is conditionally independent of others. Such a generation process sometimes makes the output sentence inconsistent, and thus the learned non-autoregressive models could only achieve inferior accuracy compared to their autoregressive counterparts. To improve then decoding consistency and reduce the inference cost at the same time, we propose to incorporate a structured inference module into the non-autoregressive models. Specifically, we design an efficient approximation for Conditional Random Fields (CRF) for non-autoregressive sequence models, and further propose a dynamic transition technique to model positional contexts in the CRF. Experiments in machine translation show that while increasing little latency (8~14ms), our model could achieve significantly better translation performance than previous non-autoregressive models on different translation datasets. In particular, for the WMT14 En-De dataset, our model obtains a BLEU score of 26.80, which largely outperforms the previous non-autoregressive baselines and is only 0.61 lower in BLEU than purely autoregressive models."""
abstract_short = ""
authors = ["Zhiqing Sun*", "**Zhuohan Li***", "Haoqing Wang", "Zi Lin", "Di He", "Zhi-Hong Deng (*Equal contribution)"]
date = "2019-10-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "NeurIPS 2019"
publication_short = "*NeurIPS 2019*"
selected = true
title = "Fast Structured Decoding for Sequence Models"
url_code = "https://github.com/Edward-Sun/structured-nart"
# url_dataset = "#"
url_pdf = "https://arxiv.org/pdf/1910.11555.pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/g2-lstm-icml18-slides.pdf"
# url_video = "https://vimeo.com/287802865"

[[url_custom]]
name = "Poster"
url = "pdf/nart-crf-poster.pdf"

[[url_custom]]
name = "arXiv"
url = "https://arxiv.org/abs/1910.11555"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
