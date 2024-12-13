# sastrabali-ml

### Overview

We built a machine learning model for Balinese Aksara classification using Convolutional Neural Network (CNN).

### Dataset

The data we used to build the aksara classification model came from 2 sources:

- [Kaggle](https://www.kaggle.com/datasets/wildanfatahh22/aksara-bali/data?select=AKSARA+WYAJANA+ALL)
- Handwritten (We created our own aksara dataset)

### Implementation

Firstly, we combined all the data we used into a single folder called `dataset`. Before using it to train the model, we augmented the dataset using `augmentation.ipynb`. We then train the model, tune it and also test it until we were satisfied with the model's performance, lastly we saved it as a tflite model using `classification.ipynb`. Lastly, before handing the model to the mobile development team, we add metadata to the model to help the integration process of the model to the mobile application using `metadata.ipynb`.
