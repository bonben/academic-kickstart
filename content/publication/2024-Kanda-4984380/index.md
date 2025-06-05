+++
title = "Design Environment of Quantization-Aware Edge AI Hardware for Few-Shot Learning"
date = 2024-08-11T00:00:00Z
authors = ['R. Kanda', 'N. Onizawa', 'Mathieu Leonardon', 'Vincent Gripon', 'T. Hanyu']
publication_types = ["1"]
abstract = "This study aims to ensure consistency in accuracy throughout the entire design flow in the implementation of edge AI hardware for few-shot learning, by implementing fixed-point data processing in the pre-training and evaluation phases. Specifically, the quantization module, called Brevitas, is applied to implement fixed-point data processing, which allows for arbitrary specification of the bit widths for the integer and fractional parts. Two methods of fixed-point data quantization, quantization-aware training (QAT) and post-training quantization (PTQ), are utilized in Brevitas. With Tensil, which is used in the current design flow, the bit widths of the integer and fractional parts need to be 8 bits each or 16 bits each when implemented in hardware, but performance validation has shown that accuracy comparable to floating-point operations can be maintained even with 6 bits or 5 bits each, indicating potential for further reduction in computational resources. These results clearly contribute to the creation of a versatile design and evaluation environment for edge AI hardware for few-shot learning."
featured = false
publication = "2024 IEEE 67th International Midwest Symposium on Circuits and Systems (MWSCAS)"
tags = ['Deep Learning', 'FPGA', 'Few shot Learning']
doi = "10.1109/MWSCAS60917.2024.10658789"
+++
