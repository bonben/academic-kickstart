+++
title = "DeepGEMM: Accelerated Ultra Low-Precision Inference on CPU Architectures using Lookup Tables"
date = 2023-06-17T00:00:00Z
authors = ['Darshan C Ganji', 'Saad Ashfaq', 'Ehsan Saaboori', 'Sudhakar Sah', 'Saptarshi Mitra', 'Mohammadhossein Askarihemmat', 'Alexander Hoffmann', 'Ahmed Hassanien', 'Mathieu Leonardon']
publication_types = ["1"]
abstract = "A lot of recent progress has been made in ultra lowbit quantization, promising significant improvements in latency, memory footprint and energy consumption on edge devices. Quantization methods such as Learned Step Size Quantization can achieve model accuracy that is comparable to full-precision floating-point baselines even with subbyte quantization. However, it is extremely challenging to deploy these ultra low-bit quantized models on mainstream CPU devices because commodity SIMD (Single Instruction, Multiple Data) hardware typically supports no less than 8-bit precision. To overcome this limitation, we propose DeepGEMM, a lookup table based approach for the execution of ultra low-precision convolutional neural networks on SIMD hardware. The proposed method precomputes all possible products of weights and activations, stores them in a lookup table, and efficiently accesses them at inference time to avoid costly multiply-accumulate operations. Our 2-bit implementation outperforms corresponding 8-bit integer kernels in the QNNPACK framework by up to 1.74× on x86 platforms."
featured = false
publication = "CVPRW 2023: IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops"
tags = ['Neural Networks', 'Quantization', 'SIMD', 'Software Implementation']
doi = "10.1109/CVPRW59228.2023.00491"
url_pdf = "https://hal.science/hal-04082069/document"
+++
