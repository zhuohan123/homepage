+++
abstract = "Long Short-Term Memory (LSTM) is one of the most widely used recurrent structures in sequence modeling. It aims to use gates to control information flow (e.g., whether to skip some information or not) in the recurrent computations, although its practical implementation based on soft gates only partially achieves this goal. In this paper, we propose a new way for LSTM training, which pushes the output values of the gates towards 0 or 1. By doing so, we can better control the information flow: the gates are mostly open or closed, instead of in a middle state, which makes the results more interpretable. Empirical studies show that (1) Although it seems that we  restrict model capacity, there is no performance drop at all: we achieve better or competitive performances due to its better generalization ability; (2) The outputs of gates are not sensitive to their inputs: we can easily compress the LSTM unit in multiple ways, e.g., low-rank approximation and low-precision approximation. The compressed models are even better than the baseline models without compression."
abstract_short = ""
authors = ["**Zhuohan Li**", "Di He", "Fei Tian", "Wei Chen", "Tao Qin", "Liwei Wang", "Tie-Yan Liu"]
date = "2018-07-05"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*Thirty-fifth International Conference on Machine Learning (ICML 2018)*"
publication_short = "*ICML 2018*"
selected = true
title = "Towards Binary-Valued Gates for Robust LSTM Training"
url_code = "https://github.com/zhuohan123/g2-lstm"
# url_dataset = "#"
url_pdf = "pdf/g2-lstm-icml18.pdf"
# url_project = "project/deep-learning/"
# url_slides = "#"
# url_video = "#"

# [[url_custom]]
# name = "Custom Link"
# url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
