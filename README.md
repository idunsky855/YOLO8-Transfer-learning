# YOLOv8 Fine-Tuning on Custom Dataset For Pet and Person Detection


## Overview
This project is centered on fine-tuning the YOLOv8 neural network with the Ultralytics framework, utilizing a custom dataset annotated by the Florence-2 model. The primary objective is to improve the model's object detection capabilities for two classes:
- **Pet**: dog or cat
- **Person**: human

The project is structured into three notebooks:
- **Dataset Creation**: based on the Flickr30k dataset
- **Model Training**
- **Model Inference**

## Dataset
The dataset is derived from Flickr30k images, from which we filtered for images containing dogs, cats, or people (including combinations of these). We then employed the Florence2 model to annotate the images and generate bounding boxes. Finally, we assembled a custom dataset consisting of 800 images for each class (pet and person), along with their corresponding bounding boxes.

## Training Process
We utilized the Ultralytics framework and the YOLOv8 model to train on the dataset we created. After analyzing the initial results, we implemented augmentations to address overfitting and enhance the model's generalization and robustness.

<img src="https://github.com/user-attachments/assets/3fcedd4d-a1da-4bef-ae8d-23f266533b6f" width="650">


## Results
The model's performance has been evaluated, and the graphs below illustrate the results. These visualizations provide detailed metrics on the model's effectiveness in detecting the specified classes.

![results](https://github.com/user-attachments/assets/6c6f3cab-d409-4bf9-bf5e-d726e889cc15)
