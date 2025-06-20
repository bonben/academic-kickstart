+++
title = "Analyzing Few-Shot Neural Architecture Search in a Metric-Driven Framework"
date = 2024-09-09T00:00:00Z
authors = ['Timotée Ly-Manson', 'Mathieu Leonardon', 'Abdeldjalil Aissa El Bey', 'Ghouti Boukli Hacene', 'Lukas Mauch']
publication_types = ["1"]
abstract = "While Neural Architecture Search (NAS) methods help find optimal neural network architectures for diverse tasks, they often come with unreasonable costs. To tackle such a drawback, the one-shot NAS setting was introduced, where a supernet is used as a superposition of all architectures in the space and performs the search in a single training phase. While this method significantly reduces the cost of running NAS, the joint optimization of every architecture degrades the performance of the search. The few-shot NAS line of work tackles this issue by splitting the supernet into sub-supernets trained separately, each with a reduced level of weight-sharing, which gives rise to the new challenge of finding the best way to split the supernet. In particular, GM-NAS utilizes a gradient matching score to group operations in a splitting schema. We extend and generalize this method by building a framework with compatibility for any arbitrary architecture evaluation metric, enabling the generation of numerous and diverse splits. We leverage this new framework in conjunction with various metrics from the zero-shot NAS literature and investigate the benefits of splitting across algorithms and metrics. We find that architectures are distributed in disadvantageous ways inside splits, and that proposed supernet selection methods are flawed."
featured = false
publication = "International Conference on Automated Machine Learning AutoML24"
tags = ['Neural net work', 'Few Shot']
url_pdf = "https://imt-atlantique.hal.science/hal-04576139/document"
+++
