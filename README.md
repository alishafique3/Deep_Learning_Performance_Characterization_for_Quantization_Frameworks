# Deep_Learning_Performance_Characterization_for_Quantization_Frameworks

## Abstract:
Deep learning finds applications in various fields like computer vision, natural language processing, robotics, and recommender systems. While large neural networks deliver high accuracy, they pose challenges in terms of training time, latency, energy consumption, and memory usage. To address these issues, optimization techniques and frameworks have been developed. This study evaluates the performance of quantization frameworks using metrics like training time, memory usage during training, and latency and throughput during inference on GPUs. In this paper, We have directed our attention to classification models to determine the prime factors in model architectures that affect quantization performance. The findings will help the developers and researchers create efficient deep learning models for GPUs, considering various factors like model type, dataset, image size, and batch size in both training and inference stages.

## Results:
We have found that model architecture and corresponding parameters are the major factors that affect quantization performance. VGG16 has a large number of parameters, while MobileNet_v1 and ResNet-50 reduce their parameters using depthwise separable convolutional layers and 1×1 filters, resulting in lesser speedup and improvement factors after quantization as compared to VGG16.

![cifar_results](https://github.com/alishafique3/Deep_Learning_Performance_Characterization_for_Quantization_Frameworks/assets/17300597/574df405-efa9-473f-aaac-014805b590b7)

## Citation:
If this study is useful or relevant to your research, please kindly recognize our contributions by citing our paper
```
@article{shafique2023deep,
  title={Deep Learning Performance Characterization on GPUs for Various Quantization Frameworks},
  author={Shafique, Muhammad Ali and Munir, Arslan and Kong, Joonho},
  journal={AI},
  volume={4},
  number={4},
  pages={926--948},
  year={2023},
  publisher={MDPI}
}
```
