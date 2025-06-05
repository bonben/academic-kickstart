+++
title = "Pipelined Architecture for a Semantic Segmentation Neural Network on FPGA"
date = 2023-12-04T00:00:00Z
authors = ['Hugo Le Blevec', 'Mathieu Léonardon', 'Hugo Tessier', 'Matthieu Arzel']
publication_types = ["1"]
abstract = "Many machine vision tasks like urban sceneunderstanding rely on machine learning, and more specifically deep neural networks to provide accurate enough results to make technology like autonomous vehicles possible. FPGAs have proven to be an excellent target for deploying highly parallel, low-latency and low-power deep neural network architectures for embedded and cloud applications. Many FPGA implementations use recursive architectures based on Deep Processing Units (DPUs) for fast and resource-efficient solutions which usually come at the cost of a higher latency. On the other hand, pipelined dataflow architectures have the potential to offer scalable, lowlatency implementations. In this work, we have explored implementing a semantic segmentation network as a pipelined architecture and evaluated the achievable performances. Our model, a convolutional encoder-decoder based on U-Net, achieves 62.9 % mIoU on the Cityscapes dataset with a 4-bit integer quantization. Once deployed on the Xilinx Alveo U250 FPGA board, the implemented neural network architecture is able to output close to 23 images per second with 44 ms latency per input. The code of this work is open-source and was released publicly."
featured = false
publication = "ICECS 2023: IEEE 30th International Conference on Electronics, Circuits and Systems"
tags = ['Semantic segmentation', 'FPGA', 'Deep learning', 'Scene-understanding']
doi = "10.1109/ICECS58634.2023.10382715"
url_pdf = "https://hal.science/hal-04262138/document"
+++
