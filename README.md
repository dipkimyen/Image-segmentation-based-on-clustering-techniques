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
a. Image 1 - Number of Clusters: 13
![image](https://github.com/user-attachments/assets/3cda2f69-981a-42c2-ad42-fdd1026a8b84)
![image](https://github.com/user-attachments/assets/02a1f05a-87ce-460d-9269-94cd70686fcf)

b. Image 2 - Number of Clusters: 3
![image](https://github.com/user-attachments/assets/283be20a-725e-4cf6-a55e-08475dacf991)
![image](https://github.com/user-attachments/assets/207c04a6-dffb-49ff-9e23-2413ee078a03)

c. Image 3 - Number of Clusters: 9
![image](https://github.com/user-attachments/assets/2646d62c-44bf-457f-a511-933fbef579e7)
![image](https://github.com/user-attachments/assets/74915cf5-6bca-41d7-bd98-08101024ef1d)

d. Image 4 - Number of Clusters: 4
![image](https://github.com/user-attachments/assets/bb3187b9-e52d-4e86-907b-96b0fb5ebffa)
![image](https://github.com/user-attachments/assets/28cf19e1-6343-477a-973d-b7cf4e8ce73b)

e. Image 5 - Number of Clusters: 8
![image](https://github.com/user-attachments/assets/79a183b1-4214-4d29-8035-755cd2bab454)
![image](https://github.com/user-attachments/assets/3dad45b7-8971-481a-b132-8e24d97cd970)

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request. You can also report issues or bugs by opening an issue in the GitHub repository.

## License

If you need more information or have any other requests, let me know!
