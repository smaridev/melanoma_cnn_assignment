# Melanoma Detection via Convolutional Neural Network (CNN)

The objective of this project is to create a Convolutional Neural Network (CNN) to classify a dermoscopic image of a skin lesion as Melanoma or Non-Melanoma. A dermoscopic image is a picture of the skin using a microscope and illumination.

## Motivation

Melanoma evolves from the rapid growth of melanin-producing cells, Melanocytes, which are located in the skin’s epidermis. Although Melanoma can only be confirmed with a biopsy, it is often identified visually in an existing or new nevus (commonly known as "mole") using the mnemonic “ABCDEs”:


## Built With

* TensorFlow
* Keras
* Python

## Models

CNN architectures were explored for this project:

1) Simple CNN built from scratch with Keras, TensorFlow, and Python.


### Keras CNN

The CNN built in Keras is able to achieve an overall accuracy of 92% and validation accuracy 82%.This is actually good for such a simple CNN. This model takes about 10 minutes (30 epochs). While this CNN is simple and straightforward to understand, it does not yield the same level of accuracy as a deeper CNN. 

- Adam optizmier (default parameters) [1]
- Fully-connected 
- 3 Conv2D layers
- Epochs = 30

## Future Work

I plan to improve this accuracy further by automating image pre-processing and/or obtaining a larger dataset or using ResNet50 based models. I also plan to integrate this model into a website or app so that users may upload an image and see the associate risk of the mole.

## Reference
https://hal.archives-ouvertes.fr/hal-03172718/document

## Author

**Shanmuga Mari** 

