+++
title = "Fast and Flexible Software Polar List Decoders"
date = 2019-01-18T00:00:00Z
authors = ['Mathieu Leonardon', 'Adrien Cassagne', 'Camille Leroux', 'Christophe Jego', 'Louis-Philippe Hamelin', 'Yvon Savaria']
publication_types = ["2"]
abstract = "Flexibility is one mandatory aspect of channel coding in modern wireless communication systems. Among other things, the channel decoder has to support several code lengths and code rates. This need for flexibility applies to polar codes that are considered for control channels in the future 5G standard. This paper presents a new generic and flexible implementation of a software Successive Cancellation List (SCL) decoder. A large set of parameters can be fine-tuned dynamically without re-compiling the software source code: the code length, the code rate, the frozen bits set, the puncturing patterns, the cyclic redundancy check, the list size, the type of decoding algorithm, the tree-pruning strategy and the data quantization. This generic and flexible SCL decoder enables to explore tradeoffs between throughput, latency and decoding performance. Several optimizations are proposed to achieve a competitive decoding speed despite the constraints induced by the genericity and the flexibility. The resulting polar list decoder is about 4 times faster than a generic software decoder and only 2 times slower than a non-flexible unrolled decoder. Thanks to the flexibility of the decoder, the fully adaptive SCL algorithm can be easily implemented and achieves higher throughput than any other similar decoder in the literature (up to 425 Mb/s on a single processor core for N = 2048 and K = 1723 at 4.5 dB)."
featured = true
publication = "Journal of Signal Processing Systems (Springer)"
doi = "10.1007/s11265-018-1430-3"
url_pdf = "https://inria.hal.science/hal-01987848/document"
+++
