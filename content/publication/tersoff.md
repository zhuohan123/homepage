+++
abstract = "Höhnerbach et al. [1] proposed a general optimization method for the multi-body potential problem by exploiting vectorization on various of architectures using LAMMPS. As a task of the Student Cluster Competition in The International Conference for High Performance Computing, Networking, Storage and Analysis (SC17), we tried to reproduce the optimizations proposed in the paper. The molecular dynamics simulation of crystalline silicon is performed with LAMMPS on both our own single-node Intel Xeon machine and the cloud resource. The accuracy of the computation results is examined. The performance of the optimized program is compared with the original version to study the effectiveness and the scalability of the proposed optimization."
abstract_short = ""
authors = ["Zhenxin Fu", "Lei Yang", "Wenbin Hou", "**Zhuohan Li**", "Yifan Wu", "Yihua Cheng", "Xiaolin Wang", "Yun Liang"]
date = "2018-06-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*Parallel Computing* (from reproducibility challenge of SC17)"
publication_short = "*Parallel Computing* (from reproducibility challenge of SC17)"
selected = true
title = "Reproducing Vectorization of the Tersoff Multi-Body Potential on the Intel Broadwell Architecture"
# url_code = "#"
# url_dataset = "#"
url_pdf = "pdf/tersoff-reproducibility-report.pdf"
# url_project = "project/deep-learning/"
# url_slides = "#"
# url_video = "#"

# [[url_custom]]
# name = "Custom Link"
# url = "http://www.example.org"

[[url_custom]]
name = "DOI"
url = "https://doi.org/10.1016/j.parco.2018.06.010"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++
[1] Höhnerbach, Markus, Ahmed E. Ismail, and Paolo Bientinesi. "The vectorization of the tersoff multi-body potential: an exercise in performance portability." *Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis.* IEEE Press, 2016.
