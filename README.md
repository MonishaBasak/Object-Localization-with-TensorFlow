# Object-Localization-with-TensorFlow
We are going to use TensorFlow's Keras API to create a convolutional neural network which will be trained to classify as well as localize emojis in images. Localization, in this context, means the position of the emojis in the images. This means that the network will have one input and two outputs. Think of this task as a simpler version of Object Detection. In Object Detection, we might have multiple objects in the input images, and an object detection model predicts the classes as well as bounding boxes for all of those objects. In Object Localization, we are working with the assumption that there is just one object in any given image, and our CNN model will classify and localize that object.

## Objectives
- Create synthetic data for model training
- Create custom metrics and callbacks in Keras
- Create and train a multi output neural network to perform object localization

## Output
![Predicted object after classification & localization](https://github.com/MonishaBasak/Object-Localization-with-TensorFlow/blob/main/Outputs/Object%20localization%201.PNG)
