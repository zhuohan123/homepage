+++
abstract = """Collective communication systems such as MPI offer high performance group communication primitives at the cost of application flexibility. Today, an increasing number of distributed applications (e.g, reinforcement learning) require flexibility in expressing dynamic and asynchronous communication patterns. To accommodate these applications, task-based distributed computing frameworks (e.g., Ray, Dask, Hydro) have become popular as they allow applications to dynamically specify communication by invoking tasks, or functions, at runtime. This design makes efficient collective communication challenging because (1) the group of communicating processes is chosen at runtime, and (2) processes may not all be ready at the same time.
We design and implement Hoplite, a communication layer for task-based distributed systems that achieves high performance collective communication without compromising application flexibility. The key idea of Hoplite is to use distributed protocols to compute a data transfer schedule on the fly. This enables the same optimizations used in traditional collective communication, but for applications that specify the communication incrementally. We show that Hoplite can achieve similar performance compared with a traditional collective communication library, MPICH. We port a popular distributed computing framework, Ray, on atop of Hoplite. We show that Hoplite can speed up asynchronous parameter server and distributed reinforcement learning workloads that are difficult to execute efficiently with traditional collective communication by up to 8.1x and 3.9x, respectively.
"""
abstract_short = ""
authors = ["Siyuan Zhuang*", "**Zhuohan Li***", "Danyang Zhuo", "Stephanie Wang", "Eric Liang", "Robert Nishihara", "Philipp Moritz", "Ion Stoica (*Equal contribution)"]
date = "2020-02-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*Preprint* (arXiv 2002.05814)"
publication_short = "*Preprint* (arXiv 2002.05814)"
selected = true
title = "Hoplite: Efficient Collective Communication for Task-Based Distributed Systems"
# url_code = "https://github.com/Edward-Sun/structured-nart"
# url_dataset = "#"
url_pdf = "https://arxiv.org/pdf/2002.05814.pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/g2-lstm-icml18-slides.pdf"
# url_video = "https://vimeo.com/287802865"

[[url_custom]]
name = "arXiv"
url = "https://arxiv.org/abs/2002.05814"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
