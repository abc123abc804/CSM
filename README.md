# CSM

# Abstract

Image compression is a critical task in the multimedia domain. With advancements in deep learning, there is a growing demand for neural network-based image compression algorithms. However, existing methods often struggle to balance image quality with compression efficiency. To address this challenge, we propose CSM, an adaptive hybrid image compression framework that integrates Convolutional Neural Networks (CNNs) and State Space Models (SSMs). The CSM framework employs a three-stage design, wherein an Adaptive Channel Partition module dynamically selects channels for local and global feature extraction using CNNs and SSMs, respectively. We introduce the State-space Residual Block (SRB), which integrates state-space models with residual blocks, and a novel channel-wise autoregressive entropy model. Experimental results demonstrate that CSM achieves state-of-the-art compression performance on benchmark datasets like Kodak and CLIC, while significantly reducing model complexity and parameters. Our approach effectively leverages both local and global context information in images, facilitating a thorough extraction of image features and distribution, thereby enhancing compression efficiency. Our code is available at https://github.com/abc123abc804/CSM.

