# KMeans-Compress

This Jupyter Notebook demonstrates an image compression technique using K-Means clustering. The notebook provides step-by-step explanations and code implementation for compressing an image by reducing its color palette.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Introduction

K-Means clustering is a popular unsupervised machine learning algorithm that can be applied to various domains, including image processing. This notebook demonstrates how K-Means clustering can be utilized to compress an image by reducing the number of distinct colors in the image. This notebook allows you compress your own custom images.

The notebook covers the following main steps:
1. Data Anlysis on RGB dataset for any given image
2. Machine Learning using KMeans clustering to compress the image
3. Comparing different values for 'k' clusters to find an optimal number of clusters for personal use-cases

## Requirements

To run this notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib

Install the required dependencies using the following command:

```shell
pip install numpy opencv-python matplotlib
```
## Usage

1. Clone this repository

```shell
git clone https://github.com/sushiselite/KMeans-Compress.git
```
(You can now open the 'images' folder, delete all contents and add a .jpg of your choice that you would like to examine and compress)

2. Navigate to the project directory

```shell
cd KMeans-Compress
```

3. Start the Jupyter Notebook server

```shell
jupyter notebook
```

4. Open the Compress.ipynb file in your browser or your choice of IDE, and run the notebook cells step-by-step to observe the image compression process.

## License

This project is licensed under the MIT License.
