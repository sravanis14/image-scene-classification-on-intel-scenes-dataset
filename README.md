## image-scene-classification-on-intel-scenes-dataset
# Overview / Usage
This project is based on the Intel Scene Classification Challenge which was released by Analytics Vidhya in collaboration with Intel.

The dataset consists of the different types of images (of 150x150 dimensions) which are nothing but natural scenes. The categories particularly were given as:
1. Buildings
2. Forest
3. Glacier
4. Mountain
5. Sea
6. Street
The task is to classify images with respect to the above categories.

# Methodology / Approach
The dataset has a decent amount of similarity with the classic Imagenet dataset. So the choice of using a vision transformer model pretrained on the Imagenet dataset came quite naturally to me. The next challenge was to fine-tune the model and set the hyperparameters accordingly.
