# Deep_Learning_Performance_Characterization_for_Quantization_Frameworks

## Problem Statement:
Deep learning finds applications in various fields like computer vision, natural language processing, robotics, and recommender systems. While large neural networks deliver high accuracy, they pose challenges in terms of training time, latency, energy consumption, and memory usage. To address these issues, optimization techniques and frameworks have been developed. This study evaluates the performance of quantization frameworks using metrics like training time, memory usage during training, and latency and throughput during inference on GPUs. We employ the TensorFlow framework with automatic mixed precision (AMP) for training and TensorRT for post-training quantization using the TensorFlow TensorRT (TF-TRT) API. The findings help developers and researchers create efficient deep learning models for GPUs, considering various factors like model type, dataset, image size, and batch size in both training and inference stages.
