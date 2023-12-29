## Introduction

Image Super-Resolution is a common problem within computer vision. Super-resolution imaging is a class of techniques that enhance the resolution of an imaging system. Deep learning models are commonly used to improve the performance of SR algorithms. This research project aims to create a model that can be comparable to state-of-the-art models.

## Method

We utilize deep learning to learn a sparse representation within an image. In simplest terms, instead of using deep learning to learn a relationship between the entire low-resolution image and the high-resolution image, we split the image into smaller regions to find relationships locally. Image super-resolution via sparse representation involves reconstructing a high-resolution image from a low-resolution version by utilizing a sparse set of learned patterns or features. Read more:
- Paper: [Image Super-Resolution Via Learning Sparse Representation](https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/Image%20Super-Resolution%20Via%20Learning%20Sparse%20Representation%20Paper.pdf)
- Presentation: [Image Super-Resolution Via Learning Sparse Representation](https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/Image%20Super-Resolution%20Via%20Learning%20Sparse%20Representation%20PPT.pdf)

### Our Model

- Sparse Representation (Sparse)

### Benchmark Models

- Bicubic Interpolation (Bicubic)
- State-of-the-Art: Laplacian Pyramid Super-Resolution Network (LapSRN)

### Datasets

- Set5
- Set14

### Metrics

- Root-Mean-Square Error (RMSE)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index Measure (SSIM)

## Results

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/Flowers%20Example.png">

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/Foreman%20Example.png">

RMSE: (lower is better)

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/RMSE.png">

PSNR: (higher is better)

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/PSNR.png">

SSIM: (higher is better)

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/SSIM.png">

Overall:

<img src="https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/code/metrics/Metric%20Comparison.png">
