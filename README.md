This project is also has a entrance in Medium.com at [link](https://medium.com/@restevesd/deep-learning-for-image-classification-4a0c3c112da)

[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This repository is to show the development of a dog breed classifier for the final project of the Udacity Nanodegree Data Science.

A Convolutional Neuronal Network (CNN) will be developed from 0.

How it works, given the image of a dog, the algorithm will identify the breed of the dog, if the image is a human it will identify it and tell us what breed of dog it is similar to.
![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

### Requirement
- Python 3
- sklearn
- Numpy
- TensorFlow  
- keras
- glob
- cv2
- matplotlib
- tqdm
- PIL

### File Descriptions
- There are 5 folders, 1 notebooks and 1 python script in this repo.

- The **haarcascades** folder should contain the OpenCV haarcascades face detector model.

- The **images** folder to place any images on which you would like to test the model

- The **requeriments** folder containing the necessary dependencies

- The **bottleneck_features** folder for pretrained models which can be downloaded from link in notebook

- The **saved_models** folder should contain the files for the pretrained ResNet50, this files is copied by the code of the notebook.

- The **extract_bottleneck_features.py** script contains the caller functions for downloading the pretrained models and predicting models with them.

- The **dog_app.ipynb** notebook is the main file which displays the classifcation models and illustartions.

## License
The contents of this repository are covered under the [MIT License](https://github.com/restevesd/UdacityDogClassification/blob/master/LICENSE.txt)