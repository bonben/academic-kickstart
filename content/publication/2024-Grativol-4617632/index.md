+++
title = "FLoCoRA: Federated Learning Compression With Low-Rank Adaptation"
date = 2024-08-26T00:00:00Z
authors = ['Lucas Grativol', 'Mathieu Leonardon', 'Guillaume Muller', 'Virginie Fresse', 'Matthieu Arzel']
publication_types = ["1"]
abstract = "Low-Rank Adaptation (LoRA) methods have gained popularity in efficient parameter fine-tuning of models containing hundreds of billions of parameters. In this work, instead, we demonstrate the application of LoRA methods to train small-vision models in Federated Learning (FL) from scratch. We first propose an aggregation-agnostic method to integrate LoRA within FL, named FLoCoRA, showing that the method is capable of reducing communication costs by 4.8 times, while having less than 1% accuracy degradation, for a CIFAR-10 classification task with a ResNet-8. Next, we show that the same method can be extended with an affine quantization scheme, dividing the communication cost by 18.6 times, while comparing it with the standard method, with still less than 1% of accuracy loss, tested with on a ResNet-18 model. Our formulation represents a strong baseline for message size reduction, even when compared to conventional model compression works, while also reducing the training memory requirements due to the low-rank adaptation."
featured = false
publication = "EUSIPCO 2024: 32nd European Signal Processing Conference"
tags = ['Low-Rank Adaptation', 'Federated Learning', 'Compression']
doi = "10.23919/EUSIPCO63174.2024.10715461"
url_pdf = "https://hal.science/hal-04617632/document"
+++
