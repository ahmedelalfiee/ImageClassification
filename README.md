# ImageClassification

## Introduction
- Build a CNN model to classify a given image into one of 21 classes. 
- There are 100 images for each class.
- Each image measures 256x256 pixels.
- The images were manually extracted from large images from the USGS National Map Urban Area Imagery collection for various urban areas around the country. The pixel resolution of this public domain imagery is 1 foot.

## Dataset
The images folder has 21 classes, each of these classes has 100 images.
Link to the images: <a href = 'https://drive.google.com/drive/folders/1BtvgSEVqjWnD4uPes7Sg5XKBPXTaZ5iS?usp=sharing'> Images </a>

## Methodology
- Loop over image classes and divide them into train, test, and validation folders.
- Using the pytorch library to build a CNN model with:
  - 6 convolution layers
  - 4 max pooling layers
  - 3 fully connected layers
    ### Architicture

## Metrics
- Using the cross-entropy loss and accuracy over 50 epochs

  ### Plot Loss



  ### Plot Accuracy
