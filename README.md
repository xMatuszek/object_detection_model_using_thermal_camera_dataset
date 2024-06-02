# Thermal Object Detection

The objective of this project was to develop a model for object detection in the **thermal spectrum**. We implemented **two models** using the large YOLO model on our custom dataset. Out of 16 object classes, we selected 5 (bus, car, other vehicle, person, sign) for this project.

One model was trained on RGB images, while the other was trained on THERMAL images. Both models were trained with the same configurations, including the number of epochs and other hyperparameters. Finally, we compared the performance of both models on thermal images.

### Dataset
The dataset used for this project can be found [here](https://adas-dataset-v2.flirconservator.com/).
