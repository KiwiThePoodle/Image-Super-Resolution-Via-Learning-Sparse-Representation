## Introduction

Image Super-Resolution is a common problem within computer vision. Super-resolution imaging is a class of techniques that enhance the resolution of an imaging system. Deep learning models are commonly used to improve the performance of SR algorithms. This research project aims to create a model that can be comparable to state-of-the-art models.

## Method

We utilize deep learning to learn a sparse representation. In simplest terms, instead of using deep learning to learn a relationship between the entire low-resolution image and the high-resolution image, we split the image into smaller regions to find relationships locally. Read more: [Image Super-Resolution Via Learning Sparse Representation](https://github.com/KiwiThePoodle/Image-Super-Resolution-Via-Learning-Sparse-Representation/blob/main/Image%20Super-Resolution%20Via%20Learning%20Sparse%20Representation%20Paper.pdf).

### Our Model

- Sparse Representation (Sparse)

### Benchmark Models

- Bicubic Interpolation (Bicubic)
- Laplacian Pyramid Super-Resolution Network (LapSRN)

### Datasets

- Set5
- Set14

### Metrics

- Root-Mean-Square Error (RMSE)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index Measure (SSIM)

## Results

