# Image Captioning 

Image captioning is the process of generating textual description of an image .
This repository contains an implementation of an image captioning model using a combination of Transformer architecture for text generation and Convolutional Neural Network (CNN) for image feature extraction.

## Overview

The code in this repository implements an image captioning model that generates textual descriptions for input images. The model consists of the following components:

CNN Encoder: Utilizes the InceptionV3 pre-trained model to extract image features.
Transformer Encoder Layer: Encodes the input image features using multi-head self-attention and feedforward neural networks.
Transformer Decoder Layer: Decodes the encoded image features to generate caption embeddings and predict the next word in the sequence.
ImageCaptioningModel: Combines the CNN encoder and Transformer encoder-decoder layers to create the complete image captioning model.

## Dataset

The dataset will be in the form [Image, Captions].
The dataset consists of input images and their corresponding output captions
The dataset that I used is MS COCO 2017 [1] that consists of 18K Image

You can run the code to download dataset :
```
!kaggle datasets download -d awsaf49/coco-2017-dataset
```

## References

[1] https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset# Image_caption_project
