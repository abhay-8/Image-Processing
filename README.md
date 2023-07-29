
# Semantic Segmentation of Drone Imagery using U-Net architecture

Performing semantic segmentation on Graz University of Technology’s drone dataset using U-Net architecture. 

Dataset - [Graz University of Technology’s drone dataset](http://dronedataset.icg.tugraz.at/)

## Requirements

Python v3.9.10

Tensorflow v2.12.1

OpenCV v.4.6.0

Pandas v1.3.2

Seaborn v0.11.2

## Results

- The model achieves an accuracy of 88 percent over the train split while achieving 85 percent in the test split.

- Using classification report, we can determine the number of correct true positive predictions made by the model with respect to each sematic label defined earlier.

    The accuracy amounts to 87 percent using the classification report. While the model performs well in a few classes, it also performs poorly in some classes depending on the number of images in the class


## U-Net Architecture

[](ray-so-export.svg)
<img src="./ray-so-export.svg">
