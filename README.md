# Image Segmentation Based on Clustering Techniques

This project implements image segmentation using the K-Means clustering technique, evaluated with the Silhouette Score. The goal is to segment images into distinct regions based on their features.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on image segmentation using the K-Means clustering algorithm. To evaluate the effectiveness of the clustering, the Silhouette Score is used. The Silhouette Score measures how similar an object is to its own cluster compared to other clusters. Higher scores indicate better-defined clusters.
![image](https://github.com/user-attachments/assets/5f8727c8-c44d-40da-9195-e59f08a0786b)


## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
   '''bash
   git clone https://github.com/dipkimyen/Image-segmentation-based-on-clustering-techniques.git'''
2. Navigate to the project directory:
   '''bash
   cd Image-segmentation-based-on-clustering-techniques'''
3. Install the required Python packages:
   '''bash
   pip install -r requirements.txt'''

## Usage

To perform image segmentation, run the provided script with the following command:
'''bash
python segment_image.py --input <path_to_image> --algorithm kmeans'''

Output
The output includes:
1. Number of Clusters: The optimal number of clusters determined for the segmentation.
2. Segmented Image: The image with distinct regions or clusters highlighted.
The segmented image will be saved in the output directory, and the optimal number of clusters will be printed to the console.
a. Image 1
![Alt text](![image](https://github.com/user-attachments/assets/eeced6e8-6ec7-407f-83d9-70a182dd90f4))
b. Image 2
c. Image 3
d. Image 4
e. Image 5

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request. You can also report issues or bugs by opening an issue in the GitHub repository.

## License

If you need more information or have any other requests, let me know!
